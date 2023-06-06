---
title: 設定Regx為有效的檔案名稱字元
description: 瞭解如何為有效的檔案名稱字元設定Regx
source-git-commit: 801c306fa120e7889d4b9428fd5bee2849bf1956
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# 設定Regx為有效的檔案名稱字元 {#id214BD0550E8}

從AEM Guides 3.8版開始，管理員可以定義檔案名稱允許的有效特殊字元清單。 在舊版中，使用者可定義包含特殊字元的檔案名稱，例如 `@`， `$`， `>`、等等。 這些特殊字元在從DITA Map儀表板開啟主題或按一下目錄中的主題連結時會導致問題，這通常會導致頁面由於URL中的特殊字元而無法開啟。

使用可讓您定義有效檔案名稱字元的regx的設定，您可以完全控制檔案在系統中如何命名。 您可以定義檔案名稱中允許的特殊字元清單。 依預設，有效的檔案名稱設定包含&quot;`a-z A-Z 0-9 - _`「。 建立新檔案時，檔案標題中可以有任何特殊字元，但內部會以「`-`」的檔案名稱。 例如，檔案標題可以是「Introduction 1」或「Introduction@1」，針對這兩種情況產生的對應檔案名稱將是「Introduction-1」。

定義有效字元清單時，請記住這些字元»`*/:[\]|#%{}?&<>"/+`「 」將一律取代為「 」`-`「。

如果您未設定有效的特殊字元清單，檔案建立程式可能會為您帶來一些未預期的結果。 若要避免這類錯誤，強烈建議您在組建版本升級至3.8版後，立即變更此設定。

若要在檔案名稱中設定regx為有效的\（或允許的\）字元，請執行以下步驟：

1. 開啟Adobe Experience Manager Web主控台設定頁面。

   存取設定頁面的預設URL為：

   ```http
   http://<server name>:<port>/system/console/configMgr
   ```

1. 搜尋並按一下 *com.adobe.fmdita.config.ConfigManager* 套件組合。

1. 在 **有效字元的Regex** 屬性，確認屬性已設為\[-a-zA-Z0-9\_\]。 您可以新增更多字元至此清單，但清單必須包含這些基本字元，且清單的開頭必須為連字型大小「 — 」。

   >[!NOTE]
   >
   > 此屬性僅適用於檔案名稱，不適用於資料夾名稱。

1. 按一下「**儲存**」。


>[!NOTE]
>
> 與有效檔案名稱字元清單類似，您也可以為AEM Site輸出指定有效檔案名稱字元清單。 如需詳細資訊，請參閱 [設定AEM網站輸出的有效檔案名稱](conf-file-names-valid-regx-aem-site-output.md#).

**父級主題：**[&#x200B;設定檔案名稱](conf-file-names.md)
