# cmfshop
后台文件：cmfshop.zip
<br>小程序文件：wei-cmf.zip
<br>数据库: cmf_address.sql
<br>访问后台：域名/admin,账号:admin,密码:123456
<br>插件列表，小程序插件填写相关信息
<br>问题反馈：qq:29285674 邮箱：29285674@qq.com
<br> 把wx_pay表中加一个notify字段：https://cmfshop.com/api/Pay/notify 域名改成自己的
<br> 把CartController中getWxpayInfo方法的$open_id获取方法改为$open_id = Db::name('third_party_user')->where('user_id', $order['uid'])->value('openid');
<br>本程序仅供学习和二次开发使用，教程本人正在录制中，后期会加上分销等功能，敬请期待
<br>
<br>![image](http://wx4.sinaimg.cn/mw690/0060lm7Tly1fw3bb82rbdj30cc0kl0u6.jpg)
<br>![image](http://wx1.sinaimg.cn/mw690/0060lm7Tly1fw3bc2c9tfj30bg0ju406.jpg)
<br>![image](http://wx4.sinaimg.cn/mw690/0060lm7Tly1fw3bcf9wq5j30bp0k6wfr.jpg)
<br>![image](http://wx3.sinaimg.cn/mw690/0060lm7Tly1fw3bbs42ioj30b90jracz.jpg)
<br>![image](http://wx3.sinaimg.cn/mw690/0060lm7Tly1fw3bctna4gj30cn0c4dgn.jpg)
<br>![image](http://wx3.sinaimg.cn/mw690/0060lm7Tly1fw3bf7736vj31gs0dtabb.jpg)
<br>![image](http://wx1.sinaimg.cn/mw690/0060lm7Tly1fw3bg2j670j31h507sdgd.jpg)
<br>![image](http://wx2.sinaimg.cn/mw690/0060lm7Tly1fw3bg5s6slj30wg0bgglu.jpg)
