# node-mongooseinstaller

安装mongoose经常会报错的解决方案

[![npm version](https://badge.fury.io/js/mongooseinstaller.svg)](http://badge.fury.io/js/mongooseinstaller)

## 问题

原因是mongoose依赖mongodb，mongodb里依赖mongodb-core，mongodb-core依赖bson

自动安装的bson不靠谱，需要自己安装

## 用法

    [sudo] npm install -g mongooseinstaller
    
然后切换到对应的有package.json的目录

    mi
    mongoosei
    mongooseinstaller
    
完成。