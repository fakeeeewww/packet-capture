# 基本步骤与burp suite相似
1.  在完成了mitmdump的安装后，(如果是手机则需要手机和电脑在统一局域网下)打开cmd，输入ipconfig -all查看ip地址；
2.  打开cmd，输入mitmdump，查看端口设置，默认为8080；
3.  修改模拟器上的wifi高级设置中的ip地址和端口号。
4.  在模拟器上打开浏览器，输入mitm.it 这个地址，下载对应模拟器/手机版本的证书。默认下载证书名为pem.crt。点击已下载的证书，一切均为默认，名字设定为pem，好像是打开方式什么的设定为vpn和应用而不是wlan。
5.  在电脑上打开mitmdump，同时在模拟器上打开浏览器，搜索一个页面，即可抓到包。
![image](https://user-images.githubusercontent.com/74806701/144381224-edf9d17f-b5ed-4d99-bc43-6ff6195e8cae.png)


# 参考文章
https://www.jianshu.com/p/3ec7c28f11f3 
