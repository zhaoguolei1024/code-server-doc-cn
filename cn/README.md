# code-server

[!["GitHub Discussions"](https://img.shields.io/badge/%20GitHub-%20Discussions-gray.svg?longCache=true&logo=github&colorB=purple)](https://github.com/coder/code-server/discussions) [!["Join us on Slack"](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=brightgreen)](https://coder.com/community) [![Twitter Follow](https://img.shields.io/twitter/follow/CoderHQ?label=%40CoderHQ&style=social)](https://twitter.com/coderhq) [![codecov](https://codecov.io/gh/coder/code-server/branch/main/graph/badge.svg?token=5iM9farjnC)](https://codecov.io/gh/coder/code-server) [![See latest](https://img.shields.io/static/v1?label=Docs&message=see%20latest&color=blue)](https://coder.com/docs/code-server/latest)

您可以在任何地方、任何机器上运行 [VS Code](https://github.com/Microsoft/vscode)并在浏览器中访问它

![Screenshot](./assets/screenshot.png)

## 优点特性

- 在具有一致开发环境的任何设备上编写代码
- 使用云服务器加速测试、编译、下载等
- 在旅途中保持电池寿命；所有密集型任务都在您的服务器上运行

> **Note**
> 要管理多个 IDE、工作区和团队，请参阅我们的新项目: [coder/coder](http://cdr.co/coder-github)

## Requirements

请参阅最低规格要求[requirements](requirements.md)，以及有关如何设置可以安装`code-server`的 Google VM 的说明。

**TL;DR:** 2核1G 的 Linux 服务器并支持WebSockets

## Getting started

There are three ways to get started:

1. Using the [install
   script](https://github.com/coder/code-server/blob/main/install.sh), which
   automates most of the process. The script uses the system package manager if
   possible.
2. Manually [installing
   code-server](https://coder.com/docs/code-server/latest/install)
3. Using our one-click buttons and guides to [deploy code-server to a cloud
   provider](https://github.com/coder/deploy-code-server) ⚡

If you use the install script, you can preview what occurs during the install
process:

```bash
curl -fsSL https://code-server.dev/install.sh | sh -s -- --dry-run
```

To install, run:

```bash
curl -fsSL https://code-server.dev/install.sh | sh
```

When done, the install script prints out instructions for running and starting
code-server.

We also have an in-depth [setup and
configuration](https://coder.com/docs/code-server/latest/guide) guide.

## 常见问题

[常见问题](https://coder.com/docs/code-server/latest/FAQ).

## 贡献人员

详细信息，请参阅贡献[Contributing](https://coder.com/docs/code-server/latest/CONTRIBUTING)

## 招聘

有兴趣在 [Coder](https://coder.com/careers) 工作吗？查看我们的[空缺职位](https://coder.com/careers#openings)！

## 组织

想要为您的组织或企业进行远程开发？访问我们的网站以了解有关 [Coder](https://coder.com) 的更多信息
