# after-install-ubuntu

### variety
```
sudo apt install variety
```

### terminator
```
sudo apt install terminator
```

### nvm
https://github.com/nvm-sh/nvm
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```
```
nvm ls-remote --lts
nvm install v12.22.6
```

### sdkman
https://sdkman.io/
```
curl -s "https://get.sdkman.io" | bash
```
```
sdk list java
sdk install java 11.0.12-open
```

### vscode
https://code.visualstudio.com/download

#### plugins
- python
- eslint
-prettier

### fonts
```
sudo apt install fonts-nanum fonts-naver-d2coding
```

### docker
https://docs.docker.com/engine/install/ubuntu/

#### Post-installation steps for Linux
https://docs.docker.com/engine/install/linux-postinstall/
```
#sudo groupadd docker
sudo usermod -aG docker $USER
```

### Ubuntu Mainline Kernel Installer
https://github.com/bkw777/mainline
```
sudo add-apt-repository ppa:cappelikan/ppa
sudo apt update
sudo apt install mainline
```

### pipewire
https://askubuntu.com/questions/1339765/replacing-pulseaudio-with-pipewire-in-ubuntu-20-04
https://ubuntuhandbook.org/index.php/2021/05/install-latest-pipewire-ppa-ubuntu-20-04/
```
sudo add-apt-repository ppa:pipewire-debian/pipewire-upstream
sudo apt install pipewire gstreamer1.0-pipewire, libspa-0.2-bluetooth, libspa-0.2-jack
```

### intellij toolbox
https://www.jetbrains.com/ko-kr/toolbox-app/

### nosqlbooster
https://www.nosqlbooster.com/home

### gitsh
https://github.com/thoughtbot/gitsh

