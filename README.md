# firmware

[中文](#中文) | [English](#english)

## 中文

自制设备固件的发布仓库。

| 目录 | 设备 |
|---|---|
| `mu5250/` | 中兴 U60 Pro（MU5250），OpenWrt 固件 |
| `mu5358/` | MU5358（预留） |

- 固件文件名：`mu5250-openwrt-<日期>.enc`，同一天的第二版起加 `-2`、`-3`……；`.delta-*` 是从某个旧版本升级用的增量包，`index.enc` 是更新索引。
- 旧版本一直保留，不会删除。

版权所有，保留一切权利。未经许可不得复制、再分发、修改或出售，详见 [LICENSE](LICENSE)。

## English

Release repository for custom device firmware.

| Folder | Device |
|---|---|
| `mu5250/` | ZTE U60 Pro (MU5250), OpenWrt firmware |
| `mu5358/` | MU5358 (reserved) |

- Firmware files are named `mu5250-openwrt-<date>.enc`; a second build on the same day gets `-2`, then `-3`, and so on. `.delta-*` files are incremental updates from an older build, `index.enc` is the update index.
- Older versions are kept and never deleted.

Copyright, all rights reserved. No copying, redistribution, modification or sale without permission; see [LICENSE](LICENSE).
