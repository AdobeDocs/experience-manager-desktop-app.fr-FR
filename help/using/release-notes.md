---
title: « Notes de mise à jour de l’application de bureau [!DNL Adobe Experience Manager] »
description: Détails des mises à jour, améliorations, nouvelles fonctionnalités, compatibilité et liens de téléchargement pour l’application de bureau  [!DNL Adobe Experience Manager] .
mini-toc-levels: 1
feature: Desktop App,Release Information
exl-id: e058e7a2-fcc8-4ad1-899e-20695db6bc72
source-git-commit: 5676e7ece8bb43f051dae72d17e15ab1c34caefc
workflow-type: tm+mt
source-wordcount: '1806'
ht-degree: 70%

---

# Notes de mise à jour de l’appli de bureau [!DNL Adobe Experience Manager] {#release-notes-v2}

Les informations de mise à jour de la dernière version de l’application de bureau 2.3.0 sont les suivantes. La date de publication est le 14 juillet 2023.

La dernière version de l’application de bureau contient les améliorations et correctifs suivants :

* Ajout de la prise en charge de la connexion IMS. L’intégration IMS permet à l’appli de bureau d’effectuer automatiquement une actualisation du jeton d’accès, ce qui permet à l’utilisateur de rester connecté pendant 14 jours au maximum.

* Amélioration de la prise en charge des proxies d’entreprise et du filtrage web.


Les **versions de [!DNL Experience Manager] prises en charge** sont les suivantes :

* [!DNL Experience Manager] as a [!DNL Cloud Service]. Voir les [notes de mise à jour](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/release-notes/home).
* [!DNL Experience Manager] 6.5.0 ou version ultérieure, sur Adobe Managed Services (AMS) ou On-Premise. Consultez les [notes de mise à jour du Service Pack](https://experienceleague.adobe.com/fr/docs/experience-manager-65/content/release-notes/release-notes).

L’appli de bureau [!DNL Adobe Experience Manager] est disponible avec les **systèmes d’exploitation** suivants :

* macOS X 10.14 ou version ultérieure, avec les correctifs de bogues les plus récents.
* Windows 10 avec les derniers Service Packs et correctifs.

Les **URL de téléchargement** pour les systèmes d’exploitation pris en charge sont les suivantes :

| Système d’exploitation | [!DNL Experience Manager] as a [!DNL Cloud Service] | [!DNL Experience Manager] 6.x |
|---|---|---|
| macOS (v2.3.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-x64-2.3.0.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-x64-2.3.0.dmg) |
| macOS avec puce Apple (M1) (v2.3.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-arm64-2.3.0.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-arm64-2.3.0.dmg) |
| Windows 64 bits (v2.3.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win-x64-2.3.0.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win-x64-2.3.0.exe) |
| macOS (v2.2.2) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-x64-2.2.2.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-x64-2.2.2.dmg) |
| macOS avec puce Apple (M1) (v2.2.2) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-arm64-2.2.2.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-arm64-2.2.2.dmg) |
| Windows 64 bits (v2.2.2) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win-x64-2.2.2.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win-x64-2.2.2.exe) |
| macOS (v2.2.1) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-x64-2.2.1.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-x64-2.2.1.dmg) |
| macOS avec puce Apple (M1) (v2.2.1) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-arm64-2.2.1.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-arm64-2.2.1.dmg) |
| Windows 64 bits (v2.2.1) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win-x64-2.2.1.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win-x64-2.2.1.exe) |
| macOS (v2.2.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-x64-2.2.0.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-x64-2.2.0.dmg) |
| macOS avec puce Apple (M1) (v2.2.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-arm64-2.2.0.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-arm64-2.2.0.dmg) |
| Windows 64 bits (v2.2.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win-x64-2.2.0.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win-x64-2.2.0.exe) |
| macOS (v2.1.5.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-2.1.5.0.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-2.1.5.0.dmg) |
| Windows 64 bits (v2.1.5.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win64-2.1.5.0.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win64-2.1.5.0.exe) |
| Windows 32 bits (v2.1.5.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win32-2.1.5.0.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win32-2.1.5.0.exe) |
| macOS (v2.1.4.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-2.1.4.0.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-2.1.4.0.dmg) |
| Windows 64 bits (v2.1.4.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win64-2.1.4.0.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win64-2.1.4.0.exe) |
| Windows 32 bits (v2.1.4.0) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win32-2.1.4.0.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win32-2.1.4.0.exe) |
| macOS (v2.1.3.4) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-osx-2.1.3.4.dmg) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-2.1.3.4.dmg) |
| Windows 64 bits (v2.1.3.4) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win64-2.1.3.4.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win64-2.1.3.4.exe) |
| Windows 32 bits (v2.1.3.1) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html?package=/content/software-distribution/en/details.html/content/dam/aemcloud/public/aem-desktop-app/aem-desktop-win32-2.1.3.1.exe) | [Lien de téléchargement](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win32-2.1.3.1.exe) |

