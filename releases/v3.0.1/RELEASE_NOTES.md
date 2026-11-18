# RipleyBookDual v3.0.1 — Vertical CJK Reading

## 🇹🇼 繁體中文｜中日文直排閱讀

v3.0.1 新增中、日文直排閱讀支援，同時保留原有的橫排閱讀方式。

**更新內容**
- **RTL（Right to Left）**：支援中文、日文直排閱讀。
- **LTR（Left to Right）**：保留原有橫排閱讀方式。
- Spread 雙機同步閱讀方向，支援跨章節及目錄跳章。
- 優化直排文字的上下留白與頁腳間距。

**重要操作說明**

使用 Spread 雙機模式時，**必須先在右機選定 RTL 或 LTR，再進行連線**。連線後兩機會使用相同閱讀方向，**連線期間無法切換方向**。如需更改，請先斷線、重新設定，再連線。

**注意：** RTL 模式不支援大捲角翻頁動畫，改用快速翻頁；LTR 模式保留原有大捲角效果。

---

## 🇯🇵 日本語｜日本語・中国語の縦書き対応

v3.0.1では、日本語・中国語の縦書きに対応しました。従来の横書き表示も引き続き利用できます。

**主な更新内容**
- **RTL（Right to Left）**：日本語・中国語の縦書きに対応。
- **LTR（Left to Right）**：従来の横書き表示に対応。
- Spreadモードで左右の端末の読書方向を同期。章をまたぐページ移動や目次からの章移動にも対応。
- 縦書きの上下余白とフッターとの間隔を調整。

**重要：読書方向の設定**

Spreadモードを使用する場合は、**接続前に右側の端末でRTLまたはLTRを選択してください**。接続後は両端末の読書方向が統一され、**接続中は変更できません**。変更する場合は、一度接続を解除して設定し直し、再接続してください。

**注意：** RTLでは大きなページカールアニメーションは使用できず、高速ページめくりとなります。LTRでは従来どおり利用できます。

---

## 🇬🇧 English｜Vertical Chinese & Japanese Reading

v3.0.1 introduces vertical Chinese and Japanese reading while preserving the original horizontal reading experience.

**What's New**
- **RTL (Right to Left):** Vertical Chinese and Japanese reading.
- **LTR (Left to Right):** Original horizontal reading.
- Synchronized reading direction across both devices in Spread mode, including chapter transitions and Contents navigation.
- Refined vertical text margins and footer spacing.

**Important: Set Reading Direction Before Pairing**

In Spread mode, **select RTL or LTR on the RIGHT device before connecting**. Once connected, both devices use the same reading direction, and **the direction cannot be changed while connected**. To switch directions, disconnect, change the setting, and reconnect.

**Note:** Large page-curl animation is unavailable in RTL; fast page turning is used instead. LTR retains the original page-curl animation.

---

**Installation:** M5Stack Paper S3 only; install the **Full Factory BIN** at offset `0x0`. Back up settings and progress before flashing. Flash the same v3.0.1 firmware on both units; it is not compatible with v3.0.0 for dual pairing. No SD Update BIN is distributed in this release.

**Firmware integrity:** `RipleyBookDual3.0.1-Full-Factory.bin`, 6,375,648 bytes, SHA-256 `f320ffb554f085fc355dee072b5b5af63b892790cd45d594372f87d276281d9f`.