# HAKO-CMS
箱·CMS系统停止公开
</br>
箱·CMS 是一款蜂巢式的CMS系统,采用PHP+AJAX+MYSQL数据库.自主实现MVC模式,兼容所有浏览器(IE 6-11,Firefox,Safari,Chrome,Opera).
</br>
</br>
系统支持:</br>
1.支持WINDOWS与LINUX平台.
</br>
</br>
安装方法:
</br>
1.将除hako_cms_install.sql外的所有文件上传至网站根目录.
</br>
</br>
2.连接至MYSQL数据库,新建库hako_cms编码选择utf8.
</br>
</br>
3.选择hako_cms库,执行hako_cms_install.sql中的内容.
</br>
</br>
4.修改/model/connmodel.php中mysql_connect的三个参数,依次对应MYSQL数据库地址,数据库用户名,数据库密码.
</br>
</br>
5.访问:"http://您的域名/index.php?c=admin&a=load&p=login",进行管理员操作,默认用户名:Admin,密码:111111.登录后请尽快修改密码.
</br>
</br>
作者:jkkj93
