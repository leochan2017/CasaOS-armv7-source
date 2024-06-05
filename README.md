# CasaOS-armv7-source
个人收集的一些能用在armv7架构(玩客云是这个架构)的软件（主要为CasaOS提供软件源用）



## 使用方法

### 1.添加软件源

CasaOS - App Store - 更多应用 - 填入"https://github.com/leochan2017/CasaOS-armv7-source/blob/main/Dist/Leo-AppStore-CasaOS.zip"

### 2.单个应用导入

##### 2.1 在这里找到你要的软件https://github.com/leochan2017/CasaOS-armv7-source/tree/main/Leo-AppStore-CasaOS/Apps

##### 2.2 把yml文件下载到本地

##### 2.3 CasaOS - App Store - 右上角自定义安装 - 右上角导入 - 把刚刚下载的yml拖入到docker compose 上传

##### 2.4 确认表单信息，如无意外右下角安装



## 为啥？
目前的应用商店部分应用的版本是最新的，但是最新版里面很多都不能用在armv7架构的设备（例如用玩客云刷的系统），他们只支持amd64和arm64
如果你想下载对应的armv7版本需要安装回旧版才能成功
