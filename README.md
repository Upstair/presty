# Presty v1.0.0

[![OSCS Status](https://www.oscs1024.com/platform/badge/Cat-Catalpa/core.svg?size=small)](https://www.oscs1024.com/project/Cat-Catalpa/core?ref=badge_small)
![Version-1.0](https://img.shields.io/badge/version-1.0-success)


Presty 是一款易上手、轻量级、完善化的后端PHP开发框架。

[框架官网](https://presty.catcatalpa.com) | [开发文档](https://doc.presty.catcatalpa.com) | [开源地址](https://github.com/catcatalpa/presty) | [开源协议](https://github.com/catcatalpa/presty/blob/master/LICENSE)

## 一、在使用本版本的Presty前，您需要了解以下重要事项：

1. Presty v1.0.0 对于 PHP 运行环境要求是 7.3 或以上。
2. 若您单独更新过框架核心文件版本，请注意您当前项目根目录下的`README.md`文件可能并不是适合您框架版本的最新版，请以`vendor/tomanday/presty`目录下的`README.md`文件为主。
3. 选择Presty版本时，请注意了解版本号中所表示的信息：
    - `dev` 表示此版本为早期研发版本，是为了验证框架是否能够正常运行而发布的版本，极其不稳定，非必要情况下请不要安装。
    - `alpha` 表示此版本为开发中版本，新版本功能尚未完全开发完成，稳定性低，不推荐安装。
    - `beta` 表示此版本为测试版本，新版本功能已基本完善，主要是各类Bug的修复，稳定性中等偏低，不推荐在生产环境中安装。
    - `patch` 表示此版本为上版本的补丁版本，修复了一些致命性Bug，其余安全性、稳定性较前一个版本有所提高。
---

## 二、Presty v1.0.0-dev-3 更新日志：

- 新增控制器中间件机制
- 新增注解解析器
- 控制器支持在注解中调用中间件
- 完善了系统中间件监听功能
- 优化了控制台输出样式
- 控制器基类新增中间件相关控件
- 修复了助手函数部分函数名不匹配的错误
- 修复了部分命名大小写及拼写的错误
- 将symfony/console包加入了感谢名单
- 修复了其他已知Bug

## 三、框架已获得以下机构的认证

[![墨菲安全](https://www.murphysec.com/assets/logo.6a136b81.svg)](https://old.murphysec.com/dr/ajgI6mrQe7eRYZmc0J)


## 四、特别感谢

Presty在开发时借助了以下开源项目的帮助，特在此向这些开源项目及其作者予以感谢。

|       项目名       |   作者    | 开源协议 |                     开源地址                     |  代码用途   | 使用程度  |
|:---------------:|:-------:|:----:|:--------------------------------------------:|:-------:|:-----:|
| symfony/console | symfony | MIT  | [Github](https://github.com/symfony/symfony) | 构建控制台命令 | 使用源代码 |


