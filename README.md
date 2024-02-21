# platform-utils
Small scripts or tools that made my life easier one way or another throughout time


## Bash scripts

Setting up `Touch ID` for `sudo` instead of typing passwords if your system allows that

```
sudo cp /etc/pam.d/sudo_local.template /etc/pam.d/sudo_local
sudo sed -i '' 's/#auth/auth/g' /etc/pam.d/sudo_local
```
