#SDK
语音这获取的sdk放入build_shell 目录中

- mix 离在线版本
- offline 纯离线版本
- online 在线版本

之后根据sdk的zip文件名，新建一个目录。如果是google play的专用版本，则加gp后缀。

修改switch.sh 

bash build_shell/switch.sh online normal
即可切换普通online版本

bash pack.sh 
打包4个线上版本
