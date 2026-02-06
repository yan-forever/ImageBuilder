# ImageBuilder
Used for building images in Minecraft.

用于在Minecraft中建造图片。

# Usage
# 使用方法：

## Internal Preparation
## 内部准备
Enable **WebSocket** in **Settings** - **General**.

需要在**设置**-**通用**中打开**WebSocket**

In the same section, disable **Require Encrypted WebSocket**.

同一级，需要关闭**需要加密的WebSocket**

Cheats and Operator permissions are required.

需要作弊和管理员权限

## External Preparation
## 外部准备
Open the **.jar** file downloaded from the GitHub **Releases** page.

从 GitHub 的 **Releases** 页面下载并打开 **.jar** 文件。

Enter the port.

输入端口

## Connection
## 连接
Enter in game:

在游戏中输入:
```
/wsserver 127.0.0.1:2333
```
or
或者
```
/connect 127.0.0.1:2333
```
**Note: The IP and port here are for reference only.**

**注：此处ip和端口仅供参考**

## Use
## 使用

Follow the command prompts to use.

按照命令提示使用即可

Tested delay of 1ms works on high-performance machines; 0ms causes freezing and is not supported.

延迟经测试1ms可以在性能良好的机器上使用，0ms卡死不受支持