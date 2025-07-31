---
title: Utilisation  [!DNL Experience Manager]  l’appli de bureau
description: Utilisation  [!DNL Adobe Experience Manager]  l’appli de bureau .
feature: Desktop App,Asset Management
source-git-commit: 2947fbd3bfeb15b37a8f1b0118e969b5d70499d0
workflow-type: tm+mt
source-wordcount: '429'
ht-degree: 58%

---


# Ouvrir des ressources sur votre bureau {#openondesktop-v2}

Vous pouvez ouvrir les ressources distantes pour les afficher dans l’application native. Les ressources sont téléchargées dans un dossier local. Elles sont ensuite lancées dans l’application native associée au format de fichier. Vous pouvez changer l’application native pour ouvrir des types de fichiers (extensions) spécifiques sous Mac ou Windows.

Cliquez sur **[!UICONTROL Open]** dans le menu de ressource. La ressource est téléchargée localement et ouverte dans l’application native. Vérifiez la progression du téléchargement et la vitesse de transfert des ressources volumineuses dans la barre d’état.

<!-- ![Download progress bar for large-sized assets](assets/download_status_bar_da2.png "Download progress bar for large-sized assets")
-->

>[!NOTE]
>
>Si les modifications attendues ne sont pas reflétées dans l’application, cliquez sur l’icône Actualiser ![Icône Actualiser](assets/do-not-localize/refresh.png) ou cliquez avec le bouton droit de la souris sur l’interface de l’application, puis cliquez sur **[!UICONTROL Refresh]**. Les actions ne sont pas disponibles lorsque des téléchargements ou des chargements plus volumineux sont en cours.

Pour ouvrir le dossier de téléchargement local d’une ressource, cliquez sur ![Icône More actions](assets/do-not-localize/more2_da2.png), puis sur l’action ![Icône Afficher](assets/do-not-localize/reveal_action2_da2.png) **[!UICONTROL Reveal File]**.

## Utiliser ou placer des ressources dans des documents natifs {#place-assets-in-native-documents}

Dans certains cas (par exemple, lorsque vous importez un fichier dans un document natif), vous accédez à un fichier dans l’Explorateur Windows ou le Finder Mac. Pour accéder à l’emplacement de système de fichiers du fichier téléchargé localement, utilisez l’option ![Icône Afficher](assets/do-not-localize/reveal_action2_da2.png) **[!UICONTROL Reveal File]**.

![Action Afficher le fichier pour une ressource](assets/revealfile_action_da2.png "Action Afficher le fichier pour une ressource")

Cliquez sur **[!UICONTROL Reveal File]**, ou **[!UICONTROL Reveal Folder]** sur un dossier, pour ouvrir l’Explorateur Windows ou le Finder Mac avec le fichier ou le dossier présélectionné sur votre ordinateur local. Par exemple, l’option est utile pour placer les fichiers [!DNL Experience Manager] dans les applications natives qui prennent en charge le placement ou la liaison de fichiers locaux. Pour savoir comment placer des fichiers dans Adobe InDesign, voir [Placement de graphiques](https://helpx.adobe.com/fr/indesign/using/placing-graphics.html).

L’action **[!UICONTROL Reveal File]** ouvre un partage réseau local. Elle affiche uniquement les ressources disponibles localement. En d’autres termes, elle affiche les ressources qui ont été révélées, téléchargées ou ouvertes/modifiées à l’aide de l’application. Le partage réseau local ne charge aucune modification dans [!DNL Experience Manager]. Pour charger les modifications, utilisez explicitement les actions **[!UICONTROL Upload Changes]** ou **[!UICONTROL Upload]** dans l’application.

>[!NOTE]
>
>Pour une compatibilité descendante avec l’appli de bureau [!DNL Experience Manager] v1.x, les fichiers affichés sont diffusés à partir d’un partage réseau local, exposant uniquement les fichiers disponibles en local. Les chemins d’accès aux fichiers affichés sont identiques à ceux créés par l’application v1.x.

>[!CAUTION]
>
>N’utilisez pas l’option **[!UICONTROL Reveal File]** pour modifier des ressources dans les applications natives. Utilisez plutôt les actions **[!UICONTROL Edit]**. Pour en savoir plus, consultez la section [Workflow avancé : collaborer sur les mêmes fichiers et éviter les conflits de modification](#adv-workflow-collaborate-avoid-conflicts).

## Étapes suivantes {#next-steps}

* [Regardez une vidéo pour commencer à utiliser l’application de bureau Adobe Experience Manager](https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app)

* Faites des commentaires sur la documentation en utilisant [!UICONTROL Edit this page] ![modifier la page](assets/do-not-localize/edit-page.png) ou [!UICONTROL Log an issue] ![créer un problème GitHub](assets/do-not-localize/github-issue.png) disponible dans la barre latérale droite.

* Contacter l’[assistance clientèle](https://experienceleague.adobe.com/fr?support-solution=General#support)

>[!MORELIKETHIS]
>
>* [Comprendre l’interface utilisateur](/help/using/user-interface.md)
>* [Gestion d’Assets dans l’application de bureau](/help/using/assets-management-tasks.md)
>* [Recherche](/help/using/search.md)
