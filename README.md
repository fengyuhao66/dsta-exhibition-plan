# DSTA 3F Exhibition Plan

这是 3F 布展交互方案的 GitHub Pages 发布仓库。

## 页面功能

- 默认公开浏览：访客可以查看平面图、搜索作品、筛选节点、查看作品详情。
- 授权编辑：输入验证码 `DSTA-T` 后可进入编辑模式。
- 编辑模式可调整布局、替换图片、修改信息、新增展位、导入/导出 JSON、导出 CSV。

## GitHub Pages 发布方式

进入仓库设置：

`Settings → Pages → Build and deployment → Source → Deploy from a branch`

选择：

`Branch: main`

`Folder: /root`

保存后，公开浏览链接通常为：

https://fengyuhao66.github.io/dsta-exhibition-plan/

## 重要说明

当前验证码属于静态网页前端权限，适合防止误操作；如果需要真正的多人权限管理和云端同步保存，后续应接入后端数据库或登录系统。