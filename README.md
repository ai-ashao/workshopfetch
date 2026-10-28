<div align="center">

<a href="https://workshopfetch.com/">
  <img src="assets/logo.png" alt="WorkshopFetch" width="88">
</a>

# WorkshopFetch

**Check Steam Workshop download options for mods, maps, and more.**

Paste a Workshop link or Published File ID. Get a direct Steam link when available, or an item-specific SteamCMD command to run on your own computer.

[![Website](https://img.shields.io/badge/Website-workshopfetch.com-e36b25?style=flat-square)](https://workshopfetch.com/)
[![Guide](https://img.shields.io/badge/Guide-How_to_use-171714?style=flat-square)](https://workshopfetch.com/how-to-use)
[![Languages](https://img.shields.io/badge/Languages-15-777365?style=flat-square)](https://workshopfetch.com/)

**[Open WorkshopFetch →](https://workshopfetch.com/)**

English · [简体中文](README.zh-CN.md)

</div>

[![WorkshopFetch homepage: paste a Steam Workshop URL or File ID to check download options](assets/home-en.jpg)](https://workshopfetch.com/)

## What is WorkshopFetch?

[WorkshopFetch](https://workshopfetch.com/) is a free online tool for checking one public Steam Workshop item at a time. It retrieves public item details from Steam and shows the download options Steam makes available. No WorkshopFetch account or installation is needed to check an item.

This is the official public product overview and documentation repository. The website's application source code is private.

## Why use it?

- **A link or an ID is enough.** Paste a Workshop item URL or its numeric Published File ID.
- **Check the item before proceeding.** Review the returned title and game to confirm you have the right content.
- **Use Steam's direct link when available.** A download button appears only when Steam returns a valid public file URL on an approved Steam download domain.
- **Get a local SteamCMD starting point.** When there is no public direct link, copy the item's command and follow the installation and usage guide on your own computer.
- **No file hosting or proxying.** WorkshopFetch never stores, caches, or redistributes Workshop files. Direct downloads go from your browser to Steam's CDN.
- **Read in your language.** The website is available in English, Simplified Chinese, Traditional Chinese, Portuguese (Brazil), Turkish, Indonesian, Vietnamese, Spanish, German, Russian, Japanese, French, Polish, Korean, and Italian.

## Use it in three steps

1. **Copy a single item's link.** Open the item in Steam Workshop and copy its URL, such as `https://steamcommunity.com/sharedfiles/filedetails/?id=122941542`.
2. **[Open WorkshopFetch](https://workshopfetch.com/) and check it.** Paste the URL or ID, then choose **Check Download Options**.
3. **Use the returned option.** Open the direct Steam link if one is available. Otherwise, follow the item-specific SteamCMD instructions locally.

The example shows the input format; it does not guarantee that this item has a public direct link or can be downloaded through SteamCMD.

## Understand the result

| Result | What to do |
| --- | --- |
| Steam returns a valid public file link | Open the download link to Steam's CDN. |
| Steam returns item details without a public file link | Review the generated SteamCMD command and local-use guide. |
| The item cannot be retrieved | Check the URL, visibility, and Steam's availability; see the troubleshooting guide below. |

SteamCMD runs on your computer. WorkshopFetch never runs it for you or asks for your Steam password. Access depends on the game, ownership, authentication, visibility, and permissions; a generated command does not guarantee success.

## Guides

- [How to use WorkshopFetch](https://workshopfetch.com/how-to-use)
- [Install and use SteamCMD for Workshop items](https://workshopfetch.com/blog/steamcmd-workshop)
- [Find a Steam Workshop item's ID](https://workshopfetch.com/blog/find-steam-workshop-id)
- [Troubleshoot Steam Workshop downloads](https://workshopfetch.com/steam-workshop-download-not-working)
- [Browse game guides](https://workshopfetch.com/games)

## FAQ

### Is it free? Do I need an account?

WorkshopFetch is free to use and does not require a WorkshopFetch account. Steam or a game may still require an account or ownership for downloading particular items.

### Can it download every Workshop item?

No. Direct links appear only when Steam supplies them. SteamCMD access also varies by game and item. WorkshopFetch cannot bypass ownership, private-item restrictions, or other Steam and game access rules.

### Does WorkshopFetch host mods or ask for Steam credentials?

No. It provides public metadata, valid direct Steam links when returned, and local SteamCMD guidance. It does not host Workshop files or handle Steam credentials.

### Does it download an entire collection?

The tool checks one Workshop item at a time. Use an individual item's URL or Published File ID.

### Is the website open source?

No. This repository contains the product introduction, screenshots, and usage documentation. It does not include the website's application source code.

## Feedback

Found a problem or have a suggestion? [Open an issue](https://github.com/ai-ashao/workshopfetch/issues) with the public page URL, what you expected, and what happened. Please do not include passwords or other private information.

For other inquiries, visit [About WorkshopFetch](https://workshopfetch.com/about).

---

WorkshopFetch is an independent tool and is not affiliated with Valve Corporation or Steam. Workshop content belongs to its respective creators and rights holders.
