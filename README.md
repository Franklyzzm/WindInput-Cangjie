# WindInput-Cangjie
清风输入法 仓颉五代输入方案，WindInput 平台

将Rime-Cangjie5的输入方案转换为WindInput-Cangjie5仓颉五代输入方案，



## 使用方法
1. 打包下载zip，
2. 把 `.\WindInput-japanese` 里的三个文件复制到 `%APPDATA%\WindInput\schemas\japanese\`，也就是 `japanese\` 子目录，名字要和 `japanese.schema.toml` 里 `path` 写的 `japanese/…` 一致。
3. 把 `japanese.schema.toml` 放到 `schemas\`，`schema_overrides\japanese.toml` 放到 `schema_overrides\`。
4. 在 `config.toml` 的 `schema.available` 里加上 "japanese"，重启输入法或切换到该方案。

