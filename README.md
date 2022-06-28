**MCCA VPN**

**配置手冊**

*20* **本 羅俊熙**

June 28, 2022 Edition

目錄

[更新內容：](#更新內容)

[前言：](#前言)

[提問方式：](#提問方式)

[1. 申請Walless PKU:](#申請walless-pku)

[2. Windows (電腦)](#windows-電腦)

[3. Mac (電腦)](#mac-電腦)

[3. IOS (iPhone, iPad,…)](#ios-iphone-ipad)

[4. Android (手機)](#android-手機)

[其他程式的設定方法：](#其他程式的設定方法)

[特別鳴謝](#特別鳴謝)

# 更新內容：

2021/10/08 : 更新線路，新增手動配置參數。

2022/02/27 : 更新Walless PKU的安裝教學。

2022/06/28 : 將yaml文件下載點改至Github，新增Shadowrocket攔截廣告教學。

**訂閱網址：**

| 訂閱配置文件         | https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml                                                                |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Clash下載地點        | **Windows or Mac:** https://github.com/Fndroid/clash_for_windows_pkg/releases **Android:** https://github.com/Kr328/ClashForAndroid/releases |
| Shadowrocket配置文件 | https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/adblock.conf                                                            |

# 前言：

此配置手冊的作用為教大家如何安裝及使用VPN，因MCCA所配置的VPN是在外租用的，而且每個月能用的流量並不是無限，所以希望各位MCCAers不要隨便將VPN公開給其他同學，不要瀏覽一些奇怪的網站，避免伺服器被攻擊。

一般情況下VPN能夠讓大家用於使用Google, Line, Facebook, Instagram及YouTube (480P左右)等等，若有任何問題或是嚴格遵守此手冊的方法都不能運行VPN，請在MCCA吹水群找**20本 物院 羅俊熙**，我在有空時會第一時間幫大家解決。

# 提問方式：

在提問時，記得提及1. 你使用的手機；2. 你所在的地方；3. 你所使用的網絡；4. 問題的詳細描述；5. 一大堆圖片。這樣做能幫忙你更快得到幫助，同時也能為小弟節省下不少的時間，謝謝

# 申請Walless PKU:

Walless PKU是北大校友搞出來的VPN伺服器，其用意是幫助北大學生在進行學術研究時更為方便，每人有最多20GB的流量，每天會補充2GB。當然我們作為北大學生/校友也可以得到這樣的待遇。

大家可以前往<https://wallesspku.com/>處得到更多資訊或是安裝教學，也可以看這個文檔來進行安裝。

1.  使用自己的北大郵箱寄一封郵件到wallesspku@hotmail.com，標題及內容隨意。

![一張含有 文字 的圖片 自動產生的描述](media/5ddd9ac0e66ad51db46b21cbc0b25e3f.png)

這裡注意有些人的郵箱是有別名的，因此你需要到寄件箱 (己發送) 中，找到自己寄出的郵箱是甚麼，這裡我們可以看到我所寄出的郵箱是seelooooo@stu.pku.edu.cn

1.  等待數分鐘到數小時後，到https://941321.xyz/register中輸出自己的郵箱，如無意外會出現下面的畫面

![](media/f2d2407ade0d610b30e14c47aa40b67d.png)

1.  然後把clash訂閱地址經過下面提及的各種類型電腦的clash安裝教學，並在url中輸入，即可享用walless PKU \~

# Windows (電腦)

1.  前往Github下載Clash for Windows

![](media/ecc7f5a3b44bcd817edeb4d5d0bb79cb.jpeg)

1.  下載後解壓縮 (最好解壓到一個文件夾)
2.  打開此程序![](media/783cd2471f995037d0385f5c6c106b84.jpeg)
1.  打開Profiles，在方框內輸入

https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

然後按下Download![](media/9beb74bee3b43b7d9ff90be277f7dcff.jpeg)

1.  若成功，則會有下列的效果，VPN到這裡就安裝成功了

![](media/933c97f8bdcd9082ed02e5cbc2423949.jpeg)

1.  若要打開VPN

則打開General，將System Proxy打開即可![](media/a1b701302755b38ddde5e69fadfbcead.jpeg)

# Mac (電腦)

1.  前往Github下載Clash for Windows 副檔名為dmg的。

    ![](media/a4ca1535f8236fd6250d00d3c3231a4e.png)

1.  打開，然後拖動至進右方的資料夾安裝

    ![](media/1d79d5ba8fc99eb62a1f5888c15f2ba3.jpeg)

2.  找到ClashX並打開它

    ![](media/6c067571f19356f92ecb40aecb8add6c.jpeg)

1.  在畫面右上方找到小貓咪，然後打開Config進行配置

    ![](media/d97ad0e1f3a26e6dc39d65d3cb58fff8.png)

2.  點選add，然後在url輸入

https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

Name可以隨意填寫，然後按OK

![](media/7cdb3512b9317093a473c5b2aa871ae9.png)

1.  按一下update

    ![](media/68eacebcdd79cf4b196b5c41f4d06472.png)

2.  把set as system proxy勾選後就可以使用VPN了

    ![](media/d922e81dbef44abf42e99561303fda5f.png)

# IOS (iPhone, iPad,…)

1.  用一切方法得到 **Shadowrocket**，並下載和安裝

    ![](media/906e6f698c02941a885173b8e17aa302.jpeg)

    *\*需要錢*

*  
*

1.  打開程式後按右上方的加號，然後將型別設定成Subscribe，在URL一行中寫入

https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

![](media/f5c6f9b001426b881ef8d602ca47a09c.jpeg) *![](media/125eb655af1a60013414374cee954613.jpeg)![](media/97884918ee354789710b63ae20f96427.jpeg)*

*  
*

1.  完成後，要打開VPN，只需在每個不同的線路中，選上ms數最低的那個即可 (注意，不要選到ms數少於10的，極大機會用不了)，然後把連線打開即口 (第一次可能需要輸入密碼同意其修改手機的網絡設定)

![](media/b9c0022f8ecc4d7125286f6ff55637be.jpeg)

(若要更新線路，只需點上圖中www.mcca.xyz右方的感嘆號，然後再按一下完成即可)

1.  要完成廣告攔截，只需要在配置-\>右上角+號輸入下面的網址-\>下載。

https://github.com/supercgor/mccanetworksettings/releases/download/mccamacau/adblock.conf

1.  在本地檔案裡點擊adblock.conf然後點使用配置即可。

# Android (手機)

1.  前往Github下載Clash For android，具體那一個我也不太清楚

https://github.com/Kr328/ClashForAndroid/releases ![](media/83936ecab761c903ecd8a7ff2d46527f.png)

又或是前往google play找到 Clash For android這一應用程式

1.  把xapk文件安裝好後打開
2.  前往配置，按右上方加號，點選從URL導入

    ![](media/c343060607a3f696326e72bd7acf8611.jpeg) ![](media/04e8b281aa05a12a16ca14f76bb2bc6c.jpeg) ![](media/3dde66583b47ae6fb1705f7e843b8e79.jpeg)

1.  名稱可以亂寫，URL寫

    https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

    自動更新建議為240分鐘，最後按右上方儲存

    ![](media/1ce9a265f492ced171f8ff30b319160d.jpeg)

2.  按右邊的三點，然後按更新

    ![](media/16049568394e46f8cc059bbba1545459.jpeg)

1.  退回去目錄，按一下中間就能夠打開VPN了

    ![](media/65a0cbde5a784eec4362bb8beb0ce225.jpeg)

# 其他程式的設定方法：

考慮到許多人已經安裝其他VPN程序，而未必全部都支援使用yaml設定，大家也可以在瀏覽器中輸入

https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

下載文件後，找到對應的線路設定進行手動設定!

# 特別鳴謝

十分感謝譚家豪師兄提供的一切幫助，還有他長期對mccavpn的維護。
