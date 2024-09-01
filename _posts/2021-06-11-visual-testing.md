---
title: Visual-Testing
categories:
- Tech
feature_image: "https://picsum.photos/2560/600?image=2"  
excerpt: |
    視覺測試評估應用程序的可見輸出，並將該輸出與設計預期的結果進行比較。 
---


#### [What] 什麼是視覺測試？？

> 視覺測試評估應用程序的可見輸出，並將該輸出與設計預期的結果進行比較。

![https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/30ca0998-2e82-4e64-b4b6-79d012606c56/_2021-06-11_8.57.10.png?table=block&id=7683a685-8078-42cf-bd68-9d87e1480342&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=jd3mL-Z6DdICC5YFCKapREmEArs7eBdmlQkx9e3mx6Y&downloadName=_2021-06-11_8.57.10.png](https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/30ca0998-2e82-4e64-b4b6-79d012606c56/_2021-06-11_8.57.10.png?table=block&id=7683a685-8078-42cf-bd68-9d87e1480342&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=jd3mL-Z6DdICC5YFCKapREmEArs7eBdmlQkx9e3mx6Y&downloadName=_2021-06-11_8.57.10.png)

#### [When] 何時進行視覺測試？？

- 開發人員在開發期間對單個組件運行可視化測試

- 在端到端測試期間對運行中的應用程序運行可視化測

- 成為持續集成工具中運行的CI/CD 管道的一部分

#### [Why] 為什麼要進行視覺測試？

##### 先看看以下圖片吧！

![https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/011b37ab-bea9-4c6d-ad95-8c58f2d4e0e6/ig.jpeg?table=block&id=d98e5fa7-3e54-4b65-8684-19ff9579dbf5&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=JaQJ6BCMPY2uTjdRy6psx1ceEPC6MEwkzVhmRaLbGlE&downloadName=ig.jpeg](https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/011b37ab-bea9-4c6d-ad95-8c58f2d4e0e6/ig.jpeg?table=block&id=d98e5fa7-3e54-4b65-8684-19ff9579dbf5&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=JaQJ6BCMPY2uTjdRy6psx1ceEPC6MEwkzVhmRaLbGlE&downloadName=ig.jpeg)

這是一則在ig上的廣告，但是他宣傳文案全部擠在一起，你認爲會對收入產生影響嗎？？

#### [Benefit] 自動化視覺測試好處都有啥？？

![https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/6303efc1-2681-489b-8e01-b8003fa952a4/test.gif?table=block&id=8202d17f-2f38-4645-8442-84d662eeceb7&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=Uj2KOFFCKstB7b3hZC6qVjKXsUkJuVIdJoA1MxwXsZ0&downloadName=test.gif](https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/6303efc1-2681-489b-8e01-b8003fa952a4/test.gif?table=block&id=8202d17f-2f38-4645-8442-84d662eeceb7&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=Uj2KOFFCKstB7b3hZC6qVjKXsUkJuVIdJoA1MxwXsZ0&downloadName=test.gif)

##### 1. 大量縮短測試時間

     假設你是一個測試人員，你有以下應用程序需測試

- 5 種操作系統：Windows、MacOS、Android、iOS 和 Chrome。
- 5 種流行瀏覽器：Chrome、Firefox、Internet Explorer（僅限 Windows）、Microsoft Edge（僅限 Windows）和 Safari（僅限 Mac）。
- 移動設備的 2 種屏幕方向：縱向和橫向。
- 10 種標準移動設備顯示分辨率和 18 種標準台式機/筆記本電腦顯示分辨率，從 XGA 到 4G

### 計算一下需要測試的屏幕配置

每個平台上運行的瀏覽器（總共 21 種組合）乘以十個移動設備的兩個方向 (2×10)=20 添加到 18 個桌面顯示分辨率

## 21 x (20+18) = 21 x 38 = 798

 如果又有100個頁面

# 798x100 = 79,800

 總共有 79800 個測試案例...

