# JavaReadWriteJson
java_json文件读写
Java的json文件读取（简单实现）
1、	java字符串和java对象互转（json-lib）需要准备如下jar包
 ![Alt Text](
     https://github.com/appliance/Scrapy_Selenium_PhantomJS/blob/master/1.png
    )

2、	读取json文件（实现如下）
 ![Alt Text](
     https://github.com/appliance/Scrapy_Selenium_PhantomJS/blob/master/1.png
    )
（需要花时间对java文件读写进行研究一下）

3、	创建javabean要和简单的json对象一样（不包括{{}}这种包含的复杂情况））
json内容如下：
 ![Alt Text](
     https://github.com/appliance/Scrapy_Selenium_PhantomJS/blob/master/1.png
    )
Javabean Player类属性如下
 ![Alt Text](
     https://github.com/appliance/Scrapy_Selenium_PhantomJS/blob/master/1.png
    )
4、	jsonArray获取json中的每一个转化对象
代码如下
 ![Alt Text](
     https://github.com/appliance/Scrapy_Selenium_PhantomJS/blob/master/1.png
    )
基本上如此就可以json文件读取实现了。

5、	java文件从文件尾部继续写入内容
代码如下：
![Alt Text](
     https://github.com/appliance/Scrapy_Selenium_PhantomJS/blob/master/1.png
    )
 


