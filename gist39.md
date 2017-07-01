[《windows下php开发环境搭建》 zeronet](https://github.com/chenjia404/how-to-self-programming/blob/master/php/windows%E4%B8%8B%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA.md)
https://blog.chenjia.info/ 
[一个牛逼的交互式脑图](https://learn-anything.xyz/design/graphic-design/photoshop)
[如何免费建立一个永远在线博客](https://blog.chenjia.info/2017/06/online-blog.html)
官网:https://zeronet.io/
[ShutIt：一个基于Python的shell自动化框架](http://geek.csdn.net/news/detail/202105)
[您的用户遇到BUG了吗](https://fundebug.com/dashboard/594ccc061e2fb100144b983e/errors/inbox?filters=%7B%7D)
[喜欢用 Git 做的一些小事](https://segmentfault.com/a/1190000009753465)
```js
但如果你对团队成员在项目中的提交数量感兴趣，使用 shortlog 就可以找到答案：

$ git shortlog -sn
    80  Harry Roberts
    34  Samantha Peters
     3  Tom Smith
     
$ git shortlog -sn --since='10 weeks' --until='2 weeks'
    59  Harry Roberts
    24  Samantha Peters
    
 通过一种比较轻松的游戏的方式来一探全貌https://github.com/Gazler/githug   
  $ git blame -L5,10 _components.buttons.scss
  仅显示单词的变化而不是整行git diff --word-diff
 git for-each-ref --count=10 --sort=-committerdate refs/heads/ --format="%(refname:short)" 查看最近工作的分支 
  去除这种空白提示非常容易，在 git diff 和 git show 使用 -w 选项就可以轻松搞定
  http://159.226.40.104:18080/dev/  看到每个人都在做什么
  git log --all --oneline --no-merges
  git config --global alias.overview "log --all --since='2 weeks' --oneline --no-merges"
  
   Chrome 扩展插件「档案娘助手」，一键删除所有微博、删除所有转发微博、删除所有包含某些关键词的微博、删除某些日期的微博
  
```
[在简书发一片文章，自动同步到知乎、公众号、微博。这个应该就可以做到](https://sspai.com/post/38989)
[中科院计算所开源了Easy Machine Learning系统，其通过交互式图形化界面让机器学习应用开发变得简单快捷](https://github.com/ICT-BDA/EasyML)
http://159.226.40.104:18080/dev/


[微博关系图功能正式上线了](http://weibo.wbdacdn.com/weibo/friends/3217179555/)



[]()
```js
Math.min() < Math.max() // false 因为Math.min() 返回 Infinity, 而 Math.max()返回 -Infinity。
const Greeters = []

for (var i = 0 ; i < 10 ; i++) {
 Greeters.push(function () { return console.log(i) })
}
Greeters[0]() // 10
Greeters[1]() // 10
Greeters[2]() // 10
有两种方法：
- 使用`let`而不是`var`。备注：可以参考Fundebug的另一篇博客[ES6之"let"能替代"var"吗?](https://blog.fundebug.com/2017/05/04/why-you-should-not-use-var/)
- 使用`bind`函数。备注：可以参考Fundebug的另一篇博客[JavaScript初学者必看“this”](https://blog.fundebug.com/2017/05/17/javascript-this-for-beginners/)
 
Greeters.push(console.log.bind(null, i))
typeof [] === 'object' // true 需要使用`Array.isArray(var)`。
1 === 1 // true
// 然而这些不行
[1,2,3] === [1,2,3] // false
{a: 1} === {a: 1} // false
{} === {} // false
`new Date(2016, 1, 1)`不会在1900年的基础上加2016，而只是表示2016年。
JavaScript默认使用字典序(alphanumeric)来排序。因此，[1,2,5,10].sort()的结果是[1, 10, 2, 5]。

如果你想正确的排序，应该这样做：[1,2,5,10].sort((a, b) => a - b)
node -e 'console.log(3 + 2)'
node -p '3 + 2'



```
[Layer 子域名挖掘机4.1 全新重构 + 175万大字典](http://paper.seebug.org/113/)
[电商购物网站 - 需求与设计](https://segmentfault.com/a/1190000009926042)
[基于浏览器插件的数据抓取工具](https://github.com/easychen/catgate)
[Feigong - 针对各种情况自由变化的 mysql 注入工具](http://paper.seebug.org/124/)
https://github.com/LoRexxar/Feigong/tree/old
[brut3k1t - 一款模块化的服务端暴力破解工具](http://paper.seebug.org/119/)
[Web 前端代码规范](https://segmentfault.com/a/1190000009935766)
[Solutions collection of my LeetCode submissions](https://github.com/hijiangtao/LeetCodeOJ)
[linux Bash-Snippets](https://github.com/alexanderepstein/Bash-Snippets)
[tp5基于workerman实现browsersync开发利器](http://www.thinkphp.cn/extend/1006.html)
composer require workerman/workerman  github地址：https://github.com/skj198568/browser_sync
[看看大家在上线了上创建的精彩网站吧](https://www.sxl.cn/s/discover)
[当你难过的想死的时候回来看一眼这条微博。 ​​​​](http://weibo.com/5650770554/F8Zy6tfFC?type=comment)
[JavaScript中的数据结构和算法学习](http://caibaojian.com/learn-javascript.html?)
[深入理解 Python 浮点数](https://mp.weixin.qq.com/s/FTZT2x5TeZTmlKqGLDh0JQ)
```js
>>> 1/3
0.3333333333333333

>>> 0.1234567890123456789
0.12345678901234568
>>> 0.1 * 3 == 0.3
False

>>> (0.1 * 3).hex()  # 显然两个存储内容并不相同。
0x1.3333333333334p-2

>>> (0.3).hex()
0x1.3333333333333p-2
>>> s = (1/3).hex()

>>> float.fromhex(s)  # 反向转换回浮点数。
0.3333333333333333
round(0.1 * 3, 2) == round(0.3, 2)  # 避免不确定性，左右都使用固定精度。
round(0.1, 2) * 3 == round(0.3, 2)

>>> int(2.6), int(-2.6)
(2, -2)
>>> from math import trunc, floor, ceil

>>> trunc(2.6), trunc(-2.6)  # 截断小数部分。
(2, -2)

>>> floor(2.6), floor(-2.6)  # 往小数字方向取最近整数。
(2, -3)

>>> ceil(2.6), ceil(-2.6)  # 往大数字方向取最近整数。
(3, -2)
>>> 1.1 + 2.2   # 结果与 3.3 近似。
3.3000000000000003

>>> (0.1 + 0.1 + 0.1 - 0.3) == 0  # 同样二进制近似值计算结果与十进制预期不符。
False
>>> from decimal import Decimal

>>> Decimal("1.1") + Decimal("2.2")
Decimal('3.3')

>>> (Decimal("0.1") + Decimal("0.1") + Decimal("0.1") - Decimal("0.3")) == 0
True
有些文章宣称 “奇舍偶入” 或 “五成双” 等
```
[利用新接口抓取微信公众号的所有文章](https://mp.weixin.qq.com/s/fT4wZckEX69ZJbiZ0JGjqA)
```js
import requests
import redis
import json
import re
import random
import time
 
gzlist = ['yq_Butler']
 
 
url = 'https://mp.weixin.qq.com'
header = {
    "HOST": "mp.weixin.qq.com",
    "User-Agent": "Mozilla/5.0 (Windows NT 6.1; WOW64; rv:53.0) Gecko/20100101 Firefox/53.0"
    }
 #http://www.bilibili.com/video/av11127609/
with open('cookie.txt', 'r', encoding='utf-8') as f:
    cookie = f.read()
cookies = json.loads(cookie)
response = requests.get(url=url, cookies=cookies)
token = re.findall(r'token=(\d+)', str(response.url))[0]
for query in gzlist:
    query_id = {
        'action': 'search_biz',
        'token' : token,
        'lang': 'zh_CN',
        'f': 'json',
        'ajax': '1',
        'random': random.random(),
        'query': query,
        'begin': '0',
        'count': '5',
    }
    search_url = 'https://mp.weixin.qq.com/cgi-bin/searchbiz?'
    search_response = requests.get(search_url, cookies=cookies, headers=header, params=query_id)
    lists = search_response.json().get('list')[0]
    fakeid = lists.get('fakeid')
    query_id_data = {
        'token': token,
        'lang': 'zh_CN',
        'f': 'json',
        'ajax': '1',
        'random': random.random(),
        'action': 'list_ex',
        'begin': '0',
        'count': '5',
        'query': '',
        'fakeid': fakeid,
        'type': '9'
    }
    appmsg_url = 'https://mp.weixin.qq.com/cgi-bin/appmsg?'
    appmsg_response = requests.get(appmsg_url, cookies=cookies, headers=header, params=query_id_data)
    max_num = appmsg_response.json().get('app_msg_cnt')
    num = int(int(max_num) / 5)
    begin = 0
    while num + 1 > 0 :
        query_id_data = {
            'token': token,
            'lang': 'zh_CN',
            'f': 'json',
            'ajax': '1',
            'random': random.random(),
            'action': 'list_ex',
            'begin': '{}'.format(str(begin)),
            'count': '5',
            'query': '',
            'fakeid': fakeid,
            'type': '9'
        }
        print('翻页###################',begin)
        query_fakeid_response = requests.get(appmsg_url, cookies=cookies, headers=header, params=query_id_data)
        fakeid_list = query_fakeid_response.json().get('app_msg_list')
        for item in fakeid_list:
            print(item.get('link'))
        num -= 1
        begin = int(begin)
        begin+=5
        time.sleep(2)
```
[python求职Top10城市，来看看是否有你所在的城市](https://mp.weixin.qq.com/s?__biz=MzI2NjY5NzI0NA==&mid=2247483767&idx=1&sn=26f1e8c43084f9e4859031d54148fe33&chksm=ea8b6e04ddfce7125d2463732557e1f4f4655271f745c83149adcf2feb0fbdecd9eb2566a110&scene=21#wechat_redirect)
[一个轻量级PHP开源接口框架](https://github.com/phalapi/phalapi)
[MathLive是一个用于渲染和编辑数学公式的Javascript库](http://www.ctolib.com/arnog-mathlive.html)
[NSC2017第五届中国网络安全大会](https://github.com/xisigr/paper/blob/master/NSC2017%E7%AC%AC%E4%BA%94%E5%B1%8A%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8%E5%A4%A7%E4%BC%9A/%E6%B5%8F%E8%A7%88%E5%99%A8%E5%9C%B0%E5%9D%80%E6%A0%8F%E4%B9%8B%E5%9B%B0.pdf)



[Python：一篇文章掌握Numpy的基本用法](https://mp.weixin.qq.com/s/qWottPMuvkAvKz1z2TBZ_A)
```js
# 基于list
arr1 = np.array([1,2,3,4])
print(arr1)
# 基于tuple
arr_tuple = np.array((1,2,3,4))
print(arr_tuple)
# 二维数组 (2*3)
arr2 = np.array([[1,2,4], [3,4,5]])
# 一维数组
arr1 = np.arange(5)
print(arr1)
# 二维数组
arr2 = np.array([np.arange(3), np.arange(3)])
arr2
```

[用Pandas获取商品期货价格并可视化](https://mp.weixin.qq.com/s?__biz=MzI2NjY5NzI0NA==&mid=2247483676&idx=1&sn=09c35c1f4bf1ddc8c19c532829bd3964&chksm=ea8b6e6fddfce77983eb87e3870d186c15e911b9020523eef9a325f2f1a10e9b0ee99fa1d23a&scene=21#wechat_redirect)
[基于PHP实现的信息收集与SQL注入漏洞扫描工具](http://www.freebuf.com/sectool/137238.html)
git clone https://github.com/Tuhinshubhra/RED_HAWK
[检测 PHP 应用的代码复杂度](https://mp.weixin.qq.com/s/mJS2jqZIFMyKblFq1iCw0Q)
composer global require 'phploc/phploc=*' composer global require 'phpmetrics/phpmetrics'
[什么是动态规划](https://mp.weixin.qq.com/s/5tUYURKzvSeLBkg0Pdhzow)
[py爬虫](http://blog.csdn.net/wds2006sdo?viewmode=contents)
[localtunnel：将内网地址转化成公网地址npm install -g localtunnel](https://github.com/localtunnel/localtunnel)
[微博上的那些神评论](https://m.weibo.cn/p/23126100007540126469068801)
[将纯文本转成漂亮的手绘框图。 ​​​​](http://shakydraw.com/)
[一个python源码库的搜索引擎，搜到一些偏门的python库](http://nullege.com/)
[MySQL 分区表原理及使用详解](http://www.codeceo.com/article/mysql-partition.html)
```js
show variables like '%partition%';
mysql> select 
 ->   partition_name,
 ->   partition_expression,
 ->   partition_description,
 ->   table_rows
 -> from 
 ->   INFORMATION_SCHEMA.partitions
 -> where
 ->   table_schema='test'
 ->   and table_name = 'emp';
 explain partitions select * from emp where store_id=10 \G; partitions:p1 表示数据在p1分区进行检索。
```
[JavaScript 常用的简写技术](https://segmentfault.com/p/1210000009906328/read)
const answer = x > 10 ? 'is greater' : 'is lesser';
const variable2 = variable1 || 'new';
for (let i = 0; i < 10000; i++) {}
for (let i = 0; i < 1e7; i++) {}

// 下面都是返回true
1e0 === 1;
1e1 === 10;
[MySQL之一道关于GROUP BY的经典面试题](http://www.revotu.com/mysql-groupby-classic-interview-question.html)
```js



有一张shop表如下，有三个字段article，author，price。选出每个author的price最高的记录（要包含所有字段）。
SELECT article,author,MAX(price)
FROM shop
GROUP BY author;

SELECT article, author, price
FROM SHOP s1
WHERE price = (SELECT MAX(s2.price)
			   FROM shop s2
			   WHERE s1.author = s2.author);
SELECT article, s1.author, s1.price
FROM shop s1
JOIN (
	SELECT author, MAX(price) AS price
	FROM shop
	GROUP BY author) AS s2
	ON s1.author = s2.author AND s1.price = s2.price;
SELECT s1.article, s1.author, s1.price
FROM shop s1
LEFT JOIN shop s2
ON s1.author = s2.author AND s1.price < s2.price
WHERE s2.article IS NULL; 当 s1.price 是当前author的最大值时，就没有 s2.price比它还要大，所以此时s2的rows的值都会是NULL
```
[Luna 是一个新推出的可视化、函数式编程语言](http://t.cn/RGSaFN9)
[免费在线视频下载](https://www.apowersoft.cn/online-video-downloader)
[如何文艺地说我爱你？](http://weibo.com/1742566624/F9cwD2VdY)
[itchat+pillow实现微信好友头像爬取和拼接](https://github.com/15331094/wxImage)
```js
from numpy import *
import itchat
import urllib
import requests
import os

import PIL.Image as Image
from os import listdir
import math

itchat.auto_login(enableCmdQR=True)

friends = itchat.get_friends(update=True)[0:]

user = friends[0]["UserName"]

print(user)

os.mkdir(user)

num = 0

for i in friends:
	img = itchat.get_head_img(userName=i["UserName"])
	fileImage = open(user + "/" + str(num) + ".jpg",'wb')
	fileImage.write(img)
	fileImage.close()
	num += 1

pics = listdir(user)

numPic = len(pics)

print(numPic)

eachsize = int(math.sqrt(float(640 * 640) / numPic))

print(eachsize)

numline = int(640 / eachsize)

toImage = Image.new('RGBA', (640, 640))


print(numline)

x = 0
y = 0

for i in pics:
	try:
		#打开图片
		img = Image.open(user + "/" + i)
	except IOError:
		print("Error: 没有找到文件或读取文件失败")
	else:
		#缩小图片
		img = img.resize((eachsize, eachsize), Image.ANTIALIAS)
		#拼接图片
		toImage.paste(img, (x * eachsize, y * eachsize))
		x += 1
		if x == numline:
			x = 0
			y += 1


toImage.save(user + ".jpg")


itchat.send_image(user + ".jpg", 'filehelper')
```
[百度网盘之家](http://wowenda.com/)
[Python编写的文字到语音的转换。](https://pythonprogramminglanguage.com/text-to-speech/)

[微博加密神器](http://resource.haorenao.cn/tse.html)
```js
  <h1>微博加密神器 by 斌叔</h1>
    <h3>使用方法：将想发的内容填入加密。对方查看时到这个网址用同样的钥匙解密。</h3>

    <p>钥匙（记住你的钥匙，解密时需要一个钥匙才能解密）</p>
    <input type="" name="" id="key">
    <p>输入</p>
    <textarea id="input1" cols="50" rows="10"></textarea>
    <br>
    <button id="encode">加密</button> <button id="decode">解密</button>
    <p>输出</p>
    <div id="after">
    </div>
  $("#encode").click(function() {
    var myString   = $('#input1').val().trim();
    var myPassword = $('#key').val().trim();
    console.log(myString);
    console.log(myPassword);

    if (myPassword == "" || myString == "") {
      alert('输入不全！');
      return;
    }

    var encrypted = CryptoJS.AES.encrypt(myString, myPassword);

    $('#after').html(encrypted.toString());
    console.log(encrypted);
  });

    $("#decode").click(function() {
    var myString   = $('#input1').val();
    var myPassword = $('#key').val();
    console.log(myString);
    console.log(myPassword);
        if (myPassword == "" || myString == "") {
      alert('输入不全！');
      return;
    }

    var decrypted = CryptoJS.AES.decrypt(myString,myPassword).toString(CryptoJS.enc.Utf8);

    $('#after').html(decrypted);
    console.log(decrypted);
  });
  
  
```
[给定一个整数数组，其中有两项之和为一个特定的数字，假设每次 input 只有一个唯一解，不允许两次使用同一个元素，返回这两个数的索引。](https://github.com/barretlee/daily-algorithms/issues/1)
```js
给定 nums = [2, 7, 11, 15]，target = 9

由于 nums[0] + nums[1] = 9
所以返回 [0, 1]
const resolveTwoSum = (nums, target) => {
  for (let i = 0; i < nums.length - 1; i++) {
    for (let j = i; j < nums.length; j++) { 
      if (nums[i] + nums[j] === target) {
        return [i,j]; 
      }
    }
  }
}
```
[文字转换器, 将文字转成倒序](http://old.haorenao.cn/reverse/)
```js
$(document).ready(function() {
	$('#reverse').click(function() {
		var text = $('#orig').val();
		var ll = [];
		for (var i = 0;i < text.length;i++) {
			var c = text.charAt(i);
			ll.push(c);
		}
		ll.reverse();
		var s = ll.join("");
		$('#result').val(s);
	});
});
```
