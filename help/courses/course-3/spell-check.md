---
title: 拼字檢查並尋找/取代
description: 在AEM Guides中使用拼字檢查和尋找/取代
exl-id: 5f39618d-a919-4d3c-a4de-2896f2d1bf20
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 1%

---

# 拼字檢查與尋找/取代

AEM Guides編輯器擁有強大的拼字檢查和尋找及取代功能。

>[!VIDEO](https://video.tv.adobe.com/v/342768?quality=12&learn=on)

修正拼字錯誤

1. 在開啟的主題中找到錯誤，並以紅色底線顯示。

1. 按住Ctrl鍵並按一下文字內的滑鼠輔助按鈕。

1. 從建議中選擇正確的拼字。

如果不建議使用正確的拼字，您可以隨時手動編輯單字。

## 切換至AEM拼字檢查

您可能要使用瀏覽器預設字典以外的拼字檢查工具。

1. 瀏覽至&#x200B;**編輯器設定**。

1. 選取&#x200B;**一般**&#x200B;設定標籤。

   ![拼字檢查設定](images/lesson-11/configure-dictionary.png)

1. 有兩個選項：

   - **瀏覽器拼字檢查** — 使用瀏覽器內建字典進行拼字檢查的預設設定。

   - **AEM拼字檢查** — 使用此項來使用AEM的自訂字典建置自訂字詞清單。

1. 選擇&#x200B;**AEM拼字檢查**。

1. 按一下「[!UICONTROL **儲存**]」。

設定自訂字典

管理員可以變更設定，讓AEM字典可以辨識自訂單字，例如公司名稱。

1. 導覽至&#x200B;**工具**&#x200B;窗格。

1. 登入&#x200B;**CRXDE Lite**。

   ![AEM UICRXDE Lite圖示](images/lesson-11/crxde-lite.png)

1. 瀏覽至&#x200B;**_/apps/fmdita/config節點_**。

   ![CRXDE Lite設定節點](images/lesson-11/config-node.png)

1. 建立新檔案。

   a.以滑鼠右鍵按一下設定資料夾。

   b.選擇&#x200B;**建立>建立檔案**。

   ![新字典檔案建立](images/lesson-11/new-dictionary-file.png)

   c.將檔案命名為&#x200B;_&#x200B;**user_dictionary.txt**&#x200B;_。

   ![使用者字典文字](images/lesson-11/user-dictionary.png)

   d.按一下&#x200B;[!UICONTROL **確定**]。

1. 開啟檔案。

1. 新增要包含在自訂字典中的單字清單。

1. 按一下&#x200B;[!UICONTROL **「儲存全部」**]。

1. 關閉檔案。

作者可能需要重新啟動網頁編輯器工作階段，才能在AEM字典中取得更新的自訂字詞清單。

## 在單一檔案中尋找和取代

1. 按一下頂端工具列上的「尋找和取代」圖示。

   ![尋找取代圖示](images/lesson-11/find-replace-icon.png)

1. 在底部的工具列中，輸入單字或片語。

1. 按一下&#x200B;[!UICONTROL **尋找**]。

1. 必要時，鍵入一個單字以取代找到的單字。

1. 按一下&#x200B;[!UICONTROL **取代**]。

## 在存放庫中尋找和取代

1. 瀏覽至&#x200B;**存放庫**。

1. 按一下畫面左下方的&#x200B;[!UICONTROL **尋找和取代**]&#x200B;圖示。

1. 按一下&#x200B;[!UICONTROL **顯示設定**]&#x200B;圖示。

1. 選擇

   - **取代前簽出檔案** — 如果管理員啟用此功能，將會在取代搜尋詞前自動簽出檔案。

   - **僅限全字** — 限制搜尋只傳回輸入的確切字詞或片語。

   ![在存放庫中尋找取代](images/lesson-11/repository-find-replace.png)

1. 按一下&#x200B;[!UICONTROL **套用篩選器**]&#x200B;圖示以選取存放庫中要執行搜尋的路徑。

1. 輸入要尋找與取代的字詞。

1. 必要時，請選取&#x200B;**取代後建立新版本**。

1. 按一下&#x200B;[!UICONTROL **尋找**]。

1. 開啟所需的檔案，然後使用箭頭來從一個找到的結果瀏覽至下一個結果。

   ![尋找取代導覽UI](images/lesson-11/find-replace-navigation.png)
