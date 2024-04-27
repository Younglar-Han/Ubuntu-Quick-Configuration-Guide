# Ubuntu 20.04快速配置指南

## 安装QQ

官网下载

## 安装clash

https://github.com/clashdownload/Clash_for_Windows/releases

## 安装Edge, VSCode

官网下载

## 安装Miniconda

官网下载

[手把手教你如何在Ubuntu下安装Miniconda - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/368095197)

## 安装Typora

www.fishros.com 下载

## 换源、安装ROS、安装微信

```shell
wget http://fishros.com/install -O fishros && . fishros
```

## 安装并配置golden dict

```shell
sudo apt install goldendict
```

https://zhuanlan.zhihu.com/p/151810213

或直接安装有道翻译

## 安装搜狗输入法

官网下载

## 安装nvdia驱动和cuda

[Ubuntu 20.04安装CUDA & CUDNN 手把手带你撸_ubuntu20.04安装cuda-CSDN博客](https://blog.csdn.net/h3c4lenovo/article/details/119003405)

```shell
ubuntu-drivers devices
```

```shell
sudo apt install nvidia-driver-XXX
```

查看cuda和cudnn版本

https://blog.csdn.net/qq_31290747/article/details/91373248

## K380在双系统下的设置

https://blog.csdn.net/Pasture93/article/details/111059164

https://blog.csdn.net/weixin_44432386/article/details/107791689

## 各种实用工具

### 安装git

```shell
sudo apt install git
```

### 安装vim, btop

```shell
sudo apt update
sudo apt install vim
sudo snap install btop
```

### 安装speed network

https://ubuntuhandbook.org/index.php/2020/06/download-upload-speed-ubuntu-20-04-panel/#:~:text=%28UPDATE%29%20Install%20Net%20Speed%20Indicator%20in%20Ubuntu%2022.04%3A,%E2%80%9CBrowser%E2%80%9D%20tab%20of%20the%20pop-up%20tool%20and%20enjoy%21

### 解决关机慢问题

https://www.zhihu.com/question/426312944

### 建立Python3链接

```shell
sudo apt install python-is-python3
```

### 关闭打印机自动发现

```shell
sudo systemctl disable cups.service
sudo systemctl disable cups-browsed.service
```

https://zhuanlan.zhihu.com/p/516468672

### 在Ubuntu使用emoji

```shell
sudo snap install emote
```

