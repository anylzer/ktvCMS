# KTVCMS

##简介

## 目录结构

初始的目录结构如下：

~~~
www  WEB部署目录（或者子目录）
├─application           应用目录
│  ├─index        模块目录
│  │  ├─controller      控制器目录
|  |  |  └─
│  │  ├─model           模型目录
|  |  |  └─
│  ├─command.php        命令行工具配置文件
│  ├─common.php         公共函数文件
│  ├─config.php         公共配置文件
│  ├─route.php          路由配置文件
│  ├─tags.php           应用行为扩展定义文件
│  └─database.php       数据库配置文件
│
├─public                WEB目录（对外访问目录）
│  ├─index.php          入口文件
│  ├─router.php         快速测试文件
│  └─.htaccess          用于apache的重写
│
├─thinkphp              框架系统目录
│  ├─lang               语言文件目录
│  ├─library            框架类库目录
│  │  ├─think           Think类库包目录
│  │  └─traits          系统Trait目录
│  │
│  ├─tpl                系统模板目录
│  ├─base.php           基础定义文件
│  ├─console.php        控制台入口文件
│  ├─convention.php     框架惯例配置文件
│  ├─helper.php         助手函数文件
│  ├─phpunit.xml        phpunit配置文件
│  └─start.php          框架入口文件
│
├─extend                扩展类库目录
├─runtime               应用的运行时目录（可写，可定制）
├─vendor                第三方类库目录（Composer依赖库）
├─build.php             自动生成定义文件（参考）
├─composer.json         composer 定义文件
├─LICENSE.txt           授权说明文件
├─README.md             README 文件
├─think                 命令行入口文件
~~~

## 接口计划

> `✘`表示未完成、`✔`表示已完成、`~`表示在完善

| 编号 | 功能        | 完成情况 |
|:---:| ----------- | :------: |
| 一、| **【用户】**|         |
| 1   |    登录     |    ✔  |
| 2   |    注册     |    ?   |
| 3   |  创建房间   |        |
| 4   |  加入房间   |        |
| 5   |    点歌     |        |
| 6   |    顶歌     |        |
| 二、| **【歌曲】**|        |
|     |    播放     |        |
| 9   |    上传     |        |
| 10  |    下载     |        |
| 11  | 搜索(按热度)|        |
| 12  | 搜索(按拼音)|        |
| 13  | 搜索(按类型)  |        |
| 三、| **【歌手】**|        |
|     |    添加    |         |
|     | 搜索(按地域) |         |
| 四、| **【房间】**|        |
|     |   创建      |        |
|     |   加入      |        |
|     |            |         |
| 五、   | **【推荐】**|        |