## Prise en charge de différents types de ressources et de fichiers {#support-for-file-types}

L’application prend en charge les ressources stockées dans [!DNL Experience Manager] qui représentent un fichier binaire pour ses opérations de base. L’ouverture de fichiers dans l’application de bureau native dépend de l’association du système d’exploitation des types de fichiers spécifiques (par exemple, PNG ou JPG) à des applications spécifiques (par exemple, Mac Preview ou Adobe Photoshop).

Certains types de fichiers prennent en charge le placement de ressources liées dans le fichier binaire. L’application pré-télécharge les ressources liées si la ressource est présente dans le référentiel [!DNL Experience Manager] lorsque ces fichiers binaires sont ouverts à l’aide de l’appli de bureau. Les types de fichiers actuellement pris en charge sont les suivants :

* Fichiers [!DNL Adobe InDesign] (format INDD)
* Fichiers [!DNL Adobe Illustrator] (format AI)
* Fichiers [!DNL Adobe Photoshop] (format PS)

Cette fonctionnalité est prise en charge avec les versions 2018 d’[!DNL Adobe Creative Cloud] et 2019 d’[!DNL Adobe Creative Cloud] de l’application ci-dessus. L’application utilise une approche heuristique et de la meilleure correspondance pour mapper les chemins d’accès de bureau locaux des ressources liées aux URL sur le serveur [!DNL Experience Manager]. Elle se base sur quelques hypothèses :

* Les chemins d’accès aux fichiers placés dans l’application native utilisent un chemin d’accès de bureau global (placé à partir du partage réseau local affiché avec l’ [!UICONTROL Reveal] ).

* Les chemins d’accès sont stockés dans l’enregistrement XMP du fichier par l’application native.

* [!DNL Experience Manager] a extrait l’enregistrement XMP avec les chemins d’accès dans l’enregistrement de métadonnées de la ressource.

* Les chemins d’accès peuvent être associés aux ressources dans [!DNL Experience Manager]. En d’autres termes, les fichiers placés se trouvent également dans [!DNL Experience Manager] sous un chemin d’accès correspondant.

## Nouvelles fonctionnalités, améliorations et corrections de bogues {#what-is-new}

