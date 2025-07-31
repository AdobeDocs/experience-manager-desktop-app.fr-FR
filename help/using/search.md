---
title: Parcourez, recherchez et prévisualisez des ressources dans l’application de bureau [!DNL Experience Manager]
description: Parcourez, recherchez et prévisualisez des ressources dans l’application  [!DNL Adobe Experience Manager]  bureau .
feature: Desktop App
source-git-commit: 2947fbd3bfeb15b37a8f1b0118e969b5d70499d0
workflow-type: tm+mt
source-wordcount: '910'
ht-degree: 75%

---


# Parcourir, rechercher et prévisualiser des ressources {#browse-search-preview-assets}

Vous pouvez parcourir, rechercher et prévisualiser les ressources disponibles dans le référentiel d’[!DNL Experience Manager], le tout depuis l’appli de bureau. Essayez les options suivantes dans l’application :

1. Accédez à un dossier et affichez des informations de base sur les ressources disponibles dans ce dossier, ainsi que de petites vignettes de toutes les ressources.

   ![Accès aux dossiers et fichiers DAM](assets/browse_folder_da2.png "Accès aux dossiers et fichiers DAM")

1. Pour afficher davantage d’informations et une vignette plus grande d’une ressource spécifique, cliquez sur le nom de fichier de la ressource.

   ![Afficher un aperçu plus grand d’une ressource et des actions](assets/large_preview_actions_da2.png "Afficher un aperçu plus grand d’une ressource et des actions")

1. Cliquez sur **[!UICONTROL Open]** ou **[!UICONTROL Edit]** pour télécharger le fichier localement et l’afficher uniquement ou pour le modifier dans l’application native, respectivement.
1. Recherchez à l’aide de mots-clés une ressource associée dans le référentiel d’[!DNL Experience Manager]. Utilisez `?` et `*` comme caractères génériques. Ces caractères génériques remplacent un caractère unique ou plusieurs caractères, respectivement. Filtrez et triez les résultats selon vos besoins.

   ![Exemple de recherche utilisant un caractère générique astérisque](assets/search_wildcard_da2.png "Exemple de recherche utilisant un caractère générique astérisque")

   ![Autre exemple de recherche utilisant un caractère générique astérisque](assets/search_wildcard2_da2.png "Autre exemple de recherche utilisant un caractère générique astérisque")

>[!NOTE]
>
>L’application affiche les ressources en faisant correspondre les critères de recherche de plusieurs champs de métadonnées et pas uniquement le titre ou le nom de fichier de la ressource.

## Ouvrir des ressources sur votre bureau {#openondesktop-v2}

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

### Gestion des caractères spéciaux dans les noms de ressources {#special-characters-in-filename}

Dans l’application héritée, les noms de nœuds créés dans le référentiel conservaient les espaces et la casse des noms de dossier fournis par l’utilisateur. Pour que l’application actuelle émule les règles de nommage de nœud de l’application v1.10, activez [!UICONTROL Use legacy conventions when creating nodes for assets and folders] dans la balise [!UICONTROL Preferences]. Consultez [Préférences de l’application](/help/using/install-upgrade.md#set-preferences). Cette préférence héritée est désactivée par défaut.

>[!NOTE]
>
>L’application modifie uniquement les noms de nœud dans le référentiel à l’aide des conventions d’affectation de nom suivantes. L’application conserve la ressource `Title` telle quelle.

| Caractères* | Préférence héritée dans l’application | Pour les noms de fichier | Pour les noms de dossier | Exemple |
|---|---|---|---|---|
| `. / : [ ] \| *` | Activé ou désactivé | Remplacé par `-` (trait d’union). Un `.` (point) dans l’extension du nom de fichier est conservé tel quel. | Remplacé par `-` (trait d’union). | `myimage.jpg` reste en l’état et `my.image.jpg` les modifications dans `my-image.jpg`. |
| `% ; # , + ? ^ { } "` et espaces blancs | ![Icône Désélectionné](assets/do-not-localize/deselect-icon.png) Désactivé | Les espaces sont conservés | Remplacé par `-` (trait d’union). | `My Folder.` remplacé par `my-folder-`. |
| `# % { } ? & .` | ![Icône Désélectionné](assets/do-not-localize/deselect-icon.png) Désactivé | Remplacé par `-` (trait d’union). | NA. | `#My New File.` remplacé par `-My New File-`. |
| Caractères en majuscule | ![Icône Désélectionné](assets/do-not-localize/deselect-icon.png) Désactivé | La casse est conservée telle quelle. | Remplacé par des caractères minuscules. | `My New Folder` remplacé par `my-new-folder`. |
| Caractères en majuscule | ![Icône Sélection cochée](assets/do-not-localize/selection-checked-icon.png) Activé | La casse est conservée telle quelle. | La casse est conservée telle quelle. | NA. |

*La liste des caractères est une liste séparée par des espaces.

## Rechercher toutes les images modifiées {#find-all-edited-images}

L’application fournit une vue, appelée **[!UICONTROL Edited locally]**, qui vous permet d’accéder rapidement à tous les fichiers que vous avez téléchargés localement (par le biais d’actions [!UICONTROL Open] ou [!UICONTROL Edit]) puis modifiés. L’application vous permet de sélectionner toutes les ressources modifiées localement et de charger les modifications en quelques clics. Cette vue affiche également les ressources modifiées localement qui présentent un conflit de modification.

![Filtrer pour afficher toutes les ressources modifiées localement](assets/edited_locally_filter_da2.png "Par exemple, filtrer pour afficher toutes les ressources modifiées localement pour un chargement en masse de modifications")

## Étapes suivantes {#next-steps}

* [Regardez une vidéo pour commencer à utiliser l’application de bureau Adobe Experience Manager](https://experienceleague.adobe.com/fr/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app)

* Faites des commentaires sur la documentation en utilisant [!UICONTROL Edit this page] ![modifier la page](assets/do-not-localize/edit-page.png) ou [!UICONTROL Log an issue] ![créer un problème GitHub](assets/do-not-localize/github-issue.png) disponible dans la barre latérale droite.

* Contacter l’[assistance clientèle](https://experienceleague.adobe.com/fr?support-solution=General#support)

>[!MORELIKETHIS]
>
>* [Comprendre l’interface utilisateur](/help/using/user-interface.md)
>* [Utilisation de l’appli de bureau](/help/using/using-desktop-app.md)
>* [Gestion d’Assets dans l’application de bureau](/help/using/assets-management-tasks.md)
