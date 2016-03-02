# Auto-Proxy-Toggle
Auto Proxy Toggle for Alfred workflows  

这个workflows的功能是关闭或开启Mac下的系统自动代理设置，方便那些使用PAC的朋友。
由于是在[Proxy Toggle](https://github.com/dalang/alfred-workflows)的基础上修改来的，所以用法和[Proxy Toggle](https://github.com/dalang/alfred-workflows)类似，下面的一些使用说明是复制过来的。
关键词默认是apt

因为使用networksetup设置Auto Proxy需要sudo权限，所以使用了Authenticate.app来保存用户名密码，第一次使用会提示输入用户密码。

如果Authenticate的窗口未自动弹出，请手动点击workflow目录内的Authenticate.app。 你可以通过Alred Preferentces -> Workflow -> Auto Proxy Toggle -> Show in Finder 进入workflow目录。


使用效果如下：
![image](https://github.com/a3587556/Auto-Proxy-Toggle/blob/master/usage.png)
