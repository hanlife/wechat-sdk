# wechat-JS-SDK-demo

###此项目暂时用于测试新版微信JS-SDK的分享API
#####*注意：分享API的调用需要确保您的appid是否通过了微信的官方认证，这一点是关键，否则无法成功调用分享API*

## 文件夹说明

####nodejs文件夹下为Nodejs
#####微信数字签名只能由服务器端生成
#####这里数字签名生成示例用于放在NodeJS服务器环境下，用于产生微信JS-SDK的数字签名服务

#####nodejs/apps-info.js为微信appid及secret的配置文件
#####nodejs/routes/index.js为签名生成服务逻辑
<br />

####client-web文件夹下为浏览器端普通WEB页
#####会请求nodejs下运行的数字签名服务，用于测试微信分享API及其它

#####*注意：服务端可以换成任意其它语言，为演示方便我使用了NodeJS版*


[更多介绍](http://www.cnblogs.com/willian/p/4254963.html)

