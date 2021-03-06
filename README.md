# <center> Simple-Common-Core

<div style="text-align: center;">

[![](https://img.shields.io/badge/blog-%40SimpleStark-blue.svg)](https://simplestark.com)
[![](https://img.shields.io/badge/SpringBoot-2.3.12.RELEASE-blue.svg)]({https://docs.spring.io/spring-boot/docs/2.3.12.RELEASE/reference/html/})
[![](https://img.shields.io/badge/license-GPL2.0-orange.svg)](https://github.com/Simple-Stark/common/blob/master/LICENSE)

</div>

## 作者
[![](https://img.shields.io/badge/author-%40SimpleStark-blue.svg)](https://github.com/Simple-Stark)
- Github: [@Simple-Stark](https://github.com/Simple-Stark)
- Blog:[烟霞志](https://simplestark.com)
- Email:wrh_1125@163.com

## 简介

一个简单的项目公共jar包，一直有着做开源项目的想法，这个项目应该可以算做是地基，在以后的开源项目中我想应该是用得到。

## 支持功能
- [x] 全局统一消息返回
  - [x] 支持引用项目自定义消息返回
- [x] 全局异常拦截
  - [x] 自定义异常类
- [x] 全局日志配置
- [x] mybatisPlus 相关 
  - [x] 代码自动生成器
    - [x] 调整模板自动生成增删改查接口
    - [x] 生成对应Vo（PageResult、PageQuery、Vo）
  - [x] 自动填充创建用户（未完成）、创建时间、修改用户（未完成）、修改时间、删除标识、乐观锁
- [x] MybatisPlus 分页插件
- [x] ~~字典工具类~~
  - [x] ~~字典数据放入缓存~~
  - [ ] ~~生成控制层接口供前端调用~~
    - [x] ~~下拉框接口~~
    - [ ] ~~查询所有字典缓存接口~~
    - [ ] ~~手动添加、删除、修改字典接口~~
    - [ ] ~~手动刷新缓存容器接口~~
  - [ ] ~~自定义定时刷新字典缓存容器~~

## 使用

最佳实践：[![](https://img.shields.io/badge/@SimpleStark-SpringBootInit-blue.svg)](https://github.com/Simple-Stark/Spring-Boot-Init)

~~计划之后推送到中央仓库，在此之前只能下载源码自己mvn install安装到本地~~

~~2021-10-05 推送common包至中央仓库，在maven 项目中可以直接引入依赖~~

~~2022-06-26 名称修改为common-core，版本号修改为 0.1.0 推送至中央仓库，在maven 项目中可以直接引入依赖~~

2022-07-09 去除版本号，版本自选
```
<dependency>
  <groupId>com.simplestark</groupId>
  <artifactId>common-core</artifactId>
</dependency>
```

其他方式请参考：https://search.maven.org/artifact/com.simplestark/common-core

## License

[![](https://img.shields.io/badge/license-GPL2.0-orange.svg)](https://github.com/Simple-Stark/common/blob/master/LICENSE)

##

