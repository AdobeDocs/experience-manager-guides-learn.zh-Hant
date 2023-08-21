---
title: 原生PDF |支援語言變數
description: 在PDF輸出和輸出範本中使用語言變數
source-git-commit: 3e922ef7ed9af200aa8fcfb0cbe4489cf059e335
workflow-type: tm+mt
source-wordcount: '1221'
ht-degree: 0%

---


# 支援語言變數

AEM Guides提供使用語言變數的功能。 您可以使用語言變數來定義PDF輸出中的本地化字串，或將輸出範本中的任何靜態文字本地化。 您可以使用CSS樣式將來自CSS的字串當地語系化。

## 在PDF輸出中使用語言變數

您可以使用語言變數來定義PDF輸出中現成可用標籤（例如「注意」、「警告」和「警告」或靜態文字）的當地語系化版本。 所有語言的變數名稱都相同，但各種語言的值可能不同。 您可以更新一或多種語言中這些變數的值，然後本地化值會自動在PDF輸出中選取。

例如，您可以透過下列方式呈現標籤 `Note` 在PDF輸出中：

- 英文：注意

- 法文：Remarque

- 德文：欣威文

<img src="./assets/language-variable-output.png" width="550">

>[!NOTE]
>
> 如果任何變數的值未以特定語言定義，則AEM Guides會從UI （應用程式的使用者介面）的語言中挑選字串作為遞補機制。
>
> 如果您尚未以UI的語言定義值，則會尋找英文(`en_us`)，否則會挑選英文(`en`)值，並在PDF輸出中顯示相同的值。

### 語言變數的型別

AEM Guides支援兩種變數型別：應用程式和使用者變數。

#### 應用程式變數

AEM Guides提供一組預先定義或現成可用的應用程式變數。 您可以使用這些預先定義的變數來新增AEM Guides專屬檔案的相關資訊。 例如， `chapter-number` 變數（若包含在頁面中）會顯示頁面所屬的章節編號。 此 `author-label` 變數會顯示檔案作者的名稱。

>[!NOTE]
>
> 您可以覆寫應用程式變數的值。


#### 使用者變數

您也可以建立新的語言變數。 例如，您可以為檔案的發行者標籤建立使用者變數Publisher。

>[!NOTE]
>
>  您應具有管理許可權，可建立使用者變數和編輯應用程式變數。

<img src="./assets/add-language-variables.png" width="550">

### 新增語言變數

1. 在網頁編輯器中，前往輸出標籤。
1. 選取 **語言變數** <img src="./assets/language-variables.svg" width="25"> 在左側面板中。
1. 選取 **編輯** 以開啟 **語言變數** 視窗。 以選取的語言呈現的應用程式和使用者變數會依字母順序列出。 值會根據選取的語言顯示。 例如，如果您選取法文，則「提示」會顯示為「Conseil」。
1. 從 **語言** 在下拉式清單中，選取您要編輯變數的語言。

   >[!NOTE]
   >
   > 如果您沒有檢視所需的語言，請從以下連結啟用所需的語言： **語言變數設定**. 選取設定 <img src="./assets/settings-icon.svg" width="25">  以開啟 **語言變數設定** 對話方塊。

1. 在中輸入變數名稱 **名稱** 欄及其值於 **值** 欄。

   >[!NOTE]
   >
   >您可以使用任何HTML內容作為變數值，以特定格式顯示變數值。 例如，您可以新增 `<b>` 標籤變數值來以粗體顯示Publisher。

1. 選取 **新增語言變數** <img src="./assets/add-language-variable.svg" width="25"> 將新的語言變數新增至選取的語言。 將變數新增至一種語言會自動將其新增至所有語言。 您無法建立與現有變數同名的變數。 顯示錯誤。

>[!NOTE]
>
> 如果您未選取 **新增語言變數**，變數不會建立並新增至清單中

### 語言變數的選項

將滑鼠指標暫留在變數上以檢視 **選項** 功能表。

<img width="550" src="./assets/language-variable-user-options.png">

您可以預覽應用程式和使用者變數。 若要檢視變數值在輸出中的顯示方式，請選取 **預覽** 從 **選項** 功能表。
您也可以選擇 **刪除** 或 **複製** 使用者變數。 從一種語言刪除變數會自動從所有語言刪除它。

### 編輯或還原應用程式變數

