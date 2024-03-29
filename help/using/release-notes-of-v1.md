---
title: Notes de mise à jour de l’appli de bureau v1.10
description: Détails des mises à jour, améliorations, nouvelles fonctionnalités, compatibilité et liens de téléchargement pour l’appli de bureau AEM version 1.10.
exl-id: 886864e0-016a-4a17-b3ba-4b18a514214a
source-git-commit: df5283f6bef6adbb007bf93c6dabb3b12e430f58
workflow-type: ht
source-wordcount: '3898'
ht-degree: 100%

---

# Notes de mise à jour de l’appli de bureau [!DNL Adobe Experience Manager] v1.10 {#aem-desktop-app-release-notes}

Pour la version 1.x de l’appli de bureau, voici les liens de téléchargement et les informations de compatibilité d’AEM.

| Produits | Appli de bureau [!DNL Adobe Experience Manager] |
|--- |--- |
| Version | 1.10 (1.10.0.6 sous Mac et 1.10.0.3 sous Windows) |
| Type | Version mineure |
| Date | 1.10.0.6 (Mac) : 15 avril 2020 ; 1.10.0.3 (Win) : 31 août 2018 |
| URL de téléchargement | [Mac OS X 64 bits](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-osx-1.10.0.6.dmg) ; [Windows 32 bits](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win32-1.10.0.3.exe) ; [Windows 64 bits](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=/content/software-distribution/en/details.html/content/dam/aem/public/adobe/packages/adobe/aem-desktop-app/aem-desktop-win64-1.10.0.3.exe) |
| Compatibilité | AEM 6.5.x ; AEM 6.4.x ; AEM 6.3 SP2 ; AEM 6.2 SP1 CFP2+ ; AEM 6.1 SP2 CFP7+ |

>[!NOTE]
>
>La limite de taille du cache n’est pas appliquée. Au démarrage de l’appli de bureau, la taille du cache est calculée une seule fois et une notification est affichée si elle est proche de la limite prédéfinie.

## Configuration requise et conditions préalables {#system-requirements-and-prerequisites}

L’appli de bureau [!DNL Adobe Experience Manager] est compatible avec les systèmes d’exploitation suivants :

* Mac OS X 10.10 ou version ultérieure, avec les correctifs de bogues les plus récents.

* Windows 10 avec les derniers Service Packs et correctifs.

