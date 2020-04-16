
Github+jsDelivr为脚本/图片等静态文件加速的全球CDN
A-A+
我是小马甲~ 2020年3月16日 9 3906 次浏览 教程资源 | 网站资源 | 网络资源 Github | jsDelivr | jsDelivr CDN加速 | jsDelivr图床 | 免费CDN | 免费图床 | 静态文件CDN
文章目录

    使用限制
    操作步骤
    演示内容
    访问速度

Github+jsDelivr为脚本/图片等静态文件加速的全球CDN

Github是目前最大的项目的托管平台！19年年初的时候被微软收购了。免费套餐还支持私有仓库了！还真不错哇！可惜国内访问比较慢！！

jsDelivr提供npm，GitHub，WordPress等项目的镜像，全球加速访问！

针对Github提供免费的CDN加速，在国内使用的是网宿的CDN加速！访问速度一点儿都不慢！

那么我们就可以好好利用一下！下面博主就分享下使用过程把！

 
使用限制

    目前GITHUB仓库容量是没有上限的！不过官方推荐在1G以内！
    仓库单个文件50M会收到警告，大于100M会被拒绝！
    jsDelivr仅能针对50M以下的文件CDN加速！

 

这样看来我们完全可以利用它来存一些静态文件了，如JS,CSS,图片等等！

 
操作步骤

1）当然你得先有一个GITHUB账号！

 

2）新建一个仓库！名称随便即可！

 

3）我们新建一个js文件，然后提交！你也可以利用git本地推送！

 

 

4）点击【releases】，然后我们点击【Create a new release】!

PS：这里不创建releases也是可以的！

 

 

5）版本号输入1.0 ，目标是 master分支！

 

 

6）然后访问：https://cdn.jsdelivr.net/gh/用户名/仓库名@版本号/ 即可访问你的内容了！

如本文示例：https://cdn.jsdelivr.net/gh/malaohu/jscdn@1.0/

 

文件不想带版本号？将版本号换成latest即可！或者不带版本号！或者直接@master(或者其他分支名称)！

如：

https://cdn.jsdelivr.net/gh/malaohu/jscdn@latest/pic.png

https://cdn.jsdelivr.net/gh/malaohu/jscdn/pic.png

https://cdn.jsdelivr.net/gh/malaohu/jscdn@master/pic.png

直接@master，就不用新建releases了！

 

 

 
演示内容

20M压缩包：https://cdn.jsdelivr.net/gh/malaohu/jscdn@master/20M.zip

美图一张~~

 

 
访问速度

在国内有网宿CDN加速访问！

在国外有CloudFlare CDN加速访问！
线路 	最快节点 	最慢节点 	平均响应
电信 	江苏常州市电信0.07s 	广东中山市电信5.58s 	0.58s
联通 	北京北京市联通0.07s 	辽宁阜新市联通2.87s 	0.34s
移动 	天津天津市移动0.07s 	黑龙江鹤岗市移动8.85s 	0.68s
海外 	美国国外0.22s 	澳大利亚国外1.08s 	0.53s
教育网 	北京北京市教育网0.17s 	辽宁沈阳市教育网0.34s 	0.25s
香港 	香港香港0.05s 	香港香港0.19s 	0.12s
台湾 	台湾台湾0.09s 	台湾台湾0.18s 	0.14s
澳门 	澳门澳门0.12s 	澳门澳门0.12s 	0.12s

 

详细报告：http://www.17ce.com/site/http/20200315_4115e56066b111eab8bc2bbb7b33a12c:1.html

 

 
Related posts:

    #Rapid START#来自日本免费的网站CDN加速服务
    国内教育用户免费申请10000元Azure试用资源
    免费申请微信支付进件接口，费率最低0.38%
    XShell中转代理隧道设置，提高操作流畅速度！

原文链接：Github+jsDelivr为脚本/图片等静态文件加速的全球CDN，转发请注明来源！
