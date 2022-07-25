# 重启
很久以前由于切换到了使用MacOS系统，所以一直在用欧陆词典。然去年我重新用回了Linux系统，发现使用GoldenDict，如果找到了好的本地词库，其易用程度远不是其他词典可以媲美的。以下为我重新收集的词库：


链接: https://pan.baidu.com/s/1yd8eTOnRICgza_W_bDfyxQ?pwd=76xg 提取码: 76xg 复制这段内容后打开百度网盘手机App，操作更方便哦


我收集的词库原本来源于：

http://louischeung.top:225/

https://downloads.freemdict.com/

这两个网站另外有很多其他英语学习相关的非常好用的资料。


==========
以下为七年前的旧内容，只有安装参考意义，词库请使用上面所述内容：

# GoldenDict

我的GoldenDict辞典配置文件和词库

[GoldenDict官网](http://goldendict.org/)

[GoldenDict维基百科](https://zh.wikipedia.org/wiki/GoldenDict)



## 声明

本源的词库均来自网络，仅供试用，如您发现有侵害您的版权，请联系作者删除之。



## 介绍

本源包含：

* 自定义配置文件
* 朗道英汉汉英字典词库
* 牛津英汉字典词库
* 21世纪英汉汉英字典词库
* 真人发音库
* Bing在线翻译网站索引
* [FORVO](http://zh.forvo.com/)在线网站发音索引





## 使用注意

该配置文件基于作者使用的系统Ubuntu14.04，Ubuntu10.04以上版本应该都可适用，但无法保证Win及Mac系统下的适用性，Win及Mac用户，可以尝试有道词典。




## 使用说明

```shell
sudo apt-get install goldendict

cd ~ && git clone https://github.com/yanyingwang/goldendict.git

ln -sf ~/goldendict/config ~/.goldendict

sudo ln -sf ~/goldendict/dictdd /usr/share/

cp ~/goldendict/goldendict.desktop ~/.config/autostart

```



## 截图示例

![1](https://raw.githubusercontent.com/yanyingwang/goldendict/master/screenshots/1.png)
![2](https://raw.githubusercontent.com/yanyingwang/goldendict/master/screenshots/2.png)
![3](https://raw.githubusercontent.com/yanyingwang/goldendict/master/screenshots/3.png)



