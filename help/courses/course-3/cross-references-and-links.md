---
title: 交叉引用和連結
description: 在AEM Guides中建立互動參照和連結
exl-id: bee7d50f-cbdd-4ac8-b15b-101febc4ae80
TQID: https://experienceleague.adobe.com/K55H51fnM7bsR68-HQWbNHrSxHgQBPkM-jnGG-OFIbw
product_v2: id: fae5e35a-80c9-4b94-9352-1a060a6aab1did: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2: id: f5c2a4bb-71ca-4d7e-8efd-442250e6ba48
source-git-commit: 27ffc636d63300fb2e99903d92cab12f0cfcbb25
workflow-type: tm+mt
source-wordcount: 362
ht-degree: 0%

---

# 交叉引用和連結

XML編輯器和DITA提供在主題之間連結的強大方式。 請務必有效管理您的內容參照，包括使用唯一的ID值。

檔案中提供您可選擇用於本課程的範例檔案
[crossreferencesandlinks.zip](assets/crossreferencesandlinks.zip)

>[!VIDEO](https://video.tv.adobe.com/v/342764?quality=12&learn=on)

## 建立外部主題的互動參照

將主題從存放庫拖放至開啟的檔案中，可以建立外部互動參照。 但是，為了避免中斷的互動參照，必須先將ID定義為與父元素相關的值。 這是建立互動參照的一種簡單方法，同時可確保正確指派ID。

1. 開啟要插入外部互動參照的檔案。

1. 將ID指派給要參考的元素。

   答： 在元素內按一下。

   b. 在「內容屬性」面板上，從「屬性」下拉式清單中選擇&#x200B;**ID**。

   c. 在「值」欄位中輸入邏輯名稱。

   d. 視需要在&#x200B;**大綱檢視**&#x200B;中檢視元素及其值。

1. **儲存**&#x200B;主題，以確儲存放庫具有更新的識別碼。

1. 按一下頂端工具列上的&#x200B;[!UICONTROL **Reference**]&#x200B;圖示。

   ![工具列](images/lesson-7/references-icon.png)

1. 從&#x200B;**內容參照**&#x200B;索引標籤中，選取要插入做為互動參照的ID和元素配對。

1. 按一下「[!UICONTROL **選取**]」。

交叉引用已新增至主題。

## 連結至網站

您可以在任何主題中插入網站的連結。 如需詳細資訊，請參閱連結至網站的AEM Guides課程1影片。


## 檢視中斷的連結

某些修改可能會導致交叉參照失效。 其中包括刪除主題、重新組織包含互動參照的截面，或在插入互動參照後變更ID。 請注意，本課程提供範例主題&#x200B;_crossreferencesandlinks.zip_，此主題將導致內部內容的多個專案符號互動參照中斷。

1. 導覽至左側面板上的&#x200B;**大綱檢視**。

1. 按一下&#x200B;[!UICONTROL **篩選器**]&#x200B;圖示。

1. 選取&#x200B;**中斷的連結**。

   ![篩選器下拉式清單](images/lesson-7/broken-links.png)

中斷的連結會顯示為可點按的物件。 您可以在主題中以紅色文字識別它們。
