# Ajian CasaOS AppStore

基于 CasaOS AppStore V2 格式的个人应用商店，仅通过 GitHub Release 发布最新版。

## 添加应用源

```text
https://github.com/AjianNie/CasaOS-appstore/releases/download/new/AppStore.zip
```

每次推送应用配置或元数据后，GitHub Actions 会重新构建并覆盖 `new` Release。仓库中的 `Apps`、`Apps_arm`、`Apps_arm64` 和 `Apps_pre` 目录保留少量示例，用于后续添加应用和架构适配。
