#Android Weight 样例    
match_parent和wrap_content权值下区别    
#离线更新gradle方式：  
由于GFW,应该配置clone后的此文件："gradle-wrapper.properties" 目录为工程下：gradle/wrapper中    
用下面这个Url:  
distributionUrl=file:///D:/gradletools/gradle-2.2.1-all.zip 
#原理： 
将本地目录+包名，拷贝到浏览器地址栏中，例如我的本地地址为：   
D:\gradletools\gradle-2.2.1-all.zip   
按下回车，浏览器即可自动转义成对应地址，无需处理其他转义字符    
#截图示例：  
![示例](https://github.com/somewhater/AndroidWeightDemo/blob/master/picture/layout-2015-12-18-143012.png) 
#match_parent-------1:10=10:1
#wrap_content-------1:10=1:10