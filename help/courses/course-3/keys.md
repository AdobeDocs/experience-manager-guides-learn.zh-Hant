---
title: 索引鍵
description: 在AEM Guides中使用DITA時，索引鍵可讓您將變數資訊加入至
exl-id: cb64e094-fe6d-4a5e-8f0e-25ae58aaa2c6
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---

# 索引鍵

不同的材料集可能包含類似的資訊，需要在特定位置自訂。 鍵可讓您在使用DITA時包含變數資訊。

您可選擇用於本課程的範例檔案會提供在[keys.zip](assets/keys.zip)檔案中。

>[!VIDEO](https://video.tv.adobe.com/v/342756?quality=12&learn=on)

## 啟用金鑰

1. 上傳提供的範例檔案集。

   a.載入zip檔案。

   b.重新整理AEM環境。

   c.選取要擷取的檔案。

   ![選取Zip](images/lesson-9/select-zip.png)

   d.按一下頂端工具列中的&#x200B;[!UICONTROL **擷取封存**]。

   ![工具列](images/lesson-9/extract-archive.png)

   e.在對話方塊中，選擇要擷取檔案的特定位置，例如名為「金鑰」的資料夾。

   f.按一下&#x200B;[!UICONTROL **下一步**]。

   g.略過任何衝突，因為之前從未上傳過的內容不存在衝突。

   h.選取畫面右上方的&#x200B;[!UICONTROL **擷取**]。

1. 擷取完成時，按一下&#x200B;[!UICONTROL **移至目標資料夾**]。

   ![確認](images/lesson-9/go-to-target.png)

## 將索引鍵解析為參考值

若要正確使用索引鍵，「使用者偏好設定」必須參照特定對應作為「根對應」。 此地圖內是索引鍵的集合，分組在主題群組內。 開啟對映和主題會將鍵解析為此對映參照的值。

1. 指定根對應。

   a.在「按鍵」畫面中，開啟地圖。

   b.設定使用者偏好設定。

   c.按一下頂端工具列上的&#x200B;[!UICONTROL **使用者偏好設定**]&#x200B;圖示。

   ![頂端工具列](images/lesson-9/author-view.png)

   d.按一下金鑰圖示以指定將用於解析金鑰的&#x200B;**根對應**。

   e.選取任何所需Assets的核取方塊。

   ![Assets下拉式清單](images/lesson-9/select-assets.png)

   f.按一下&#x200B;[!UICONTROL **選取**]。

   g. **儲存**&#x200B;使用者偏好設定。

1. 瀏覽至&#x200B;**地圖檢視**。

1. 開啟指定的對應。

鍵已解析。

## 手動新增索引鍵

1. 開啟具有指定根對映的對映。

1. 選取金鑰。

   ![索引鍵下拉式清單](images/lesson-9/hybrid-key.png)

1. 插入新的索引鍵。

   a.按一下地圖中的有效位置。

   b.選取頂端工具列上的&#x200B;**Keydef**&#x200B;圖示。

   ![索引鍵工具列](images/lesson-9/key-icon.png)

   c.在「插入Keydef」對話方塊中，輸入唯一的「索引鍵」值，以符合您正在建立的定義。

   d.按一下&#x200B;[!UICONTROL **插入**]。

1. 在keydef中新增topicmeta。

   a.按一下頂端工具列上的&#x200B;[!UICONTROL **插入元素**]&#x200B;圖示。

   ![索引鍵工具列](images/lesson-9/add-icon.png)

   b.在插入元素對話方塊中，搜尋並選取「topicmeta」。

1. 在topicmeta中新增關鍵字。

   a.按一下頂端工具列上的&#x200B;[!UICONTROL **插入元素**]&#x200B;圖示。

   ![索引鍵工具列](images/lesson-9/add-icon.png)

   b.在插入元素對話方塊中，搜尋並選取「關鍵字」。

1. 在topicmeta中新增關鍵字。

   a.按一下頂端工具列上的&#x200B;[!UICONTROL **插入元素**]&#x200B;圖示。

   ![索引鍵工具列](images/lesson-9/add-icon.png)

   b.在&#x200B;**插入元素**&#x200B;對話方塊中，搜尋並選取「關鍵字」

1. 在關鍵字中輸入keydef的值。

在地圖中，您的keydef現在看起來應該像這樣：

![Keydef已完成](images/lesson-9/keydef.png)

## 將keydef設定為程式碼片段

程式碼片段是小型內容片段，可在說明檔案專案的各種主題中重複使用。 您可以將單一金鑰定義設定為程式碼片段，而不需手動產生每個金鑰定義。

1. 在地圖中選取keydef元素。

1. 在內容功能表中，按一下&#x200B;[!UICONTROL **建立程式碼片段**]。

1. 在新程式碼片段對話方塊中，新增標題和說明。
您也可以從內容中移除現有的金鑰或關鍵字定義。

1. 按一下&#x200B;[!UICONTROL **建立**]。

1. 在左側面板上，選取&#x200B;**代碼片段**。

1. 從「代碼片段」面板將您剛建立的代碼片段拖放至地圖。

1. 視需要使用「內容屬性」更新keydef。
儲存並重新整理後，此組金鑰將可供已定義包含相同根對映之對映的任何使用者使用。
