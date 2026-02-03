---
title: Prise en main  [!DNL Experience Manager]  l’appli de bureau
description: Découvrez comment l’appli  [!DNL Experience Manager]  bureau améliore la création et la publication de contenu grâce à des workflows rationalisés et à des fonctionnalités de productivité.
feature: Desktop App,Asset Management
exl-id: 6cf29b6a-74e6-4860-a25b-d3e91abbaa9d
source-git-commit: 2bf5ee7454846c288cc1c976d8f69c6bfed8eabf
workflow-type: tm+mt
source-wordcount: '1213'
ht-degree: 42%

---

# Prise en main de l’application de bureau [!DNL Adobe Experience Manager] {#getting-started-desktop-app}

Utilisez l’application de bureau [!DNL Adobe Experience Manager] pour accéder aux ressources numériques stockées dans un référentiel de gestion des ressources numériques [!DNL Adobe Experience Manager] sur votre bureau local. Vous pouvez ensuite utiliser ces ressources dans n’importe quelle application de bureau. Vous pouvez ouvrir et modifier les ressources localement dans les applications de bureau. Après avoir apporté des modifications, chargez-les à nouveau dans [!DNL Experience Manager] avec le contrôle de version pour partager les mises à jour avec d’autres utilisateurs. Vous pouvez également charger de nouveaux fichiers et des hiérarchies de dossiers vers [!DNL Experience Manager], créer des dossiers et supprimer des ressources ou des dossiers dans le DAM d’[!DNL Experience Manager].

L’intégration permet à divers rôles de l’organisation de gérer les ressources de manière centralisée dans [!DNL Experience Manager Assets] et d’accéder aux ressources sur le bureau local dans les applications natives sous Windows ou macOS.

Lorsque vous ouvrez l’application après vous être déconnecté ou lorsque vous vous connectez pour la première fois, fournissez l’URL de votre serveur [!DNL Experience Manager] au format `https://[aem-server-url]:[port]/`. Sélectionnez ensuite l’option [!UICONTROL Connect]. Indiquez vos informations d’identification pour connecter l’application au serveur.

