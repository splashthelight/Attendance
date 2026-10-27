# 到场点名

**[![在线体验](https://img.shields.io/badge/🚀_在线体验-attendance--en0.pages.dev-4CAF50?style=for-the-badge)](https://attendance-en0.pages.dev)**

一个无需构建的静态点名页面。直接在浏览器打开 `index.html` 即可使用。

## 功能

- 粘贴换行分隔的姓名，生成五列点名方格；自动忽略空行和重复姓名。
- 点击方格切换到场状态，支持正向和反转模式。
- 搜索姓名、只看未到场、复制名单、导出带 UTF-8 BOM 的 CSV。
- 使用浏览器 `localStorage` 保存名单和点名结果，刷新后自动恢复。

点名数据只保存在当前浏览器中，不会在不同设备之间同步。更换名单会清空旧名单的点名结果。

## 部署

这是纯静态站点。将仓库发布到 GitHub 后，可以用 Vercel 导入该仓库；无需安装依赖或配置构建命令，站点入口是仓库根目录的 `index.html`。
