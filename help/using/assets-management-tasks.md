---
title: 'Utilisation de l’appli de bureau [!DNL Experience Manager] '
description: Utilisez l’application de bureau [!DNL Adobe Experience Manager] pour travailler avec des ressources DAM [!DNL Adobe Experience Manager] directement depuis votre bureau Windows ou Mac et les utiliser dans d’autres applications.
feature: Desktop App,Asset Management
source-git-commit: c5aeee9ab636ba7bedff4225172140d59cfe627d
workflow-type: tm+mt
source-wordcount: '1416'
ht-degree: 40%

---


# Tâches de gestion Assets dans [!DNL AEM Desktop App] {#assets-management-tasks}

La gestion des ressources implique l’organisation, la maintenance et l’optimisation des ressources numériques afin de rationaliser les workflows. Cela inclut des tâches telles que la duplication et le changement de nom de fichiers, l’épinglage ou le détachement de dossiers pour un accès rapide, ainsi que l’affichage de ressources dans différentes dispositions. Cela permet d’améliorer l’efficacité, de simplifier le suivi des ressources et d’assurer une récupération et une organisation faciles des ressources numériques sur plusieurs plateformes.

## Afficher les ressources {#view-assets}

L’application de bureau AEM vous permet d’afficher des ressources dans quatre vues différentes :

