# 利用python生成Hilbert曲线
>fork的仓库 [tujinhao/GS_Hbed_Generator](https://github.com/tujinhao/GS_Hbed_Generator)

## 参数设置
``` python
#pcb坐标系原点在左上角，X轴从左到右递增，y轴从上到下递增  
pcb_x0 = 4020
pcb_y0 = 3343

# 曲线
strokeWidth = 3  # 线宽为strokeWidth * 10 mil
clearance = 5    #两条线中心间距为clearance* 10 mil  线边缘的间距为（clearance - strokeWidth）*10mil
order = 6   #曲线阶数
```