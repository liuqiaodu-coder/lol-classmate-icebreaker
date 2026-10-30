# lol-classmate-icebreaker

以英雄联盟世界赛为话题的 QQ 同学群破冰 Agent。本仓库通过 Release 提供 Linux/Docker 部署包。

## 下载安装包

前往 [Releases](https://github.com/liuqiaodu-coder/lol-classmate-icebreaker/releases)，下载附件 `lol-classmate-icebreaker-v1.0.0-github-ready.zip`。请下载这个附件，不要下载 GitHub 自动生成的 `Source code.zip`。

## 运行条件

需要 Linux、Docker Compose v2、专用机器人 QQ 号和对话模型 API Key。群记忆与媒体理解还需要相应的模型服务及配置。

## 安装

```bash
unzip lol-classmate-icebreaker-v1.0.0-github-ready.zip
cd lol-classmate-icebreaker/deploy
./setup.sh
```

按向导提示扫码登录 QQ，并在 AstrBot 面板配置模型。详细步骤见安装包内的 `README.md` 和 `tutorial/图文教程.md`。

## 状态与许可

v1.0.0 是提交候选版；干净服务器上的完整 QQ 消息闭环仍待验收。原创内容和第三方组件适用不同许可证，详见安装包内的 `LICENSE` 与 `THIRD_PARTY_NOTICES.md`。
