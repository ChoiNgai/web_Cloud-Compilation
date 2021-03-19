## 云编译系统

开发时间为2020年1月至2020年3月，该项目主要是因为深度学习训练所需环境受限，故开发一个与已有的web在线编译平台相似的系统部署在自己的服务器上。
该项目中技术栈以JavaScript、vue.js为主 , 依靠docker完成后端环境的部署。我负责的部分是前端，使用微软开源的`monaco editor`完成web端的前端界面。

合作者：[ZhiHang Liu](https://leetcode-cn.com/u/lzh-18/)（架构+后端+整合）

## 使用教程

1. 在服务器端进入解压该文件，安装nodejs，进入steup文件夹，按顺序运行文件夹内的文件

   ```shell
   ./ Dockerfile
   ./ Install.sh
   ./ UpdateDocker.sh
   ```

   

2. 在文件根目录下打开终端输入`npm start`

3. 打开服务器端口，其他电脑通过ip+端口访问