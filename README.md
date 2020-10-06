# laminar_BL_OpenFOAM
this is a laminar boundary layer ysing OpenFOAM icoFoam solver

边界条件在速度U文件中是：

顶部的边界和底部的入口附近的边界为zeroGradient
左侧入口区域为恒定的速度流入边界
右侧出口边界也为zeroGradient
然后出口附近的底部区域边界为noSlip
