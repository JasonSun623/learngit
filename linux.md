# 网络问题

```
sudo ifconfig docker0 down
/etc/init.d/networking restart
```

安装docker 0 导致

```
sudo apt-get remove bcmwl-kernel-source
```

安装其他驱动覆盖导致

软件商店有时候会报错：

has install snap change in progress 

是由于正在进行安装导致

```
snap changes
```

显示所有的进程

```
abort <the progress number>
```

# 后台管理 

采用 nohup command & 

重定向输出文件 ： 

nohup python -u gcn_v2_lei/train.py >train.log 2>&1 &  (针对 python 而言， 重定向到 train.log )

# 内核问题

内核更换会导致系统监测不到硬件，比如无线网卡....

查看内核 uname -r

# Linux on windows

file location : 

C:\Users\dell\AppData\Local\Packages\CanonicalGroupLimited.Ubuntu18.04onWindows_79rhkp1fndgsc\LocalState\rootfs
