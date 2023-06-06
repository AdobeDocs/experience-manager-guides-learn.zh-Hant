---
title: 首次下載並安裝AEM Guides
description: 首次瞭解如何下載和安裝AEM Guides
source-git-commit: 5ac066bb8db32944abd046f64da11eeb1bdbe467
workflow-type: tm+mt
source-wordcount: '235'
ht-degree: 2%

---


# 首次下載並安裝AEM Guides {#id213BCL00KEV}

第一次在電腦上下載和安裝AEM Guides時，請執行下列步驟：

>[!IMPORTANT]
>
> 如果您想要搭配AEM Guides使用Livefyre，請務必先安裝3.0之前的Livefyre版本，然後再安裝AEM Guides。 如果您使用Livefyre 3.0版或更新版本，則沒有此限制。

1. 從Adobe軟體發佈入口網站下載AEM Guides。

1. 登入您的AEM執行個體並導覽至CRX封裝管理員。 存取封裝管理器的預設URL為：

   ```http
   http://<server name>:<port>/crx/packmgr/index.jsp
   ```

   封裝管理員會管理本機AEM安裝上的封裝。 如需有關使用「封裝管理員」的詳細資訊，請參閱 [如何使用套件](https://helpx.adobe.com/tw/experience-manager/6-5/sites/administering/using/package-manager.html) 在AEM檔案中。

   ![](assets/package-manager.png){width="650" align="left"}

1. 若要上傳AEM Guides套件，請按一下 **上傳套裝**.

1. 在上傳套件對話方塊中，導覽至您在步驟1下載的AEM Guides檔案，然後按一下 **確定**.

   套件會上傳至您的AEM執行個體。

1. 若要安裝套件，請按一下 **安裝**.

   ![](assets/install-package.png){width="650" align="left"}

1. 在安裝套件對話方塊中，按一下 **安裝**.

1. 若要開始使用AEM Guides，請按一下「首頁」按鈕 ![](assets/home-button.png) （位於CRX封裝管理員的左上角）。


>[!NOTE]
>
> 在設定中的AEM伺服器所有執行個體上執行安裝程式。

**父級主題：**[&#x200B;下載並安裝](download-install.md)
