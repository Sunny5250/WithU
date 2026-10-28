<div align="center">
  <img src="assets/icon.png" width="88" alt="WithU 图标" />
  <h1>WithU</h1>
  <p>在你的桌面，留一小块陪伴的位置。</p>
  <p>聊天 · 房间 · 记忆 · 日常互动</p>
  <p>
    <a href="https://github.com/Sunny5250/WithU/releases/latest"><img alt="最新版本" src="https://img.shields.io/badge/version-1.0.0-7b8d86?style=flat-square" /></a>
    <img alt="macOS" src="https://img.shields.io/badge/macOS-13%2B%20%C2%B7%20Apple%20Silicon-555?style=flat-square" />
    <img alt="Windows" src="https://img.shields.io/badge/Windows-10%20%2F%2011%20%C2%B7%20x64-555?style=flat-square" />
  </p>
  <p>
    <a href="https://github.com/Sunny5250/WithU/releases/latest/download/WithU-1.0.0-macOS-arm64.dmg"><strong>下载 Mac 版</strong></a>
    &nbsp; · &nbsp;
    <a href="https://github.com/Sunny5250/WithU/releases/latest/download/WithU-1.0.0-Windows-x64-Setup.exe"><strong>下载 Windows 版</strong></a>
    &nbsp; · &nbsp;
    <a href="https://github.com/Sunny5250/WithU/releases">更新记录</a>
  </p>
</div>

<br />

![WithU 的小房间](assets/room.png)

## 慢慢聊，也一起生活

一个待在桌面的小伙伴：可以聊几句、摸摸头、递点心，也可以一起布置房间，把相处中的片刻留下来。

| 陪伴方式 | 你可以做什么 |
| --- | --- |
| 桌面伙伴 | 选择女生或男生形象，在桌面快捷聊天，和伙伴互动 |
| 自然聊天 | 使用已有的 ChatGPT 订阅连接，发送照片、截图与表情，接收短句、网络图片和偶尔分条的回复 |
| 图片分享 | 直接粘贴、拖入或选择图片；查看网络图片来源，预览后分享网页或应用窗口截图 |
| 我们的房间 | 调整家具、配色和活动区域，查看心情、饱腹与精力 |
| 相处记忆 | 查看、修正或忘记聊天中积累的画像，收藏想留下的消息 |
| 日常小事 | 设置提醒、开始专注，玩石头剪刀布或骰子真心话大冒险 |

## 下载与安装

| 系统 | 安装包 | 安装方式 |
| --- | --- | --- |
| macOS 13+ · Apple Silicon | [DMG 下载](https://github.com/Sunny5250/WithU/releases/latest/download/WithU-1.0.0-macOS-arm64.dmg) | 打开安装包，将 WithU 拖入 Applications |
| Windows 10 / 11 · x64 | [EXE 下载](https://github.com/Sunny5250/WithU/releases/latest/download/WithU-1.0.0-Windows-x64-Setup.exe) | 跟随安装向导，可自行选择安装目录 |

Mac 安装包适用于 M 系列芯片，不支持 Intel Mac。Windows 安装包适用于 Intel / AMD x64。

无需安装其他开发环境。安装后，在设置的「软件更新」中检查、下载并安装新版本。开启「自动下载新版本」后，WithU 会在后台下载，并在「今天」页面提醒你安装；点击后重新打开应用，聊天、记忆和房间资料都会保留。

Windows 可在设置的「数据存储位置」选择空文件夹，迁移资料并重启。

## 账号与资料

- **AI 聊天沿用 ChatGPT 订阅授权。** 在设置中连接账号，使用账号可用的 Work / Codex 额度；实际可用性以账号授权结果为准。聊天、联网图片和表情搜索需要网络。
- **资料保存在本机。** Mac 为 `~/Library/Application Support/WithU`；Windows 默认为 `%APPDATA%\WithU`，可在设置中调整。
- **两端可手动迁移。** 在设置中导出 JSON 备份，再到另一台设备恢复。最大 256 MiB，备份不含登录凭据，新设备需要重新连接 ChatGPT。

聊天、选中的图片和用于回答的记忆会随 AI 请求发送给服务提供方；联网搜索会发送关键词。网络图片来自 Wikimedia Commons，并显示来源与许可信息。网页截图使用独立会话，不读取浏览器登录状态；应用窗口截图需选择并预览确认后分享。可在设置中关闭订阅推理与主动关怀，在「相处记忆」管理保留的内容。

## 1.0.0

支持每条消息附带最多四张图片，也可以只发图片。新增网络图片回复、网页截图与应用窗口截图分享，支持放大查看、保存及来源查看。图片随本机资料保留，可通过 JSON 备份在 Mac 与 Windows 间迁移。

本仓库用于发布安装包与使用说明，不包含维护源码。详细变更见 [Release](https://github.com/Sunny5250/WithU/releases/latest)。
