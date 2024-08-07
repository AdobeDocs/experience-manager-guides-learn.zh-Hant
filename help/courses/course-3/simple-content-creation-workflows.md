---
title: 簡單的內容建立工作流程
description: 在AEM Guides中建立內容
exl-id: e4b8e512-0688-44f7-b981-78af33b57b08
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '719'
ht-degree: 1%

---

# 簡單內容建立工作流程

AEM Guides編輯器提供多個捷徑，可簡化內容建立工作流程。 這些捷徑可讓使用者快速新增和修改影像、一次處理多個主題、更正錯誤、下載主題PDF，以及處理版本和標籤。

>[!VIDEO](https://video.tv.adobe.com/v/342770?quality=12&learn=on)

## 新增影像

可以直接從本機磁碟機新增影像。

1. 將影像直接拖放至主題中。 **上傳Assets**&#x200B;對話方塊就會顯示。

   ![上傳Assets對話方塊](images/lesson-15/upload-assets-dialog.png)

1. 將資料夾路徑修改至所需的影像位置。

1. 將影像名稱變更為代表其用途的名稱。

1. 按一下 [!UICONTROL **上傳**]。

## 修改影像

1. 拖放角落以調整影像大小。

1. 拖放影像至主題中的其他位置。

1. 使用右側面板上的&#x200B;**內容屬性**&#x200B;來修改影像的

   - 縮放

   - position

   - 對齊方式，或

   - 其他屬性。

   ![內容屬性](images/lesson-15/content-properties.png)

## 使用多個主題

「分割檢視」在比較主題、在主題之間複製和貼上，或在不同主題之間拖放內容時相當實用。

1. 開啟兩個或多個相關主題。

1. 按一下某個檔案的「標題」標籤以開啟內容功能表。

1. 選取&#x200B;[!UICONTROL **分割**]。

1. 選擇&#x200B;**右**。

   ![分割檢視](images/lesson-15/split-view.png)

## 更正拼字錯誤

1. 找到包含錯誤的字詞或片語。

1. 按住&#x200B;[!UICONTROL **Ctrl**]。

1. 在錯誤上按一下滑鼠的次要按鈕。

1. 選取正確的拼字。

已在主題文字中更正錯誤。

## 下載主題PDF

使用者可能想要下載目前主題的PDF，以標籤或與其他人共用。

1. 按一下熒幕右上方的&#x200B;[!UICONTROL **預覽**]。

1. 按一下主題上方的&#x200B;[!UICONTROL **PDF圖示**]。 對話方塊隨即顯示。

   ![PDF匯出](images/lesson-15/pdf-export.png)

1. 視需要填入&#x200B;**轉換名稱**&#x200B;或&#x200B;**DITA-OT命令列引數**&#x200B;的資訊。 請注意，如果所有欄位都保留空白，仍會產生PDF。

1. 按一下&#x200B;[!UICONTROL **下載**]。 會產生PDF。

1. 使用可用的圖示來設定、下載或共用PDF主題。

## 在存放庫或地圖中尋找主題

1. 開啟主題。

1. 在「標題」標籤上按一下滑鼠的次要按鈕。

1. 選取&#x200B;**在**&#x200B;中尋找。

1. 選擇&#x200B;**存放庫**&#x200B;或&#x200B;**對應**&#x200B;以跳至所要的主題位置。

## 版本主題

1. 變更主題。

1. 儲存主題。

1. 按一下左上方功能表上的&#x200B;**存放庫**&#x200B;圖示。

   ![存放庫圖示](images/lesson-15/repository-icon.png)

1. 在對話方塊中，為新版本&#x200B;**新增**&#x200B;個註解。

   ![新版本對話方塊](images/lesson-15/version-dialog.png)

1. 按一下「[!UICONTROL **儲存**]」。

版本號碼會更新。

## 載入版本標籤

嘗試僅根據版本號碼來追蹤主題的狀態可能會很困難。 標籤可讓您更容易識別經歷了多次修訂之主題的確切狀態。

1. 選取&#x200B;**資料夾設定檔**。

1. 在資料夾設定檔中，設定XML編輯器。

   a.選取畫面左上方的編輯。

   b.在「XML內容版本標籤」下，新增主題或使用現有主題。

   ![內容版本標籤](images/lesson-15/version-labels.png)

1. 選取&#x200B;[!UICONTROL **上傳**]。

1. 選擇檔案，如ReviewLabels.json或類似檔案。 另一部影片將說明如何建立這類檔案。

1. 按一下&#x200B;[!UICONTROL **開啟**]。

1. 按一下「資料夾設定檔」畫面左上角的&#x200B;[!UICONTROL **儲存**]。

1. 按一下右上方的&#x200B;[!UICONTROL **關閉**]。

現在已載入版本標籤。

## 指派版本標籤

1. 載入版本標籤。

1. 按一下目前主題左上角的&#x200B;[!UICONTROL **使用者偏好設定**]&#x200B;圖示。

   ![資料夾設定檔](images/lesson-15/folder-profile-icon.png)

1. 選取先前已載入版本標籤的相同資料夾設定檔。

1. 在「使用者偏好設定」對話方塊中，確定「基本路徑」參照的資訊與「資料夾設定檔」已套用的資訊相同。

   ![使用者喜好設定](images/lesson-15/user-preferences.png)

1. 按一下「[!UICONTROL **儲存**]」。

1. 版本主題。

1. 新增註解，並從下拉式清單中選取版本標籤。

   ![新版本標籤對話方塊](images/lesson-15/labels-dialog.png)

1. 按一下「[!UICONTROL **儲存**]」。

版本號碼會更新。

## 檢視版本記錄和標籤

1. 從左側面板，找出目前的主題標題。

1. 按一下標題以開啟內容功能表。

1. 選取Assets UI中的&#x200B;[!UICONTROL **檢視**]。

   ![Assets UI](images/lesson-15/view-assets-ui.png)

   - 含有標籤的版本記錄會顯示在左側。

   ![版本記錄](images/lesson-15/version-history.png)

1. 按一下版本以存取選項，例如&#x200B;**還原到此版本**&#x200B;和&#x200B;**預覽版本**。

## 建立新範本

主題和地圖都有範本。 管理員可以存取左側面板中的範本。

1. 按一下左側面板中的&#x200B;[!UICONTROL **範本**]。

1. 選取「地圖」或「主題」以開啟相關的內容功能表。

1. 按一下以新增範本。

   ![新主題範本](images/lesson-15/version-history.png)

1. 填入結果對話方塊中的欄位。

殼層範本隨即出現，其中包含範例內容和範例結構。
