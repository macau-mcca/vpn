# MCCA VPN

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

![一張含有 文字 的圖片 自動產生的描述](media/1.png)

這裡注意有些人的郵箱是有別名的，因此你需要到寄件箱 (己發送) 中，找到自己寄出的郵箱是甚麼，這裡我們可以看到我所寄出的郵箱是seelooooo@stu.pku.edu.cn

1.  等待數分鐘到數小時後，到https://941321.xyz/register中輸出自己的郵箱，如無意外會出現下面的畫面

![](media/26.png)

1.  然後把clash訂閱地址經過下面提及的各種類型電腦的clash安裝教學，並在url中輸入，即可享用walless PKU \~

# Windows (電腦)

1.  前往Github下載Clash for Windows

![](media/2.jpg)

1.  下載後解壓縮 (最好解壓到一個文件夾)
2.  打開此程序![](media/3.jpg)
1.  打開Profiles，在方框內輸入

https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

然後按下Download![](media/4.jpg)

1.  若成功，則會有下列的效果，VPN到這裡就安裝成功了

![](media/5.jpg)

1.  若要打開VPN

則打開General，將System Proxy打開即可![](media/6.jpg)

# Mac (電腦)

1.  前往Github下載Clash for Windows 副檔名為dmg的。

    ![](media/7.png)

1.  打開，然後拖動至進右方的資料夾安裝

    ![](media/8.jpg)

2.  找到ClashX並打開它

    ![](media/9.jpg)

1.  在畫面右上方找到小貓咪，然後打開Config進行配置

    ![](media/10.png)

2.  點選add，然後在url輸入

https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

Name可以隨意填寫，然後按OK

![](media/11.png)

1.  按一下update

    ![](media/12.png)

2.  把set as system proxy勾選後就可以使用VPN了

    ![](media/13.png)

# IOS (iPhone, iPad,…)

1.  用一切方法得到 **Shadowrocket**，並下載和安裝

    ![](media/14.jpg)

    *\*需要錢*

*  
*

1.  打開程式後按右上方的加號，然後將型別設定成Subscribe，在URL一行中寫入

https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

![](media/15.jpg) *![](media/16.jpg)![](media/17.jpg)*

*  
*

1.  完成後，要打開VPN，只需在每個不同的線路中，選上ms數最低的那個即可 (注意，不要選到ms數少於10的，極大機會用不了)，然後把連線打開即口 (第一次可能需要輸入密碼同意其修改手機的網絡設定)

![](media/18.jpg)

(若要更新線路，只需點上圖中www.mcca.xyz右方的感嘆號，然後再按一下完成即可)

1.  要完成廣告攔截，只需要在配置-\>右上角+號輸入下面的網址-\>下載。

https://github.com/supercgor/mccanetworksettings/releases/download/mccamacau/adblock.conf

1.  在本地檔案裡點擊adblock.conf然後點使用配置即可。

# Android (手機)

1.  前往Github下載Clash For android，具體那一個我也不太清楚

https://github.com/Kr328/ClashForAndroid/releases ![](media/19.png)

又或是前往google play找到 Clash For android這一應用程式

1.  把xapk文件安裝好後打開
2.  前往配置，按右上方加號，點選從URL導入

    ![](media/20.jpg) ![](media/21.jpg) ![](media/22.jpg)

1.  名稱可以亂寫，URL寫

    https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

    自動更新建議為240分鐘，最後按右上方儲存

    ![](media/23.jpg)

2.  按右邊的三點，然後按更新

    ![](media/24.jpg)

1.  退回去目錄，按一下中間就能夠打開VPN了

    ![](media/25.jpg)

# 其他程式的設定方法：

考慮到許多人已經安裝其他VPN程序，而未必全部都支援使用yaml設定，大家也可以在瀏覽器中輸入

https://github.com/macau-mcca/vpn/releases/download/mcca-vpn-setting/mcca.yml

下載文件後，找到對應的線路設定進行手動設定!

# 特別鳴謝

十分感謝譚家豪師兄提供的一切幫助，還有他長期對mccavpn的維護。
