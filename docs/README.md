```shell
wsl --install
wsl --set-default-version 2

wsl --list --verbose

wsl --install -d Ubuntu

wsl --import <发行版名称> <安装目录> <镜像文件路径>
wsl --import Ubuntu-24.04 "D:\WSL\Ubuntu-24.04" "E:\Edge Download\ubuntu-24.04.2-wsl-amd64.tar"

# 开启虚拟机平台 
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart  
# 开启 WSL 子系统 
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

dism.exe /online /disable-feature /featurename:Microsoft-Windows-Subsystem-Linux /norestart
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```