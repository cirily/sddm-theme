# SDDM Theme for Piscesy

![screenshot](screenshot.png)

## Compile dependencies (For Debian)

```shell
apt install build-essential cmake extra-cmake-modules qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev qttools5-dev qttools5-dev-tools
```

## Build & install 
```shell
git clone https://github.com/cirily/sddm-theme.git
cd sddm-theme
mkdir build
cd build
cmake ..
make
sudo make install
```
