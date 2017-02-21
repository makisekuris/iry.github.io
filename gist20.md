###[python编码](https://zhuanlan.zhihu.com/p/25272901)
```js
print sys.getdefaultencoding()    #系统默认编码 ascii
当需要将unicode格式的字符串存入到文件时，python内部会默认将其先转换为Str格式的系统编码，然后再执行存入步骤。而在这过程中，容易引发ascii异常。
#! -*- coding:utf-8 -*-
#python程序开头加上这句代码，指定python源代码编码格式为utf-8。
a=u"中文"
f=open("test.txt","w")
f.write(a)
报错异常信息：UnicodeEncodeError: ‘ascii’ codec can’t encode characters in position 0-1……
说明：因为ascii不支持中文，而变量a为unicode格式的中文字符串，因此无法进行编码而引发异常。
windows控制台为gbk编码，而变量a本身为utf-8编码。
变量a是str格式，编码为utf-8的字符串，我们要将之转化为str格式，GBK编码的字符串。
在python内部无法直接转化，需要借助decod()与encode()函数。decode()函数先将str格式的字符串a转化为unicode，再将unicode编码为str格式GBK。


#! -*- coding:utf-8 -*-
a='你好'
b=a.decode("utf-8").encode("gbk")
print b

python2.x从外部获取的内容都是string编码，其内部分为String编码与Unicode编码，而String编码又分为UTF-8，GBK，GB2312等等
。因此为了避免不同编码造成的报错，python内部最好都转化为unicode编码，在输出时再转化为str编码 。
可以用encode()/decode()函数，将string与unicode编码互换。
 在windows下，最好将文件内容转为unicode，可以使用codecs：

f=codecs.open("test.txt", encoding='gbk').read()

#! -*- coding:utf-8 -*-
a=u"中文"  #a为unicode格式编码
f=open("test.txt","w")
f.write(a.encode("gbk"))
python代码内部请全部使用unicode编码，在获取外部内容时，先decode为unicode，向外输出时再encode为Str

a="\\u8fdd\\u6cd5\\u8fdd\\u89c4" # unicode转化为中文
b=a.decode('unicode-escape')
print b
```
###[PyShell 木马后门](http://thief.one/2016/09/05/PyShell-%E6%9C%A8%E9%A9%AC%E5%90%8E%E9%97%A8/)

https://github.com/tengzhangchao/PyShell/
###[基于Python的WebServer](http://thief.one/2016/09/14/%E5%9F%BA%E4%BA%8EPython%E7%9A%84WebServer/)
https://github.com/tengzhangchao/PyWebServer 
python PyWebServer.py -h
python PyWebServer.py -i 10.0.0.1 -p 8888   ##指定ip与端口,默认为8888
PyWebServer.exe -h  
PyWebServer.exe -p 8888      ##指定端口,默认为8888

###[PyCmd 加密隐形木马](http://thief.one/2016/09/18/PyCmd-%E5%8A%A0%E5%AF%86%E9%9A%90%E5%BD%A2%E6%9C%A8%E9%A9%AC/)

	https://github.com/tengzhangchao/PyCmd
python PyCmd.py -u http://10.0.3.13/test/p.php -p test [--proxy]
python PyCmd.py -u http://192.168.10.149:8080/Test/1.jsp -p test [--proxy]
###[windows服务器信息收集工具](http://thief.one/2016/09/04/windows%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%BF%A1%E6%81%AF%E6%94%B6%E9%9B%86%E5%B7%A5%E5%85%B7/)
https://github.com/tengzhangchao/InForMation 
information.exe -i start -L start -s start  运行所有功能
information.exe -i start  运行收集系统信息功能