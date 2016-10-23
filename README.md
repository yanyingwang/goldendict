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



