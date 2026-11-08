# 歌单搬家 / Playlist Porter

多平台和文件导入说明适用于 1.1 及更新版本，具体可用功能以已安装版本为准。
Multi-platform and file import instructions apply to version 1.1 or later. Available features depend on your installed version.

支持 iOS 17 或更新版本，需要有效的 Apple Music 订阅。
Requires iOS 17 or later and an active Apple Music subscription.

复制来源平台的公开歌单分享链接，在首页粘贴后点“读取歌单”；点击歌单查看匹配，或勾选多个歌单后统一匹配。使用“待确认”筛选检查未匹配歌曲，选择版本或编辑搜索词，确认后点“转移到 Apple Music”。1.1 版本中的对应操作为“导入歌单”。
Paste a public playlist share link and choose Read playlist. Open a playlist to review its matches, or select several to match together. Use To review to find songs needing attention, choose a version or edit the search terms, then choose Transfer. In version 1.1, the corresponding first action is Import Playlist.

| 来源 / Source | 直接链接 / Direct links |
|---|---|
| 网易云 / NetEase | 歌单及单曲 / Playlists and songs |
| QQ 音乐 / QQ Music | 公开歌单，完整性核对 / Public playlists with completeness checks |
| 汽水音乐 / Qishui | 公开歌单，完整性核对 / Public playlists with completeness checks |
| 酷狗 / Kugou | 公开 collection 标识可读取；部分 GCID 分享格式受限 / Public collection IDs; some GCID share formats are restricted |
| 酷我 / Kuwo | 公开歌单，完整性核对 / Public playlists with completeness checks |
| 咪咕 / Migu | 公开歌单接口，受可见性限制 / Public playlist endpoints depend on visibility |

无法完整读取时，应用会显示已读取数量，您可取消、仅导入已读取曲目，或改用文件。公开链接的可用性不保证 Apple Music 有对应歌曲。
When a playlist is incomplete, the app shows the readable count. Cancel, import only available songs or use a file. Source availability does not guarantee a match in your Apple Music storefront.

文件格式为 UTF-8 或带 BOM 的 UTF-16 CSV/TSV。必填列：`歌名`/`title`、`歌手`/`artist`；可选列：`专辑`/`album`。导入前预览并检查无效行。
Use UTF-8 or BOM-marked UTF-16 CSV/TSV. Required headers: `title`, `artist`; optional: `album`. Chinese equivalents are accepted. Review invalid rows before importing.

```csv
title,artist,album
晴天,周杰伦,叶惠美
```

免费额度为 30 首成功转移。100 首、500 首额度包可重复购买，Pro 为永久无限制。重复交易通知不会重复增加额度；已拥有的 Pro 无需重新购买。消耗型额度保存在当前设备，不能通过“恢复购买”恢复已消耗交易。
Includes 30 free successful transfers. Credit packs add 100 or 500 transfers; Pro is a one-time unlimited purchase. Duplicate transaction notifications do not duplicate credits. Existing Pro owners do not need to buy again. Consumable balances are stored on the current device and are not restored by Restore Purchases after transactions have been consumed.

1.2 新界面：顶部额度入口显示剩余歌曲数或 Pro；文件导入在首页“从文件导入”或歌单页“文件”。转移时可点“暂停转移”，下次打开应用继续；只在核对成功后使用额度。
In version 1.2, credits or Pro appear in the top bar. Use Import from file on Home or File in the playlist list. Pause a transfer and resume it when reopening the app. Credits are used only after songs are successfully added.

反馈 / Feedback: [GitHub Issues](https://github.com/LINZHI97/TransferToAppleMusic-Support/issues)

本应用仅转移歌曲元数据，不下载音频，与上述平台无官方合作关系。
This independent app transfers song metadata without downloading audio and is not affiliated with the listed platforms.
