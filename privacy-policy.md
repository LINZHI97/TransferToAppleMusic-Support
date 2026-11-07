# 隐私政策 / Privacy Policy

更新日期 / Updated: 2026-11-07

歌单搬家（Playlist Porter）无需注册账号，不使用广告、分析或追踪 SDK。我们不运营歌单解析服务器。

Playlist Porter requires no account and uses no advertising, analytics or tracking SDKs. We do not operate a playlist parsing server.

## 歌单与歌曲 / Playlists and songs

应用直接向您所选的来源音乐平台请求公开歌单或歌曲元数据（歌名、歌手、专辑及来源 ID），并向 Apple Music 发送搜索词和所选歌曲 ID，以完成匹配和导入。各服务可能接收您的网络地址等网络请求必需的信息。我们不下载或转存音频。

The app requests public song metadata directly from the selected source platform and sends search terms and selected song IDs to Apple Music to match and import songs. These services receive information needed to serve network requests, such as your network address. We do not download or redistribute audio.

支持的来源包括网易云音乐、QQ 音乐、汽水音乐、酷狗音乐、酷我音乐、咪咕音乐；公开访问可能受平台限制。CSV/TSV 文件在设备本地读取，不上传给开发者；其中的歌名、歌手、专辑用于 Apple Music 搜索。

Sources include NetEase, QQ, Qishui, Kugou, Kuwo and Migu. Public access may be limited by the source. CSV/TSV files are read on your device and are not uploaded to the developer. Their song titles, artists and albums are used for Apple Music searches.

## 设备存储与授权 / On-device storage and authorization

应用在内存缓存匹配结果；为恢复中断的转移，会在设备本地保存歌曲元数据、Apple Music 歌曲和目标歌单 ID、进度与结果。完成或放弃转移会删除待恢复记录。为防止重复导入，会读取目标 Apple Music 歌单内容并在本地保存目标 ID。应用需要用户明确授权后才能访问 Apple Music 资料库。

Matches are cached in memory. To resume an interrupted transfer, the app stores song metadata, Apple Music song and destination playlist IDs, progress and results on your device. The pending record is deleted when the transfer completes or is discarded. The app reads the destination playlist and stores its ID locally to avoid duplicate imports. Apple Music library access requires your authorization.

购买交易由 Apple StoreKit 处理。应用在设备上保存已验证交易 ID、已购额度、使用计数和 Pro 权益信息，用于防止重复入账。我们无法读取您的付款卡信息。不使用来源平台密码、Cookie 登录或自有账户。

Purchases are processed by Apple StoreKit. Verified transaction IDs, credits, usage counts and Pro access are stored on the device to prevent duplicate grants. We cannot access your payment card information. The app does not request source-platform passwords or authenticated cookies and has no developer-operated account system.

隐私问题请通过 [GitHub Issues](https://github.com/LINZHI97/TransferToAppleMusic-Support/issues) 联系。第三方服务受各自隐私政策约束，Apple 服务参见 [Apple 隐私政策](https://www.apple.com/legal/privacy/)。

For privacy questions, contact us through [GitHub Issues](https://github.com/LINZHI97/TransferToAppleMusic-Support/issues). Third-party services have their own privacy policies; see [Apple’s Privacy Policy](https://www.apple.com/legal/privacy/).
