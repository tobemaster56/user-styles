# user-styles

个人自定义样式合集，适用于 [Stylus](https://github.com/openstyles/stylus) 浏览器扩展。

## 样式列表

### X（推特）互关检查助手

检查你的关注列表里，对方有没有回关你。在【正在关注】页面中：

- 未回关的账号：红色边框 + 红色背景标记
- 已互关的账号：隐藏，只显示未回关的

| 文件 | 说明 |
|------|------|
| `src/styles/x-unfollow-detector.css` | 完整版，包含更多规则 |
| `src/styles/x-unfollow-detector-clean.css` | 清爽版，只保留核心功能 |

**安装方式：** 在 Stylus 扩展中导入对应 CSS 文件即可。

**适用页面：** `https://x.com/` 关注列表页

## 开发

```bash
pnpm install
```