>[!VIDEO](https://video.tv.adobe.com/v/28868?quality=12&learn=on){transcript=true}

L’application de bureau [!DNL Adobe Experience Manager] vous permet d’effectuer les tâches clés suivantes :

![Workflows et tâches pouvant être effectués avec [!DNL Experience Manager]’appli de bureau](assets/aem_desktop_app_usecases_v2.png)

## Fonctionnement de l’appli de bureau {#how-app-works2}

Avant de commencer à utiliser l’application, vous devez comprendre [son fonctionnement](release-notes.md#how-app-works). Familiarisez-vous également avec les termes suivants :

* **[!UICONTROL Desktop Actions]** : à partir de l’interface web d’Assets, dans un navigateur , vous pouvez explorer l’emplacement des ressources ou extraire et ouvrir la ressource pour la modifier dans votre application de bureau native. Ces actions sont disponibles à partir de l’interface web et utilisent la fonctionnalité de l’application de bureau .

* Le statut du fichier est **[!UICONTROL Cloud Only]** : ces ressources ne sont pas téléchargées sur l’ordinateur local et ne sont disponibles que sur le serveur [!DNL Experience Manager].

* Le statut du fichier est **[!UICONTROL Available locally]** : les ressources sont téléchargées et disponibles sur l’ordinateur local en l’état. Les ressources ne sont pas modifiées.

* Le statut du fichier est **[!UICONTROL Edited locally]** : ces ressources sont modifiées localement et les modifications restent à charger vers le serveur [!DNL Experience Manager]. Après le chargement, le statut passe à [!UICONTROL Available locally]. Voir [Modification de ressources](upload-assets.md#edit-assets-upload-updated-assets).

* Le statut du fichier est **[!UICONTROL Editing conflict]** : si vous et d’autres personnes modifiez une ressource simultanément, l’application indique qu’un conflit de modification s’est produit. L’application propose également des options pour conserver ou ignorer vos modifications. Découvrez [comment éviter les conflits de modification](assets-management-tasks.md#adv-workflow-collaborate-avoid-conflicts).

* Le statut du fichier est **[!UICONTROL Modified remotely]** : l’application indique si une ressource que vous avez téléchargée est modifiée sur le serveur [!DNL Experience Manager]. L’application permet également de télécharger la dernière version et de mettre à jour votre copie locale. Découvrez [comment éviter les conflits de modification](assets-management-tasks.md#adv-workflow-collaborate-avoid-conflicts).

* **[!UICONTROL Check-out]** : si vous modifiez un fichier ou envisagez de le modifier, faites-le passer au statut d’extraction. Une icône de cadenas est ajoutée à la ressource dans l’application et [!DNL Experience Manager]’interface web. Cette icône indique aux autres utilisateurs d’éviter de modifier simultanément la même ressource, car cela entraînerait un conflit de modification.

* **[!UICONTROL Check-in]** : marquez la ressource comme étant sécurisée pour que d’autres utilisateurs puissent la modifier sans provoquer de conflit de modification. Lorsque vous chargez vos modifications, l’icône de verrouillage disparaît automatiquement. Activer/désactiver le statut d’archivage supprime également l’icône de cadenas, bien qu’Adobe recommande d’éviter de procéder à l’archivage manuel sans charger les modifications. Si vous annulez vos modifications, activez manuellement le statut d’archivage.

* Action **[!UICONTROL Open]** : ouvrez simplement la ressource pour la prévisualiser dans l’application native. Adobe vous recommande d’éviter de modifier la ressource à l’aide de cette action. La raison en est qu’il n’extrait pas la ressource. Pendant ce temps, d’autres utilisateurs peuvent apporter des modifications entraînant des conflits de modification.

* Action **[!UICONTROL Edit]** : utilisez l’action pour modifier l’image. Un clic sur [!UICONTROL Edit] extrait la ressource et ajoute une icône de verrou à la ressource. Après avoir cliqué sur Edit (Modifier), si vous ne souhaitez pas modifier la ressource, cliquez sur [!UICONTROL Toggle check-in]. Pour supprimer, renommer ou déplacer des ressources dans la hiérarchie de dossiers de la gestion des ressources numériques [!DNL Experience Manager], utilisez les actions de l’interface web [!DNL Experience Manager] et non l’action de modification.

* Action **[!UICONTROL Download]** : téléchargez la ressource sur votre ordinateur local. Vous pouvez télécharger les ressources maintenant et les modifier ultérieurement et travailler hors ligne et charger les modifications ultérieurement. Les fichiers sont téléchargés dans un dossier de cache sur votre système de fichiers.

* Action **[!UICONTROL Reveal File]** ou **[!UICONTROL Reveal Folder]** : lorsque les ressources sont téléchargées dans un dossier de cache local, l’application imite un lecteur réseau local. Il fournit un chemin d’accès local pour chaque ressource. Pour découvrir ce chemin d’accès, utilisez l’option d’affichage appropriée dans l’application. Une action d’affichage est requise pour placer des ressources dans l’application Creative Cloud. Voir [Placement de ressources](search.md#place-assets-in-native-documents).

* Action **[!UICONTROL Open In Web]** : pour afficher la ressource dans l’interface web [!DNL Experience Manager], ouvrez-la dans le Web. Vous pouvez lancer d’autres workflows à partir de l’interface [!DNL Experience Manager], comme la mise à jour des métadonnées ou la découverte de ressources.

* Action **[!UICONTROL Delete]** : supprimez la ressource du référentiel DAM d’[!DNL Experience Manager]. L’action supprime la copie d’origine de la ressource sur le serveur Experience Manager. Si vous souhaitez uniquement ignorer les modifications apportées à la ressource locale, voir [ignorer les modifications](upload-assets.md#edit-assets-upload-updated-assets).

* **[!UICONTROL Upload Changes]** : l’application de bureau charge la ressource mise à jour uniquement lorsque vous effectuez un chargement explicite sur le serveur [!DNL Experience Manager]. Lorsque vous enregistrez vos modifications, celles-ci ne sont enregistrées que sur votre ordinateur local. Lors du chargement, la ressource est automatiquement archivée et l’icône de verrouillage est supprimée. Voir [Modification de ressources](upload-assets.md#edit-assets-upload-updated-assets).

## Activation des actions de bureau dans [!DNL Experience Manager]’interface web d’ {#desktopactions-v2}

À partir de l’interface utilisateur d’[!DNL Assets] ouverte dans un navigateur, vous pouvez explorer l’emplacement des ressources ou extraire et ouvrir une ressource pour la modifier dans votre appli de bureau. Ces options, qui sont appelées [!UICONTROL Desktop Actions], ne sont pas activées par défaut. Pour les activer, procédez comme suit.

1. Dans la console [!DNL Assets], cliquez sur l’icône **[!UICONTROL User]** dans la barre d’outils.
1. Cliquez sur **[!UICONTROL My Preferences]** pour afficher la boîte de dialogue **[!UICONTROL Preferences]**.

1. Dans la boîte de dialogue [!UICONTROL User Preferences], sélectionnez **[!UICONTROL Show Desktop Actions For Assets]**, puis cliquez sur **[!UICONTROL Accept]**.

   ![Sélectionnez Afficher les actions de bureau pour Assets afin d’activer les actions de bureau](assets/enable_desktop_actions1.png)

## Démarrer à partir de l’interface Web d’[!DNL Assets] {#adv-workflow-start-from-aem-ui}

Si nécessaire, lancez votre workflow à partir de l’interface web d’Assets. L’appli de bureau s’intègre à [!DNL Experience Manager] pour prendre le relais si nécessaire à l’aide des actions de bureau.

La découverte de ressources est un cas particulier de démarrage d’un workflow à partir de l’interface web. La barre Omnisearch de l’interface utilisateur d’Assets offre une expérience de recherche riche et avancée. Vous pouvez d’abord localiser une ressource souhaitée sur le Web, puis lancer le workflow dans l’application à l’aide de [!UICONTROL Desktop Actions]. Certains exemples de cas incluent le filtrage des résultats de recherche à l’aide de facettes, la localisation d’une ressource spécifique sous licence Adobe Stock ou une personnalisation implémentée par votre organisation qui vous permet d’effectuer une meilleure découverte à partir de l’interface web.

La fonctionnalité de l’appli de bureau est utilisée lorsque vous tentez d’effectuer les actions suivantes sur l’interface web d’Assets :

* Les [!UICONTROL Desktop Actions] qui autorisent les [!UICONTROL Open], les [!UICONTROL Edit] et les [!UICONTROL Reveal]
* [!UICONTROL Upload folder]
* [!UICONTROL Check-out] ou [!UICONTROL check-in]

Par exemple, les actions sur l’interface Web disponibles pour une ressource extraite dans l’application sont [!UICONTROL Open], [!UICONTROL Reveal] et [!UICONTROL Check in].

![Actions de bureau dans l’interface Web [!DNL Experience Manager]](assets/assets_web_actions_da2.png "Actions de bureau dans l’interface Web d’Experience Manager")

>[!NOTE]
>
>Le navigateur peut vous inviter à autoriser le lancement du bureau [!DNL Adobe Experience Manager]. Pour que le transfert du navigateur à l’application soit ininterrompu à chaque fois, cochez la case appropriée pour permettre à l’application de prendre le relais.

Vous ne pouvez pas trouver les informations ou le workflow suivant à l’aide de l’interface Web . Utilisez l’application de bureau , car l’interface Web d’ ne suit pas les modifications locales et ne prend pas en compte les éléments suivants :

* Les fichiers sont modifiés localement.
* Fichiers présentant un conflit d’édition et un moyen de le résoudre.
* Chargement des modifications locales dans [!DNL Experience Manager].
* Différents statuts des fichiers disponibles localement.

Au contraire, vous pouvez ouvrir la ressource dans l’interface web à partir de l’application de bureau à l’aide de l’action **[!UICONTROL Open In Web]**.

## Étapes suivantes {#next-steps}

* [Regardez une vidéo pour commencer à utiliser l’application de bureau Adobe Experience Manager](https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app)

* Faites des commentaires sur la documentation en utilisant [!UICONTROL Edit this page] ![modifier la page](assets/do-not-localize/edit-page.png) ou [!UICONTROL Log an issue] ![créer un problème GitHub](assets/do-not-localize/github-issue.png) disponible dans la barre latérale droite.

* Contacter l’[assistance clientèle](https://experienceleague.adobe.com/fr?support-solution=General#support)

>[!MORELIKETHIS]
>
>* [Comprendre l’interface utilisateur](/help/using/user-interface.md)
>* [Notes de mise à jour et problèmes connus](/help/using/release-notes.md)
>* [Installation ou mise à niveau de l’appli de bureau](/help/using/install-upgrade.md)
