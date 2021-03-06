# emerge

<img src="https://img.shields.io/badge/version-1.0-yellow" alt="https://img.shields.io/badge/version-1.0-yellow"  />
<img src="https://img.shields.io/badge/vue-2.6.10-brightgreen" />
<img src="https://img.shields.io/badge/electron-2.0.4-blue" /> 
<img src="https://img.shields.io/badge/monacoEditor-0.18.1-red" /> 
<img src="https://img.shields.io/badge/prettydiff-101.2.6-orange" /> 
<img src="https://img.shields.io/badge/artTemplate-4.13.2-inactive" /> 

# 可视化代码生成器

## 数据库和标签
通过新增数据库连接，和拖动标签实现对数据库表相关字段的自定义

![数据库](https://raw.githubusercontent.com/2507483326/emerge/master/static/img/sql.jpg)

![标签](https://raw.githubusercontent.com/2507483326/emerge/master/static/img/tag.jpg)

## 模板
模板采用art-template语法生成, 通过与数据库相关 table 、table.columns 等字段，实现针对于数据库表的代码生成

![模板](https://raw.githubusercontent.com/2507483326/emerge/master/static/img/template.jpg)

## 代码生成
通过选择需要生成的模板、和数据库表，生成模板到指定位置

![选择模板](https://raw.githubusercontent.com/2507483326/emerge/master/static/img/generate-01.jpg)

![选择数据库](https://raw.githubusercontent.com/2507483326/emerge/master/static/img/generate-02.jpg)

![完成](https://raw.githubusercontent.com/2507483326/emerge/master/static/img/finnish.jpg)

## 项目使用说明

emerge代码生成器主要是以MYSQL数据库表结合以artTemplate逆向自动生成前后端代码，减少前后端代码重复代码编写

项目主要实现功能

- mysql数据库连接
- 自定义表字段扩展
- 编辑器集成、模板编写、代码提示
- 代码生成
