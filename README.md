# WindInput-Cangjie
清风输入法 仓颉五代输入方案，WindInput 平台

将Rime-Cangjie5的输入方案转换为WindInput-Cangjie5仓颉五代输入方案，



## 使用方法
1. 打包下载zip，
2. 把 `.\WindInput-cangjie` 里的文件复制到 `%APPDATA%\WindInput\schemas\cangjie5\`，也就是 `cangjie5\` 子目录，名字要和 `cangjie5.schema.toml` 里 `path` 写的 `cangjie5/…` 一致。
3. 把 `cangjie5.schema.toml` 放到 `schemas\`。
4. 在 `config.toml` 的 `schema.available` 里加上 "cangjie5"，重启输入法或切换到该方案。

