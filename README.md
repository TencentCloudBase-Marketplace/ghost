<p align="center">
  <img height="100px" src="./logo.svg" center />
</p>

# [Ghost](https://github.com/TryGhost/Ghost)

Ghost 是一套基于 Node.js 构建的开源博客平台（Open source blogging platform），具有易用的书写界面和体验。

## 部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&tdl_anchor=github&tdl_site=0&appUrl=https://github.com/TencentCloudBase-Marketplace/ghost)

### 配置

- `database__client`：数据库类型，支持 `mysql`、`postgres`、`mariadb`、`mssql` 或 `sqlite`
- `database__connection__host`：数据库 Host
- `database__connection__port`： 数据库端口
- `database__connection__user`： 数据库用户
- `database__connection__password`： 数据库密码
- `database__connection__database`： 数据库名称
- `logging__path`：日志路径

更多配置参考：https://ghost.org/docs/concepts/config/

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