* **[!UICONTROL Show Assets]:** permet d’afficher toutes les ressources.
* **[!UICONTROL Show Collections]:** permet d’afficher toutes les collections créées dans l’application AEM native. En savoir plus [collections](#collections-desktop-app).
* **[!UICONTROL Edited Locally]:** permet d’afficher toutes les ressources modifiées localement. Dans cette vue, vous pouvez ajouter et charger plusieurs ressources.
* **[!UICONTROL Asset transfers]:** vous permet d’afficher toutes les ressources transférées de l’application native vers l’application locale ou vice versa.
* **[!UICONTROL Pinned items]:** vous permet d’afficher tous les éléments épinglés.

Pour choisir parmi différentes vues de ressources dans l’application AEM Desktop, procédez comme suit :

1. Ouvrez l’application de bureau AEM.

1. Accédez à la liste déroulante Affichage dans le coin supérieur droit. Choisissez-en une parmi les vues disponibles.

   ![épingler ou détacher un dossier](assets/view-pinned-assets.png)

## Afficher les dossiers et fichiers nouvellement ajoutés {#view-newly-added-files-folders}

Vous pouvez charger les ressources nouvellement créées à partir de votre ordinateur local vers AEM, où le référentiel central est stocké. Pour afficher localement ces ressources nouvellement créées, accédez au menu déroulant **[!UICONTROL View]** et sélectionnez **[!UICONTROL Show Assets]** pour afficher toutes les mises à jour avec leur journal et leur titre, ou sélectionnez **[!UICONTROL Edited Locally]**. Les deux options affichent explicitement les ressources modifiées localement.

## Dupliquer les fichiers {#duplicate-files}

Lorsque vous souhaitez conserver un fichier d’origine et apporter des modifications au fichier similaire, vous pouvez dupliquer des fichiers à différents emplacements (local et cloud) simultanément. Cela peut être effectué au moyen de fichiers en double sur plusieurs ressources.

Pour dupliquer des fichiers dans l’application de bureau AEM, procédez comme suit :

1. Accédez à un dossier et sélectionnez la ressource à dupliquer.

   ![Autres options](assets/more-options1.png)

1. Cliquez sur **[!UICONTROL More actions]** ![icône Autres actions](assets/do-not-localize/more2_da2.png) et sélectionnez ![icône de duplication](assets/do-not-localize/duplicate.svg) **[!UICONTROL Duplicate File]** action.

1. Le fichier en double est créé avec un nom de fichier et un contenu identiques.

## Renommer le titre d’une ressource ou d’un dossier {#rename-asset-title}

Pour renommer le titre d’une ressource ou d’un dossier, procédez comme suit :

1. Parcourez la ressource à renommer. Lors de l’attribution d’un nom à un dossier, les caractères spéciaux tels que `\ / : * ?  | < > [ ] %` ne sont pas autorisés. S’ils sont inclus, ils sont automatiquement remplacés par un trait d’`-`.

1. Cliquez sur **[!UICONTROL More actions]** ![icône Autres actions](assets/do-not-localize/more2_da2.png) et sélectionnez **[!UICONTROL Rename]** pour ajouter le titre de votre choix à une ressource.


## Épingler ou désépingler un dossier {#pin-unpin-folder}

Les dossiers épinglés sont automatiquement synchronisés pour refléter toutes les modifications apportées en mode natif dans l’application. Pour l’accès rapide, vous pouvez épingler ou désépingler un dossier en procédant comme suit :

1. Parcourez la ressource que vous souhaitez épingler ou désépingler.

1. Cliquez sur **[!UICONTROL More actions]** ![icône Autres actions](assets/do-not-localize/more2_da2.png) et sélectionnez [!UICONTROL pin] pour épingler la ressource ou le dossier. Vous pouvez également cliquer sur [!UICONTROL unpin] pour le désépingler.

   ![épingler ou détacher un dossier](assets/pin-unpin.png)

## Actualisation automatique {#auto-refresh}

La fonction d’actualisation automatique met automatiquement à jour le contenu en temps réel, ce qui vous permet de toujours voir les informations les plus récentes sans recharger manuellement la page. Exécutez les étapes ci-dessous pour actualiser automatiquement les ressources afin d’obtenir la liste des ressources mises à jour :

1. Ouvrez l’application de bureau AEM.

1. Cliquez sur ![icône d’actualisation](assets/do-not-localize/refresh.png) dans la barre de menus pour obtenir les mises à jour.

## Collections {#collections-desktop-app}

L’application de bureau AEM vous permet d’[afficher](#view-collections-desktop-app), [télécharger](#download-collections-desktop-app) et de parcourir les collections créées sur [!DNL Adobe Experience Manager Assets] application.

### Affichage des collections {#view-collections-desktop-app}

Pour afficher les collections dans l’application Desktop, procédez comme suit :

1. Ouvrez l’application de bureau AEM et accédez à [Affichage des ressources](#view-assets).

1. Sélectionnez **[!UICONTROL Show Collections]**. Les collections disponibles dans l’application native s’affichent.

   ![Application de bureau Collections](assets/collections-desktop-app.png)

### Télécharger des collections {#download-collections-desktop-app}

Exécutez les étapes suivantes pour télécharger des collections dans l’application de bureau :

1. Suivez les étapes 1 et 2 comme indiqué dans [Affichage des collections](#view-collections-desktop-app).

1. Accédez à Autres actions ![icône Autres actions](assets/do-not-localize/more2_da2.png) sur la collection à télécharger.

1. Cliquez sur **[!UICONTROL Download]** pour télécharger la collection en question.

## Créer un dossier avec le schéma de métadonnées {#create-folder-with-metadata-schema}

L’application de bureau AEM vous permet d’attribuer des métadonnées lors de la création d’un dossier. Pour cela, procédez comme suit :

1. Accédez à l’icône Créer un répertoire ![icône Ajouter un dossier](assets/do-not-localize/add-folder.svg). **[!UICONTROL Create Directory]** écran s’affiche.

1. Ajoutez les détails suivants :
   * **[!UICONTROL Name]** du dossier.
   * **[!UICONTROL Folder Metadata Schema]** de choisir la hiérarchie des métadonnées du dossier ou choisissez **[!UICONTROL none]** si vous ne souhaitez pas y lier des métadonnées.

1. Cliquez sur **[!UICONTROL OK]** pour continuer.

## Liste des ressources transférées {#list-of-transferred-assets}

Pour afficher la liste des ressources transférées au cours d’une session donnée, consultez [Chargement de ressources dans [!DNL Experience Manager]](#upload-and-add-new-assets-to-aem).

## Processus avancé : collaborer sur les mêmes fichiers et éviter les conflits de modification {#adv-workflow-collaborate-avoid-conflicts}

Dans les environnements collaboratifs, plusieurs utilisateurs et utilisatrices peuvent travailler sur le même ensemble de ressources, ce qui peut entraîner des conflits de version. Pour prévenir les conflits, observez les bonnes pratiques suivantes :

* Ne modifiez aucune ressource en cliquant sur [!UICONTROL Open]. Ne modifiez pas les ressources téléchargées localement en les ouvrant à partir du dossier de votre système de fichiers. Les autres utilisateurs ne savent pas que ces ressources sont en cours de modification.
* Pour modifier une ressource, cliquez toujours sur [!UICONTROL Edit]. Cela ouvre la ressource dans l’application native et lui ajoute une icône de verrouillage pour indiquer aux autres utilisateurs que la ressource est en cours de modification.
* Cliquez sur [!UICONTROL Toggle Check-in] si vous avez accidentellement commencé à effectuer des modifications sans cliquer sur [!UICONTROL Edit]. Cette fonctionnalité ajoute une icône de verrou à la ressource. Si vous prévoyez de modifier une ressource ultérieurement et que vous souhaitez éviter que d’autres utilisateurs la modifient, cliquez sur [!UICONTROL Toggle Check-in] pour la verrouiller.
* Avant de modifier une ressource, vérifiez qu’elle n’est pas en train d’être modifiée par d’autres utilisateurs. Recherchez l’icône de verrouillage sur la ressource.
* Une fois les modifications terminées, téléchargez-les toutes, puis archivez la ressource.

![Statuts de la modification des conflits](assets/edits_conflicts_status_da2.png "Statuts de la modification des conflits")

Si une ressource téléchargée localement est mise à jour sur le serveur [!DNL Experience Manager], l’application affiche le statut **[!UICONTROL Modified remotely]**. Vous pouvez supprimer votre copie locale ou l’actualiser en cliquant sur [!UICONTROL Remove] ou [!UICONTROL Update], respectivement. Les liens de la boîte de dialogue vous permettent d’afficher les deux versions de la ressource.

![Options pour résoudre le conflit lorsque la ressource est modifiée à distance](assets/modified_remotely_dialog_da2.png "Options pour résoudre le conflit lorsque la ressource est modifiée à distance")

Si une ressource que vous modifiez localement est également mise à jour sur le serveur à votre insu, l’application affiche le statut **[!UICONTROL Editing Conflict]**. Vous pouvez conserver un jeu de modifications : conservez vos mises à jour (cliquez sur **[!UICONTROL Keep Mine]**) et supprimez les modifications de l’autre utilisateur ou utilisatrice, ou conservez les modifications de l’autre utilisateur ou utilisatrice et supprimez les vôtres (cliquez sur **[!UICONTROL Overwrite Mine]**).

![Options pour résoudre un conflit de modification](assets/editing_conflict_dialog_da2.png "Options pour résoudre un conflit de modification")

## Processus avancé : placer et lier des ressources dans un fichier InDesign {#adv-workflow-place-assets-indesign}

Lorsque vous utilisez l’application de bureau [!DNL Experience Manager] pour ouvrir des fichiers avec des ressources liées, les ressources sont prétéléchargées et apparaissent placées dans les applications natives. Pour que ce processus fonctionne, votre application native doit prendre en charge le placement de liens dans des ressources locales et [!DNL Experience Manager] doit prendre en charge la résolution de ces liens dans les fichiers binaires vers des références côté serveur.

L’appli de bureau [!DNL Experience Manager] prend en charge ce processus avec quelques applications de bureau et formats de fichier Adobe Creative Cloud (Adobe InDesign, Adobe Illustrator et Adobe Photoshop). Le processus vous permet d’utiliser efficacement les fichiers Creative Cloud pris en charge. Si l’utilisateur A ajoute des ressources à un fichier InDesign et les consigne dans [!DNL Experience Manager], l’utilisateur B peut voir les ressources du fichier même si elles ne font pas partie de celui-ci. Les ressources sont téléchargées localement sur l’ordinateur de l’utilisateur B.

>[!NOTE]
>
>L’appli de bureau peut mapper sur n’importe quel lecteur sous Windows. Toutefois, pour un fonctionnement harmonieux, ne changez pas la lettre de lecteur par défaut. Si les utilisateurs d’une même organisation utilisent des lettres de lecteur différentes, ils ne peuvent pas voir les ressources placées par d’autres utilisateurs. Les ressources placées ne sont pas récupérées lorsque le chemin d’accès change. Les ressources placées demeurent placées dans le fichier binaire (par exemple, INDD) et ne sont pas supprimées.

Pour connaître les limites de ce processus, voir la [configuration requise et les versions prises en charge](release-notes.md).

Pour tester ce processus avec une ressource d’image et InDesign, procédez comme suit :

1. Conservez à portée de main un fichier INDD avec des ressources placées dans [!DNL Experience Manager]. Pour savoir comment créer un tel fichier INDD, voir [Placement de graphiques](https://helpx.adobe.com/fr/indesign/using/placing-graphics.html).
1. À partir de l’application de bureau , **[!UICONTROL Edit]** le fichier INDD avec les ressources placées dans [!DNL Experience Manager].
1. L’application télécharge le fichier InDesign et les ressources liées. Lorsque InDesign ouvre le document, les liens sont résolus et les ressources sont téléchargées et s’affichent dans le document InDesign.
1. Pour placer un nouveau graphique dans le fichier InDesign, utilisez l’action **[!UICONTROL Reveal File]** sur la ressource. L’action télécharge la ressource localement et ouvre l’emplacement du partage réseau local dans l’Explorateur Windows ou le Finder Mac.
1. Placez la ressource affichée dans le document InDesign. Cela crée un lien dans le document.
1. Une fois les modifications effectuées dans le document InDesign, enregistrez-les et chargez-les dans [!DNL Experience Manager] à l’aide de l’appli de bureau.

## Étapes suivantes {#next-steps}

* [Regardez une vidéo pour commencer à utiliser l’application de bureau Adobe Experience Manager](https://experienceleague.adobe.com/fr/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app)

* Faites des commentaires sur la documentation en utilisant [!UICONTROL Edit this page] ![modifier la page](assets/do-not-localize/edit-page.png) ou [!UICONTROL Log an issue] ![créer un problème GitHub](assets/do-not-localize/github-issue.png) disponible dans la barre latérale droite.

* Contactez l’[assistance clientèle](https://experienceleague.adobe.com/fr?support-solution=General#support).

<!--* Provide product feedback using the [!UICONTROL Feedback] option available on the AEM Desktop App user interface>-->

>[!MORELIKETHIS]
>
>* [Comprendre l’interface utilisateur](/help/using/user-interface.md).
>* [ Guide de prise en main ](/help/using/get-started.md).
