# cashbook-lzcapp

项目已升级为 LPK v2。每天 23:00 UTC 检查 `dingdangdog/cashbook` 稳定版本，自动复制 `linux/amd64` 应用镜像、创建版本化 LPK Release，并提交懒猫官方商店和喵喵私有商店。PostgreSQL 镜像不由自动更新管理。

需要显式配置 `LAZYCAT_TOKEN`、`APPSTORE_URL`、`APPSTORE_TOKEN`；`APP_ID` 和 `PRIVATE_STORE_GROUP_CODES` 可选。组织 Secret 必须授权本仓库。
