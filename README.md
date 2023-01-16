# KSP-Language
Kerbal Space Program 的多語言包

> 此儲存庫僅適用於自Epic Games取得的遊戲

由於Epic Games未提供任何語言選項，原版中僅有英文(en-us)，所以我將來自其他地方的語言包整合成一個檔案，方便玩家切換。

## 下載
[點此下載最新版本](/releases/latest/download/KSP-Language.zip)

## 安裝
1. 先取得遊戲的安裝路徑，詳見[遊戲安裝路徑](#遊戲安裝路徑)。
2. 將下載的`KSP-Language.zip`檔案解壓縮，再將`KSP-Language`資料夾中的`dictionary.cfg`複製到`{遊戲安裝路徑}/English/GameData/Squad/Localization`取代原先的`dictionary.cfg`。
3. 切換語言，詳見[切換語言](#切換語言)。


## 切換語言
1. 開啟`{遊戲安裝路徑}/English/buildID64.txt`，預設檔案結構如下：
```txt
[config]
build id = 03190
2022.12.12 at 14:02:28 PST
Branch: master
language = en-us
distribution name = Store
```
2. 將`language`的值改為您想要使用且此存儲庫[支援的語言](#支援的語言)代碼，例如`zh-tw`，並儲存。

## 常見問題
### 遊戲安裝路徑
在Epic Games 啟動器中，點擊 Kerbal Space Program 右下方的三個點，選擇｢管理」。
![EpicGamesManageOption.png](/img/EpicGamesManageOption.png)
點擊資料夾圖示，Epic Games 啟動器會開啟一個資料夾。
![EpicGamesManageInstallPath.png](/img/EpicGamesManageInstallPath.png)
此資料夾之路徑即為遊戲的安裝路徑。
![EpicGamesManageOpenInstallPath.png](/img/EpicGamesManageOpenInstallPath.png)



### 支援的語言
|語言|代碼|來源|
|:-:|:-:|:--:|
|Engilsh|`en-us`|Epic Games|
|繁體中文|`zh-tw`|[GitHub:shuwn/KSP-Traditional-Chinese](https://github.com/shuwn/KSP-Traditional-Chinese)|
|简体中文|`zh-cn`|[百度贴吧:坎巴拉太空计划Epic版汉化包](https://tieba.baidu.com/p/8210907618?pid=146522485836&cid=146523873847#146523873847)
|ру́сский язы́к|`ru-ru`|[YuoTube:Kerbal Space Program Русификатор Эпик геймс KSP EGS](https://www.youtube.com/watch?v=dsRnGtr_GGE)|