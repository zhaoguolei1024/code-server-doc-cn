# 使用 UserLAnd 运行 code-server

1. 从 [Google Play](https://play.google.com/store/apps/details?id=tech.ula&hl=en_US&gl=US) 安装 UserLAnd
2. 安装一个Ubuntu VM
3. 启动应用
4. 用 `sudo apt install nodejs npm yarn curl -y` 安装 Node.js, `curl` ，`yarn`
5. 安装 `nvm`:

```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
```

6. 使用 `exit` 退出终端并重新打开终端
7. 安装并切换到 Node.js 16:

```shell
nvm install 16
nvm use 16
```

8. 使用 `npm i -g code-server` 在设备上全局安装code-server
9. 使用 `code-server` 运行code-server
10. 在浏览器中访问 `localhost:8080`
