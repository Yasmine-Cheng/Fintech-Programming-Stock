### (自身定位)是什麼屬性的投資人？
->利用公司2021 Q1的資訊選擇投資標的，於3月買入、6月預計賣出

1. 本益比的概念

    本益比 = 股價 / 每股盈餘 ( 股價 = EPS * 本益比 )

    本益比 = 總市值 / 淨利潤

    意義：公司每賺1元，投資人願意投資的金額

    EX： 假設一家公司的 EPS 為 1 元，而股價為 15 元，表示公司每賺 1 元，投資人願意出 15 元投資。
    PS： 將本益比倒過來看，就是投資報酬率的概念，表示投資人花 15 元投資一年後，公司會幫投資人賺取 1 元，也就是 6.67% 的報酬。
2. 甚麼是本益比?

    本益比(Price-to-Earning Ratio ) 簡稱 PE 或 PER，顧名思義是「成本和獲利的比例」

    本益比的意義 : 買進股票後，多久可以回本

    **本益比 (倍) = 現在股價(Price) / 預估未來每年每股盈餘(EPS)**

    EX：例如公司A股價100元，而預估未來每年的[每股盈餘EPS](https://rich01.com/what-is-eps/)是5元，([每股盈餘](https://rich01.com/what-is-eps/)意思是你手上的每1股股票今年賺了多少錢)，

    本益比 = 股價100元/每年賺5元 = 20倍，換句話說需要20年才能回本。

    ![image](https://github.com/Yasmine-Cheng/Fintech-Programming-Stock/blob/main/test%20stage/PE_ratio.png)

3. 為什麼使用本益比

    - 股票估值最常運用的指標之一
    
    - 簡單明瞭告訴投資者在假定公司利潤不變的情況下，以交易價格買入，投資股票靠利潤回報需要多少年的時間回本，同時它也代表了市場對股票的悲觀或者樂觀程度
4. 什麼產業適合使用本益比？

    需檢驗公司性質，不適合使用本益比作為評價：
    
    1. 盈餘操弄很容易的行業（如金融業）
    
    2. 盈餘波動性非常大的行業（如不動產業）
5. 常見的本益比衡量方式
    - 使用該公司歷史平均
      **注意公司是否曾經轉型或營收組合大幅改變**

    - 使用產業平均
      **要先清楚定義同業，與該公司直接競爭的競爭對手本益比做平均**

    - 利用營收成長率對本益比調整
      **使用營收成長率搭配本益比逕行估價，營收成長率與本益比若明顯呈現正比，表示這家公司適合使用**

6. 本益比數字高低怎麼看? (方法一，以2020年舉例)

    **昂貴 : 本益比>20**  (相當於報酬率低於5%)

    **合理 : 本益比=15**  (相當於報酬率6.6%)

    **便宜 : 本益比<12**  (相當於報酬率8.3%以上)

    但仍然要考慮**成長性**與**安全性**

    1. **安全性**：獲利越安全穩定的公司，市場傾向給它更低的報酬率，也就是更高的本益比。想像一下如果買一間公司的股票跟買債券一樣安全，那股票和債券報酬率應該會差不多低。

    2. **成長性**：當成長性越高，本益比通常也越高，用歷史本益比通常無法反映未來成長性，因此乍看之下本益比會偏高看起來較昂貴。

    本益比越小，代表股價越便宜，投資可以更快回本

    - 以味全1201為例
        - **本益比 = 現在股價 / 預估未來每年每股盈餘(EPS)**
        - 2020年資料來源 : [https://www.twse.com.tw/zh/page/trading/exchange/FMNPTK.html](https://www.twse.com.tw/zh/page/trading/exchange/FMNPTK.html)
        - 2020年的股價為 : 21.18元
        - 2020年EPS資料來源 : [https://invest.cnyes.com/twstock/TWS/1201/financials/ratios](https://invest.cnyes.com/twstock/TWS/1201/financials/ratios)
        - 2020年EPS為 : 1.06元
        - 2020年本益比為 : 21.18 / 1.06 = 19.9811(和實際值有誤差)
        - 每月本益比資料來源(計算時，將12個月的本益比做平均): [https://www.wantgoo.com/stock/1201/enterprise-value/price-to-earning-ratio](https://www.wantgoo.com/stock/1201/enterprise-value/price-to-earning-ratio)
7. 用本益比計算合理股價(方法二：用5年內的本益比及EPS來推算股價區間)
    - 計算方式參考資料：
       1. [https://www.cmoney.tw/notes/note-detail.aspx?nid=8070](https://www.cmoney.tw/notes/note-detail.aspx?nid=8070)
       2. [https://manage-money.com/pe-ratio/](https://manage-money.com/pe-ratio/)

    - 將近5年的本益比按造最小值、中間值、最大值排列出來，計算合理區間。
         1.  最小值：歷年最低本益比取平均數(便宜股價)
         2.  P25：最小值與中間值的平均數(安全股價)
         3.  中間值：所有數值取平均數(合理股價)
         4.  P75：最大值與中間值的平均數(觀察股價)
         5.  最大值：歷年最高本益比取平均數(昂貴股價)

        **注意：若EPS太低(小於1)，推估出來的合理股價會失真**
    - 以統一1216為例

        - 最近5年EPS資料來源：[https://invest.cnyes.com/twstock/TWS/1201/financials/ratios](https://invest.cnyes.com/twstock/TWS/1201/financials/ratios)
        - 資料位置：網頁右邊選「年度」，下拉左側「獲利能力」中的最後一行「每股盈餘(元)」
        - 可得出最近5年EPS的平均為：(3.79+3.35+3.07+7.01+2.56=19.78)/5=3.956
        - 歷年本益比資料來源：[https://www.twse.com.tw/zh/page/trading/exchange/BWIBBU.html](https://www.twse.com.tw/zh/page/trading/exchange/BWIBBU.html)
        - 可得出105~109年之本益比區間：

               便宜股價：8.64 x 3.956 = 34.17984

               安全股價：9.202083 x 3.956 = 36.403442

               合理股價：15.417858671853656 x3.956 = 60.993048905853065

               觀察股價：20.607083 x 3.956 = 81.521622

               昂貴股價：20.686 x 3.956 = 81.833816

8. 使用本益比衡量的注意事項
    - 股價表現出來的是當時的市場情緒，當一家公司的本益比很高時，往往不是因為投資人真的願意賺取比較低的報酬，而是預期公司未來會賺很多才投資。
    - 有些產業的本益比本來就比較低，通常是這樣的公司是成熟穩定的公司，而正在成長的產業則會有比較高的本益比。
9. 食品業本益比的相關連結參考:
    - 類股明細：[https://www.cmoney.tw/follow/Channel/category-stock-8-12010](https://www.cmoney.tw/follow/Channel/category-stock-8-12010)
    - 食品業分類：[https://statementdog.com/taiex/5-food-industry](https://statementdog.com/taiex/5-food-industry)
    - 食品工業財務資訊 : [https://mops.twse.com.tw/mops/web/t123sb09_q1](https://mops.twse.com.tw/mops/web/t123sb09_q1)
    - [https://goodinfo.tw/StockInfo/ShowK_ChartFlow.asp?RPT_CAT=PER&STOCK_ID=1201&CHT_CAT=WEEK](https://goodinfo.tw/StockInfo/ShowK_ChartFlow.asp?RPT_CAT=PER&STOCK_ID=1201&CHT_CAT=WEEK)
