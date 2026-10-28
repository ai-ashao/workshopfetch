<div align="center">

<a href="https://workshopfetch.com/zh-cn">
  <img src="assets/logo.png" alt="WorkshopFetch" width="88">
</a>

# WorkshopFetch

**查询 Steam 创意工坊 Mod、地图等内容的下载方式。**

粘贴创意工坊链接或 Published File ID。Steam 返回公开直链时直接打开；没有直链时，获取对应的 SteamCMD 命令，在自己的电脑上运行。

[![官网](https://img.shields.io/badge/官网-workshopfetch.com-e36b25?style=flat-square)](https://workshopfetch.com/zh-cn)
[![使用方法](https://img.shields.io/badge/指南-使用方法-171714?style=flat-square)](https://workshopfetch.com/zh-cn/how-to-use)
[![语言](https://img.shields.io/badge/语言-15_种-777365?style=flat-square)](https://workshopfetch.com/zh-cn)

**[打开 WorkshopFetch →](https://workshopfetch.com/zh-cn)**

[English](README.md) · 简体中文

</div>

[![WorkshopFetch 中文首页：输入创意工坊链接或 ID，查询下载方式](assets/home-zh-cn.jpg)](https://workshopfetch.com/zh-cn)

## WorkshopFetch 是什么？

[WorkshopFetch](https://workshopfetch.com/zh-cn) 是一个免费的在线工具，一次查询一个公开的 Steam 创意工坊内容。它向 Steam 查询公开信息，并展示 Steam 当前提供的下载方式。查询本身无需注册 WorkshopFetch 账号，也不需要安装软件。

这里是 WorkshopFetch 的官方产品介绍与使用文档仓库。网站业务源码保持私有。

## 为什么用它？

- **输入链接或 ID 即可查询。** 支持单个创意工坊内容的页面链接，或数字 Published File ID。
- **先核对内容。** 查看 Steam 返回的标题和所属游戏，确认是自己需要的 Mod 或地图。
- **有 Steam 直链就直接打开。** 只有 Steam 返回经过校验、属于允许的 Steam 下载域名的 HTTPS 公开链接时，才显示下载按钮。
- **没有直链时，获取本地 SteamCMD 指引。** 复制该内容对应的命令，并按照教程在自己的电脑上安装和运行 SteamCMD。
- **本站不存储或中转文件。** 不托管、缓存或重新分发创意工坊文件；直链下载由浏览器直接访问 Steam CDN。
- **支持 15 种语言。** 包括英语、简体中文、繁体中文、巴西葡萄牙语、土耳其语、印尼语、越南语、西班牙语、德语、俄语、日语、法语、波兰语、韩语和意大利语。

## 三步使用

1. **复制单个内容的链接。** 在 Steam 创意工坊打开目标内容，复制页面地址，例如 `https://steamcommunity.com/sharedfiles/filedetails/?id=122941542`。
2. **[打开 WorkshopFetch](https://workshopfetch.com/zh-cn) 查询。** 粘贴链接或数字 ID，点击「查询下载方式」。
3. **使用返回的结果。** 有公开 Steam 直链时打开直链；没有时，按该内容的 SteamCMD 指引在本机尝试运行。

示例仅用于说明输入格式，不代表该内容一定存在公开直链，或一定能够通过 SteamCMD 下载。

## 如何理解查询结果？

| 查询结果 | 接下来怎么做 |
| --- | --- |
| Steam 返回有效的公开文件链接 | 打开下载链接，直接访问 Steam CDN。 |
| Steam 返回内容信息，但没有公开文件链接 | 查看对应的 SteamCMD 命令和本地使用教程。 |
| 无法查询到内容 | 检查链接、内容可见性和 Steam 服务状态，并参考下方故障排查指南。 |

SteamCMD 需要在你自己的电脑上运行。WorkshopFetch 不会代为执行，也不会索取 Steam 密码。能否下载取决于游戏、所有权、登录状态、可见性和访问权限；生成命令不代表下载一定成功。

## 使用指南

- [WorkshopFetch 使用方法](https://workshopfetch.com/zh-cn/how-to-use)
- [SteamCMD 安装与创意工坊使用教程](https://workshopfetch.com/zh-cn/blog/steamcmd-workshop)
- [如何找到创意工坊内容的 ID](https://workshopfetch.com/zh-cn/blog/find-steam-workshop-id)
- [创意工坊下载卡住或不下载：故障排查](https://workshopfetch.com/zh-cn/blog/steam-workshop-download-stuck)
- [查看游戏指南](https://workshopfetch.com/zh-cn/games)

## 常见问题

### 免费吗？需要注册账号吗？

WorkshopFetch 免费使用，无需注册本站账号。但下载某些内容时，Steam 或游戏本身仍可能要求登录或拥有游戏。

### 所有创意工坊内容都能下载吗？

不能保证。只有 Steam 提供公开链接时才有直链；SteamCMD 的访问条件也因游戏和内容而异。WorkshopFetch 不能绕过游戏所有权、私有内容限制或其他访问规则。

### 本站会保存 Mod 文件或 Steam 密码吗？

不会。本站提供公开信息、Steam 返回的有效直链和本地 SteamCMD 指引，不托管创意工坊文件，也不处理 Steam 凭据。

### 可以一次下载整个合集吗？

目前一次查询一个创意工坊内容，请使用单个内容的链接或 Published File ID。

### 网站开源吗？

不开源。本仓库公开产品介绍、截图和使用文档，不包含网站业务源码。

## 问题反馈

遇到问题或有建议，可以[提交 Issue](https://github.com/ai-ashao/workshopfetch/issues)，附上公开页面链接、预期结果和实际情况。请不要包含密码或其他私人信息。

其他信息见[关于 WorkshopFetch](https://workshopfetch.com/zh-cn/about)。

---

WorkshopFetch 是独立工具，与 Valve Corporation 或 Steam 无关联。创意工坊内容归相应创作者及权利人所有。
