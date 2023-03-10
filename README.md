# 議題物流平台：商城式的參與校務治理體驗

* 0302 Kick-off Meeting｜https://docs.google.com/document/d/1JtLwniq1omWy37leENl53GL1RzaufQAUof0A1D2yG34/edit?usp=sharing

```「將想向學校表達的事物，簡易實現於生活中。」```

現場簡報版｜[議題物流平台：商城式的參與校務治理體驗.pdf](https://github.com/nccusp4u/issue-delivery/blob/main/%E8%AD%B0%E9%A1%8C%E7%89%A9%E6%B5%81%E5%B9%B3%E5%8F%B0%EF%BC%9A%E5%95%86%E5%9F%8E%E5%BC%8F%E7%9A%84%E5%8F%83%E8%88%87%E6%A0%A1%E5%8B%99%E6%B2%BB%E7%90%86%E9%AB%94%E9%A9%97.pdf)

## 目錄
- [專案動機：為什麼想做](#專案動機為什麼想做)
- [具體目標](#具體目標)
- [專案預計時程](#專案預計時程)
- [預計用什麼技術達成](#預計用什麼技術達成)
- [招募對象](#招募對象)

---

專案主持人：

石宗霖 Tsunglin Shih／108306033@nccu.edu.tw

https://github.com/z15r7

政治大學資訊管理學系學士班 四年級

校務會議學生代表

曾任學生議會議長、秘書長

---

# 專案動機：為什麼想做

在上學期，許多GDSC的夥伴第一次在分享場合上，接觸到令人陌生的「學生議會」。

先來說說學生議會秘書處為什麼想推動這個行銷專案？

學生通常遇到問題第一個會尋求幫助的對象會是學生會。但許多問題必須透過學校的「會議」解決。當然學生會可以在會議上反應問題，然而實際上學生議會的代表席次是學生會的五倍（你可以將其視作影響力的五倍），讓學生議會來執行力量會比學生會大，可是學生對我們的熟悉度卻僅是學生會的1/10（按讚數）

於是我們想打造一個簡易且生活化的平台，讓同學可以即時反映問題，也可以更認識學生議會！

同學們對於問題反映，通常會有以下幾個共通點：

1. 不知道向誰開口
2. 不知道如何開口
3. 開口之後不知道有沒有用

舉個例子，今天我覺得四維道的磁磚非常糟糕，但我不知道要向哪個議員反映，又或是甚至不知道議會的存在。假使知道了，同學多半也不知道要怎麼將自己的議題聚焦成一個提案。縱使最後完成了提案，但同學們往往不會知道自己的提案執行狀況如何？或是是否已經被吃案了。

我們想要改善這個問題，於是我們開啟「議題物流平台」計畫。我們觀察到學生非常喜歡在Dcard上面反應校園生活問題，原因可能出自於他的匿名性。另一方面，對於學生族群來說，電商平台的使用也已成為日常。

有沒有一種可能，是我們將議題的傳達，打造成像電商平台一樣，讓顧客（同學）提出商品需求，由業主（學生議員）回應需求。顧客可以隨時查看自己的訂單是否有人接受，顧客亦可追蹤自己的訂單被執行到哪一個階段；另一方面，業主可以知道顧客有什麼需求，業主亦有管道擴大接觸面，解決更多問題。

有很多夥伴在接觸到這個議題時告訴我們，這個計畫有搞頭，他們有興趣加入。我們也希望此計畫能夠被實現，讓同學可以更簡單的反應問題，並一起參與改革的進行。

此計畫要在這學期開始推動了！希望對計畫有興趣的夥伴可以一起加入我們的行列！

# 具體目標

* 實現這個物流平台

* 誰可以使用這個平台？
  * 一般學生
  * 學生議員／學生代表
  * 議會秘書處

* 他有什麼功能呢？
  * 一般學生：在商城裡關注自己所留意的議題，不僅可以下單追蹤議題進度，還可以在留言區給予意見或回饋；當自己有興趣的議題沒人提過時，就自己上架吧！
  * 學生議員／學生代表／議會幕僚：接受商城裡的議題訂單，指派任務給幕僚一起研究推動議題，整合所需要的資料向學校提案！
  * 議會秘書處：檢視提案、分發任務，解決平台上的操作問題，幫助學生和議員追蹤議題的推動進度！

* 我們怎麼開始實現
  * 雖然一般學生那端看起來比較好做，因為類似的東西就有校務建言、提點子平台等等
  * 但這次（至少這學期）我們「必須」先完成學生議員端的功能和介面！
    * 為什麼？設計一個讓學生議員／學生代表／議會幕僚容易上手的系統，才能夠確保一般同學對學校有許多想法的時候，背後有人默默為他們付出。（如果老闆不在了，顧客想下單議題是沒辦法的）
    * Insider = 學生議員／學生代表／議會幕僚！

# 專案預計時程
* 3月：學習技術（如果有需要）、畫出／做出學生議員端的功能和介面prototype（還不需要有後端）
* 4月：進行第一次的Insider測試、行銷（告訴大家我們正在開發這個系統）、開始交付後端的API
* 5月：迭代出新一版的學生議員端介面、跟後端整合在一起讓系統可以儲存資料
* 期末發表會：商城裡面有一些預設商品，議員可以模擬操作接單的過程。

這是一個長期專案（很可能會延續到下個學期甚至更久！）

如果進度超前，我們會開始製作一般學生端的功能（例如：開放大家關注商品、上架商品）！

# 預計用什麼技術達成

我們期待即戰力加入我們的團隊，但學習陌生但有用的技術也是不可或缺的！

* Web Application，網頁
* 前端 (Vue, JavaScript)
* 後端 (Express, JavaScript, Restful Web API)

# 招募對象

為了讓大家知道令人陌生的議會也有這麼好用的系統，我們非常需要行銷高手！
* 視覺設計 (含行銷、介面設計)：2-3人
* 文案撰寫：1-2人

* 前端工程師 (Vue, JavaScript)：2-3人
* 後端工程師 (Express, JavaScript, Restful Web API) 1-2人

* 願意跟專案主持人一起討論這個平台的想法，甚至是校務議題本身的人：不限！
  * 前提是你必須為GDSC社員：D
