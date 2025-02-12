---
title: Read me
---

## Features

- 🦄 Open source and free forever
- 🚀 Support for self-hosting with `Docker` in seconds
- 📜 Plain textarea first and support some useful Markdown syntax
- 👥 Set memo private or public to others
- 🧑‍💻 RESTful API for self-service
- 📋 Embed memos on other sites using iframe
- #️⃣ Hashtags for organizing memos
- 📆 Interactive calendar view
- 💾 Easy data migration and backups

## Deploy with Docker in seconds

### Docker Run

```docker
docker run -d --name memos -p 5230:5230 -v ~/.memos/:/var/opt/memos neosmemo/memos:latest
```

> `~/.memos/` will be used as the data directory in your machine and `/var/opt/memos` is the directory of the volume in Docker and should not be modified.

### Docker Compose

- Provided docker compose YAML file: [`docker-compose.yaml`](./docker-compose.yaml).

- You can upgrade to the latest version memos with:

```sh
docker-compose down && docker image rm neosmemo/memos:latest && docker-compose up -d
```

### Other installation methods

- [Deploy on render.com](./docs/deploy-with-render.md)
- [Deploy on fly.io](https://github.com/hu3rror/memos-on-fly)

## Contribute

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated. 🥰

Learn more about contributing in [development guide](./docs/development.md).

### Products made by our Community

- [Moe Memos](https://memos.moe/) - Third party client for iOS and Android
- [lmm214/memos-bber](https://github.com/lmm214/memos-bber) - Chrome extension
- [Rabithua/memos_wmp](https://github.com/Rabithua/memos_wmp) - WeChat MiniProgram
- [qazxcdswe123/telegramMemoBot](https://github.com/qazxcdswe123/telegramMemoBot) - Telegram bot
- [eallion/memos.top](https://github.com/eallion/memos.top) - A static page rendered with the Memos API
- [eindex/logseq-memos-sync](https://github.com/EINDEX/logseq-memos-sync) - A Logseq plugin
- [JakeLaoyu/memos-import-from-flomo](https://github.com/JakeLaoyu/memos-import-from-flomo) - Import data. Support from flomo, wechat reading.
- [Send to memos](https://sharecuts.cn/shortcut/12640) - A shortcut for iOS.
- [Memos Raycast Extension](https://www.raycast.com/JakeYu/memos) - Raycast extension, [source code](https://github.com/JakeLaoyu/memos-raycast).

### User stories

- [Memos - A Twitter Like Notes App You can Self Host](https://noted.lol/memos/)

## Acknowledgements

- Thanks [Uffizzi](https://www.uffizzi.com/) for sponsoring preview environments for PRs.

## License

[MIT License](https://github.com/usememos/memos/blob/main/LICENSE)

## Star history

[![Star History Chart](https://api.star-history.com/svg?repos=usememos/memos&type=Date)](https://star-history.com/#usememos/memos&Date)
