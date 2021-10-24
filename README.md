# hoppinzq-jquery-zjax

#### 是什么？
zjax是基于JQuery的Ajax的拓展，是对原生ajax的二次封装。

#### 使用说明

1.  拉取代码，直接打开html即可。demo里上传文件的接口我是用本地后台的，你要测试文件上传监听进度，需要有一个接口。
2.  ```$.zjax({config})```
3.  ```$dom.zjax({$.extend(config,success:function(){//this.resporse,this.$dom})})```  
4.  ```$.zjaxChain({config}).zjaxChain({config}).zjaxChain({config}).runZjax()```

#### 特技

1.   支持缓存，锁定请求，绑定ajax到dom元素，链式请求，代理URL，自阻塞请求，文件上传进度跟踪，绑定遮罩，轮询，进入ZQ网关等功能。
2.   ajax返回值的缓存做的非常好
