---
title: 如何將產出的html部屬到githubpage
categories:
- Tech
feature_image: "https://picsum.photos/2560/600?image=2"  
excerpt: |
  快速demo網頁
---

### 1.新建一個repo

![https://docs.github.com/assets/cb-29762/mw-1440/images/help/repository/repo-create-global-nav-update.webp](https://docs.github.com/assets/cb-29762/mw-1440/images/help/repository/repo-create-global-nav-update.webp)

### 2.為repo命名

記得將repo設成(公開)public

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/94107a68-28b0-49fe-9acf-e75d00feda7b/Untitled.png?table=block&id=7dadd207-a469-446a-9a42-49e81da34d5f&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=gBfgh0yATa01rMNb29kZgMW7dv1mKpqaGPeFNUU5tDs&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/94107a68-28b0-49fe-9acf-e75d00feda7b/Untitled.png?table=block&id=7dadd207-a469-446a-9a42-49e81da34d5f&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=gBfgh0yATa01rMNb29kZgMW7dv1mKpqaGPeFNUU5tDs&downloadName=Untitled.png)

### 3.複製這段網址

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/943eac9f-58af-4f0f-9194-c99d8595a2d3/Untitled.png?table=block&id=320577e5-08cf-42a2-96a1-ff40780220d2&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=TFyMx3SCpEjpdKBwzqE1CPm5DKlhr99wngdoBgRhnWg&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/943eac9f-58af-4f0f-9194-c99d8595a2d3/Untitled.png?table=block&id=320577e5-08cf-42a2-96a1-ff40780220d2&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=TFyMx3SCpEjpdKBwzqE1CPm5DKlhr99wngdoBgRhnWg&downloadName=Untitled.png)

在終端機上輸入以下指令

git clone  [https://github.com/{{github帳號}}/{{repo名稱}}.git](https://github.com/princend/regression-simulator.git)

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/20dba264-0e35-4b6f-9965-f04e3ca2481a/Untitled.png?table=block&id=043cc936-c1cc-41c1-be82-5e3d6f70a071&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=7-CGcFcMUEESBUDjh7JgrpHh0RwRQGSlvGnXNW4eT8Q&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/20dba264-0e35-4b6f-9965-f04e3ca2481a/Untitled.png?table=block&id=043cc936-c1cc-41c1-be82-5e3d6f70a071&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=7-CGcFcMUEESBUDjh7JgrpHh0RwRQGSlvGnXNW4eT8Q&downloadName=Untitled.png)

### 4.打開對應的資料夾 將昨日的產出的線性回歸模擬器html 複製到資料夾

請將檔案名稱更名為index.html 比較不會有問題

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/fc82980f-72b6-46ab-b184-58a05559026a/Untitled.png?table=block&id=5b822b58-d234-480c-8c7c-d9fc27eb0fb3&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=aFcKoFgEik0TySMgJWH7CbEm7Pxe7lp4A6oy_twi6jw&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/fc82980f-72b6-46ab-b184-58a05559026a/Untitled.png?table=block&id=5b822b58-d234-480c-8c7c-d9fc27eb0fb3&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=aFcKoFgEik0TySMgJWH7CbEm7Pxe7lp4A6oy_twi6jw&downloadName=Untitled.png)

### 5.打開vscode commit 並push 上去

這裡有兩個步驟 
1.記得要提交(別忘了寫一下提交訊息)

2.記得要推送

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/90a2d305-c5f9-430f-bc6b-a35215fc0f42/Untitled.png?table=block&id=ce84a4a9-584f-4b93-81f3-9206bd80d1bf&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=Y3HTLAHlwJHGPLlDfPi45AEM1jE1kVIgn0yhoTYCcSs&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/90a2d305-c5f9-430f-bc6b-a35215fc0f42/Untitled.png?table=block&id=ce84a4a9-584f-4b93-81f3-9206bd80d1bf&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=Y3HTLAHlwJHGPLlDfPi45AEM1jE1kVIgn0yhoTYCcSs&downloadName=Untitled.png)

### 6.在github 的settings 選master 分支 按下save

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/6f8ab257-f6f8-4f20-8596-0e932bff8cc8/Untitled.png?table=block&id=255cb975-2afb-43c5-a966-b6da1571d94f&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=Yw3Ij3ctnAchbIZK8zhk6Nhcu53vFVferMKqUuiQffg&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/6f8ab257-f6f8-4f20-8596-0e932bff8cc8/Untitled.png?table=block&id=255cb975-2afb-43c5-a966-b6da1571d94f&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=Yw3Ij3ctnAchbIZK8zhk6Nhcu53vFVferMKqUuiQffg&downloadName=Untitled.png)

### 7.等待github部屬一下

右下角會出現deployments github page的超連結

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/e3bb8c4c-6f04-4054-93ef-377930100d4a/Untitled.png?table=block&id=ae436141-2c75-4fdc-851b-03c02ebab4a2&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=5IYvoLvmcys9aty2OLsvZccUhf1XJktf-694xnsRejI&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/e3bb8c4c-6f04-4054-93ef-377930100d4a/Untitled.png?table=block&id=ae436141-2c75-4fdc-851b-03c02ebab4a2&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=5IYvoLvmcys9aty2OLsvZccUhf1XJktf-694xnsRejI&downloadName=Untitled.png)

點一下會切換到另外一個頁面

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/17c89e15-ae15-4d7a-b274-cf59ece568c6/Untitled.png?table=block&id=fd8f9cb8-be83-45a3-bce0-687a9e988618&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=arEVKto6AbmTqCC6ToeDUKxPf4_vG2HMNhVQeGSN_oI&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/17c89e15-ae15-4d7a-b274-cf59ece568c6/Untitled.png?table=block&id=fd8f9cb8-be83-45a3-bce0-687a9e988618&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=arEVKto6AbmTqCC6ToeDUKxPf4_vG2HMNhVQeGSN_oI&downloadName=Untitled.png)

### 8.點開連結就會就會轉導到githubpage

![https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/a29428e7-8466-49bb-9b6c-5b604bfb304e/Untitled.png?table=block&id=6425e7c0-9fea-469c-838a-1b5ee8f94719&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=02Rn5_3kVSACFAjlTRg-tUUMPQ-uWERsCn4eUFjeWgk&downloadName=Untitled.png](https://file.notion.so/f/f/953daab3-6439-45b3-8cc8-b5c2b345f7ed/a29428e7-8466-49bb-9b6c-5b604bfb304e/Untitled.png?table=block&id=6425e7c0-9fea-469c-838a-1b5ee8f94719&spaceId=953daab3-6439-45b3-8cc8-b5c2b345f7ed&expirationTimestamp=1725264000000&signature=02Rn5_3kVSACFAjlTRg-tUUMPQ-uWERsCn4eUFjeWgk&downloadName=Untitled.png)

以下是我的github page

{% include iframe.html  url="https://princend.github.io/regression-simulator/" title="regression-simulator"%}
