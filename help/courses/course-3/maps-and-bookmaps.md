---
title: 地圖和書籤
description: 在AEM Guides中建立和編輯地圖和書籤
exl-id: 9c717e4b-017b-4f2b-b93e-f2c0e7525c55
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '465'
ht-degree: 1%

---

# 地圖和書圖

Adobe Experience Manager Guides的「地圖編輯器」可讓您建立和編輯地圖檔案。 使用「對映編輯器」，您可以編輯兩種型別的檔案 — DITA map和bookmap。 在我們的目的中，將這些概念視為大致上可互換的概念。
地圖編輯器有兩種模式 — 「基本地圖編輯器」和「進階地圖編輯器」。

>[!VIDEO](https://video.tv.adobe.com/v/342766?quality=12&learn=on)

## 建立地圖

AEM Guides提供兩個現成可用的地圖範本 — DITA map和bookmap。 您也可以建立自己的地圖範本，並與作者共用這些範本，以建立地圖檔案。

執行以下步驟來建立對應檔案。

1. 在Assets UI中，導覽至您要建立地圖檔案的位置。

1. 按一下&#x200B;[!UICONTROL **建立> DITA Map**]。

1. 在Blueprint頁面上，選取您要使用的對應範本型別，然後按一下[下一步][!UICONTROL **&#x200B;**]。

1. 在[內容]頁面上，輸入地圖的&#x200B;**標題**&#x200B;和&#x200B;**名稱**。

1. 按一下&#x200B;[!UICONTROL **建立**]。

## 使用進階地圖編輯器開啟地圖

1. 在&#x200B;**Assets UI**&#x200B;中，選取要編輯的地圖。

1. 按一下&#x200B;[!UICONTROL **編輯主題**]。

   ![編輯主題UI](images/lesson-14/edit-topics.png)

或

1. 將滑鼠停留在地圖圖示上。

1. 從&#x200B;**動作**&#x200B;功能表選取&#x200B;**編輯主題**。


## 將內容新增至地圖或書籤

1. 瀏覽至&#x200B;**存放庫檢視**。

1. 從存放庫檢視拖放內容至地圖或書籤地圖中的有效位置。

或

1. 按一下地圖或書籤地圖內的有效位置。

1. 按一下適當的&#x200B;[!UICONTROL **工具列圖示**]&#x200B;以新增章節、主題或主題參照。

   ![工具列圖示](images/lesson-14/toolbar-icons.png)

1. 選擇一或多個要新增的Assets。

1. 按一下&#x200B;[!UICONTROL **選取**]。

### 提升或降低地圖中的元素

使用&#x200B;**工具列箭頭**&#x200B;來提升或降低地圖或書籤地圖中的章節和主題參照。

1. 在地圖中選取元素。

1. 按一下&#x200B;[!UICONTROL **向左箭號**]&#x200B;將topicref升級為章節，或按一下&#x200B;[!UICONTROL **向右箭號**]&#x200B;將章節降級為topicref。

   ![箭頭圖示](images/lesson-14/toolbar-arrows.png)

1. 視需要儲存地圖並進行版本設定。

或

1. 拖放元素以將其重新組織。

## 將中繼資料新增至地圖

1. 從&#x200B;**地圖工具列**，插入主題群組。

   ![新增屬性](images/lesson-14/add-topicgroup.png)

1. 按一下&#x200B;[!UICONTROL **加號圖示**]&#x200B;以插入元素。

1. 選擇要插入的元素。

   ![插入中繼資料](images/lesson-14/insert-metadata.png)

1. 按一下&#x200B;[!UICONTROL **關閉**]。

## 將表格新增至地圖

可以在結構對應之後新增表格。

1. 在地圖中按一下要插入表格的位置。

1. 使用&#x200B;**工具列圖示**&#x200B;將關聯式加入對映。

   ![可讀圖示](images/lesson-14/reltable-icon.png)

1. 設定對話方塊。

1. 按一下&#x200B;[!UICONTROL **插入**]。

1. 將必要主題從&#x200B;**存放庫**&#x200B;拖放至關聯式中。

1. 使用標準鍵盤快速鍵，將地圖中所需的元素複製並貼上到可關聯元素中。

## 將屬性指派給地圖中的主題參照

1. 在地圖中反白顯示topicref或巢狀的topicref集合。

1. 在「內容屬性」面板的「其他屬性」下，選擇&#x200B;**屬性**&#x200B;及其&#x200B;**值。**

   ![新增屬性](images/lesson-14/add-attribute.png)
