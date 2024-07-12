---
title: 使用報表
description: 使用 [!DNL Adobe Experience Manager Guides]中的報告
exl-id: 755506a6-c416-4a8c-8359-8db7e63a90a4
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '693'
ht-degree: 0%

---

# 使用報表

「對映控制面板」中的「報表」索引標籤可讓您識別並解決中斷的連結、被參照和重複使用的內容(conref)、交叉參照或其他遺漏資訊。

>[!VIDEO](https://video.tv.adobe.com/v/339039?quality=12&learn=on)

## 準備練習

您可以在此處下載練習的範例檔案。

[練習 — 下載](assets/exercises/working-with-reports.zip)

## 上傳Assets

1. 在「存放庫檢視」中，選取主資料夾中的省略符號圖示，以開啟「選項」功能表。

   ![省略符號–9.png](images/ellipses-9.png)

1. 選取&#x200B;**[!UICONTROL 上傳Assets]**。

   ![upload-assets.png](images/upload-assets.png)

1. 選取您要上傳至資料夾的檔案，然後選取&#x200B;**上傳**。

DITA檔案會開啟，您應該檢閱它們是否有遺失內容、conref或交叉參照的問題。

## 建立地圖

1. 選取主資料夾中的省略符號圖示，開啟「選項」功能表。

   ![省略符號–9.png](images/ellipses-9.png)

1. 選取&#x200B;**建立>對應**。

   ![create-map.png](images/create-map.png)

   「建立新對應」對話方塊隨即顯示。

1. 在[範本]欄位中，從下拉式功能表選取&#x200B;**Bookmap** （或根據您正在建立的內容型別選取&#x200B;**Map**），並為您的地圖指定標題。

1. 選取「**建立**」。

您的地圖隨即建立，且左側邊欄會自動從「存放庫」檢視變更為「地圖」檢視。

## 插入地圖元件

1. 在左側邊欄中選取鉛筆圖示。
這是編輯圖示，可讓您在編輯器中開啟對應。

   ![edit-map.png](images/edit-map.png)

1. 選取存放庫圖示，切換回「存放庫」檢視。

   ![repository-button.png](images/repository-button.png)

1. 將主題從存放庫拖放到編輯器的對映中，以新增主題。
行指示器會顯示主題將放置的位置。

1. 視需要繼續新增主題。

1. 完成時，請選取&#x200B;**另存為新版本。**

   ![save-as-new-version.png](images/save-as-new-version.png)

1. 在新版本&#x200B;*的*&#x200B;註解欄位中，輸入描述性註解。

1. 選取「**儲存**」。

## 產生AEM網站輸出

1. 在存放庫中，選取地圖上的省略符號圖示以開啟[選項]功能表，然後&#x200B;**開啟[地圖儀表板]。**

   ![open-map-dashboard.png](images/open-map-dashboard.png)

   「對映圖示板」會在另一個標籤中開啟。
1. 在[輸出預設集]索引標籤中，選取&#x200B;**AEM Site**。

   ![aem-site-checkbox](images/aem-site-checkbox.png)

1. 選取&#x200B;**產生**。

1. 導覽至「輸出」頁面，檢視所產生的輸出狀態。
如果發生錯誤，「輸出」標籤可能會在「產生設定」欄下顯示橘色圓圈，而非綠色，表示產生已完成。

1. 選取「產生設定」欄下的連結，開啟產生的輸出。
檢閱您的輸出是否有缺少的內容。

## 「報表」標籤

「報表」標籤會顯示主題摘要，以及包含主題資訊和地圖中問題的表格。

理想情況下，您一律在匯入內容後檢查報表中的對應。

![reports.png](images/reports.png)

「缺少的元素」欄指出缺少的影像和損壞的conref數目。 您可以選取&#x200B;**鉛筆**&#x200B;圖示以在編輯器中開啟主題。

## 解析缺少的影像

如果檔案中缺少影像，常見原因可能是內容已上傳，但影像尚未上傳。 如果是這樣的話，請將影像上傳至符合檔案預期路徑和檔案名稱的特定資料夾，以解決遺失的影像問題。

1. 在&#x200B;*存放庫檢視*&#x200B;中，選取影像資料夾上的省略符號圖示以開啟[選項]功能表。

   ![image-ellipsis.png](images/image-ellipsis.png)

1. 選取&#x200B;**[!UICONTROL 上傳Assets]**，然後選取遺失的影像。

1. 選取&#x200B;**上傳**。

已上傳遺失的影像。 現在，新產生的AEM Site輸出將顯示這些影像，而「報表」索引標籤將不再顯示任何遺失的影像錯誤。

## 解決中斷的conref

如果在其他位置參照的內容(conref)連結至另一個資料夾中的檔案（例如，名為「reuse」的檔案）， 且內容未上傳，錯誤必須解決。 例如，您必須建立名為「reuse」的子資料夾，並將遺失的檔案上傳到「reuse」中。

### 使用[!UICONTROL Assets] UI上傳資產

除了[!UICONTROL 上傳Assets]選項以外，您也可以拖放至Assets UI中來上傳資產。

1. 在「存放庫檢視」中，選取重複使用資料夾上的省略符號圖示，以開啟「選項」功能表。

   ![重複使用省略符號.png](images/reuse-ellipsis.png)

1. 選取Assets UI中的&#x200B;**檢視**。

   ![assets_ui.png](images/assets_ui.png)

1. 將檔案拖放至資料夾。
檔案已上傳，並解決conref錯誤。

所有錯誤現已解決。 「報表」頁面會指出沒有其他錯誤，產生AEM Site會產生完整的輸出，而不會遺失元件。
