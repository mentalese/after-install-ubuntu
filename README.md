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
