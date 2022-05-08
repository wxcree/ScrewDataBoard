# ScrewDataBoard
> A simple business intelligence system that can easily analyze xlsx data uploaded by users

一个简单的商务智能系统，可以使用户上传自定义图表快捷的进行多维分析并且导出图表。

## 快速开始
```bash
# node/14.19.1
cd app-client
yarn install
yarn build

cp -r dist ../app-server/

cd ../app-server
yarn install
yarn start
```

## 功能介绍
1. 导入csv、xlsx表格类文件并保存为原始数据集
2. 对应不同的业务可以创建不同的数据包
2. 选定数据集进行表格处理、多维分析
3. 可以把表格处理、多维分析的结果保存为用户数据集
4. 可选定数据集快速导出图表📈