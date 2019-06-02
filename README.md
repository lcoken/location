# 
What is CEP?

CEP和RMS是GPS的定位准确度(俗称精度)单位，是误差概率单位。就拿2.5M CEP说吧，意思是以2.5M为半径画圆，有50%的点能打在圆内，也就是说，GPS定位在2.5M精度的概率是50%，相应的RMS（66.7%）2DRMS（95%）。当然很多商家为了参数好看，愿意给出CEP，因为单位大了，前面的数就小了。

水平精度以圆概率误差(CEP) 意味着 50% 的结果在给出的圆直径内，50%的结果在圆外。

RMS是1 sigma或1倍标准差，如果结果是无偏的，概率为67%。
2D RMS是2 sigma或2倍标准差，概率为95%。

他们的相互转换可以按照下面的规则：

CEP 乘以1.2能转换为RMS，CEP 乘以2.4能转换为2D RMS。

2.5M CEP -> 3M RMS -> 6M 2D RMS
