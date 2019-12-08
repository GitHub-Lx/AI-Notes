# 常见问题解决

## 1. roscore 联网无法启动
vim .zshrc 或者 .bashrc，末尾加上：
```
export ROS_HOSTNAME=localhost
export ROS_MASTER_URI=http://localhost:11311
```
重新 source：
```
source .zshrc 或者 source .bashrc
```
问题解决。