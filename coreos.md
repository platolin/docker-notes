設定時區
```
sudo timedatectl set-timezone Asia/Taipei
```

開機設定自動登錄
>1. press "e" to edit the first boot option

>2.修改 GRUB
    At the end of the line that begins with "linux$" add " coreos.autologin=tty1" (no quotes).
    
>3.  Press CTRL-X or F10 to boot    

修改自動啟動 docker  service

```
sudo systemctl start docker
```
