# 导出项目规范
> 梗概：本页手册详解了导出项目规范

$\color{red} {注意：所有导出并发布的TGW项目必须加密！} $

## 基础项目的导出
- 关于如何导出项目到指定平台，请阅读[Godot官方手册-导出项目](https://docs.godotengine.org/en/stable/tutorials/export/exporting_projects.html)，在此不再赘述

## 导出加密的项目版本
- 对于TGW项目来说，为防止恶意拆包/逆向，应当对导出结果进行进行加密，这一过程实际上通过[Godot的PCK加密](https://docs.godotengine.org/zh-cn/4.x/contributing/development/compiling/compiling_with_script_encryption_key.html)实现
- 请在导出前向项目管理员申请加密模板以及密钥

