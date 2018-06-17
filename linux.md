# linux基本操作
### 1.注销重启关机
#### 01.logou 注销
#### 02.reboot 重启
```
- shutdown -r now #现在立即重启
- shutdown -r +3 #三分钟后重启
- shutdown -r 1212 #三分钟后重启
```
#### 03.shutdown 关机
```
- shutdown -h now #现在立即关机
- shutdown -h +3  “The System will shutdown after 3 minutes” #提示使用者将在三分钟后关机
- shutdown -h +5  #  5分钟后关机
- shutdown -h 1200  # 12点钟关机
- shutdown -c   # 取消关机操作
```
### 2.cd：切换目录
```
01. .cd # 回到当前用户的家目录
02. ～  #可用于表示用户家目录
03. cd etc # 切换到etc目录
04. cd - # 切换到上一次的目录
05. . #当前目录
06. .. #上一级目录
```
### 3.pwd
```
查看当前的工作路径
```

### 4.创建目录(文件夹)
```
01. mkdir 目录名 
    #mkdir my_dir
02.mkdir- p 
    #参数  递归创建目录，用于同时创建多级目录
    #例子 mkdir -p abcd 
```
### 5.修改密码
```
01. passwd #修改当前用户密码
02. sudo passwd username #更改制定用户密码,需要权限
```
### 6.获取帮助
01.-h
02.--help
03.info
04.man
```
001.man man  # 查看man命令的手册  
002.man cd 
003.man pwd 
man 5 passwd #第五章内passwd内容
man -k passwd # 模糊查找
man -f  passwd  # 精确查找 
```