您也可以編輯應用程式變數的值。 稍後，您可以將應用程式變數回覆成原始值。 **回覆變數** <img src="./assets/application-variable-revert.svg" width="25">  會針對值已變更的應用程式變數顯示。

## 在輸出範本中使用語言變數

您應在當地語系化的檔案中新增語言變數。 您可以在本地化檔案中跨不同頁面顯示的頁面版面中插入這些語言變數。 例如，您可以新增語言變數用於 `author-name` 出現在頁面配置的頁首區域（或任何其他部分，如頁尾或內文）中。

<img src="./assets/language-variable-page-layout.png" width="550">

下列熒幕擷圖顯示針對法文產生之PDF輸出中的作者和品牌名稱當地語系化。


若要插入語言變數，例如 `copyright-label` 在標題區域中，執行下列步驟：

1. 開啟所需的頁面版面以進行編輯。

   >[!NOTE]
   >
   > 檢視 [自訂頁面配置](../native-pdf/components-pdf-template.md#customize-a-page-layout-customize-page-layout) 區段，用於開啟頁面版面以進行自訂或編輯。

1. 選取標頭，將其設為使用中以插入變數。
1. 選取 **插入變數**  <img src="./assets/insert-language-variable.svg" width="25"> （在工具列中）。
1. 在 **插入變數** 快顯視窗，選取要插入的語言變數名稱，然後按一下 **插入** 將其插入頁首區域。

   >[!NOTE]
   >
   > 您也可以在文字方塊中輸入搜尋字串。 包含指定字串的變數名稱會經過篩選，並顯示在清單中。
   > 選取的語言變數會插入頁首區域中。

下列熒幕擷圖顯示 `copyright-label` 在標題區域中新增。

<img src="./assets/language-variable-header.png" width="550">

### 將內容樣式套用至語言變數

除了您指派給語言變數的值之外，您也可以使用HTML標籤，以特定格式顯示變數值。 例如，您可以顯示 `publisher-label` 以粗體顯示。

- 您也可以使用下列專案來格式化值的樣式： <span> 標籤之間。 例如，使用頁碼語言變數，您可以用英文羅馬數字格式顯示頁碼，並指定其他語言的格式。

  英文的值：
  `<span data-field="page-number" data-format="upper-roman">1</span>`

  泰米爾文的值：
  `<span data-field="page-number" data-format="tamil">1</span>`

同樣地，您可以新增語言變數，並格式化列在頁面配置圖的「插入欄位」功能中的其他欄位。 如需新增欄位的詳細資訊，請檢視 [新增欄位和中繼資料](../native-pdf/design-page-layout.md#add-fields-metadata).

- 您也可以在值中新增本地化的影像。 例如，您可以使用章節編號語言新增影像圖示，並在PDF輸出中取得圖示的本地化影像。

  如果是英文，影像的變數值可能如下 `<img src="banner-en.jpg">`，而且對於德文中的相同變數，它可以 `<img src="banner-de.jpg">`. 因此，它會根據語言挑選影像。

## 使用CSS樣式將字串當地語系化

使用CSS樣式，您也可以本地化Autonumber中使用的字串，例如Chapter、Section、Figure和Table。 由於這些字串來自CSS檔案，因此您無法使用語言變數將其當地語系化。 若要將這些字串當地語系化，您可以針對您想要將其當地語系化的每種語言建立CSS樣式。
例如，您可以使用以下CSS以各種語言顯示章節首碼和對應的數字格式。
例如，您可以使用以下CSS將章節顯示為德文的Hoofdstuk，將章節編號顯示為十進位格式。 如果是日文，您可以使用日文數字格式，在目錄中顯示章節編號。

```
// for English
h1:before {
  counter-increment: h11;
  content: "Chapter " counter(h11, decimal)".";
}

// for German
:root:lang(de) h1:before {
  content: "Hoofdstuk " counter(h11, decimal)".";
}

// for Japanese
:root:lang(ja) h1:before {
  content: "章 " counter(h11, japanese-formal)".";
}
```

下列熒幕擷取畫面顯示德文和日文PDF輸出的本地化字串。

<img src="./assets/localize-chapter-german.png" width="550">

<img src="./assets/localize-chapter-japanese.png" width="550">

### 格式化字首

您可以使用CSS樣式來格式化字首。 例如，您可以格式化標籤 `Note` 以紅色顯示在各種語言的PDF輸出中。

```
.note .prefix-content 
{
color: red;
} 
```


