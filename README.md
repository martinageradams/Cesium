# Cesium
An open-source JavaScript library for world-class 3D globes and maps :earth_americas:  

项目源地址：https://github.com/AnalyticalGraphicsInc/cesium  

`仅用作个人学习` `2018年10月7日`  
***
#### 运行
- 准备条件
```shell
$ npm -v
6.4.1

$ node -v
8.12.0
```
- 安装依赖
```shell
$ npm install
```

- 运行服务
```shell
$ node server
```
*默认会运行在本地服务器(即 localhost/127.0.0.1) 上*  
*使用命令行参数控制是否运行在所有服务器上*  

```shell
$ node server --public true     # 全服务器
{ address: '0.0.0.0', family: 'IPv4', port: 8080 }
Cesium development server running publicly.  Connect to http://0.0.0.0:8080/

$ node server --public false    # 本地服务器
{ address: '127.0.0.1', family: 'IPv4', port: 8080 }
Cesium development server running locally.  Connect to http://127.0.0.1:8080/
```
*进入 `server.js` 搜索 '8080' 修改端口号*  
***

#### 参考
 
> 1. [API Reference | cesiumjs.org](https://cesiumjs.org/refdoc/)  
> 2. [Cesium教程 | 火星科技|合肥火星科技|合肥火星科技有限公司](http://cesium.marsgis.cn/forcesium/tutorials/index.html)
> 3. [Cesium教程系列汇总 - fu*k - 博客园](https://www.cnblogs.com/fuckgiser/p/5706842.html)  
> 4. [cesium中文网 | 学习cesiumjs 的好地方--伐罗密](http://cesium.xin/wordpress/)
> 5. [绿色记忆:Cesium学习笔记](https://blog.gmem.cc/cesium-study-note)
> 6. [Cesium环境搭建 + 参考资料](https://blog.csdn.net/qq_18144905/article/details/80769981?utm_source=blogxgwz7)

