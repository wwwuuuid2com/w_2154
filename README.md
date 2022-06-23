# w_2154
Let正版短信测压开源源码
<br/></br>
[下载地址](https://www.uuid2.com/2154.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>Let正版短信测压开源源码<p>
<p>源码仅供学习参考，不附带接口。<p>
<p>安装教程<p>
<p>php调至7.2以上
设置伪静态为thinkphp<p>
<p>设置网站运行目录为public<p>
<p>编辑根目录下的.env文件配置数据库信息<p>
<p>导入数据库dkewl.sql
默认后台地址/admins   默认账号密码admin/123456
ADMIN_PATH = admins
在此配置后台路径<p>
<p>新建一个站点，上传并编辑根目录下的sub.php
然后提交计划任务进行监控
可多个服务器挂脚本分担压力
如果客户端套了cdn导致无法正常执行脚本可以尝试添加白名单
这边建议使用MySQL方式 同服务器下直接配置数据库信息即可
多台服务器请将数据库账户权限设置成公开<p>
<p>计划任务1秒监控shell脚本<p>
<p>计划任务重启php
/etc/init.d/php-fpm-72 restart
推荐加上释放内存 半小时一次<p>
<p>用户提交订单api<p>
<p>http://域名/api/index/submit?key=用户KEY&phone=手机号&time=执行时间<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202206/5769f5a259.png" alt="Let正版短信测压开源源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202206/5769f5a752.png" alt="Let正版短信测压开源源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202206/5769f5a127.png" alt="Let正版短信测压开源源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202206/5769f5a152.png" alt="Let正版短信测压开源源码">
