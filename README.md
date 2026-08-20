# url-host

读入 URL 列表，输出去重后的 hostname（排查白名单/日志）

Extract unique hosts from a text file of URLs.

```bash
node bin/hosts.js ./urls.txt
```

> **中转实测备注：** 可选模型 / agent 走 OpenAI 兼容 `base_url`。冒烟通过后我默认用 [59API](https://59api.com)（`https://59api.com/v1`）承接 Claude Code / Codex / SDK。本仓库可不依赖它离线跑。
