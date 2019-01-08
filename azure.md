# Azure Cafe'

*2019/1/8*


## Azure Function

OS: window, linux

## 巨量使用量

延展性:

向外延展 / 向上延展
scale out / scale up

善用分散式 cache 減少不必要之資料存取

### issue:
雲端 server 如何稽核

不具備向外延展的設計

Azure CDN 有三家產品，我們用哪一套 CDN?
(Akami, ?, ?)

**CDN purge?**
>>> preload 或 purge API 清除
>>> 建議動態產生檔名

**如何知道單點故障發生在哪?**
>>> Azure Moniter?

**server 互為備援的舉例, 那架構該怎麼做?**
>>> Staging & Produciton 有各自環境

DB 如何做資料備份?

現在用的 Azure Storage & VM & 頻寬的規格是多少?

不停機的策略
swap 的做法? staging > old
DNS 切換
