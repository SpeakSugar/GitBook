#### 配置shell

`vi .bash_profile` insert env variable

`vi .zshrc` insert `source ~/.bash_profile` then `source .zshrc`

```bash
vi .bash_profile
alias forti='sudo openforticli -c /usr/local/etc/openforticli/config'
alias gios='ga da 893A0AFC-1BD8-4B84-8EC9-5B95FE7CFFD5'
alias gand='ga da emulator-5554'
alias emu='emulator -avd Pixel_2_API_30 &'
alias iemu='open -a Simulator'
alias ll='ls -l'

export NVM_DIR="$HOME/.nvm"
[ -s "$(brew --prefix)/opt/nvm/nvm.sh" ] && \. "$(brew --prefix)/opt/nvm/nvm.sh" # This loads nvm
[ -s "$(brew --prefix)/opt/nvm/etc/bash_completion.d/nvm" ] && \. "$(brew --prefix)/opt/nvm/etc/bash_completion.d/nvm" # This loads nvm bash_completion

export ANDROID_SDK_ROOT="$HOME/Library/Android/sdk"
export PATH=$PATH:$ANDROID_SDK_ROOT/platform-tools:$ANDROID_SDK_ROOT/emulator
```

#### 下载Brew
```bash
/usr/bin/ruby -e "$(curl -fsSL https://cdn.jsdelivr.net/gh/ineo6/homebrew-install/install)"
```

#### 常用的Brew工具下载
`brew install nvm` > `nvm install 18.2.0` && `nvm install 12.18.3`  

`brew install libimobiledevice`  

`brew install tesseract`  

`brew install usbmuxd`  iproxy命令
```bash
wget https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb && brew install sshpass.rb
```
`brew install --cask goldendict` 翻译软件, 详细配置见 `https://github.com/easeflyer/gd_plugin/blob/master/youdao/README.md`

通过命令行连接vpn
```bash
curl -O https://yanminhui.github.io/assets/formula/openforticli.rb  
brew install -s --formula openfortivpn-tunnel.rb
vi /usr/local/etc/openforticli/config
### configuration file for openforticli, see man openforticli(1) ###

# you can fill in multiple host by `;`

host = sslvpn.xmn.rcoffice.online;110.87.98.82;210.13.208.82
port = 4443
username = <vpn_user>
password = <vpn_password>
otp-secret = <otp_secret>
persistent = 5
trusted-cert = 1bab7e42984704be042da7668a58631f6cd82bc2bc87029412bfd2acd7ae4307
set-dns = 0
pppd-use-peerdns = 1

sudo openforticli -c /usr/local/etc/openforticli/config

sudo vi /etc/sudoers
# root and users in group wheel can run anything on any machine as any user
root		ALL = (ALL) ALL
jeffries.yu     ALL = (ALL) NOPASSWD: ALL
%admin		ALL = (ALL) NOPASSWD: ALL
```