##### 2.減少人事成本

    

      不用再多請測試人員，並由機器取代，以減少公司人事成本

##### 3.跟上敏捷開發

      若是開發團隊採用敏捷開發模式，用戶界面測試通常是隨意的和隨機的，我們會在發布的最後一天或更糟地在生產中發現問題，並被迫做出關於延遲發布和重新組織已經在進行中的工作的艱難決定，如果採用自動化視覺測試，可以解決此問題。

     

# [Tool] Percy

![https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/061b4fde-9ee0-4538-88d4-488aa3d29d73/_2021-06-11_9.01.01.png?table=block&id=18e986eb-be4e-42de-bc44-bcd2193b128e&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=Miwyhn4Sn5Is6QT-Nu2v_TSYWlywe1un8CmRRM3ZEHE&downloadName=_2021-06-11_9.01.01.png](https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/061b4fde-9ee0-4538-88d4-488aa3d29d73/_2021-06-11_9.01.01.png?table=block&id=18e986eb-be4e-42de-bc44-bcd2193b128e&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=Miwyhn4Sn5Is6QT-Nu2v_TSYWlywe1un8CmRRM3ZEHE&downloadName=_2021-06-11_9.01.01.png)

                                                                percy 歷史寓意為「刺破」

## 介紹

對Ｗeb應用程序進行連續的視覺檢查測試工具

1分鐘介紹 percy on youtube

{%include video.html id="1Sr_h9_3MI0" title="percy video" %}



### 使用percyscript

