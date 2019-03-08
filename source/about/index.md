---
title: About
layout: post
---


# **关于我**
<img src='https://dha4w82d62smt.cloudfront.net/items/2E05363w3V2l0F3L083C/CA%20Logo.png?' align='right' style=' width:200px;height:200 px'/>

· 高中生
· 喜欢摄影，拍Vlog，平面设计，制图，后期，程序开发，航天器，折腾
· Sony粉，Google粉，Apple粉
· 个人标示包括：CA，Carter，CarterJimmy等
· 联系方式详见Footer。



###### 设备
· iPhone8
· iMac 21.5 inch Mid 2013 Late & 2010 Late
· Thinkpad W540
· iPad Mini 4
· VIAO


***


# 关于本站

### 定位与内容
* 主要用于记录日常生活以及些许技术向的文章。


### 历史

|    版本 | 博客程序   |   域名     |   持续时间 |
| :----: |   :----:  | :----:    |   :----:  |
| 1      | Wordpress |  cabl.ml  | 2012-2013 |
| 2      | Wordpress |  cabl.ml  | 2013-2014 |
| 3      |    Hexo   | ca2te.com | 2017-  ∞  |


### 域名
* 基于英文名Carter的发音 `/'kɑ:tə/`, 而构思出的域名。
* 发音为：英文的Ca + 普通话的“2”的发音 + 英文的Te。连起来也就是Carter。


### 折腾史
* 2017.10.1 Github公共仓库设置完毕
* 2017.12.11 在Namesilo购买当前域名ca2te.com
* 2017.12.12
  * 雏形完成，托管Github
  * backup分支设置，通过该分支进行备份作业
* 2017.12.14
  * 第一编博文`Hello World`诞生
  * 解决域名无限重定向问题
  * 强制Https访问。小绿锁Get✅
* 2017.12.16 再次出现无限重定向问题，移除`Header.ejs`的重定向代码后解决
* 2017.12.19 新增Links页面
* 2017.12.24 添加媒体播放器`aplayer`，本地调试
* 2017.12.26
  * 部署`aplayer`，并添加文档到LIM
  * Fontawesome的矢量图出现无法显示的问题
* 2017.12.27 修复上述问题
* 2017.12.28-29
  * 更换Markdown渲染引擎，并使其支持GFM(Github Flavored Markdown)语法
  * 修复移动端部分显示错位问题
  * 解决Checkbox无法显示的问题
  * 删除无效源码
  * 处理无效引用资源
  * 压缩部分过大的多媒体
  * 同步LIM
* 2017.12.30
  * 增加点击后加载Disqus功能以提升加载速度
  * 加入Lazyload
* 2018.1.1
  * 加入ServiceWorker缓存方案
  * 加入Prefetch方案


### 其他
· 目前托管在Github上，使用的主题是自己修改过的[Daily](https://github.com/GallenHu/hexo-theme-Daily)←原版 [修改版](https://github.com/CarterJimmy/LIM)
· 评论系统是使用Disqus，搜索系统使用Google的搜索命令
· 图床·外链使用[CloudApp](https://www.getcloudapp.com)的Team Plan以及[Flickr](https://www.flickr.com/photos/146675969@N03/)
· 域名在Namesilo购买
· 使用CloudFlare的CDN以及SSL加密服务。




## **本站运行时间**

<!-- time -->
<!-- Count Form 0(=1) -->
<script>
  function secondToDate(second){
    if(!second){return 0}var time=new Array(0,0,0,0,0);
    if(second>=365*24*3600){time[0]=parseInt(second/(365*24*3600));
      second%=365*24*3600}if(second>=24*3600){time[1]=parseInt(second/(24*3600));
      second%=24*3600}if(second>=3600){time[2]=parseInt(second/3600);
      second%=3600}if(second>=60){
        time[3]=parseInt(second/60);
        second%=60}
      if(second>0){time[4]=second}
      return time};

  function setTime(){
    var create_time=Math.round(new Date(Date.UTC(2017,11,12,00,24,30)).getTime()/1000);
    var timestamp=Math.round((new Date().getTime()+8*60*60*1000)/1000);
      currentTime=secondToDate((timestamp-create_time));
      currentTimeHtml=currentTime[0]+'年'+currentTime[1]+'天'+currentTime[2]+'小时'+currentTime[3]+'分'+currentTime[4]+'秒';
    document.getElementById("htmer_time").innerHTML=currentTimeHtml}
  setInterval(setTime,1000);
</script>

本站已稳定运行 **<span class="sidebar-badge" id="htmer_time"></span>**
***

# **服务以及捐助**
· Shadowsocks代理服务 （付费订阅制）

> Server端搭建于Raspberry Pi 3
>
> 目前还没确认是否开启该服务，有此需求的访客可以留言，根据需求情况决定。

· 推广链接：[Dropbox](https://db.tt/JROjAFY7Np)(注册可+500MB)
