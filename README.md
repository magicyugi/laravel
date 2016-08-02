﻿# Laravel Angular Admin
使用技术:Laravel + Angularjs + Angulartrap + AdminLTE + Rquirejs
11 


## Screenshots
![api](http://a1.qpic.cn/psb?/V11BOt0S4MAKLC/OrsvIoievKOW5N7nLGQr7ZaSFquKk6JcMMfWee1SDlM!/b/dOQAAAAAAAAA&bo=*ASAAgAAAAADB1g!&rf=viewer_4)

![create code](http://a2.qpic.cn/psb?/V11BOt0S4MAKLC/EenzPVIrRJV.Eo25f4kXRpKjqdwZNSlJgbWLrobEpaU!/b/dAwBAAAAAAAA&bo=tgSAAgAAAAADBxI!&rf=viewer_4)

![data](http://a3.qpic.cn/psb?/V11BOt0S4MAKLC/.yI5Ri3vs0YhqQJRrR35uER6DJzvHfdvOPl*aZPXpmM!/b/dNoAAAAAAAAA&bo=xgSAAgAAAAADAGU!&rf=viewer_4)


![index](http://a2.qpic.cn/psb?/V11BOt0S4MAKLC/0jGOAqd7u*Hq4bYUtYyWheVC7G*Ydw0dzZgwtcjlrhs!/b/dI0BAAAAAAAA&bo=nASAAgAAAAADBzg!&rf=viewer_4)

## Demo



![laradmin](https://cloud.githubusercontent.com/assets/1888261/15561320/1899b4b2-2327-11e6-8a3a-7e3d7ce31621.png)

## 安装:
**要求:**

一. php >=5.6

二. 安装好composer

**php.ini文件需要开启**
```
```
1. extension=php_fileinfo.dll
2. always_populate_raw_post_data = -1
3. extension=php_openssl.dll

```
$ git clone https://github.com/zsping1989/laravel.git

$ cd laravel/

$ git checkout dev

$ composer install
```

1. 根目录创建 ```.env``` 文件
2. 修改好数据库等相关配置
3. cmd到项目根目录

```
$ php artisan migrate --seed
```
* 将站点目录指向根目录下的public(/public);
* 路由访问:/admin/index
* Note: 登录用户名:13699411148 密码:123456

