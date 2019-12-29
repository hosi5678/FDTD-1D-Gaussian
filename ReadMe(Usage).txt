Usage of 1D Electronic Field(FDTD)

マクスウェル方程式から1次元電磁界を導出
電流:gaussian

終端条件:固定端(Ey(0)=Ey(L)=0)
アルゴリズム:FDTD法 

cell size=91

1000 timesteps

1タイムステップを1フレームにして静止画を作成、静止画を集めて動画作成
OS: Win 10
Language:c

その他:terapad,makeを使用

 Compiler:gcc

静止画:PPM形式
静止画→動画はffmpegを使用

 ソースファイル
https://github.com/hosi5678/FDTD-1D-Gaussian/tree/master/1D/Gaussian

mail:
hosi5678@gmail.com