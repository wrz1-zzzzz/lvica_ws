# 关于项目编译  
 cmake eigen 3 opencv 2.4 是之前装过的 
 编译之前将cmakelist.txt中PCL 1.9版本去掉了 
 ## 关于依赖安装
 ```
 sudo apt-get update
 sudo apt-get install libepoxy-dev
```
Pangolin 
```
sudo apt-get update
sudo apt-get install git cmake libglew-dev pkg-config libegl1-mesa-dev libwayland-dev libxkbcommon-dev wayland-protocols
```
### 随便找个文件夹  
````
git clone https://github.com/stevenlovegrove/Pangolin.git
cd ~/Pangolin
git fetch --all --tags
git checkout v0.6
mkdir build && cd build
cmake ..
make -j 
sudo make install 