clone github上的專案
[https://github.com/percy/example-percyscript](https://github.com/percy/example-percyscript)

程式主要內容

```jsx
PercyScript.run(async (page, percySnapshot) => {

  // 起server
  let server = httpServer.createServer();
  server.listen(PORT);

  console.log(`Server started at ${TEST_URL}`);

  // 去該網址拍照
  await page.goto(TEST_URL);
  await percySnapshot('TodoMVC home page');

  await page.type('.new-todo', 'A really important todo');

  //針對該測試網頁按下enter
  await page.keyboard.press('Enter');
  // 針對 768, 992, 1200 的螢幕寬度 作snapshot
  await percySnapshot('TodoMVC with a new todo', { widths: [768, 992, 1200] });
  server.close();
});
```

按照範本步驟操作後，最後匯出差異圖檔於percy.io上

![https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/cda41608-ce10-48ca-8991-acaf032eb239/_2021-06-11_8.07.56.png?table=block&id=af3e4942-7b68-4aec-bb80-e86b6ba92f01&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=YPbvPczsnq-wdprRyuQ9eyjvs4_LfJ-6g3w4PKZbu08&downloadName=_2021-06-11_8.07.56.png](https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/cda41608-ce10-48ca-8991-acaf032eb239/_2021-06-11_8.07.56.png?table=block&id=af3e4942-7b68-4aec-bb80-e86b6ba92f01&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=YPbvPczsnq-wdprRyuQ9eyjvs4_LfJ-6g3w4PKZbu08&downloadName=_2021-06-11_8.07.56.png)

## 優點

 1. 可以用CI/CD中

    只要塞入 PERCY_TOKEN 的環境變數在CI環境中

 2. 可以用於 github action中

    同上

 3. 可以用於storybook中

 

```jsx
// add Percy parameters to a single story via add's 3rd argument.
storiesOf('Circle Stories', module)
  .add(
    'with multiple widths',
    () => <span>This span renders in widths of 222px and 333px</span>,
    { percy: { widths: [222, 333] } }
  );
```

 4. 多種測試框架(Cypress,Puppeteer,Protracto....) 可以利用 Percy  SDK 針對現有套件進行視覺測試

   以下為Cypress測試框架

```jsx
describe('CurrencySPA', () => {

    beforeEach(() => {
        cy.server();
        cy.route('GET', '/api/rates', 'fixture:rates.json'); // Mock Daily Rates Response

        cy.visit('localhost:3000');
    })

    it('Loads Daily Rates', () => {
        cy.get('#app > h1').should('have.text', 'Currency Rates'); // Confirm Page Header Title
        cy.get('.loading').should('not.be.visible');
        cy.get('tbody>tr').eq(0).should('contain', 'EUR');
        cy.get('tbody>tr').eq(1).should('contain', '1.12805');
        cy.percySnapshot();
    });

    it('Convert Currency', () => {
        cy.route('POST', '/api/convert', { // Mock Convert Currency Response
            "rate": 10244.442
        });
        cy.get('.menu > a:nth-child(3)').click(); // Click Exchange Rates Menu
        cy.get('#app > h1').should('have.text', 'Exchange Rate'); // Confirm Page Header Title
        cy.get('.loading').should('not.be.visible');
        cy.get('#from').select('BTC');
        cy.get('#to').select('USD');
        cy.get('#amount').type('1');
        cy.get('.submit').click();
        cy.get('#result').should('have.text', 'USD 10244.442');
        cy.percySnapshot();
    });

    it('Loads Historical Rates', () => {
        cy.get('.menu > a:nth-child(4)').click(); // Click Historicals Rates Menu
        cy.get('#app > h1').should('have.text', 'Historical Rates'); // Confirm Page Header Title
        cy.get('#date')
            .type('2019-07-02') // Will revert to 2019-07-01 (known bug)
            .blur();
        cy.get('.submit').click();
        cy.get('table').should('be.visible');
        cy.percySnapshot();
    });
});
```

5.可發布通知於slack上

![https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/7e31f7b2-74d9-4c9d-9559-6ec227490dd9/_2021-06-11_8.51.14.png?table=block&id=0a309ef1-5064-4a65-9e62-62397573c7a2&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=V3q057ejKCW863iLlUzqZGbK9U4VvRYuS8DE5eP1YWg&downloadName=_2021-06-11_8.51.14.png](https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/7e31f7b2-74d9-4c9d-9559-6ec227490dd9/_2021-06-11_8.51.14.png?table=block&id=0a309ef1-5064-4a65-9e62-62397573c7a2&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=V3q057ejKCW863iLlUzqZGbK9U4VvRYuS8DE5eP1YWg&downloadName=_2021-06-11_8.51.14.png)

## 缺點

  1.需註冊

     若是免費會員則圖片上限一個月只有5000張screenshots

![https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/116dc59e-8328-4f3c-bcda-e476d0217493/_2021-06-11_8.54.49.png?table=block&id=8047a479-1466-4a0f-b08f-081b3fa73507&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=Vg-c94MHf6Sgpg7wz_6BB6jZeLc_qSvL9TF4hr6zsoI&downloadName=_2021-06-11_8.54.49.png](https://file.notion.so/f/f/43e70cd6-a5b7-43d6-8a08-628e36b11757/116dc59e-8328-4f3c-bcda-e476d0217493/_2021-06-11_8.54.49.png?table=block&id=8047a479-1466-4a0f-b08f-081b3fa73507&spaceId=43e70cd6-a5b7-43d6-8a08-628e36b11757&expirationTimestamp=1725264000000&signature=Vg-c94MHf6Sgpg7wz_6BB6jZeLc_qSvL9TF4hr6zsoI&downloadName=_2021-06-11_8.54.49.png)

   

   2.一定會匯出圖檔到註冊的percy.io 專案中

# 參考

[什麼是視覺測試](https://applitools.com/blog/visual-testing/?fbclid=IwAR2MxyS4ko9q4dP6QvVnXMhSMuMociZiMJuacVOA0LUhW0dhCj_XQQ3sAK8)

[https://docs.percy.io/docs/percy-platform-basics](https://docs.percy.io/docs/percy-platform-basics)

[https://www.sitepoint.com/vue-slots-comprehensive-guide/](https://www.sitepoint.com/vue-slots-comprehensive-guide/)