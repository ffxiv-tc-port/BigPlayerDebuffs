# BigPlayerDebuffs

[rgd87/BigPlayerDebuffs](https://github.com/rgd87/BigPlayerDebuffs) 的台服移植版。
放大目標資訊視窗中「由自己施放」的強化／弱化狀態圖示，方便一眼辨識自己
造成的持續效果，同時支援分離式與合併式兩種目標資訊框架版面。

## 功能

- 自動放大目標身上由自己施放的強化／弱化狀態圖示。
- 可調整縮放倍率（1.0～4.0 倍）。

## 指令

- `/bigplayerdebuffs`：開啟設定視窗。

## 台服版的修改

- 只做台服相容性修正（Dalamud 版本、繁中翻譯），功能與上游相同
- 降低記憶體用量

## 安裝

`/xlsettings` 開「Dalamud 設定」→「試驗性功能」→「第三方插件倉庫」，加入 `https://raw.githubusercontent.com/ffxiv-tc-port/DalamudPluginsTC/main/repo.json` 並啟用、儲存，再到「插件管理員」（`/xlplugins`）安裝；同一個插件只裝這裡的版本，不要同時裝上游版。

原作者：[d87（rgd87）](https://github.com/rgd87)

授權：上游未附授權。
