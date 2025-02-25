---
title: AEM Guides編輯器設定
description: 為AEM Guides設定編輯器
exl-id: 437d9598-4afc-431f-81bd-6762e22656b7
source-git-commit: 988c288fc03e509a3a55e87b1e1ecd8fd07d1c92
workflow-type: tm+mt
source-wordcount: '778'
ht-degree: 0%

---

# XML編輯器設定

如果您在受限的環境中工作，則可以在特定資料夾設定檔中自訂「編輯器組態」 ，以選擇作者能夠檢視的功能。 套用此資料夾描述檔可以變更編輯器本身的外觀、CSS範本、可用的程式碼片段以及內容版本標籤。

您可能會選擇用於本課程的範例檔案會提供在[xmleditorconfiguration.zip](assets/xmleditorconfiguration.zip)檔案中。

>[!VIDEO](https://video.tv.adobe.com/v/342762?quality=12&learn=on)

## 自訂預設編輯器UI設定

您隨時可以將預設UI設定下載到本機系統，在您選擇的文字編輯器中對其進行變更，然後再次上傳。

1. 從「導覽」畫面中，按一下&#x200B;[!UICONTROL **工具**]&#x200B;圖示。

   ![工具圖示](images/reuse/tools-icon.png)

1. 在左側面板上選取&#x200B;**參考線**。

1. 按一下&#x200B;[!UICONTROL **資料夾設定檔**]&#x200B;圖磚。

   ![資料夾設定檔](images/reuse/folder-profiles-tile.png)

1. 選取資料夾設定檔。

1. 按一下&#x200B;[!UICONTROL **XML編輯器組態**]&#x200B;索引標籤。

1. 按一下「預設值」[!UICONTROL **「下載」**]。

   ![下載預設值](images/lesson-4/download-default.png)

您現在可以在文字編輯器中開啟及修改內容。 _AEM Guides安裝與設定_&#x200B;指南包含如何移除、自訂或新增功能到UI設定的範例。

## 上傳修改過的XML編輯器設定

自訂UI設定後，您可以上傳它。 請注意，範例設定檔&#x200B;_ui-config-restricted-editor.json_&#x200B;已隨附本課程的一組支援主題。

1. 在資料夾設定檔中，按一下&#x200B;[!UICONTROL **XML編輯器組態**]&#x200B;索引標籤。

1. 在XML編輯器設定下，按一下&#x200B;[!UICONTROL **上傳**]。

   ![上傳](images/lesson-4/upload.png)

1. 按兩下您修改後UI設定的檔案，或如這裡所示按一下提供的範例檔案。

   ![範例設定檔](images/lesson-4/sample-config-file.png)

1. 按一下熒幕左上角的&#x200B;[!UICONTROL **儲存**]。

您已成功上傳修改過的UI設定。

## 自訂CSS範本版面

和UI設定一樣，您可以下載CSS範本版面配置。 您可以在文字編輯器中開啟它並進行修改，以在上傳之前自訂主題的外觀和風格。

1. 從「導覽」畫面中，按一下&#x200B;[!UICONTROL **工具**]&#x200B;圖示。

   ![工具圖示](images/reuse/tools-icon.png)

1. 在左側面板上選取&#x200B;**參考線**。

1. 按一下&#x200B;[!UICONTROL **資料夾設定檔**]&#x200B;圖磚。

   ![資料夾設定檔](images/reuse/folder-profiles-tile.png)

1. 選取資料夾設定檔。

1. 按一下&#x200B;[!UICONTROL **XML編輯器組態**]&#x200B;索引標籤。

1. 在CSS範本配置下，按一下&#x200B;[!UICONTROL **下載**]。

   ![下載CSS](images/lesson-4/download-css.png)

您現在可以在文字編輯器中修改及儲存CSS內容。

## 上傳修改過的CSS範本版面

自訂CSS範本佈局後，您可以上傳它。 請注意，範例檔案&#x200B;_css-layout-ONLY-draft-comment-change.css_&#x200B;已隨附本課程的一組支援主題。 此檔案僅包含草稿註解變更，而&#x200B;_css-layout-draft-comment-change.css_&#x200B;則是整個檔案，僅供您測試或檢閱之用。

1. 在資料夾設定檔中，按一下&#x200B;[!UICONTROL **XML編輯器組態**]&#x200B;索引標籤。

1. 在CSS範本配置下，按一下&#x200B;[!UICONTROL **上傳**]。

   ![上傳CSS](images/lesson-4/upload-css.png)

1. 連按兩下您自己的自訂CSS配置或此處顯示的提供範例檔案的檔案。

   ![範例CSS檔案](images/lesson-4/sample-css-file.png)

1. 按一下熒幕左上角的&#x200B;[!UICONTROL **儲存**]。
您已成功上傳自訂的CSS範本版面配置。

## 編輯XML編輯器代碼片段

程式碼片段是可重複使用的內容片段，可以特定於產品或群組。 請注意，範常式式碼片段會隨本課程的支援檔案一起提供。

1. 從「導覽」畫面中，按一下&#x200B;[!UICONTROL **工具**]&#x200B;圖示。

   ![工具圖示](images/reuse/tools-icon.png)

1. 在左側面板上選取&#x200B;**參考線**。

1. 按一下&#x200B;[!UICONTROL **資料夾設定檔**]&#x200B;圖磚。

   ![資料夾設定檔](images/reuse/folder-profiles-tile.png)

1. 選取資料夾設定檔。

1. 按一下&#x200B;[!UICONTROL **XML編輯器組態**]&#x200B;索引標籤。

1. 在XML編輯器程式碼片段底下，按一下&#x200B;**上傳**。

   ![上傳代碼片段](images/lesson-4/upload-snippets.png)

1. 選擇您自己的程式碼片段，或使用提供的範例。

   ![範常式式碼片段](images/lesson-4/sample-snippet.png)

1. 按一下熒幕左上角的&#x200B;[!UICONTROL **儲存**]。

您已成功將新程式碼片段新增至編輯器。

## 自訂XML內容版本標籤

依預設，作者可建立自己選擇的標籤，並將這些標籤與主題檔案建立關聯。 這可能會導致同一標籤上出現不同的變化。 若要避免標籤不一致，您也可以從預先定義的標籤清單中選擇。

1. 從「導覽」畫面中，按一下&#x200B;[!UICONTROL **工具**]&#x200B;圖示。

   ![工具圖示](images/reuse/tools-icon.png)

1. 在左側面板上選取&#x200B;**參考線**。

1. 按一下&#x200B;[!UICONTROL **資料夾設定檔**]&#x200B;圖磚。

   ![資料夾設定檔](images/reuse/folder-profiles-tile.png)

1. 選取資料夾設定檔。

1. 按一下&#x200B;[!UICONTROL **XML編輯器組態**]&#x200B;索引標籤。

1. 在「XML內容版本標籤」下，按一下&#x200B;[!UICONTROL **下載**]。

   ![下載標籤](images/lesson-4/download-labels.png)

您現在已準備好視需要自訂標籤。

## 上傳XML內容版本標籤

下載並修改標籤之後，您就可以上傳「XML內容版本標籤」主題。 您可以選擇使用範例檔案&#x200B;_labels.json_，此範例檔案隨附本課程的一組支援主題。

1. 在資料夾設定檔中，按一下&#x200B;[!UICONTROL **XML編輯器組態**]&#x200B;索引標籤。

1. 在XML內容版本標籤下，按一下&#x200B;[!UICONTROL **上傳**]。

   ![上傳標籤](images/lesson-4/upload-labels.png)

1. 連按兩下您自己的自訂標籤或此處顯示的範例檔案。

   ![範例標籤檔案](images/lesson-4/sample-labels-file.png)

1. 按一下熒幕左上角的&#x200B;[!UICONTROL **儲存**]。

您已成功上傳自訂XML內容版本標籤。
