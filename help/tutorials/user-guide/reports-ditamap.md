---
title: 從映射儀表板建立DITA映射報告
description: 了解如何從對應控制面板將DITA對應報表
source-git-commit: 8a104cfe17778a71915e3700f49fc6892493ccd0
workflow-type: tm+mt
source-wordcount: '730'
ht-degree: 0%

---


# 從映射儀表板建立DITA映射報告 {#id205BB800EEN}

AEM指南可讓管理員在檔案上線或提供給使用者之前，檢查檔案的整體完整性。 來自AEM參考線中地圖控制面板的DITA地圖報表提供重要資訊，例如遺失主題、元素遺失的主題、參考主題和媒體檔案的UUID，以及每個主題的檢閱狀態。 詳細的個別主題層級報表也提供DITA內容相關資訊，例如內容參考和遺失影像或交叉參考。

>[!NOTE]
>
> AEM參考線會針對導致映射檔案變更的每個事件，或更新主題檔案中的任何參考時，重新整理此報告。

執行下列步驟來檢視DITA對應報表：

1. 在資產UI中，導覽至，然後按一下您要檢視其報表的DITA對應檔案。

1. 按一下 **報表**.

   ![](images/reports-page-uuid.png)

   「報表」頁面分為兩部分：

   - **主題摘要：**

      列出所選映射檔案的總體摘要。 查看「摘要」，您可以快速了解地圖中的主題總數、缺少的主題、缺少元素的主題數、主題的狀態（草稿、審閱或已審閱狀態）。

   - **詳細資料:**

      按一下主題時，將顯示所選主題的詳細報告。

      ![](images/detailed-report-uuid.png)

      在下面突出顯示的項目 **A**, **B**, **C** 和 **D** 如下所述：

      - **主題**:DITA映射中指定的主題的標題。 將滑鼠指針懸停在主題的標題上會顯示主題的完整路徑。 如果主題中有問題，例如遺失參照或影像，則在主題標題前會顯示一個紅點。

      - **檔案名**:檔案名稱。

      - **UUID**:檔案的通用唯一識別碼\(UUID\)。

      - **作者**:上次處理此主題的用戶。

      - **檔案狀態**:文檔的當前狀態 — 草稿、正在審查或已審查。

      - **缺少主題\(B\)**:如果有參考中斷的主題，則這些主題會列在「缺少主題」清單下。

      - **缺少元素**:列出遺失影像或損壞的交叉引用（如果有）的數量。

      - **在編輯器\(D\)中開啟**:按一下此表徵圖將開啟Web編輯器中的主題。

   在下面突出顯示的項目 **E** 如下所述：

   - **多媒體**:主題中使用的影像路徑及其UUID會一併顯示。 如果按一下影像路徑，則會在快顯視窗中開啟對應的影像。 中斷的影像連結會以紅色列出。

   - **內容參考**:主題中參考的內容路徑及其UUID會顯示。 如果按一下參考內容的標題，則會以「預覽」模式開啟對應的主題。

   - **交叉參考**:交叉引用內容的路徑及其UUID顯示。 如果按一下參考內容的標題，則會以「預覽」模式開啟對應的主題。 中斷的交叉引用以紅色列出。

   - **檢閱**:顯示主題的審閱任務的狀態。 您可以查看所審查主題的狀態\（開啟或關閉\）、到期日和受託人。 如果按一下主題連結，它將以審閱模式開啟主題。

   - **用於**:顯示使用該主題的其他主題或映射的清單。 也會列出所有此類主題和地圖的UUID。



除了每個個別主題的報表外，管理員還可以存取資訊，例如發佈DITA映射的歷史記錄。 有關生成輸出歷史記錄的詳細資訊，請參見 [查看輸出生成任務的狀態](generate-output-for-a-dita-map.md#viewing_output_history).

## 產生DITA地圖報表的CSV

您可以下載並匯出DITA地圖報表的CSV。 CSV包含詳細的DITA對應報表。

執行下列步驟來產生DITA映射報表的CSV:

1. 按一下 **產生報表** ，以產生DITA對應報表。

   ![](images/generate-DITA-map-report.png)

1. 報表準備好下載後，您會收到通知。 按一下 **下載** 下載產生報表的CSV。

   ![](images/download-report-dialog.png)


   您也可以稍後從AEM通知收件匣下載產生報表的CSV。

   按一下收件匣中產生的報表，即可下載報表。

   ![](images/report-inbox--notification.png)

報表下載到「收件匣」後，您也可以選取報表，並使用頂端的「開啟」圖示來開啟選取的報表。

**上層主題：**[&#x200B;報表](reports-intro.md)
