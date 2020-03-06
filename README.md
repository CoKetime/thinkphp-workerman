thinkphp5.1与workerman 小程序开发聊天室
=========

小程序配置修改
===
1修改utils/http.js 服务器请求地址<br>
2修改pages/chat/index.js 定位至方法webSocket 修改workerman请求地址<br>

thinkphp5.1配置修改
======
1:下载安装[GatewayWorker](http://workerman.net/gatewaydoc/)
=
2：安装[GatewayClient] <br>
==
命令：composer require workerman/gatewayclient  
=
3：thinkphp5 app.php配置文件成你的七牛云<br>
==
+----------------------------------------------------------------------<br>
    // | 七牛云设置<br>
    // +----------------------------------------------------------------------<br>
  	'ACCESSKEY' => '', //存储ACCESSKEY<br>
    'SECRETKEY' => '', //存储SECRETKEY<br>
    'BUCKET' => '', //存储空间名<br>
    'DOMAIN' => '',//存储空间域名<br>
    
    基本配置完成
    进入GatewayWorker目录下启动
    php start.php start
![image](https://github.com/CoKetime/thinkphp-workerman/blob/master/1583488350(1).jpg)
