# Mooder_next团队贡献系统

Mooder_next是从Mooder二次开发而来的产物。

关于Mooder的介绍移步(https://github.com/phith0n/mooder)

## 为什么会有Mooder_next

由于原作者未响应合并请求（大概已经放弃了这个历史项目），现开启新分支进行后续开发，新分支更名为：Mooder_next。

## How to run

### 使用 all in one docker 镜像

1. 基于默认文件修改配置文件

    ```bash
    cp .env.default_aio .env
    ```

2. `docker-compose -f docker-compose_aio.yml up -d`

## 站在巨人的肩膀上

感谢原作者开发、开源这么优秀的项目，Mooder_next会添加更多功能，使得更加便于使用。


## Change Log
- 2024-09-06
  - 新增前台搜索功能
- 2024-08-14
  - 新增公告系统，升级方法，首先拉取代码，然后更新数据库：1、`python manage.py makemigrations`2、`python manage.py migrate`
- 2024-07-04
  - 新增pillow依赖，解决验证码无法生成问题（根据本地开发环境补全）
- 2024-05-21
  - 补充依赖版本号（根据本地开发环境补全）
- 2024-04-17
  - 添加后台评论管理功能
- 2022-07-01
  - 修复礼物页面报错

## 开源协议

使用Mooder、Mooder_next请遵守LGPL协议。

## 案例

![image](https://github.com/user-attachments/assets/9ab880e6-93fe-4c63-8b71-7ffda831bc48)
[https://wiki.shikangsi.com](https://wiki.shikangsi.com)
