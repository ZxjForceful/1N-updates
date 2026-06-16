# 1N Updates

这个仓库只负责公开发布一念写作插件的更新元数据和 `.vsix` 安装包。

## 目录

- `latest.json`：当前最新版本元数据
- `downloads/`：按版本号命名的 `.vsix` 安装包

## 发布约定

- 每个 `.vsix` 文件名必须带版本号，不覆盖旧文件
- `latest.json` 只指向当前最新版本
- 插件端只需要读取 `latest.json`，发现新版本后提示用户下载对应 `.vsix`
