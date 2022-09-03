# install-sh
安装脚本收集

> 如出现Permision Denied， 视情况使用`sudo`
## fe

### nvm/npm/node/yarn

```sh
1. 安装nvm，用于多版本node
- curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
- wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

# bash 重启shell进程

nvm -v



2. 安装node
nvm install node # 下载最新node
nvm install v14.0.0
nvm ls-remote # list全量可用版本
nvm use v14.0.0 # 使用v14.0.0

3. 安装npm
nvm install-latest-npm # 自动安装适合当前node版本的最新npm

3. 安装yarn
npm install --global yarn

```

# python
```sh
1. 安装python
sudo apt-get install python2.7
sudo apt-get install python3.6

2. 安装pip
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py # 遇到网络问题可以直接浏览器打开复制到本地（curl和浏览器不一定是一个代理）
sudo python get-pip.py 
sudo python2 get-pip.py 
sudo python2.7 get-pip.py
python -m pip install requests
```