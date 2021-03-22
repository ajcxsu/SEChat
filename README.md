![SEChat_logo](https://user-images.githubusercontent.com/31349569/111941576-4a754580-8b0c-11eb-83a4-4d0c2c37cd79.png)

一款用 GMS2 编写的 p2p 聊天工具。即时聊天、文件、图片、音乐播放与加密传输。


<!--more-->

# 简介
个人因学习 GMS2 用途兴趣使然编写的 p2p 聊天工具。

![screenshot](https://user-images.githubusercontent.com/31349569/111941881-09316580-8b0d-11eb-89a1-b05aaa79db5d.png)


### 特性
* 无需经过服务器，端到端加密的即时聊天工具（局域网、公网访问或内网映射）
* 无损图片传输，可修改/自适应图片预览大小（支持 jpeg、png 等常见图片格式）
* 文件传输与音乐播放（支持 mp3、flac 等常见音乐格式）
* 聊天历史导出
* 聊天背景、主题色自定义，支持背景图高斯模糊
* 彩虹色的彩蛋
* 相对高效的文件处理、数据加密与网络传输
* 传输的文件、图片、音乐以无损形式立即保存在本地文件夹内
* 设置保留
* 可调整帧率

# 使用方法
建议使用环境：Windows 7/8/10 x86/64

## 基本内容
右键粘贴/替换。右上角退出。

Export History 导出聊天历史。

Clear History 清屏与清理内存。操作不可逆。

FPS 调整全局帧率。

Wheel Speed 调整滚轮速度。

## 聊天
输入内容，然后回车。

## 建立连接
### 服务器端
进入 Settings 调整 Local Port（本地服务器端口）后选择 Create Server。

### 客户端
填写 Server Address（服务器地址）与 Server Port（服务器端口）后选择 Connect。

## 传输文件/图片/音乐
将想要传输的**单个**文件拖入到聊天框中。

在 Image Size 一栏中填写预览图片大小（不改变已经生成的图片预览）。

## 自定义主题
Front Color 修改前景色。

Background Color 修改背景色。修改完成后背景将变成纯色类型。

Background Image 修改背景图片。修改完成后背景将变成图片类型。背景图左上角中心等比例拉伸。

Background Blur Amount 修改背景图片模糊量。值越高模糊半径越高。只在背景为图片类型下生效。

# 警告
你应只与你信任的人使用该工具。该工具未对聊天双方传输的文件作任何限制。音乐文件收到后会立即播放，而相关设置还没做好。

# BUG相关
请将崩溃时的日志记录并提 issue 来进行反馈。

# 使用/修改的项目（不完全）

**FMODGMS by mstop4**
https://github.com/mstop4/FMODGMS