Pour en savoir plus, voir [Nouveautés de la version v2.0](introduction.md#whats-new-v2).

**Mises à jour dans la version v2.2.2 de l’application**

* (Windows uniquement) L’appli de bureau affiche un écran vide après l’installation des versions 2.2.0 et 2.2.1.

**Mises à jour dans la version v2.2.1 de l’application**

* L’appli de bureau affiche un message d’erreur de délai d’expiration de session lorsque vous cliquez sur **[!UICONTROL Sign In]**.

* Problèmes lors de l’accès à l’application de bureau v2.2.0 sur macOS.

* L’appli de bureau affiche un message d’erreur lorsque vous triez des ressources en cliquant sur **[!UICONTROL Edited Locally]**.

**Mises à jour dans la version v2.2.0 de l’application**

* Prise en charge de la puce Apple (M1).

* Possibilité de mémoriser la chaîne de connexion lors de la connexion à l’application de bureau.

**Mises à jour dans la version v2.1.5.0 de l’application**

* L’application de bureau ne répond plus lorsque vous téléchargez des fichiers dans un dossier contenant des caractères chinois (ASSETS-9237).

* L’application de bureau remplace les points par des tirets dans les noms de fichier (ASSETS-10955).

**Mises à jour dans la version v2.1.4.0 de l’application**

La nouvelle version de l’application inclut des correctifs de bugs.

**Mises à jour dans la version v2.1.3.4 de l’application**

La nouvelle version de l’application inclut un correctif de bogue.

**Mises à jour dans la version v2.1.3.3 de l’application**

La nouvelle version de l’application inclut un correctif de bogue.

**Mises à jour dans la version v2.1.3.2 de l’application**

Cette version de l’application inclut un correctif de bogue.

**Mises à jour dans la version v2.1.3.1 de l’application**

Le bogue corrigé dans cette version est le suivant :

* Les vitesses de chargement et de téléchargement des ressources ont été améliorées, même pour les ressources volumineuses. Cette version corrige un problème en raison duquel les chargements de ressources avec la variable [!DNL desktop app] échouait parfois lorsque des fichiers très volumineux étaient chargés.

**Mise à jour dans la version v2.1.2.0 de l’application**

* Une nouvelle option pour [!UICONTROL Clear Cookies] est ajoutée au menu principal de l’application. Cela permet de résoudre des problèmes de connexion potentiels, par exemple lorsque vous changez une connexion d’un serveur à un autre. Voir la section [Effacer les cookies avant de se connecter](/help/using/troubleshoot.md#cannot-login-cookies-issue).

* Une nouvelle option a été ajoutée qui, si elle est sélectionnée, permet à l’application de charger des dossiers et des fichiers avec des noms de noeud dans [!DNL Adobe Experience Manager] correspondant aux noms de fichiers et de dossiers locaux. Ce processus assure la cohérence entre les noms locaux et téléchargés.

  Ce comportement est similaire au comportement par défaut dans la version 1 de l’appli de bureau. En revanche, dans la version actuelle, si l’option n’est pas activée, les espaces et les caractères `% ; # , + ? ^ { } "` dans les noms de dossier sont remplacés par des tirets dans les chemins d’accès aux dossiers. En outre, les caractères majuscules sont convertis en minuscules dans les chemins d’accès aux dossiers. Toutefois, dans les noms de fichier, les caractères `# % { } ? &` sont remplacés par un tiret ; les espaces et la casse sont conservés. Pour plus d’informations, consultez les [Préférences de l’application](/help/using/install-upgrade.md#set-preferences) et [Chargement et ajout de nouvelles ressources](/help/using/using.md#upload-and-add-new-assets-to-aem).

**Mise à jour dans la version v2.1.1.0 de l’application**

* Un des paramètres avancés permet à l’application d’émuler le comportement de l’application v1.10 lors du chargement de dossiers. Dans la version 1.10, les noms de noeud créés dans le référentiel respectent les espaces et la casse des noms de dossiers fournis par l’utilisateur. Dans la version 2.1, le comportement par défaut reste le même : plusieurs espaces dans les noms de dossier sont remplacés par des tirets dans le nom du noeud du référentiel et les noms de noeud sont convertis en minuscules. Consultez [les préférences de l’application](/help/using/install-upgrade.md#set-preferences).

**Mise à jour dans la version v2.1.0.0 de l’application**

* Pour charger des ressources, les utilisateurs peuvent désormais faire glisser les fichiers ou les dossiers sur l’interface de l’application, directement depuis l’Explorateur Windows ou le Finder Mac. Ce processus fonctionne en plus de l’option de téléchargement disponible dans l’application. Consultez [Chargement de ressources](/help/using/using.md#upload-and-add-new-assets-to-aem) <!-- CQ-4309527 -->

**Mise à jour dans la version v2.0.3 de l’application**

Le bogue corrigé dans cette version est le suivant :

* Correction du problème de connexion des utilisateurs de l’applications sous Windows qui tentaient d’accéder au référentiel DAM sur [!DNL Adobe Experience Manager] 6.5.5.0.

**Mises à jour dans la version v2.0.2 de l’application**

Les correctifs de bogues et mises à jour sont les suivants :

* Le paramètre d’accélération des chargements est désormais disponible pour améliorer les performances de chargement. Lorsque ce paramètre est activé, l’application charge plus rapidement en utilisant davantage de threads de CPU locaux et de ressources.

* Le chargement de ressources dont les noms de fichier ou les chemins d’accès contiennent certains caractères GB18030 a été résolu. <!-- CQ-4283494 -->

* L’option Trier par ordre de pertinence est disponible après le passage à un autre type de tri dans les résultats de la recherche. <!-- CQ-4286874 -->

* L’appli de bureau répertorie désormais les sous-dossiers sans avoir à effectuer d’actualisation explicite. <!-- CQ-4285711 -->

* (Windows) Correction d’un rare problème d’interface d’application inutilisable sur certains ordinateurs Windows. Les utilisateurs ne peuvent pas cliquer sur l’interface de l’application, car elle semble déformée avec un décalage de la zone de clic des éléments de l’interface. <!-- CQ-4280785 -->

**Mises à jour dans la version v2.0.1 de l’application**

Les correctifs de bogues et mises à jour sont les suivants :

* Option permettant de configurer le répertoire `%Temp%` de façon à ce qu’il corresponde au chemin d’accès à `%APPDATA%`. <!-- CQ-4282665 -->

* Permet aux utilisateurs de se connecter à l’instance Auteur d’[!DNL Experience Manager] via l’authentification SAML Okta. <!-- CQ-4278134 -->

## Instructions d’installation {#installation-instructions-v2}

Pour savoir comment installer et configurer l’application, voir [Installation [!DNL Experience Manager]  de l’appli de bureau](install-upgrade.md).

Si vous effectuez une mise à niveau à partir d’un précédent [!DNL Experience Manager] sur l’appli de bureau , vous devez suivre les bonnes pratiques de transition répertoriées dans la section [mise à niveau à partir de la version précédente](install-upgrade.md#upgrade-from-previous-version).

## Remarques importantes sur le fonctionnement de l’application {#how-app-works}

Il est important de comprendre ce qui suit à propos de l’application et de son fonctionnement.

* L’application offre un contrôle total sur les opérations qui nécessitent un transfert complet des fichiers binaires depuis et vers . [!DNL Experience Manager] (**Ouvrir**, **Modifier**, **Chargement des modifications**, et **Chargement d’Assets**).

   * Si vous souhaitez utiliser la ressource figurant sur le bureau, vous devez explicitement ouvrir, modifier ou télécharger sur votre bureau, que ce soit individuellement, dans un dossier ou par sélection multiple.

   * Si vous souhaitez que les modifications locales apportées aux ressources soient chargées dans [!DNL Experience Manager], vous devez sélectionner [!UICONTROL Upload Changes], individuellement ou par sélection multiple.

   * L’application n’est pas un client de synchronisation qui synchronise les ressources sur le bureau et [!DNL Experience Manager].

   * L’application ne fournit pas de partage réseau qui mappe le référentiel [!DNL Experience Manager] en tant que structure de dossiers virtuelle.

* La liste des ressources affichées par l’application est basée sur le statut du référentiel Assets. Les fichiers téléchargés localement puis renommés dans les fichiers locaux ou le dossier de cache ne sont ni affichés ni gérés avec l’application.

* Si l’application n’affiche pas les résultats attendus, cliquez sur l’icône d’actualisation dans la barre supérieure.

* Le partage réseau local, qui apparaît lorsque vous utilisez l’action [!UICONTROL Reveal File], n’affiche que les fichiers (et les dossiers) disponibles localement. Les actions [!UICONTROL Reveal File] et [!UICONTROL Reveal Folder] pré-téléchargent les ressources pour afficher les ressources appropriées dans le partage réseau local.

* Le partage réseau local SMB (Mac)/WebDAV (Win) est utilisé lorsqu’une application Adobe Creative Cloud lit les fichiers de ressources liés/placés dans un fichier natif de l’application de Creative Cloud.

Le diagramme suivant illustre le flux de ressources et de fichiers allant du cloud au système de fichiers local et vice versa, tel qu’il est initié par les actions de l’utilisateur.

![Flux de ressources allant du serveur [!DNL Experience Manager] aux applications de bureau natives via l’appli de bureau](assets/da20_flow_diagram.png)

## Problèmes connus {#known-issues-v2}

**Problèmes liés à l’interface utilisateur :**

* Parfois, l’interface de l’appli de bureau peut devenir vide. Cliquez avec le bouton droit, puis cliquez sur [!UICONTROL Refresh] pour recharger l’application. Après une telle actualisation, vous démarrez à la racine du référentiel DAM. Les mises à jour ou les états de vos ressources sont conservés. <!-- CQ-4270267 -->

* Difficulté à naviguer dans les dossiers/résultats de recherche sans pavé tactile ni pointeur de souris. La barre de défilement n’apparaît pas avec les dispositifs de souris sans roue. <!-- CQ-4269947 -->

* Rarement, la barre de progression ne s’affiche pas correctement lorsque la ressource de téléchargement change.

* Après avoir appliqué et supprimé le filtre pour rechercher toutes les ressources modifiées localement, l’application n’amène pas l’utilisateur à ses résultats de recherche ou à la vue de dossiers par laquelle il a commencé. L’application affiche le dossier racine du référentiel DAM.

* Parfois, lorsque vous vous connectez à une URL qui n’a pas de [!DNL Experience Manager] s’exécutant sur le serveur, l’écran de connexion ne répond plus. Quittez l’application et redémarrez-la.

**Problèmes CRUD (Create, Read, Update et Delete) :**

* Lors du chargement de modifications avec commentaires d’une ressource, les commentaires sont stockés avec la ressource dans [!DNL Experience Manager], mais ne sont pas visibles en tant que commentaires de contrôle de version. Ce problème est résolu dans les versions 6.4.5 d’[!DNL Experience Manager] et 6.5.1 d’[!DNL Experience Manager]. Adobe recommande vivement d’installer les derniers Service Packs. <!-- CQ-4268990 -->

* Un utilisateur ne peut pas annuler les transferts de ressources. Si vous avez déclenché involontairement un transfert volumineux, quittez l’application et redémarrez-la. <!-- CQ-4278940 -->

**Problèmes de plateforme :**

* Parfois, sous Windows, le statut d’une ressource peut passer immédiatement à [!UICONTROL Edited Locally] après son ouverture, même si vous ne l’avez pas modifié. Cliquez sur [!UICONTROL Refresh] pour mettre le statut à jour.

>[!MORELIKETHIS]
>
>* [[!DNL Experience Manager] as a [!DNL Cloud Service] documentation](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service)
>* [[!DNL Experience Manager] as a [!DNL Cloud Service] [!DNL Assets] documentation](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/overview)
>* [Comment utiliser l’appli de bureau [!DNL Experience Manager] ](using.md)
>* [Installation et mise à niveau d’une appli de bureau](install-upgrade.md)
>* [Bonnes pratiques et résolution des problèmes](troubleshoot.md)
