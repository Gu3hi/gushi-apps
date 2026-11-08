# Gushi 自用源（LCSign 软件源）

个人自用软件源，全部为**未签名 IPA**，在 LCSign 里下载后用自己的证书签名安装。

## 源地址

```
https://raw.githubusercontent.com/Gu3hi/gushi-apps/main/apps.json
```

LCSign 里：软件源 → 添加 → 粘贴上面地址。同一个源也能在轻松签 / Feather / SideStore / AltStore 里添加（`apps.json` 同时带扁平字段与 AltStore 2.0 的 `versions[]`）。

落地页：https://gu3hi.github.io/gushi-apps/

## 内容

| App | Bundle ID | 版本 | 最低系统 | 大小 |
|---|---|---|---|---|
| 低调影视 DDYS | com.gushi.ddys | 1.0.2 (build 2) | iOS 16.0 | 676,395 |
| D2R Mobile | org.d2rmobile.app | 1.0 (build 1) | iOS 17.0 | 123,530,804 |

SHA-256 写在 `apps.json` 每个版本条目里，可核对。

注：Burger Swift 不在此仓（其未签名包只走私有渠道）。