>[!NOTE]
>
>Windows 7 n’est plus pris en charge. Consultez [l’article sur la fin du support de Windows 7](https://support.microsoft.com/fr-fr/help/4057281/windows-7-support-ended-on-january-14-2020).

Adobe recommande vivement d’utiliser la version la plus récente de l’appli de bureau AEM pour bénéficier des dernières fonctionnalités, des correctifs de bogues les plus récents et d’un niveau de performance optimal.

La version de l’appli de bureau AEM que vous prévoyez d’installer sur votre ordinateur local nécessite une version spécifique du serveur AEM/des composants supplémentaires côté serveur (Service Packs, correctifs logiciels ou Feature Packs). Assurez-vous que le serveur AEM est correctement configuré avant de vous y connecter pour la première fois. Si vous avez besoin d’aide, contactez votre administrateur ou administratrice AEM.

Consultez le [tableau de compatibilité détaillé](#compatibilitymatrix) à la fin de ce document pour évaluer les conditions préalables à la configuration.

## Nouveautés de l’appli de bureau v1.10 {#what-s-new-in-aem-desktop-app}

L’appli de bureau AEM 1.10 vise à améliorer l’expérience utilisateur en ce qui concerne les chargements volumineux, les informations relatives aux opérations en arrière-plan et une expérience optimisée lors de l’ouverture de ressources avec des fichiers liés (comme InDesign).

>[!NOTE]
>
>Si vous utilisez macOS 10.15.4 ou version ultérieure, utilisez au moins la version 1.10.0.6 de l’application. Cette version de correctif est conforme aux [exigences de certification d’Apple](https://developer.apple.com/news/?id=04102019a).

**Modification/extraction locale** : les chargements automatiques des modifications enregistrées dans les ressources peuvent être désactivés dans la fenêtre de statut. Ainsi, l’utilisateur ou l’utilisatrice peut continuer à travailler sur les fichiers et à enregistrer les modifications. Ensuite, lorsque tout est prêt, toutes les modifications peuvent être chargées.

**Fenêtre simplifiée de statut des ressources**. la fenêtre de statut a été simplifiée. L’onglet [!UICONTROL Uploads] affiche désormais à la fois les ressources individuelles et les téléchargements de dossiers ou massifs. L’onglet Chargements en bloc précédent a été supprimé.

**Icône d’application indiquant les chargements en bloc**. l’icône d’application affichera une incrustation « transfert » pour indiquer qu’un téléchargement massif est en cours.

**Notifications de conflits de mise à jour** : si l’application détecte un conflit en essayant de mettre à jour une ressource, elle affiche une notification, de sorte que l’utilisateur puisse examiner ce conflit sans avoir à surveiller la fenêtre de statut. Lorsque l’application démarre, elle recherche tous les conflits pour que l’utilisateur ou l’utilisatrice puisse les résoudre.

**Amélioration de la gestion des pertes de connexion**. les téléchargements massifs sont interrompus en cas de perte de connexion et l’utilisateur est en mesure de reprendre l’opération ultérieurement. Une option [!UICONTROL Retry] est disponible pour effectuer une nouvelle tentative en cas d’échec du téléchargement d’un fichier.

## Instructions d’installation {#installation-instructions}

Pour obtenir des instructions détaillées, voir [Installation et configuration de l’appli de bureau AEM](install-configure-app-v1.md).

## Améliorations effectuées dans les versions précédentes {#enhancements-in-the-previous-versions}

Cette version étend et remplace les versions précédentes de l’appli de bureau [!DNL Experience Manager], qui fournissaient les améliorations principales suivantes :

* **Version 1.9/1.9.1** : reprise des chargements interrompus, fenêtre de statut améliorée, icônes indiquant le statut de l’application/de la connexion et récupération anticipée des ressources liées pour les fichiers InDesign.

* **Version 1.8** : meilleur contrôle de la taille du cache pour l’utilisateur, expérience de connexion améliorée pour SAML/SSO sous Windows, prise en charge du proxy réseau .pac sous Mac et des problèmes signalés par les clients.

* **Version 1.7** : améliorations sur le plan de la stabilité et de la logique de mise en mémoire cache, meilleure prise en charge du proxy réseau et possibilité de nettoyer les fichiers internes après la désinstallation.

* **Version 1.6** : améliorations du processus de connexion pour différentes configurations de sécurité AEM, des performances et de la stabilité de l’application.

* **Version 1.5** : stabilité et résilience de l’application face aux différents problèmes de mise en réseau, amélioration de la capacité de prise en charge.

* **Version 1.4** : possibilité de charger des dossiers hiérarchiques en arrière-plan avec surveillance de la progression.

* **Version 1.3** : performances stables et améliorées lors de l’accès aux fichiers et de l’enregistrement des modifications dans AEM, en particulier à partir des applications de bureau Creative Cloud, telles que InDesign, Illustrator ou Photoshop. Cette version avait pour objectif d’offrir aux utilisateurs une expérience davantage similaire à celle d’un poste de travail local lorsqu’ils travaillaient avec des fichiers, tout en gérant simultanément les opérations de transfert de données réseau en arrière-plan.

### Améliorations disponibles depuis l’appli de bureau AEM 1.9 {#Enhancements-Available-Since-AEM-Desktop-App-19x}

L’appli de bureau [!DNL Adobe Experience Manager] version 1.9.1 était une version corrective qui corrigeait quelques problèmes majeurs rencontrés par les clients concernant l’extraction de ressources et la copie de fichiers d’un partage réseau vers un répertoire local.

* Les ressources extraites par un utilisateur ne doivent pas être accessibles à d’autres utilisateurs en vue de la modification (CQ-4246009).

* Prise en charge de la copie depuis un dossier mappé vers un dossier local lorsque le dossier utilisateur se trouve sur une partition de disque distincte (CQ-4243978).

L’appli de bureau AEM 1.9 mettait l’accent sur l’amélioration de l’expérience utilisateur en ce qui concerne les chargements volumineux, les informations relatives aux opérations en arrière-plan et une expérience optimisée lors de l’ouverture de ressources avec des fichiers liés (comme InDesign).

**Chargements pouvant reprendre**
Une option disponible dans la nouvelle fenêtre Asset Status (Statut de la ressource) permet de suspendre/relancer les chargements dans le cas de fichiers volumineux.

**Amélioration de la fenêtre de statut des ressources**
Une fenêtre de statut des ressources améliorée fournit les informations suivantes sur les ressources.

[!UICONTROL Changes]

* Affiche les modifications placées actuellement en file d’attente.

* Affiche les chargements en cours, y compris une barre de progression, la vitesse de transfert, la taille totale du fichier et la taille transférée jusqu’à présent.

* Chargements terminés affichés avec la taille totale transférée et le débit final.

* Les chargements ayant échoué sont accompagnés d’un message d’erreur et d’informations de transfert, le cas échéant.

* Les chargements ayant échoué à trois reprises affichent un message d’erreur.

* Fichiers en conflit indiqués par une icône sur lequel il est possible de cliquer. Cliquez sur l’icône pour afficher une boîte de dialogue contenant une explication et deux options :

   * [!UICONTROL Keep Mine] charge immédiatement le fichier sur le serveur.

   * [!UICONTROL Overwrite Mine] supprime immédiatement le fichier local et télécharge une nouvelle copie à partir du serveur.

[!UICONTROL Downloads]

* Affiche les téléchargements en cours, y compris la vitesse de transfert et la taille transférée jusqu’à présent.

* Téléchargements terminés affichés avec le volume transféré final, le débit final et une icône qui ouvre le fichier lorsque l’utilisateur clique sur celle-ci (disponible uniquement pour les fichiers uniques).

* Les téléchargements ayant échoué sont accompagnés d’un message d’erreur et d’informations sur le transfert, le cas échéant.

* Le pied de page affiche le nombre total de fichiers téléchargés, ainsi que la vitesse de transfert moyenne.

* Si un utilisateur choisit d’ouvrir ou de modifier plusieurs fichiers à partir de l’interface Web d’[!DNL Experience Manager Assets], ceux-ci seront regroupés. Par exemple, myasset.jpeg et 4 autres fichiers.

* Lorsque vous téléchargez des documents InDesign comprenant des ressources liées stockées dans AEM Assets, l’appli de bureau télécharge l’ensemble des ressources liées avant d’ouvrir le document [!UICONTROL Adobe InDesign] et d’indiquer le téléchargement des ressources liées. Par exemple, 5 sur 24.

[!UICONTROL Bulk Uploads]

Cette boîte de dialogue s’affiche lorsque vous chargez des hiérarchies de dossiers de grande taille par le biais de l’option [!UICONTROL Create] > [!UICONTROL Upload Folder] (Créer > Charger un dossier) dans l’interface utilisateur web AEM ou lorsque vous copiez et sélectionnez Paste Assets (Coller les ressources) dans le Finder ou l’Explorateur dans le menu contextuel de l’appli de bureau.

* Affiche les chargements en cours, y compris une barre de progression et le nom du fichier en cours de transfert.

* Les chargements en cours comprennent une icône qui annule le chargement lorsque l’utilisateur ou l’utilisatrice clique dessus. Le transfert s’arrêtera une fois le transfert du fichier en cours terminé.

* Les processus de transfert qui ont échoué sont affichés, accompagnés d’un message d’erreur (uniquement si tout le transfert échoue).

* Si le transfert d’un seul fichier échoue, il est affiché sur l’onglet sous la forme d’une erreur. Dans le cas contraire, les fichiers individuels ne sont pas affichés sur l’onglet ; une seule entrée est répertoriée pour l’ensemble du téléchargement.

**Icônes indiquant le statut des opérations en arrière-plan**

L’icône de l’application indique l’état des opérations en arrière-plan, afin de fournir un meilleur repère visuel aux utilisateurs et utilisatrices. Par exemple, lorsque l’application n’est pas connectée à AEM, l’icône est grisée. Lorsqu’un chargement est actif, une incrustation « sync » est affichée, etc.

**Prérécupération des ressources liées**

Pour améliorer l’expérience utilisateur lors de l’utilisation de documents InDesign contenant des ressources liées stockées dans AEM, l’appli de bureau tente d’effectuer une prérécupération de ces fichiers liés dans le cache local avant de télécharger et d’ouvrir le document InDesign. L’utilisateur dispose ainsi des fichiers liés en local et ne doit pas attendre longtemps pour y accéder dans InDesign (dans le panneau Links (Liens)).
Veuillez noter que la pré-récupération ne fonctionne que si AEM reconnaît les liens du côté serveur. Dans le cas d’une ressource contenant des liens reconnus, une liste de « Références » figure dans la vue Propriétés de la ressource InDesign.

### Améliorations disponibles depuis l’appli de bureau AEM 1.8.x {#enhancements-available-since-aem-desktop-app-18x}

L’appli de bureau AEM 1.8.1 s’accompagnait d’améliorations au niveau de l’ouverture simultanée de plusieurs fichiers à partir de l’interface utilisateur AEM vers la version 1.8 (CQ-4237747, CQ-4238780). Les améliorations apportées dans l’appli de bureau AEM 1.8 sont les suivantes :

* Mise en cache : nouvelle interface utilisateur pour gérer le cache de l’appli de bureau AEM (CQ-4208690), incluant les fonctionnalités suivantes :

   * Affichage de la taille actuelle du cache

   * Définition de la taille maximale du cache avant l’envoi d’une notification

   * La taille du cache est vérifiée uniquement au démarrage de l’appli de bureau, et une notification est envoyée si cette taille atteint la limite configurée

   * Le bouton « Effacer le cache » est désormais disponible dans la nouvelle interface utilisateur.

* Connexion : (Windows) connexion fixe à une instance AEM configurée pour utiliser SAML et SSL (CQ-4216353).

* Réseau :

   * lors de l’expiration d’une session AEM, l’utilisateur en est maintenant informé et peut cliquer sur la notification pour se reconnecter (CQ-4202028).

   * (Mac) Ajout d’une prise en charge pour se connecter à AEM à l’aide d’une configuration de proxy .pac (CQ-4233430).

   * (Windows) Résolution de problèmes relatifs à la boîte de dialogue Advanced > Login URL (Avancé > URL de connexion) (CQ-4236061).

* Correctifs :

   * Boîte de dialogue More Asset Info (Plus d’informations sur la ressource) : dans certains cas, la barre d’actions n’était pas visible (CQ-4208540).

   * (Windows) Le fichier peut maintenant être synchronisé après rétablissement d’une version antérieure à partir de l’interface utilisateur AEM Assets (CQ-4216411).

### Améliorations disponibles depuis l’appli de bureau AEM 1.7 {#Enhancements-Available-Since-AEM-Desktop-App-17}

* Stabilité :

   * stabilité améliorée lorsque l’appli de bureau AEM se connecte à un serveur AEM surchargé (CQ-4224803).

   * Stabilité améliorée lorsque de nombreux fichiers sont demandés (CQ-4224212).

   * Mise à jour des ressources améliorée avec vérification supplémentaire (CQ-4228291).

* Mise en cache :

   * Résolution des erreurs de disque et des problèmes d’ouverture de fichiers dans Photoshop, InDesign, Finder (CQ-4223993, CQ-4217603, CQ-4223717).

   * Mise en cache améliorée pour éviter les fichiers binaires de taille nulle (CQ-4216599).

* Connexion : autorisation de connexion avec l’option strictSSL désactivée pour les configurations spéciales (comme les certificats délivrés en local) (CQ-4223949).

* Mise en réseau : prise en charge améliorée pour une connexion sur un serveur proxy de réseau (CQ-4223477, CQ-4221280, CQ-4206854).

* Installation et désinstallation :

   * (Windows) Désinstallation de Cleaner (CQ-4220906).

   * [Windows 32 bits] Échec du programme d’installation lors de la tentative d’installation de Microsoft .NET Framework v.4.5 (CQ-4218084).

   * (Mac) Script manuel pour la suppression complète des fichiers de l’appli de bureau (CQ-4216489).

>[!NOTE]
>
>Problèmes détectés dans les chargements de l’appli de bureau AEM 1.7 bêta (les problèmes qui ne figuraient pas dans la version 1.6 ne sont pas repris dans les notes de mise à jour).

### Améliorations disponibles depuis l’appli de bureau AEM 1.6 {#Enhancements-Available-Since-AEM-Desktop-App-16}

* Documentation : nouvelles [Bonnes pratiques pour la documentation de l’application v1.x](/help/using/best-practices-for-v1.md).

* Amélioration du processus de connexion à AEM :

   * Amélioration de la prise en charge du format SAML * - assouplissement des règles (CQ-4202781).

   * Ajout de la possibilité de configurer une URL de connexion distincte dans les préférences (CQ-4214052, CQ-4214051).

* Convivialité : notification de l’utilisateur lorsqu’une ressource est toujours en cours de téléchargement pour les ressources volumineuses (CQ-4216284).

* Mise en réseau :

   * Mise en cache DNS (CQ-4210176).

   * Prise en charge de la connexion via un proxy sous Windows (CQ-4206854).

* Mise en cache et accès au partage de réseau dans le Finder/l’Explorateur :

   * Icône de verrouillage désormais visible pour les ressources extraites sous Windows 10 (CQ-90957).

   * Le contenu du dossier peut disparaître/réapparaître dans le partage réseau (CQ-4209160, CQ-4210180).

   * Erreur lors du chargement d’un fichier, en raison d’un conflit signalé dans le statut de la file d’attente des chargements (CQ-4215727).

   * Lors de l’ouverture de plusieurs fichiers à partir du dossier de l’appli de bureau dans PS, des fichiers tronqués ou des messages incomplets peuvent s’afficher (CQ-4216276).

* Correctifs en matière de stabilité et de performances :

   * Amélioration des performances lors de la navigation dans des dossiers comportant de nombreuses ressources (CQ-4214933).

   * L’appli de bureau version 1.5 peut ralentir l’ordinateur de bureau au fil du temps (CQ-4209159).

   * L’affichage du statut de la file d’attente fonctionne uniquement pour l’utilisateur qui a installé l’application (CQ-4212199).

   * (Windows) Assurez-vous que le programme d’installation 32 bits ne contient pas de code 64 bits (CQ-4217406).

* Problèmes sélectionnés identifiés et résolus dans la version bêta 1.6 :

   * Utilisation intensive du processeur (CQ-4218070).

   * Faire glisser et déposer des fichiers génère une erreur lors du chargement vers AEM (CQ-4217006).

### Améliorations disponibles depuis l’appli de bureau AEM 1.5 {#Enhancements-Available-Since-AEM-Desktop-App-15}

**Version 1.5.1.5 pour Mac OS X :** La version 1.5.1.5 offre les avantages suivants :

* Nouvelles fonctionnalités et améliorations : ajout de la fonctionnalité Copier/coller à l’intégration du Finder pour permettre le transfert direct à partir du bureau vers AEM (CQ-4208158).

* Corrections de bogues :

   * Correction d’un problème d’erreur 43 qui se produisait parfois lors du changement de nom d’une ressource (CQ-4207900).

   * La restauration d’une ancienne version depuis la chronologie dans AEM ne met pas à jour la ressource dans le Finder (CQ-4205194).

   * L’appli de bureau se bloque lors de la navigation dans des répertoires imbriqués volumineux (CQ-4208539).

   * Le point de montage de l’appli de bureau est désormais /Volumes/DAM, et est donc cohérent pour tous les utilisateurs (CQ-4208159).

   * Le placement d’un fichier dans InDesign pour la première fois déclenche un avertissement de mise à jour (CQ-4207454).

Remarque concernant les avertissements relatifs aux liens : les applications Creative Cloud (par exemple, InDesign) prennent un « instantané » de la date et de l’heure de la dernière modification de l’élément au moment où il est placé. Si cette date et cette heure changent ultérieurement, l’application Adobe Creative Cloud signale que les liens sont obsolètes. Ce signalement revêt plusieurs formes :

* À son lancement, l’application Adobe Creative Cloud affiche une boîte de dialogue informant l’utilisateur que les ressources liées sont obsolètes et invite l’utilisateur à prendre des mesures.

* Si l’application Adobe Creative Cloud est déjà en cours d’exécution, une icône d’avertissement en forme de triangle jaune apparaît sur la ressource liée.

Ce comportement est identique pour les ressources du disque local et celles du répertoire monté de l’appli de bureau AEM, avec les exceptions suivantes :

* Si une ressource placée est modifiée par une autre personne, une icône d’avertissement s’affiche la première fois que d’autres personnes ouvrent un document contenant la ressource placée. Cela se produira uniquement si la ressource importée a déjà été mise en cache localement.

* Si un utilisateur modifie une ressource importée par l’intermédiaire du répertoire monté de l’appli de bureau AEM, puis efface le cache local, la ressource est signalée comme obsolète.

Ces deux cas sont attendus et sont des répercussions secondaires de l’architecture « synchronisation différée » de l’appli de bureau AEM.

**Version 1.5.0.x pour Mac OS X et Windows** : cette version de l’appli de bureau AEM offre les avantages suivants :

* Amélioration de la stabilité et de la résilience face aux problèmes de réseau.

   * Mappage plus stable des dossiers AEM Assets (CQ-103276, CQ-4204669, CQ-4203957).

   * Amélioration de la gestion des fichiers en mémoire cache (CQ-4204336, CQ-4206263).

   * Amélioration de la gestion du téléchargement/chargement de fichiers volumineux de plus de 2 Go (CQ-4206438).

   * Correction d’une « Erreur 36 » lors du déplacement ou du changement de nom d’un plus grand nombre de fichiers dans le Finder (CQ-4204640).

* Optimisations de la communication réseau avec le serveur AEM (CQ-4204974, CQ-100903).

* Plus grande fiabilité de l’ouverture, du placement et de l’enregistrement des ressources AEM dans les applications Creative Cloud (CQ-4203968, CQ-4205511, CQ-103543, CQ-4207141, CQ-90980).

* Amélioration de la capacité de prise en charge : option pour effacer le cache (CQ-4202541), accès facile aux journaux (CQ-4202340, CQ-4204673).

* Autres correctifs :
   * Amélioration de la prise en charge des ressources et des dossiers comportant des caractères japonais dans les paramètres de nom/langue autres que l’anglais (CQ-4195433, CQ-4205793, CQ-4199446).

   * Amélioration de la gestion de la connexion avec SSL (CQ-4200217).

   * Amélioration de la fiabilité du montage de partage (CQ-4200793).

   * Diverses améliorations de la stabilité (CQ-4207539, CQ-4200378).

   * Amélioration de la gestion de l’URL d’AEM Assets dans les préférences (CQ-97388).

### Améliorations disponibles depuis l’appli de bureau AEM 1.4 {#Enhancements-Available-Since-AEM-Desktop-App-14}

* Simplification du chargement des dossiers hiérarchiques par l’intermédiaire de la nouvelle opération Create > Upload Folder (Créer > Charger un dossier) de l’interface utilisateur tactile.
   * L’action lance un chargement de dossier effectué par l’appli de bureau
   * L’appli de bureau traverse la hiérarchie de dossiers donnée sur le bureau en arrière-plan et charge les fichiers dans AEM Assets.
   * La personne peut surveiller la progression dans la nouvelle fenêtre Statut de la file d’attente des chargements, grâce à une barre de progression pour les opérations en cours.
   * Le statut de la file d’attente des chargements fournit également des informations de résolution de problème (par exemple, aucune connexion au serveur)
* Nouvelle action Modifier de l’interface utilisateur tactile qui combine les opérations Extraction et Ouverture en une seule.
* Regroupement optimisé des actions liées à l’application de bureau dans l’interface utilisateur tactile (AEM 6.3).
* Amélioration de la compatibilité avec les dernières versions du système d’exploitation
* Correctifs signalés par les clients et ls clientes

### Améliorations disponibles depuis l’appli de bureau AEM 1.3 {#Enhancements-Available-Since-AEM-Desktop-App-13}

* Efficacité accrue Les personnes passent moins de temps à attendre la fin des opérations réseau.
* Amélioration de l’intégration du Finder, qui offre une amélioration de la stabilité et un accès aux fonctionnalités telles que les miniatures.
* Améliorations de la mise en cache et des performances.
* Amélioration de la prise en charge de l’enregistrement directement depuis les applications de bureau (PS, ID, AI, etc.).
* Amélioration de l’intégration avec Mac OS (le protocole du lecteur réseau local est passé de WebDAV à SMB1, plus stable).
* L’appli de bureau se connecte au serveur AEM à l’aide du protocole HTTP RESTful natif d’AEM.
* Les fichiers sont d’abord enregistrés localement, puis rechargés en arrière-plan vers AEM après une durée prédéfinie (30 secondes). Cela réduit le temps d’enregistrement des fichiers.
* Amélioration de la gestion des applications de bureau qui utilisent des opérations de fichiers intermédiaires pour enregistrer un fichier (enregistrements partiels et fichiers temporaires), ce qui permet à la chronologie des ressources AEM d’afficher les informations correctes sur la version et le chargement des ressources.
* Boîte de dialogue permettant d’effectuer le suivi du statut des tâches de chargement en arrière-plan.

## Liste des modifications {#list-of-changes}

### Point de montage sous Mac {#mount-point-on-mac}

Depuis MacOS 10.12 (Sierra), Apple a modifié les autorisations du dossier /Volumes utilisé pour monter les lecteurs et appareils réseau de manière plus restrictive. La création d’un nouveau point de montage nécessitait des droits d’administration. Ce problème a été corrigé dans MacOS 10.12.5.

Comme l’appli de bureau AEM doit fonctionner pour les utilisateurs ne disposant pas de droits d’administration pour l’ordinateur local, le point de montage du référentiel AEM Assets a été remplacé dans les versions 1.4 et 1.5 par un sous-dossier DAM du dossier local de l’utilisateur sous MacOS (CQ-104183).

Comme le dossier /Volumes ne nécessite plus de droits d’administration, cette modification a été annulée dans la version 1.5.1. Cela permet également aux utilisateurs de MacOS de partager des documents InDesign disposant de ressources AEM importées.

### Modification de protocoles (depuis la version 1.3) {#protocol-change-since}

* Mac OS X :
   * Le protocole du lecteur réseau local pour l’intégration de bureau OS X a été remplacé par SMB1, à la place de WebDAV.
   * Le référentiel AEM monté avec l’appli de bureau sera visible sous la forme d’un lecteur réseau « smb » dans le Finder, au lieu d’un lecteur WebDAV.
* Windows :
   * Le protocole de lecteur réseau local pour les intégrations de bureau Windows reste le même ; AEM est monté en tant que partage WebDAV.
* Pour les deux plateformes (Windows et Mac) :
   * Le protocole permettant d’accéder/de télécharger des ressources et de charger des modifications dans AEM a été remplacé par le protocole natif d’AEM, qui est un protocole RESTful basé sur HTTP. Il offre un meilleur contrôle sur les opérations réseau et est davantage compatible avec l’infrastructure réseau.

>[!NOTE]
>
>Sous Mac OS X, le passage du protocole de lecteur réseau local de WebDAV à SMB1 résulte en un chemin d’accès local différent vers la même ressource du référentiel. Cela peut avoir un impact sur les liens vers les fichiers placés dans les applications Adobe Creative Cloud via la commande « Place » (Placer). Pour plus d’informations, reportez-vous à [Utilisation de l’appli de bureau AEM](use-app-v1.md).

### Gestion des fichiers (depuis la version 1.3) {#file-handling-since}

* Les fichiers sont automatiquement mis à jour après une période prédéfinie (actuellement, 30 s).
* Les fichiers extraits par d’autres utilisateurs sont marqués comme étant en lecture seule.
* Les fichiers sont enregistrés en deux phases dans un emplacement de lecteur réseau monté par l’intermédiaire de l’appli de bureau.
* Dans la première phase, un fichier est enregistré localement. Ainsi, la personne enregistrant le fichier n’a pas besoin d’attendre que ce dernier soit entièrement transféré vers AEM et peut reprendre le travail dès que le fichier est enregistré.
* Dans la seconde phase, l’appli de bureau charge le fichier mis à jour vers le serveur AEM après une période prédéfinie (par exemple, 30 s). Cette opération s’effectue en arrière-plan. Utilisez l’option **Show Background File Sync Status** (Afficher le statut de synchronisation du fichier en arrière-plan) pour afficher le statut de l’opération de chargement.

## Remarques importantes {#important-notices}

**Chargement des dossiers :** Il est recommandé d’utiliser la nouvelle fonctionnalité de chargement de dossiers pour charger des dossiers hiérarchiques plus volumineux dans AEM, plutôt que d’utiliser une opération de copie/glisser-déposer dans un référentiel AEM monté à partir du Finder/de l’Explorateur. Lors de l’utilisation de la fonctionnalité de chargement de dossiers, l’appli de bureau communique directement avec AEM et dispose ainsi d’un meilleur contrôle sur l’ensemble du processus.

**Maintenir la session AEM disponible :** L’appli de bureau AEM dépend d’une session ouverte sur le serveur AEM Assets pour garantir son bon fonctionnement. Il est recommandé aux utilisateurs travaillant quotidiennement avec l’appli de bureau de démonter AEM Assets à la fin de leur journée pour forcer la déconnexion, puis de « monter AEM Assets » le matin pour s’assurer qu’ils sont connectés et que le partage réseau est opérationnel.

**Désactiver l’option « Aperçu de l’icône » dans le Finder :** Pour une navigation performante dans les dossiers volumineux avec le Finder, en particulier avec une mauvaise connectivité réseau, assurez-vous que les options Icône et Aperçu de l’icône sont désactivées. Sinon, le Finder commence à télécharger chaque ressource dans un dossier afin de générer un petit aperçu, ce qui peut entraîner des performances médiocres et une utilisation élevée de la bande passante (CQ-4219779).

* Dans le Finder, accédez au dossier réseau partagé AEM Assets.
* Effectuez un clic droit sur le point de montage DAM.
* Sélectionnez Afficher les options d’affichage.
* Désélectionnez Afficher l’aperçu de l’icône.
* Cliquez sur Utiliser comme valeurs par défaut.

**Nettoyer le cache lors de la connexion à un nouveau serveur AEM :** Si l’appli de bureau se connecte à un autre serveur AEM doté de la même URL, le cache n’est pas effacé automatiquement. Effacez manuellement le cache pour garantir des opérations correctes. Notez que cela se produit généralement lors du test, lorsque les installations AEM peuvent être remplacées lors de l’exécution sur la même URL (CQ-4216982).

**Utiliser des certificats SSL signés par une autorité de certification :** Veuillez noter que l’appli de bureau AEM ne prend pas en charge les certificats SSL auto-signés lors de la connexion à AEM via une connexion sécurisée HTTPS. Un certificat signé par une autorité de certification est requis sur le serveur pour ce type de connexion (CQ-87941).

## Problèmes connus {#known-issues}

* Général :
   * Les URL du serveur sont requises pour pointer vers le serveur sans chemin d’accès (par exemple, `http://server`, `https://server`, `http://server:port` ou `https://server:port`). Les chemins d’accès au contexte et les sous-dossiers de contexte autres que /content/dam ne sont pas pris en charge (CQ-89343, CQ-87272).
* Noms de fichiers/localisation :
   * Les noms de fichiers et de dossiers comportant des caractères réservés ne sont pas gérés correctement. Veillez à utiliser les noms de fichiers et de dossiers qui correspondent aux exigences d’AEM (CQ-93361, CQ-93308, CQ-89276, CQ-4217183).
   * Certaines applications telles que Adobe Illustrator peuvent créer des fichiers dont les noms ne sont pas pris en charge dans AEM. Par exemple, ajouter `Converted` après la conversion d’un fichier empêche son chargement (CQ-4216985).
   * Les ressources avec des noms internationaux peuvent apparaître et disparaître toutes les quelques secondes.
* Archivage et extraction :
   * Une ressource extraite par un utilisateur ne peut pas être ouverte pour un autre utilisateur, que ce soit par l’option Open (Ouvrir) de l’interface utilisateur tactile ou directement sur le bureau. Certaines applications peuvent la signaler comme verrouillée, mais aussi corrompue ou même bloquée lors d’une tentative d’ouverture. (CQ-4199234).
   * La modification simultanée de fichiers par plusieurs utilisateurs peut entraîner la perte de certaines modifications. La solution consiste à utiliser la fonctionnalité  d’archivage/d’extraction pour empêcher plusieurs utilisateurs de modifier le même fichier (CQ-97035).
   * Certaines applications ne prennent pas correctement en charge l’indicateur en lecture seule qui permet d’enregistrer un fichier extrait par une autre personne. Le fichier modifié n’est pas transféré tant que l’autre personne n’a pas archivé le fichier. Les deux modifications sont disponibles dans AEM sous la forme de versions différentes de la ressource (CQ-89551, CQ-87572, CQ-89615).
   * Les états « extrait » et « en lecture seule » sont signalés indépendamment dans le Finder. Il s’affiche ainsi 2 icônes de verrouillage lorsqu’une personne extrait une ressource (CQ-89507).
* Intégration du Finder :
   * Lorsque vous effectuer un glisser/déplacer de fichiers volumineux, le Finder peut expirer pendant le transfert des fichiers en arrière-plan. Cela provoque une `Error - 36`. La solution consiste à faire un glisser/déposer ou à ouvrir de nouveau la ressource (CQ-4219628).
   * Le rechargement manuel de dossier ne fonctionne pas toujours. Solution : patientez 30 secondes pour que le dossier soit automatiquement mis à jour (CQ-97389).
   * L’option More Asset Info... (Plus d’informations sur la ressource...) est limitée aux sélections de fichiers uniques (CQ-89542, CQ-87656).
   * L’option Ouvrir dans AEM Assets... est limitée aux sélections de fichiers et de dossiers uniques (CQ-83382).
   * Erreur lors du changement de nom des ressources sans extension (CQ-4218971)
* Fonctionnalité Copier/coller : la fonctionnalité Coller est disponible lorsqu’aucune ressource n’a été copiée dans le presse-papiers.
* Windows :
   * Les fichiers avec des flux de données alternatifs (ADS, Alternate Data Streams) ne sont entièrement pris en charge que par NTFS. Si vous copiez ces fichiers sur le partage WebDAV fourni par l’appli de bureau, une boîte de dialogue d’avertissement indique à l’utilisateur que le fichier contient des propriétés ne pouvant pas être copiées vers le nouvel emplacement. Cela ne pose généralement pas problème puisque les propriétés ne sont pertinentes que pour une application spécifique du bureau de l’utilisateur et n’ont rien à voir avec le contenu réel du fichier (CQ-103770) (Windows).
   * L’appli de bureau sous Windows doit être installée par l’utilisateur qui l’utilise (CQ-4216389) (Windows).
   * L’appli peut se bloquer, dans certains cas, lorsque vous sélectionnez l’option [!UICONTROL Retry] pour un chargement qui a échoué, suite à la reprise d’un chargement par lots alors qu’aucune connexion n’est établie, par exemple (CQ-4251884) (Windows).

## Ressources utiles {#helpful-resources}

* [Documentation AEM](https://experienceleague.adobe.com/docs/?lang=fr)
* [Utilisation de l’appli de bureau AEM v1.x](use-app-v1.md)
* [Bonnes pratiques relatives à l’appli de bureau AEM v1.x](best-practices-for-v1.md)

## Tableau de compatibilité et conditions préalables {#compatibilitymatrix}

L’appli de bureau AEM fonctionne avec différentes versions d’AEM. Voir le tableau de compatibilité pour connaître les versions prises en charge.

| Version | Révision | Date de publication | Compatibilité |
|--- |--- |--- |--- |
| 1.10 | 1.10.0.3 (Mac et Windows) | 31 août 2018 | AEM 6.5 ; AEM 6.4 SP1 ; AEM 6.3 SP2 ; AEM 6.2 SP1 CFP2+ ; AEM 6.1 SP2 CFP7+ |
| 1.9 | 1.9.1.1 (Mac et Windows) | 21 juin 2018 | AEM 6.4 ; AEM 6.3 SP1 ; AEM 6.2 SP1 CFP2+ ; AEM 6.1 SP2 CFP7+ |
| 1.8 | 1.8.1.0 (Mac et Windows) | 28 mars 2018 | AEM 6.4 ; AEM 6.3 SP1 ; AEM 6.2 SP1 CFP2+ ; AEM 6.1 SP2 CFP7+ |
| 1.7 | 1.7.0.3 (Mac et Windows) | Jan 10, 2018 | AEM 6.3 SP1 ; AEM 6.2 SP1 CFP2+ ; AEM 6.1 SP2 CFP7+ |
