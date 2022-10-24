谷歌翻译服务已正式退出中国，通过修改Host的方法可以实现谷歌翻译复活。   
1. 在host文件内加入以下的配置即可
~~~
180.163.151.34 translate.googleapis.com
~~~
2.  或者通过[SwitchHosts](https://swh.app/zh)来配置。Host类型选择远程，在URL栏填入一下地址   
~~~
https://raw.githubusercontent.com/bovindev/google-translate-host/master/hosts
~~~
