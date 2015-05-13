# node-mongooser

安装mongoose经常会报错的解决方案


## 问题

原因是mongoose依赖mongodb，mongodb里依赖mongodb-core，mongodb-core依赖bson

自动安装的bson不靠谱，需要自己安装

## 用法

    [sudo] npm install -g mongooser
    
然后切换到对应的有package.json的目录

    mongooser
    
完成。