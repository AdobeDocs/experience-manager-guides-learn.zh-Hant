---
title: 條件
description: 使用AEM Guid中的條件
exl-id: 2cb670d9-1a22-47c6-8409-52d1d526010a
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '497'
ht-degree: 1%

---

# 條件

在DITA中，條件通常透過「產品」、「平台」和「對象」等屬性驅動。 這些檔案也可以指派特定的值。 使用者可以透過資料夾設定檔控制所有這些內容。

您可選擇用於本課程的範例檔案會提供在[conditions.zip](assets/conditions.zip)檔案中。

>[!VIDEO](https://video.tv.adobe.com/v/342755?quality=12&learn=on)

## 將條件指派給資料夾設定檔

1. 選取&#x200B;**資料夾設定檔**&#x200B;拼貼。

1. 按一下&#x200B;[!UICONTROL **條件屬性**]。

1. 按一下設定檔左上角的&#x200B;[!UICONTROL **編輯**]。

1. 按一下&#x200B;[!UICONTROL **新增**]。

   資料夾設定檔中的![條件](images/lesson-13/add-name.png)

1. 填寫必填欄位。

   - Name應該對應到用來進行效能分析的屬性。

   - 值是將用於DITA程式碼來源的確切專案。

   - 「標籤」是輸入屬性的使用者將會看到的單字。

1. 按一下「[!UICONTROL **儲存**]」。

>[!NOTE]
>
>注意：設定全域設定檔可能是控制使用屬性和值來遵循一致樣式指南的早期且有效率的方式。

## 將屬性指派給元素

如果未將任何自訂資料夾設定檔指派給概念，您可能想要將屬性指派給特定元素，例如段落。

1. 從&#x200B;**存放庫檢視**，按一下您要使用的元素以選取它。

1. 在&#x200B;**Content Properties**&#x200B;面板中，按一下&#x200B;[!UICONTROL **Attribute**]&#x200B;下拉式清單。

1. 選擇您要指派的屬性。

1. 新增&#x200B;**值**。

屬性和值配對現在已指派給所選元素。

## 使用條件指派屬性和值配對

「條件」面板允許對屬性和值配對進行控制的指派。

1. 修改&#x200B;**使用者偏好設定**。

   a.按一下「使用者偏好設定」圖示。

   ![使用者偏好設定圖示](images/lesson-13/user-prefs-icon.png)

   b.完成&#x200B;**使用者偏好設定**&#x200B;對話方塊中的必要欄位。 例如：

   ![使用者喜好設定](images/lesson-13/user-preferences.png)

   c.按一下&#x200B;[!UICONTROL **儲存**]。

1. 從「條件」面板，展開「對象」和「平台」的下拉式清單。 請注意，可用的條件是「資料夾設定檔」特定的。

1. 將條件拖放至所需的元素以進行指派。

## 指派主旨配置

主旨配置對映是一種專門的ditamap形式，由對映參照。 主體配置用於定義分類。 它們提供可用值的控制權。

1. 瀏覽至&#x200B;**存放庫檢視**。

1. 選取參照「主旨配置」ditamap的對應。 這個範例使用名為&#x200B;_設計與配置_&#x200B;的對應。

   ![使用者喜好設定](images/lesson-13/subject-scheme-map.png)

1. 設定使用者偏好設定。

   a.按一下&#x200B;[!UICONTROL **使用者偏好設定**]&#x200B;圖示。

   ![使用者喜好設定](images/lesson-13/user-prefs-icon-2.png)

   b.在&#x200B;**使用者偏好設定**&#x200B;對話方塊中填入欄位。

   c.按一下「基本路徑」欄位旁的資料夾符號，選擇所需檔案的路徑。

   d.按一下&#x200B;[!UICONTROL **選取**]。

   e.按一下&#x200B;**根對應**&#x200B;欄位旁的索引鍵符號，以輸入路徑。

   >[!IMPORTANT]
   >
   >重要：選取的根對映必須是包含主旨配置的對映。

   ![使用者喜好設定](images/lesson-13/user-preferences-2.png)

   f.選取您要使用的資料夾，以限制顯示的資產。

   g.按一下&#x200B;[!UICONTROL **選取**]。

   h.按一下&#x200B;[!UICONTROL **儲存**]。

主旨配置現已指派。

## 從條件面板檢視主旨配置

1. 瀏覽至&#x200B;**編輯器設定**。

1. 選取&#x200B;**條件**&#x200B;標籤。

1. 核取方塊&#x200B;**在條件面板中顯示主旨配置**
