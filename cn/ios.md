# 在 iOS 通过 iSH 使用 code-server

1. 从 [App Store](https://apps.apple.com/us/app/ish-shell/id1436902243) 安装 iSH
2. 使用 `apk add curl nano` 安装 `curl` 和 `nano`
3. 配置 iSH 用于 NodeJS 较早的版本，并在两个存储库`v3.14` 和 `v3.12`链接上进行编辑 `nano /etc/apk/repositories`
4. 使用 `apk add nodejs npm` 安装 `nodejs` 和 `npm`
5. 使用 `curl -fsSL https://code-server.dev/install.sh | sh` 安装code-server
6. 使用 `code-server` 运行code-server
7. 在浏览器中访问 localhost:8080
