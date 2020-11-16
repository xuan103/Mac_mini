
# 認識 Mac mini

- [辨識 Mac mini 機型](https://support.apple.com/zh-tw/HT201894)
    - [Mac mini (2011 年中) - 技術規格](https://support.apple.com/kb/SP632?locale=zh_TW)
    - [Mac mini（2014 年末）- 技術規格](https://support.apple.com/kb/SP710?viewlocale=zh_MO&locale=zh_MO)

### 圖示規格：

- 2011 年中

![2011](https://i.imgur.com/2jXJLA3.png)



```
- Thunderbolt 連接埠 (傳輸速率高達 10 Gbps)
- FireWire 800 連接埠 (傳輸速率高達 800 Mbps)
- 四個 USB 2.0 連接埠 (傳輸速率高達 480 Mbps)
- HDMI 連接埠
- SDXC 卡插槽
- Gigabit 乙太網路連接埠
- 音訊輸入/輸出
```

---

- 2014 年末

![2014](https://i.imgur.com/jR8baR4.png)



```
- 兩個 Thunderbolt 2 埠 (可達 20 Gbps)
- 四個 USB 3 埠 (可達 5 Gbps)
- HDMI 埠
- SDXC 卡插槽
- Gigabit 乙太網路埠
- 音訊輸入埠
- 3.5 公釐耳機插孔
- 紅外線接收器
```

---

# 事前準備

- 檢查設備

    -  MAC MINI 設備規格確認（年份）
    -  螢幕輸出規格（VGA, HDMI, DP...）
    -  有線網路或無線網路

- 準備器材

    - 鍵盤滑鼠
    - 螢幕轉接線
    - 隨身碟（非必須）

---

# 開機

## 主要步驟

### 圖解：

- 選單

![](https://i.imgur.com/peXxF3c.jpg)

 > 選擇 磁碟工具程式

---

- 清除磁碟機1（硬碟

![](https://i.imgur.com/gKiQQrZ.jpg)

 > 左欄位 選擇要清除硬碟

---

- 清除磁碟機2（硬碟

![](https://i.imgur.com/k2HGRa6.jpg)

> 右邊 點擊清除

---

- 確認清除

![](https://i.imgur.com/lMT9bw4.jpg)

> 清除

---

- 選單

![](https://i.imgur.com/oxlYLlk.jpg)

> 重新安裝 OS X 

---

- 確認安裝

![](https://i.imgur.com/DhPxOFa.jpg)

> 繼續

---

# 安裝（重灌）

## 主要步驟

- 選擇地區 > 選擇鍵盤 > 備份 > 選擇登入 > 選擇確認 > 檢視條例 > 選擇確認 > 建立電腦帳號 > 診斷與用量
 
### 圖解：

- 選擇地理位址（地區）

![install-where](https://i.imgur.com/2KUI4Yv.jpg)

>  台灣

---

- 選擇鍵盤規格

![install-keyboard](https://i.imgur.com/ouETKkr.jpg)

> 美國

---

- 備份

![install-int](https://i.imgur.com/iYZANx8.jpg)

> 不用備份（個人PC, 依據需求選擇, 此僅供參考）

---

- 詢問登入

![install-id](https://i.imgur.com/zDtZEwL.jpg)

> 不要登入

---

- 確認選擇

![install-idyn](https://i.imgur.com/Nc20R1N.jpg)

> 略過

---

- 檢視條例

![agree](https://i.imgur.com/zNIX0av.jpg)

> 同意

---

- 確認選擇
 
![selet](https://i.imgur.com/Vy0YZru.jpg)

> 同意


---

- 建立電腦帳號

![bigred](https://i.imgur.com/J0jgz11.jpg)

> 僅供參考

---

- 診斷與用量

![use](https://i.imgur.com/HcMpFhp.jpg)

> 不要傳送！

---

# 基本設定

##  主要步驟

- 點擊`蘋果` > 系統偏好設定 > 網路 > 設定 ipv4 > 設定 DNS > 設定 hostname > 下載 Docker > 產生 ssh 金鑰

--- 
### 圖解：

#### 網路設置

![set](https://i.imgur.com/Tvcdf6K.png)
> 點擊`蘋果`(右上) > 系統偏好設定 

---
![web](https://i.imgur.com/m5IRgEi.png)
> 選擇`網路`（第三行中間）

---

![web1](https://i.imgur.com/WSYLRzI.png)
> 找到 `設定 ipv4:` > `使用 DHCP` 改 `手動`

---
![web2](https://i.imgur.com/Fm78Wgt.png)
> 設置 ip 位址 及 路由器，之後右下`進階`

---
![dns](https://i.imgur.com/TwiNEVD.png)
> 設定 DNS, 右下 "+" 新增

---
![dns1](https://i.imgur.com/M7ZaeIM.png)
> 以上參考

---
#### 設置 hostname（主機名稱）

![host](https://i.imgur.com/N6SlLM4.png)

> sudo hostname "m150"

> "m150" 為參考主機名稱 (設定完，重開終端機)

---

#### 下載 Docker

![docker](https://i.imgur.com/h8mBk16.png)

> 搜尋 "docker desktop for mac"

---


![docker1](https://i.imgur.com/IKe0HR9.png)

> 打開參考網頁



---

![docker2](https://i.imgur.com/u6JGqRi.png)

> 下載 docker



---

![docker3](https://i.imgur.com/ImoiZeb.png)

> 下載中



---

![docker4](https://i.imgur.com/9pUo8eN.png)

> 圖形（拖移）界面

---

![docker5](https://i.imgur.com/C047i35.png)

> 將 docker 壓縮檔掛載


---

![docker6](https://i.imgur.com/tsHqaof.png)

> 掛載中 (安裝中) 


---


![docker7](https://i.imgur.com/dta05Q6.png)

> 安裝完成


---


![docker8](https://i.imgur.com/Zydg6FW.png)

> 打開 docker, 右上出現一隻小鯨魚, 點擊設置 Preferences（效能調整）

---


![docker9](https://i.imgur.com/7KG5ubg.png)

> 點擊 Resourcrs


---

![dockera1](https://i.imgur.com/mRjaQdE.png)

>  更改 Memory（記憶體）大小


---


![dockera2](https://i.imgur.com/HJvdwMM.png)

> 同意並且重開

---

#### 產生遠端金鑰（SSH)

![ssh](https://i.imgur.com/Cp3bWZ6.png)

> ssh-keygen -t rsa -P ''


---

##### 複製遠端金鑰至其他機器（SSH 免密碼登入）

![ssh1](https://i.imgur.com/fsZtPfH.png)

> ssh-copy-id username@ip

---

##### 遠端測試設定成功否？

![ssh2](https://i.imgur.com/TeXeNfO.png)

> ssh username@ip



























