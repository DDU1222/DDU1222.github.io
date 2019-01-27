# 晨雪的博客

### 工具类
*****
bankcard-validator：

业务场景：项目中需要对用户银行卡信息的正确性进行校验。一是为了减少乱输、输错的卡号提交到后端服务的请求次数，减少不必要的网络开销。二是为了避免错误卡号提交到银行处理，节省业务成本，提现专业性。故做成公共工具也能共同行们使用。

功能介绍： 1、Luhn算法（模10算法）检验银行卡号正确性 2、批量生成符合规则的银行卡号

[算法参考链接](https://www.jianshu.com/p/193d8b84a6a1)    
[校验银行卡号链接](https://ddu1222.github.io/bankcard-validator/bcValidator.html)   
[生成银行卡号链接](https://ddu1222.github.io/bankcard-validator/bcBuilder.html)
*****
fetch-polyfill：

业务场景：项目脱离jQuery，转为react技术栈，就考虑采用window下的fetch来承担发送请求的任务。但fetch又有些不足，没有超时和终止机制，故封装了一个fetch文件。

[项目地址](https://github.com/DDU1222/fetch-polyfill)
*****
batch-download:

业务场景：在前端mock开发时，有需要许多图片站位的需求。但是爬下来的都是图片的链接，那么如何通过这些链接批量下载图片呢？下载下来的图片太大想要压缩下怎么办呢？

功能介绍：图片链接数组批量下载到指定文件夹；利用tinify工具压缩图片；

[项目地址](https://github.com/DDU1222/Batch-download)

### 游戏类
*****

五子棋：    

![QQ20190127-175506-HD.gif](https://upload-images.jianshu.io/upload_images/3860275-becac677e1458e06.gif?imageMogr2/auto-orient/strip)


[项目地址](http://ddu1222.github.io/Five_chesses/)

*****

俄罗斯方块小程序：      

![QQ20190127-181728.gif](https://upload-images.jianshu.io/upload_images/3860275-399b372fd2276c97.gif?imageMogr2/auto-orient/strip)

[项目地址](https://github.com/DDU1222/tetris)

