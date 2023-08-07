# 在线版本


## 一行代码搭建机器人开发环境(ROS/ROS2/ROSDEP)

```
wget http://fishros.com/install -O fishros && . fishros
```

目前支持工具：
```
一键安装:ROS(支持ROS和ROS2,树莓派Jetson) 
一键安装:VsCode(支持amd64和arm64)  
一键安装:github桌面版(小鱼常用的github客户端) 
一键安装:nodejs开发环境(通过nodejs可以预览小鱼官网噢  
一键配置:rosdep(小鱼的rosdepc,又快又好用)  
一键配置:ROS环境(快速更新ROS环境设置,自动生成环境选择)  
一键配置:系统源(更换系统源,支持全版本Ubuntu系统)  
一键安装:Docker(支持amd64和arm64)  
```

# 自定义版本

下载工程到本地

这里以docker+ros的自定义为例

在工程文件夹中的tools文件夹修改相应的文件：`tool_install_ros_with_docker.py`

回到工程文件夹目录

用Python运行`install.py`文件即可

`python3 install.py`

