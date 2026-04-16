```shell
wsl --install

wsl --install -d Ubuntu
wsl --install -d Debian

wsl --list --verbose
wsl --set-default-version 2
wsl --list --online

wsl --set-default Ubuntu
bash

wsl --list --verbose
wsl --export Ubuntu E:\WSL\Ubuntu.tar
wsl --unregister Ubuntu
wsl --import Ubuntu E:\WSL\Ubuntu E:\WSL\Ubuntu.tar --version 2
del E:\WSL\Ubuntu.tar
wsl -d Ubuntu

winget install Anthropic.ClaudeCode

bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
nvm install 20
npm config set registry https://registry.npmmirror.com
npm install -g @anthropic-ai/claude-code
export HTTP_PROXY="http://192.168.6.105:8118"
export HTTPS_PROXY="http://192.168.6.105:8118"
claude
/theme

sudo cp /etc/apt/sources.list.d/ubuntu.sources /etc/apt/sources.list.d/ubuntu.sources.bak
sudo vim /etc/apt/sources.list.d/ubuntu.sources
Types: deb
URIs: http://mirrors.aliyun.com/ubuntu/
Suites: noble noble-updates noble-security
Components: main restricted universe multiverse
Signed-By: /usr/share/keyrings/ubuntu-archive-keyring.gpg

sudo apt update


开发一个sbti人格测试网站
完成seo优化

重构页面，美化页面，seo优化​
更新README.md，增加agent.md供AI阅读

winget --version
git --version
winget install --id Git.Git -e --source winget
git --version
where.exe git

wsl --import <发行版名称> <安装目录> <镜像文件路径>
wsl --import Ubuntu-24.04 "D:\WSL\Ubuntu-24.04" "E:\Edge Download\ubuntu-24.04.2-wsl-amd64.tar"

# 开启虚拟机平台 
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart  
# 开启 WSL 子系统 
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

dism.exe /online /disable-feature /featurename:Microsoft-Windows-Subsystem-Linux /norestart
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```