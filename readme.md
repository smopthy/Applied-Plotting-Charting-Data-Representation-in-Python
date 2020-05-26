## python with matablot 

matabolt 有四個layer 

`
import numpy as np 
import pandas as pd 
import matplotlib.pyplot as plt 
`
其中pylab 裡面包含numpy and pandas 的函數 

//創建新的畫布
plt.figure()

plot.plt()

四個layer 
* backend 
* artist 

matplotlib的結構組成
* 第一層 canvas ： 
    位於數據最底層 
* 第二層 figure 類似畫布 畫圖的區域 ：
    我開開始操作地方 
* 第三層 axes 子圖 坐標系 ：
    建立於 figure 之上 
* 第四層 各類圖表訊息 包括：axis-x , axis-y , title , legend-圖例 , grid-網格 spine-邊匡線 data-數據 
    建立
