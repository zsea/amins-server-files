存储amis-server为中打包的amis.asar的解压文件，用于jsdelivr使用

# 目录结构

以版本号为根目录，根目录下按照项目要求，所有文件放于html文件夹下，所以访问一个js访问的路径为：```/0.4.1/html/amis/sdk.js```。

# 使用方法

使用```hadmin```0.5.0以上版本，添加以下参数启动。

```
--amis https://cdn.jsdelivr.net/gh/zsea/amis-server@master/0.4.1```
```