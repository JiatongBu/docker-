# docker-
4月组队


一、安装WSL


1.电脑windows版本为20H2，符合WSL2的安装条件。

2.在 Windows 上启用 wsl2特性。
3.采用手动安装的方式
    
首先需要安装 Windows 10 的 WSL 功能：

`dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart`

        
 升级成WSL2，安装 WSL2 功能模块：

`dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart`

重启电脑完成 WSL2 的安装
    
3.下载并安装 Linux 内核更新包。

4.安装Linux发行版

5.安装docker。
