- [Mémo Defold](#m-mo-defold)
  * [Introduction](#introduction)
  * [Télécharger et installer Defold](#t-l-charger-et-installer-defold)
  * [Mettre à jour Defold](#mettre---jour-defold)
  * [Création et ouverture de projets](#cr-ation-et-ouverture-de-projets)
    + [Home](#home)
    + [New Project](#new-project)
      - [From Template](#from-template)
      - [From Tutorial](#from-tutorial)
      - [From Sample](#from-sample)
    + [Import Project](#import-project)
  * [Editeur](#editeur)
    + [Vue Assets](#vue-assets)
    + [Vue Changed Files](#vue-changed-files)
    + [Vue Outline](#vue-outline)
    + [Vue Properties](#vue-properties)
    + [Vue Console, Curve Editor, Build Errors, Search Results](#vue-console--curve-editor--build-errors--search-results)
    + [Vue Editor](#vue-editor)
      - [Editeur de collection et de ressources](#editeur-de-collection-et-de-ressources)
      - [Editeur de code](#editeur-de-code)
      - [Editeur de configuration du projet](#editeur-de-configuration-du-projet)
        * [Liste des paramètres](#liste-des-param-tres)
  * [Menus](#menus)
    + [Menu `File`](#menu--file-)
      - [Boîte de dialogue `Preferences`](#bo-te-de-dialogue--preferences-)
    + [Menu `Edit`](#menu--edit-)
    + [Menu `View`](#menu--view-)
    + [Menu `Project`](#menu--project-)
    + [Menu `Debug`](#menu--debug-)
    + [Menu `Help`](#menu--help-)
  * [Etapes dans la création d'un projet](#etapes-dans-la-cr-ation-d-un-projet)
  * [Importer les ressources externes](#importer-les-ressources-externes)
    + [Importer des images](#importer-des-images)
      - [Gérer des images individuelles](#g-rer-des-images-individuelles)
      - [Gérer des tilesheet ou spritesheet](#g-rer-des-tilesheet-ou-spritesheet)
    + [Importer des modèles Spine](#importer-des-mod-les-spine)
    + [Importer des sons et des musiques](#importer-des-sons-et-des-musiques)
    + [Importer des polices de caractères](#importer-des-polices-de-caract-res)
    + [Importer des modèles 3D](#importer-des-mod-les-3d)
  * [Structure du jeu](#structure-du-jeu)
  * [Fichiers ressources](#fichiers-ressources)
    + [Propriétés communes aux components](#propri-t-s-communes-aux-components)
    + [Animation Set](#animation-set)
      - [Ajouter une animation à un animation set](#ajouter-une-animation---un-animation-set)
      - [Supprimer une animation à un animation set](#supprimer-une-animation---un-animation-set)
    + [Atlas](#atlas)
      - [Ajouter des images à un atlas](#ajouter-des-images---un-atlas)
      - [Créer un groupe d'animation](#cr-er-un-groupe-d-animation)
        * [Ajouter des images à un groupe d'animation](#ajouter-des-images---un-groupe-d-animation)
    + [Camera](#camera)
      - [Créer un fichier ressource Camera](#cr-er-un-fichier-ressource-camera)
      - [Plans de caméra](#plans-de-cam-ra)
      - [Champ de vue de caméra](#champ-de-vue-de-cam-ra)
      - [Créer une caméra](#cr-er-une-cam-ra)
      - [Propriétés de caméra](#propri-t-s-de-cam-ra)
      - [Camera speed distance](#camera-speed-distance)
      - [Rotated camera](#rotated-camera)
      - [Orthographic projection](#orthographic-projection)
    + [Collection](#collection)
      - [Créer une collection](#cr-er-une-collection)
      - [Attacher un game object en place à une collection](#attacher-un-game-object-en-place---une-collection)
      - [Attacher un fichier ressource game object à une collection](#attacher-un-fichier-ressource-game-object---une-collection)
    + [Collection Factory](#collection-factory)
      - [Créer un fichier ressource Collection Factory](#cr-er-un-fichier-ressource-collection-factory)
      - [Propriétés de Collection Factory](#propri-t-s-de-collection-factory)
    + [Collection Proxy](#collection-proxy)
      - [Créer un fichier ressource Collection Proxy](#cr-er-un-fichier-ressource-collection-proxy)
      - [Propriétés de Collection Proxy](#propri-t-s-de-collection-proxy)
    + [Collision Object](#collision-object)
      - [Créer un fichier ressource Collision Object](#cr-er-un-fichier-ressource-collision-object)
      - [Propriétés des collision objects](#propri-t-s-des-collision-objects)
      - [Ajouter des ressources Shapes au collision object](#ajouter-des-ressources-shapes-au-collision-object)
    + [Cubemap](#cubemap)
    + [Display Profiles](#display-profiles)
    + [Factory](#factory)
      - [Créer un fichier ressource Factory](#cr-er-un-fichier-ressource-factory)
      - [Propriétés de Factory](#propri-t-s-de-factory)
    + [Font](#font)
    + [Fragment Program](#fragment-program)
    + [Game Object](#game-object)
      - [Créer un game object en place](#cr-er-un-game-object-en-place)
      - [Créer un fichier ressource Game Object](#cr-er-un-fichier-ressource-game-object)
      - [Attacher un component à un game object](#attacher-un-component---un-game-object)
    + [Gamepads](#gamepads)
    + [Gui](#gui)
    + [Gui Script](#gui-script)
    + [Input Binding](#input-binding)
    + [Label](#label)
      - [Créer un fichier ressource Label](#cr-er-un-fichier-ressource-label)
      - [Propriétés de Label](#propri-t-s-de-label)
    + [Lua Module](#lua-module)
    + [Material](#material)
    + [Model](#model)
      - [Créer un fichier ressource Model](#cr-er-un-fichier-ressource-model)
      - [Propriétés de Model](#propri-t-s-de-model)
    + [Particle FX](#particle-fx)
    + [Render](#render)
    + [Render Script](#render-script)
    + [Script](#script)
      - [Créer un fichier ressource Script](#cr-er-un-fichier-ressource-script)
    + [Sound](#sound)
      - [Créer un fichier ressource Sound](#cr-er-un-fichier-ressource-sound)
      - [Propriétés de Sound](#propri-t-s-de-sound)
    + [Spine Model](#spine-model)
      - [Créer un fichier ressource Spine Model](#cr-er-un-fichier-ressource-spine-model)
      - [Propriétés de Spine Model](#propri-t-s-de-spine-model)
    + [Spine Scene](#spine-scene)
    + [Sprite](#sprite)
      - [Créer un fichier ressource Sprite](#cr-er-un-fichier-ressource-sprite)
      - [Propriétés de Sprite](#propri-t-s-de-sprite)
    + [Texture Profiles](#texture-profiles)
    + [Tile Map](#tile-map)
    + [Tile Source](#tile-source)
      - [Créer une tile source](#cr-er-une-tile-source)
      - [Attacher un fichier ressource image à une tile source](#attacher-un-fichier-ressource-image---une-tile-source)
      - [Propriétés d'une tile source](#propri-t-s-d-une-tile-source)
      - [Définir des animations de tile source](#d-finir-des-animations-de-tile-source)
        * [Propriétés d'animations de tile source](#propri-t-s-d-animations-de-tile-source)
    + [Vertex Program](#vertex-program)
  * [Programmation](#programmation)
    + [Portée des variables](#port-e-des-variables)
    + [Définir une propriété visible dans la vue Properties](#d-finir-une-propri-t--visible-dans-la-vue-properties)
    + [Adressage](#adressage)
      - [Envoyer un message](#envoyer-un-message)
    + [Créer un game object depuis un script](#cr-er-un-game-object-depuis-un-script)
  * [Astuces diverses](#astuces-diverses)
    + [Définir la collection principale](#d-finir-la-collection-principale)
    + [Définir les dimensions logiques du jeu](#d-finir-les-dimensions-logiques-du-jeu)
    + [Afficher une image](#afficher-une-image)
    + [Afficher des images en pixel art](#afficher-des-images-en-pixel-art)
    + [Quitter le jeu avec la touche Echap](#quitter-le-jeu-avec-la-touche-echap)
    + [Tester une modification de script sans redémarrer le jeu](#tester-une-modification-de-script-sans-red-marrer-le-jeu)
    + [Détruire un game object depuis un script](#d-truire-un-game-object-depuis-un-script)
      - [Paramétrer les valeurs de configuration au démarrage du moteur](#param-trer-les-valeurs-de-configuration-au-d-marrage-du-moteur)

# Mémo Defold

*par flashjaysan*

Licence Creative Commons : Cette œuvre est mise à disposition selon les termes de la Licence Creative Commons Attribution - Pas d’Utilisation Commerciale 4.0 Internationale.

![Creative Commons Non Commercial logo](ccnc.png)

## Introduction

*Defold* est un logiciel pour créer des jeux vidéos. Il est gratuit mais non open source. La société *King* (*Candy Crush*) utilise ce moteur pour créer ses jeux et le fournit au public gratuitement et sans licence ni contrepartie. Les jeux créés avec *Defold* sont programmés en *Lua*, un langage de script facile à apprendre et puissant. Vous pouvez exporter vos jeux sur les plateformes *Windows*, *Mac OS X*, *Linux*, *Android*, *iOS* et *HTML*. Vous pouvez stocker vos projets sur le cloud dédié de *Defold* (ou un cloud compatible avec *Git*) et les partager avec d'autres membres de votre équipe ou, si vous préférez, sur votre propre ordinateur.

**Attention !** *Defold* nécessite de posséder un compte *Google* et vous devrez être connecté à *Internet* pour créer vos premiers projets (basés sur des modèles en ligne).

## Télécharger et installer Defold

Visitez le site de [Defold](https://www.defold.com/) et cliquez sur la section `Get Defold` :

![Get Defold link](defold_get.png)

Pour télécharger *Defold*, vous devez vous identifier avec un compte *Google* :

![Google login](defold_google.png)

Une fois connecté, cliquez sur la section `Dashboard` :

![Defold dashboard](defold_dashboard.png)

Téléchargez la dernière version de *Defold* correspondante à votre système en cliquant sur le bouton `Download editor` :

![Defold download](defold_download.png)

- Sur *Windows*, décompressez l'intégralité du contenu du fichier téléchargé à l'emplacement de votre choix puis exécutez le fichier `Defold.exe`.
- Sur *Mac OS X*, montez le fichier téléchargé et faites glisser l'application `Defold` dans le dossier `Applications` puis lancez-la.
- Sur *Linux*, décompressez l'intégralité du contenu du fichier téléchargé à l'emplacement de votre choix puis exécutez le fichier `./Defold`.

## Mettre à jour Defold

Au démarrage de *Defold*, si une nouvelle version est disponible, le texte `Update Available` apparaît :

![Update Available](defold_update.png)

Cliquez dessus pour afficher la boîte de dialogue `Update Available` :

![Update Available dialog](defold_update_dialog.png)

Cliquez alors sur le bouton `Download` pour télécharger et mettre à jour *Defold* ou sur le bouton `Not Now` pour annuler la procédure.

Si vous effectuez une mise à jour de *Defold*, une barre de chargement apparaît pour indiquer l'état d'avancement du téléchargement :

![update progress bar](defold_update_progress.png)

**Attention !** Le téléchargement d'une mise à jour est assez long.

**Remarque :** Vous pouvez continuer à utiliser *Defold* pendant le téléchargement de la mise à jour. Une barre de progression apparaît en bas de l'éditeur :
 
![update progress bar in editor](defold_update_progress2.png)

Lorsque le téléchargement est terminé, le texte `Restart to Update` s'affiche :

![Restart to Update](defold_update_restart.png)

Cliquez dessus pour afficher la boîte de dialogue `Please Confirm` :

![Restart to Update dialog](defold_update_restart_dialog.png)

Cliquez alors sur le bouton `OK` pour redémarrer *Defold* et installer la mise à jour automatiquement ou sur le bouton `Cancel` pour annuler la procédure.

## Création et ouverture de projets

Lorsque vous démarrez *Defold*, l'écran de création et de sélection de projet s'affiche :

![Defold startup](defold_start.png)

Sur la gauche, il y a trois options :
- Home (par défaut)
- New Project
- Import Project

### Home 

Si vous venez d'installer *Defold*, cette section est vide (voir image précédente). Cliquez sur le texte `Create New Project` pour créer un nouveau projet. La section `New Project` (voir section suivante) s'affiche alors. Par la suite, la section `Home` affichera la liste de vos projets déjà ouverts dans *Defold* et stockés sur votre ordinateur. Sélectionnez alors un des projets de la liste puis cliquez sur le bouton `Open Selected` pour ouvrir le projet dans l'éditeur.

![Recent Projects](defold_recent_projects.png)

Le bouton `Open From Disk…` présent dans les deux cas de figure vous permet d'ouvrir un projet *Defold* situé sur votre ordinateur. Une boîte de dialogue s'ouvre alors et vous demande de sélectionner un fichier `game.project` associé à un projet.

### New Project

Cette section sert à créer de nouveaux projets.

![New Project](defold_new_project.png)

**Attention !** Vous devez obligatoirement être connecté à *Internet* pour créer un nouveau projet car *Defold* se base sur des modèles stockés en ligne. 

Cliquez sur l'un des trois onglets :
- From Template (par défaut)
- From Tutorial
- From Sample

**Conseil :** Si vous voulez créer un nouveau projet sans connexion *Internet*, créez des modèles de projets lorsque vous êtes connecté et sauvegardez-les sur votre ordinateur. Vous n'aurez plus qu'à les copier et à ouvrir ces copies de projets dans *Defold*.

**Remarque :** N'oubliez pas de choisir un nom de projet et de définir son emplacement sur votre ordinateur en bas de la fenêtre de *Defold*.

#### From Template

Cette option crée un nouveau projet à partir de modèles pré-existants (voir image précédente). Cliquez sur l'une des options proposées :
- **Empty project :** Cette option crée un projet vide générique. Vous devez tout paramétrer vous-même.
- **Mobile game :** Cette option crée un projet adapté aux smartphones ou aux tablettes.
- **Desktop game :** Cette option crée un projet adapté aux ordinateurs classiques.
- **Basic 3D project :** Cette option crée un projet en 3D.

#### From Tutorial

Cette option crée un projet destiné à apprendre à utiliser *Defold*. Chaque projet vous apprend une technique différente. Choisissez un des projets proposés et suivez les instructions (en anglais) contenues dans le fichier `README.md` situé dans la vue `Assets` (voir section **Editeur** plus loin).

![New Project From Tutorial](defold_new_project_from_tutorial.png)

#### From Sample

Cette option crée un projet à partir de projets exemples divers. Choisissez un des projets proposés et examinez les différents éléments les constituants pour étudier leur structure.

![New Project From Sample](defold_new_project_from_sample.png)

**Remarque :** N'oubliez pas de choisir un nom de projet et de définir son emplacement sur votre ordinateur en bas de la fenêtre de *Defold*.

### Import Project

Cette section est utilisée pour importer un de vos projets stockés en ligne (par défaut sur le cloud de *Defold* mais vous pouvez paramétrer un autre cloud *Git*). Ces projets peuvent être partagés avec d'autres personnes.

![Import Project](defold_import_project.png)

**Attention !** Vous devez vous connecter à *Defold* avec votre compte *Google* pour utiliser cette option. Celle-ci vous permet de télécharger un des projets stockés en ligne et de travailler localement dessus. C'est utile si vous travaillez à plusieurs sur le projet ou si vous utilisez plusieurs machines pour développer votre jeu. Cliquez sur le bouton `Sign in with Google` pour vous connecter ou sur le texte `Create Account` pour créer un nouveau compte. Une fois connecté, *Defold* affiche la liste des projets stockés en ligne. Sélectionnez alors un des projets de la liste puis cliquez sur le bouton `Import Project` pour télécharger et ouvrir le projet dans l'éditeur.

![Import Project connected](defold_import_project_connected.png)

**Remarque :** N'oubliez pas de choisir un emplacement sur votre ordinateur en bas de la fenêtre de *Defold*.

## Editeur

Une fois un projet ouvert, vous vous retrouvez devant la fenêtre de l'éditeur. Elle se compose de nombreuses sections :

![Defold editor tour](defold_full_editor.png)

### Vue Assets

Cette vue liste les fichiers ressources importés, les collections et les fichiers ressources créés dans *Defold* et utilisés dans votre projet.

![Assets panel](defold_assets_panel.png)

  - Par un clic droit, créez des dossiers (`New Folder`) ou des éléments (`New` puis un des nombreux choix) utiles à votre jeu.
  - Vous pouvez couper (`Cut`), copier (`Copy`), coller (`Paste`), effacer (`Delete`) ou renommer (`Rename…`) des fichiers.
  - Vous pouvez afficher un dossier dans l'explorateur de votre système (`Show In Desktop`).
  - Double cliquez sur un fichier pour l'ouvrir dans l'éditeur (pour les fichiers créés par *Defold*) ou un programme externe (pour les fichiers importés).
  - Cliquez sur la flèche à gauche d'un nom de dossier pour le déplier ou le replier.
  - Faites glisser des fichiers externes depuis votre système dans cette vue pour les importer (ils sont copiés) dans votre projet.
  - Déplacez des fichiers dans la liste à un autre emplacement pour réorganiser votre projet.

### Vue Changed Files

Cette vue affiche les fichiers qui ont été modifiés ou créés depuis la dernière synchronisation avec les fichiers stockés en ligne.

![Changed Files panel](defold_changed_files_panel.png)

  - Les fichiers modifiés sont précédés du signe `*`.
  - Les fichiers créés sont précédés du signe `+`.
  - Les fichiers supprimés sont précédés du signe `-`.
  - Les fichiers déplacés sont précédés du signe `>>`.

Cliquez sur le bouton `Diff` pour voir les modifications effectuées sur un fichier.
Cliquez sur le bouton `Revert` pour rétablir l'état initial.

**Remarque :** Cette vue ne fonctionne que si vous avez déjà synchronisé au moins une fois votre projet en ligne.

### Vue Outline

Cette vue montre la structure d'une collection ou d'une ressource ouverte dans *Defold*.

![Outline panel](defold_outline_panel.png)

Par un clic droit puis `New`, créez de nouveaux éléments enfants (des sous-collections, des game objects ou des components).

### Vue Properties

Cette vue affiche la liste des propriétés de l'élément sélectionné actuellement dans la vue `Outline` ou la vue `Editor`.

![Properties panel](defold_properties_panel.png)

Cela vous permet d'éditer les propriétés des divers éléments de votre jeu.

### Vue Console, Curve Editor, Build Errors, Search Results

Cette vue affiche plusieurs outils utiles au développement du jeu.

![Console, Curve Editor, Build Errors, Search Results panels](defold_tools_panel.png)

  - **Onglet Console :** Affiche les traces des scripts avec la fonction prédéfinie de *Lua* `print`. Également utilisé avec le débogueur intégré.
  - **Onglet Curve Editor :** Affiche l'éditeur de courbes pour la gestion des particules.
  - **Onglet Build Errors :** Affiche les erreurs lors de la construction du projet.
  - **Onglet Search Results :** Affiche les recherches diverses.

### Vue Editor

Double cliquez sur un fichier existant dans la vue `Assets` (ou créez-en un nouveau) pour ouvrir l'éditeur correspondant. Selon le fichier ouvert, la vue `Editor` affiche un éditeur différent. Chaque fichier s'ouvre dans son propre onglet :

![Editor panel](defold_editor_panel.png)

Par un clic droit sur un onglet et en sélectionnant `Move to other tab pane`, vous pouvez scinder la vue en deux pour travailler avec deux fichiers ouverts en même temps (par exemple, pour lire le tutoriel d'un fichier `README.md` tout en effectuant les consignes).
L'option `Swap with other tab pane` inverse le contenu des deux panneaux de la vue `Editor`.
L'option `Join tab panes` rassemble les deux panneaux en un seul.

**Remarque :** Le système de coordonnées de *Defold* est le même qu'en mathématiques. L'axe *Y* augmente vers le haut.

#### Editeur de collection et de ressources

Double cliquez sur un fichier collection, ou la plupart des fichiers ressources dans la vue `Assets` pour ouvrir l'éditeur général :

![Collection Editor](defold_collection_editor.png)

Pour sélectionner un élément, cliquez dessus dans l'éditeur de scène ou dans l'arborescence de la vue `Outline`.
Un objet sélectionné est encadré d'une ligne verte dans l'éditeur de scène et son élément est surligné dans la vue `Outline`.
Sélectionnez plusieurs éléments par cliqué glissé dans l'éditeur ou utilisez la touche `SHIFT` ou `CTRL` dans l'éditeur ou la vue `Outline`.
Pour déplacer un élément sélectionné, activez le mode `Move` (touche `W`). Cliquez glissez sur une des flèches du gizmo pour déplacer l'élément sur un seul axe. Faites de même sur les carrés pour déplacer l'élément librement.
Pour faire tourner un élément sélectionné, activez le mode `Rotate` (touche `E`). Cliquez glissez sur une des lignes colorées du gizmo pour faire tourner l'élément sur un seul axe ou sur le cercle pour faire tourner l'élément librement.
Pour redimensionner un élément sélectionné, activez le mode `Scale` (touche `R`). Cliquez glissez sur un des carrés du gizmo pour redimensionner l'élément sur un seul axe ou proportionnellement.

#### Editeur de code

Lorsque vous double-cliquez sur un fichier script *Lua* dans la vue `Assets`, l'éditeur de code intégré à *Defold* ouvre le script :

![Script Editor](defold_script_editor.png)

#### Editeur de configuration du projet

Tous les paramètres du projet sont définis dans un fichier de configuration appelé `game.project`. Double cliquez sur lui dans la vue `Assets` pour afficher dans la vue `Editor` un formulaire éditable qui vous permet de contrôler tous les paramètres de configuration. Les paramètres ayant des valeurs modifiées ont un bouton en forme de flèche circulaire pour rétablir leur valeur par défaut. Ils sont classés par catégories.

![Configuration editor](defold_configuration_file.png)

**Attention !** Ce fichier doit rester à la racine du projet et ne doit pas être renommé.

**Remarque :** Vous pouvez éditer ce fichier avec un éditeur de texte. Seuls les attributs ayant déjà été modifiés (qui n'ont pas leur valeur par défaut) sont visibles. Vous pouvez également ouvrir ce fichier dans *Defold* en tant que fichier texte par un clic droit dans la vue `Assets` puis en choisissant `Open As` > `Text`. Le format des données dans le fichier texte est le suivant :

```
[catégorie1]
réglage1 = valeur1
réglage2 = valeur2
[catégorie2]
...
```

Voici un exemple :

```
[bootstrap]
main_collection = /main/main.collectionc
```

Qui indique que le paramètre `main_collection` appartient à la catégorie `bootstrap`. Quand une référence à un fichier est utilisé (comme dans le cas précédent), le chemin doit être suivi du caractère `'c'` pour indiquer que l'on fait référence à une version compilée du fichier. Le caractère `'/'` initial indique que le chemin part de la racine du projet.

##### Liste des paramètres

*Project*

**Title :** Le titre de l'application. Apparaît dans la barre de la fenêtre du jeu.

**Version :** Version de l'application. Utile pour les mises à jour du jeu.

**Write Log :** Si vous cochez cette option, *Defold* crée un fichier `log.txt` dans la racine du projet. Sur *iOS*, le fichier `log` peut être accédé avec *iTunes* et l'onglet `App` dans la section `Partage de Fichier`. Sur *Android*, le fichier est stocké dans l'emplacement externe de l'application. Lorsque vous exécutez l'application de développement `dmengine`, vous pouvez voir le `log` avec la commande :
`$ adb shell cat /mnt/sdcard/Android/data/com.defold.dmengine/files/log.txt`

**Compress Archive :** Active la compression des archives lors du paquetage du jeu. Cela s'applique à toutes les plateformes à l'exception d'*Android* où l'`apk` compress toujours les données.

**Dependencies :** Définit la liste des adresses ùURL* des bibliothèques du projet. Pour les projets stockés sur le site de *Defold*, l'`URL` se trouve sur la page du projet dans le dashboard (sur le site de *Defold*). Vous devez avoir un accès en lecture à cette `URL`. Pour les projets stockés sur le site de *Defold*, cela signifie que vous devez être un membre de ces projets.

**Custom Resources :** Définit une liste de ressources (séparées par des virgules) qui doivent être incluses dans le paquetage final du jeu. Si des dossiers sont spécifiés, tous les sous éléments sont inclus récursivement.

**bundle_resources (hidden setting) :** A directory containing resource files and folders that should be copied as-is into the resulting package when bundling. The directory is specified with an absolute path from the project root, for example /res. The resource directory must contain subfolders named by platform, or architecure-platform.
Supported platforms are *ios*, *android*, *osx*, *win32*, *linux*, *web*.
Supported arc-platform pairs are *armv7-ios*, *arm64-ios*, *armv7-android*, *x86-osx*, *x86_64-osx*, *x86-win32*, *x86_64-win32*, *x86-linux*, *x86_64-linux*, *js-web*.
A subfolder named `common` is also allowed, containing resource files common for all platforms.

**bundle_exclude_resources (hidden setting) :** Définit une liste de ressources (séparées par des virgules) qui ne devraient pas être incluses dans le paquetage final du jeu.

*Bootstrap*

**Main Collection :** Définit le fichier collection à ouvrir au lancement du jeu. Par défaut : `/logic/main.collection`.

**Render :** Définit quel pipeline de rendu utiliser pour afficher le jeu. Par défaut : `/builtins/render/default.render`.

*Library*

**Include Dirs :** Définit une liste de dossiers (séparés par un espace) à partager depuis votre projet via le partage de bibliothèque.

*Script*

**Shared State :** Cochez cette option si vous souhaitez partager un seul état *Lua* entre tous les types de scripts (standards, GUI et Render). Par défaut, non coché.

*Tracking*

**App Id :** Définit un identifiant unique de suivi pour ce projet. Cet identifiant peut être obtenu sur le dashboard du projet (sur le site de *Defold*).

*Display*

**Width :** La largeur en pixels de votre fenêtre de jeu. Par défaut : `960`.

**Height :** La hauteur en pixels de votre fenêtre de jeu. Par défaut : `640`.

**High Dpi :** Crée un tampon vidéo haute résolution sur les écran qui le supportent. Typiquement, le jeu sera rendu au double de la résolution spécifiée avec les réglages `Width` et `Height` qui seront utilisés dans les scripts et les propriétés.

**Samples :** Combien d'échantillons utiliser pour l’anti-crénelage de super échantillonnage (*SSAA*). Paramètre la valeur `GLFW_FSAA_SAMPLES`. Par défaut, vaut `0`, ce qui veut dire que l'anti-crénelage n'est pas activé.

**Fullscreen :** Cocher cette option si vous souhaitez que votre jeu démarre en mode plein écran. Par défaut, décoché. Le jeu démarre en mode fenêtré.

**Update Frequency :** Fréquence de rafraîchissement en images par secondes. Par défaut : `60`. Les valeurs autorisées sont : `60`, `30`, `20`, `15`, `12`, `10`, `6`, `5`, `4`, `3`, `2` ou `1`.

**Variable Dt :** Check if time step should be measured against actual time spent in the update loop, uncheck if you want fixed time step (as set in `update_frequency`).

**Display Profiles :** Specifies which display profiles file to use, `/builtins/render/default.display_profilesc` par défaut.

**Dynamic Orientation :** Check if the app should dynamically switch between portrait and landscape on device rotation. Note that the development app does not currently respect this setting.

*Physics*

**Type :** Which type of physics to use, `2D` (default) or `3D`.

**Gravity Y :** World gravity along y-axis, -10 par défaut (natural gravity)

**Debug :** Check if physics should be visualized for debugging.

**Debug Alpha :** Alpha component value for visualized physics, 0–1. The value is `0.9` par défaut.

**World Count :** Max number of concurrent physics worlds, 4 par défaut. If you load more than 4 worlds simultaneously through collection proxies you need to increase this value. Be aware that each physics world allocates a fair amount of memory.

**Gravity X :** World gravity along x-axis, `0` par défaut.

**Gravity Z :** World gravity along z-axis, `0` par défaut.

**Scale :** Tells the physics engine how to scale the physics worlds in relation to the game world for numerical precision, 0.01–1.0. If the value is set to 0.02, it means that the physics engine will view 50 units as 1 meter (1 / 0.021/0.02). The default value is `1.0`.

**Debug Scale :** How big to draw unit objects in physics, like triads and normals, `30` par défaut.

**Max Collisions :** How many collisions that will be reported back to the scripts, `64` par défaut.

**Max Contacts :** How many contact points that will be reported back to the scripts, `128` par défaut.

**Contact Impulse Limit :** Ignore contact impulses with values less than this setting, `0.0` par défaut.

**Ray Cast Limit 2d :** The max number of 2d ray cast requests per frame. `64` par défaut.

**Ray Cast Limit 3d :** The max number of 3d ray cast requests per frame. `128` par défaut.

**Trigger Overlap Capacity :** The maximum number of overlapping physics triggers. `16` par défaut.

*Graphics*

**Default Texture Min Filter :** Specifies which filtering to use for minification filtering, `linear` (par défaut) pour des images haute résolution ou `nearest` pour des images en pixel art.

**Default Texture Mag Filter :** Specifies which filtering to use for magnification filtering, `linear` (par défaut) pour des images haute résolution ou `nearest` pour des images en pixel art.

**Max Draw Calls :** The max number of render calls, `1024` par défaut.

**Max Characters :** The number of characters pre-allocated in the text rendering buffer, i.e. the number of characters that can be displayed each frame, `8192` par défaut.

**Max Debug Vertices :** The maximum number of debug vertices. Used for physics shape rendering among other things, 10000 par défaut.

**Texture Profiles :** The texture profiles file to use for this project, `/builtins/graphics/default.texture_profiles` par défaut.

*Input*

**Repeat Delay :** Seconds to wait before a held down input should start repeating itself, `0.5` par défaut.

**Repeat Interval :** Seconds to wait between each repetition of a held down input, `0.2` par défaut.

**Gamepads :** File reference of the gamepads config file, which maps gamepad signals to OS, `/builtins/input/default.gamepads` par défaut.

**Game Binding :** File reference of the input config file, which maps hardware inputs to actions, `/input/game.input_binding` par défaut.

**Use Accelerometer :** Check to make the engine receive accelerator input events each frame. Disabling accelerometer input may give some performance benefit, checked par défaut.

*Resource*

**Http Cache :** If checked, a HTTP cache is enabled for faster loading of resources over the network to the running engine on device, unset par défaut.

**Uri :** Where to find the project build data, in URI format.

**Max Resources :** The max number of resources that can be loaded at the same time, `1024` par défaut.

*Network*

**Http Timeout :** The HTTP timeout in seconds. Set to `0` to disable timeout, which is the default.

*Collection*

**Max Instances :** Max number of game object instances in a collection, `1024` par défaut.

*Sound*

**Gain :** Global gain (volume), 0–1, The value is `1` par défaut.

**Max Sound Data :** Max number of sound resources, i.e the number of unique sound files at runtime, `128` par défaut.

**Max Sound Buffers :** (Currently not used) Max number of concurrent sound buffers, `32` par défaut.

**Max Sound Sources :** (Currently not used) Max number of concurrently playing sounds, `16` par défaut.

**Max Sound Instances :** Max number of concurrent sound instances, i.e. actual sounds played at the same time. `256` par défaut.

*Sprite*

**Max Count :** Max number of sprites, `128` par défaut.

**Subpixels :** Check to allow sprites to appear unaligned with respect to pixels, checked par défaut.

*Spine*

**Max Count :** Max number of spine models, `128` par défaut.

*model*

**Max Count :** `128` par défaut.

*GUI*

**Max Count :** Max number of GUI components, `64` par défaut.

**Max Particlefx Count :** The max number of concurrent emitters, `64` par défaut.

**Max Particle Count :** The max number of concurrent particles, `1024` par défaut.

*Label*

**Max Count :** Max number of labels, `64` par défaut.

**Subpixels :** Check to allow lables to appear unaligned with respect to pixels, checked par défaut.

*Particle FX*

**Max Count :** The max number of concurrent emitters, `64` par défaut.

**Max Particle Count :** The max number of concurrent particles, `1024` par défaut.

*Collection proxy*

**Max Count :** Max number of collection proxies, `8` par défaut.

*Collection factory*

**Max Count :** Max number of collection factories, `128` par défaut.

*Factory*

**Max Count :** Max number of game object factories, `128` par défaut.

*iOS*

**App Icon 57x57–180x180 :** Image file to use as application icon at given width and height dimensions W × H.

**Launch Image 320x480–2436x1125 :** Image file to use as application launch image for resolution width and height dimensions W × H. iOS selects the display resolution based on the launch image.

**Pre Rendered Icons :** (iOS 6 and earlier) Check if your icons are pre-rendered. If this is unchecked the icons will get a glossy highlight added automatically.

**Bundle Identifier :** The bundle identifier lets iOS recognize any updates to your app. Your bundle ID must be registered with Apple and be unique to your app. You cannot use the same identifier for both iOS and OS X apps.

**Info.plist :** If specified, use this info.plist file when bundling your app.

*Android*

**App Icon 36x36–192x192 :** Image file to use as application icon at given width and height dimensions W × H.

**Push Icon Small–LargeXxxhdpi :** Image files to be used as custom push notification icon on Android. The icons will automatically be used for both local or remote push notifications. If not set the application icon will be used par défaut.

**Push Field Title :** Specifies which payload JSON field should be used as notification title. Leaving this setting empty makes the pushes default to the application name as title.

**Push Field Text :** Specifies which payload JSON field should be used as notification text. If left empty, the text in the field alert is used, just as on iOS.

**Version Code :** An integer value indicating the version of the app. Increase the value for each subsequent update.

**Package :** Package identifier.

**Gcm Sender Id :** Google Cloud Messaging Sender Id. Set this to the string assigned by Google to enable push notifications.

**Manifest :** If set, use the specified Android manifest XML file when bundling.

**Iap Provider :** Specifies which store to use. Valid options are Amazon and GooglePlay, `GooglePlay` par défaut.

**Input Method :** Specifies which method to use to get keyboard input on Android devices. Valid options are KeyEvent (old method) and HiddenInputField (new). `KeyEvent` par défaut.

**Immersive Mode :** If set, hides the navigation and status bars and lets your app capture all touch events on the screen.

*MacOS / OS X*

**App Icon :** Image file to use as application icon on MacOS.

**Info.plist :** If set, use the specified info.plist file when bundling.

**Bundle Identifier :** The bundle identifier lets OS X recognize updates to your app. Your bundle ID must be registered with Apple and be unique to your app. You cannot use the same identifier for both iOS and OS X apps.

*Windows*

**App Icon :** Image file to use as application icon on Windows.

**Iap Provider :** Specifies which store to use. Valid options are None and Gameroom, `None` par défaut.

*HTML5*

**Set Custom Heap Size :** If set, Emscripten allocates custom_heap_size number of bytes for the application heap.

**Custom Heap Size :** Sets the custom heap size (number of bytes) for Emscripten to use if `set_custom_heap_size` is set. If not set, `256MB` is allocated for the application heap.

**Include Dev Tool :** Includes a visual dev-tool in the application that allows tracking of memory usage.

**.html Shell :** If set, use the specified template *HTML* file when bundling.

**Custom .css :** If set, use the specified *CSS* file when bundling.

**Splash Image :** If set, use the specified splash image on startup when bundling.

**Archive Location Prefix :** When bundling for *HTML5* game data is split up into one or more archive data files. When the engine starts the game, these archive files are read into memory. Use this setting to specify the location of the data, `archive` par défaut.

**Archive Location Suffix :** Suffix to be appended to the archive files. Useful to, for instance, force non-cached content from a CDN (?version2 for example).

*Facebook*

**Appid :** The application id as issued by Facebook.

*IAP*

**Auto Finish Transactions :** Check to automatically finish IAP transactions. If unchecked, you need to explicitly call `iap.finish()` after a successful transaction, checked par défaut.

*native_extension*

**App Manifest :** If set, use the app manifest to customize the engine build. This allows you to remove unneeded parts from the engine making it possible to decrease the final binary size. Note that this feature is in alpha state. Please visit the forum for information on how to proceed. Default empty.

*profiler*

**TrackCpu :** If checked, enable CPU profiling in release versions of the builds. Normally, you can only access profiling information in debug builds. Default disabled.

*Live update*

**Private Key :** If set, use the specified private key file when bundling live update content. If no key file is set, a key is generated.

**Public Key :** If set, use the specified public key file when bundling live update content. If no key file is set, a key is generated.

## Menus

Voici une présentation des menus de *Defold* :

### Menu `File`

![File menu](defold_file_menu.png)

- L'option `New...` (ou le raccourci `CTRL+N`) ouvre la boîte de dialogue `New...` et vous permet de créer une nouvelle ressource parmi celles proposées dans la liste. Cela a le même effet que d'effectuer un clic droit dans la vue `Assets` puis de choisir l'option `New...` suivie d'une des ressources de la liste. Consultez la section `Fichiers ressources` pour plus d'informations sur ces derniers.
- L'option `Open` (ou le raccourci `CTRL+O`) vous permet d'ouvrir la ou les ressources sélectionnées dans la vue `Assets`. En général, un double clic sur une ressource dans cette vue est plus rapide.
- L'option `Synchronize...` vous permet de synchroniser le projet ouvert dans *Defold* avec celui stocké sur le cloud. La vue `Changed Files` peut vous être utile dans ce cas. Gardez à l'esprit que pour utiliser cette fonctionnalité, vous devez être connecté à votre compte.
- L'option `Save All` (ou le raccourci `CTRL+S`) vous permet de sauvegarder toutes les ressources ouvertes dans l'éditeur.
- L'option `Open Assets...` (ou le raccourci `CTRL+SHIFT+R`) ouvre la boîte de dialogue `Open Assets` pour vous permettre d'ouvrir une ou plusieurs ressources.
- L'option `Search in Files...` (ou le raccourci `CTRL+SHIFT+F`) ouvre la boîte de dialogue `Search in Files` et vous permet de rechercher un ou plusieurs mots dans les fichiers ressources.
- L'option `Close` (ou le raccourci `CTRL+W`) vous permet de fermer l'onglet actif de la vue `Editor`.
- L'option `Close All` (ou le raccourci `CTRL+SHIFT+W`) vous permet de fermer tous les onglets ouverts dans la vue `Editor`.
- L'option `Close Others` vous permet de fermer tous les onglets ouverts dans la vue `Editor` à l'exception de celui actif.
- L'option `Referencing Files...` vous permet de [????].
- L'option `Dependencies...` vous permet de [????].
- L'option `Hot Reload` (ou le raccourci `CTRL+R`) vous permet de recharger le jeu s'il est déjà ouvert pour tester les effets de la modification d'un script.
- L'option `Sign Out` vous permet de vous déconnecter de votre compte dans *Defold*.
- L'option `Preferences...` (ou le raccourci `CTRL+,`) ouvre la boîte de dialogue `Preferences` et vous permet de configurer *Defold* (voir section suivante).
- L'option `Quit` (ou le raccourci `CTRL+Q`) vous permet de quitter *Defold*. Si votre projet n'est pas sauvegardé, une demande de confirmation apparaît.

#### Boîte de dialogue `Preferences`

![Preferences dialog](defold_preferences_dialog.png)

- Onglet `General`
  - La case `Enable Texture Compression:` si cochée vous permet de [????]. Décochée par défaut.
  - La case `Escape Quits Game:` si cochée vous permet de quitter le jeu avec la touche `ECHAP` lorsque vous testez le jeu dans *Defold*. Cochée par défaut.
  - La case `Track Active Tab in Asset Browser:` si cochée vous permet de [????]. Décochée par défaut.
- Onglet `Scene`
  - Le menu déroulant `Selection Color:` vous permet de définir une couleur pour les éléments sélectionnés dans la vue `Editor`. `Lime` par défaut.
  - Le menu déroulant `Grid:` vous permet de choisir [????] (`Auto`) ou (`Manual`) pour la grille. `Auto` par défaut.
  - Le menu déroulant `Grid Size:` vous permet de choisir la taille des cases la grille. `100` par défaut.
  - Le menu déroulant `Grid Color:` vous permet de définir une couleur pour la grille. `#999999` par défaut.
- Onglet `Code`
  - Le champ `Custom Editor:` [????]. Vide par défaut.
  - Le champ `Open File:` [????]. `{file}` par défaut.
  - Le champ `Open File at Line:` [????]. `{file}:{line}` par défaut.
- Onglet `Extensions`
  - Le champ `Build Server:` [????]. `https://build.defold.com` par défaut.

### Menu `Edit`

![Edit menu](defold_edit_menu.png)

- L'option `Undo` (ou le raccourci `CTRL+Z`) vous permet d'annuler la dernière action effectuée.
- L'option `Redo` (ou le raccourci `CTRL+SHIFT+Z`) vous permet de rétablir la dernière action annulée.
- L'option `Cut` (ou le raccourci `CTRL+X`) vous permet de couper le ou les éléments sélectionnés.
- L'option `Copy` (ou le raccourci `CTRL+C`) vous permet de copier le ou les éléments sélectionnés.
- L'option `Paste` (ou le raccourci `CTRL+V`) vous permet de coller à l'endroit sélectionné, le ou les éléments coupés ou copiés.
- L'option `Delete` (ou le raccourci `SUPPR`) vous permet d'effacer ou de supprimer le ou les éléments sélectionnés. Une boîte de dialogue vous demander de confirmer la suppression.
- L'option `World Space` [????]. Actif par défaut.
- L'option `Local Space` [????]. Inactif par défaut.
- L'option `Move Whole Pixels` . Actif par défaut.

**Remarque :** Certaines options ne sont pas toujours accessibles car elles dépendent du contexte.

### Menu `View`

![View menu](defold_view_menu.png)

- L'option `Toggle Assets Pane` (ou le raccourci `F6`) vous permet d'afficher ou de masquer la vue `Assets`.
- L'option `Toggle Tools Pane` (ou le raccourci `F7`) vous permet d'afficher ou de masquer la vue `Tools` contenant les onglets `Console`, `Curve Editor`, `Build Errors` et `Search Results`. Il est souvent plus simple d'afficher la vue `Tools` et de cliquer sur l'onglet désiré.
- L'option `toggle Properties Pane` (ou le raccourci `F8`) vous permet d'afficher ou de masquer les vues `Outline` et `Properties`.
- L'option `Show Console` vous permet d'afficher la vue `Tools` sur l'onglet `Console`.
- L'option `Show Curve Editor` vous permet d'afficher la vue `Tools` sur l'onglet `Curve Editor`.
- L'option `Show Build Errors` vous permet d'afficher la vue `Tools` sur l'onglet `Build Errors`.
- L'option `Show Search Results` vous permet d'afficher la vue `Tools` sur l'onglet `Search Results`.
- L'option `Toggle Visibility Filters` (ou le raccourci `CTRL+SHIFT+I`) vous permet [????].
- L'option `Toggle Component Guides` (ou le raccourci `CTRL+H`) vous permet [????].
- L'option `Toggle Grid` vous permet d'afficher ou de masquer la grille.
- L'option `Hide Selected Objects` (ou le raccourci `CTRL+E`) vous permet de masquer les objets sélectionnés.
- L'option `Hide Unselected Objects`  vous permet de masquer les objets non sélectionnés.
- L'option `Show Selected Objects`  vous permet d'afficher les objets sélectionnés.
- L'option `Show Last hidden Objects` (ou le raccourci CTRL+SHIFT+E) vous permet d'afficher les derniers objets masqués.
- L'option `Show All Hidden Objects` vous permet d'afficher tous les objects masqués.
- L'option `Frame Selection` (ou le raccourci `F`) vous permet de centrer la vue `Editor` sur le ou les objets sélectionnés.
- L'option `Realign Camera` (ou le raccourci `.`) vous permet de réajuster la caméra de la vue `Editor` sur l'axe *Z*.

**Remarque :** Certaines options ne sont pas toujours accessibles car elles dépendent du contexte.

### Menu `Project`

![Project menu](defold_project_menu.png)

- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .

[VIDE]

### Menu `Debug`

![Debug menu](defold_debug_menu.png)

- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .
- L'option `-` .

[VIDE]

### Menu `Help`

![Help menu](defold_help_menu.png)

- L'option `Profiler` [????].
- L'option `Reload Stylesheet` [????].
- L'option `Show Logs` [????].
- L'option `Documentation` (ou le raccourci `F1`) ouvre votre navigateur par défaut sur la page de documentation de *Defold*.
- L'option `Support Forum` [????].
- L'option `Find Assets` [????].
- L'option `Report Issue` vous permet d'envoyer aux développeurs de *Defold* des problèmes que vous auriez notés dans *Defold*.
- L'option `Report Suggestion` vous permet d'envoyer aux développeurs de *Defold* des suggestions pour améliorer ce dernier.
- L'option `Search Issues` vous permet d'effectuer des recherches d problèmes.
- L'option `About` affiche une fenêtre contenant les informations sur la version de *Defold* que vous utilisez.

[VIDE]

## Etapes dans la création d'un projet

Voici un découpage grossier des étapes de création d'un jeu :

- Importation des ressources externes nécessaires au projet (images, sons, modèles, etc...).
- Création des fichiers ressources dans *Defold* (atlas, tile sources, etc...).
- Création de la structure de la collection principale (sous-collections, game objects, components, etc...).
- Répétition jusqu'à obtention d'un résultat satisfaisant des étapes suivantes :
  - Ajout de fonctionnalités et programmation de la logique du jeu.
  - Test et débogage.
- Export du jeu sur les plateformes cibles.
- Publication du jeu.

**Remarque :** Il va sans dire que dans un projet commercial, d'autres étapes (comme le marketing du jeu) sont essentielles.

## Importer les ressources externes

*Defold* suppose que les ressources externes (images, sons, polices de caractères, modèles Spine, modèles 3D) nécessaires au projet soient finalisées. Vous devez donc commencer par les importer dans votre projet ou à défaut, utiliser des ressources temporaires.

**Remarque :** Si vous utilisez des ressources externes temporaires, cela va vous compliquer les choses par la suite car vous devrez faire de nombreuses modifications (atlas, tile source, références aux fichiers dans les components, etc...).

### Importer des images

Pour importer des images dans votre projet, faites simplement glisser depuis votre système les fichiers images (au format `.png` ou `.jpg`) dans la vue `Assets` à l'emplacement désiré. Les fichiers sont dupliqués dans le projet. Les images originales sont donc toujours accessibles à leur emplacement d'origine.

**Remarque :** N'oubliez pas que vous pouvez supprimer les fichiers ressources inutiles dans la vue `Assets` par un clic droit suivi de l'option `Delete`.

*Defold* propose deux façons de gérer les images selon qu'elles sont rassemblées ou non dans un même fichier.

#### Gérer des images individuelles

Les images individuelles ne peuvent pas être directement utilisées dans *Defold*. Elles doivent d'abord être intégrées à un fichier ressource `Atlas`. Ce dernier rassemble plusieurs images individuelles dans une seule texture (une image chargée en mémoire vidéo) pour optimiser le jeu (principalement pour économiser la mémoire et améliorer la performance d'accès à ces images). Un atlas peut en outre posséder des groupes d'animations qui contiendront à leur tour une série d'images qui définiront une animation. Pour plus d'informations, consultez la section **Atlas** de ce document.

**Remarque :** *Defold* ne permet pas d'importer un atlas préparé depuis un outils externe. Vous devez importer les images séparément puis les ajouter à un fichier ressource atlas dans *Defold*.

#### Gérer des tilesheet ou spritesheet

Si un fichier image contient plusieurs images disposés sur une grille uniforme (chaque image est placé dans une case de taille identique), créez un fichier ressource `Tile Source` dans la vue `Assets`. Cette ressource permet de définir des tuiles et des animations dans l'image. Pour plus d'informations, consultez la section **Tile Source** de ce document.

**Remarque :** *Defold* ne permet pas d'importer de spritesheet ou de tilesheet composées d'images disposées dans des cases de taille variable. Vous devez importer les images séparément puis les ajouter à un fichier ressource atlas dans *Defold*. Certains logiciels permettent d'extraire les images individuelles de tels fichiers (par exemple l'excellent [ShoeBox](https://renderhjs.net/shoebox/)).

### Importer des modèles Spine

*Defold* est compatible avec les modèles d'animation exportés au format *Spine JSON* par le logiciel [Spine](http://fr.esotericsoftware.com/). Ce dernier vous permet d'animer un groupe d'images associées à un squelette. C'est utile si vous souhaitez donner du mouvement à des images fixes plutôt que de créer une série d'images pour définir une animation.

**Remarque :** Je n'utilise pas ce logiciel et la documentation de *Defold* est assez limitée sur ce sujet. Je ne peux donc pas vous expliquer correctement comment utiliser ce format. Voici le lien vers la documentation de *Defold* sur les [modèles Spine](https://www.defold.com/manuals/spine/).

### Importer des sons et des musiques

Pour importer des sons ou des musiques dans votre projet, faites simplement glisser depuis votre système les fichiers audios (au format `.wav` (*WAVE*) ou `.ogg` (*OGG Vorbis*)) dans la vue `Assets` à l'emplacement désiré. Les fichiers sont dupliqués dans le projet. Les fichiers originaux sont donc toujours accessibles à leur emplacement d'origine. Pour les sons courts, préférez le format `.wav` qui est non compressé mais prend plus de place. Pour les musiques et les sons longs, préférez le format `.ogg` qui demande plus de ressources pour décompresser l'audio mais prend moins de place.

**Remarque :** N'oubliez pas que vous pouvez supprimer les fichiers ressources inutiles dans la vue `Assets` par un clic droit suivi de l'option `Delete`.

### Importer des polices de caractères

Pour importer des polices de caractères dans votre projet, faites simplement glisser depuis votre système les fichiers de police (au format `.ttf` (*TrueType*), `.otf` (*OpenType*) ou `.fnt` (*BMFont*)) dans la vue `Assets` à l'emplacement désiré. Les fichiers sont dupliqués dans le projet. Les fichiers originaux sont donc toujours accessibles à leur emplacement d'origine. Pour les polices au format *BMFont*, n'oubliez pas d'importer le fichier image associé (au format `.png`) dans le même dossier quel le fichier `.fnt`.

**Remarque :** N'oubliez pas que vous pouvez supprimer les fichiers ressources inutiles dans la vue `Assets` par un clic droit suivi de l'option `Delete`.

### Importer des modèles 3D

*Defold* est compatible avec les modèles 3D exportés au format *Collada* (`.dae`).

**Remarque :** Je n'utilise pas ce genre de modèles. Je ne peux donc pas vous expliquer correctement comment utiliser ce format.

## Structure du jeu

Dans *Defold*, un écran de jeu est représenté par une *Collection*. Une collection est toujours un fichier portant l'extension `.collection`. Dans le fichier de configuration `game.project`, un fichier collection doit définir la collection de démarrage du jeu (section `Bootstrap` > `Main collection`).

**Remarque :** Par défaut, *Defold* crée un fichier `main.collection` défini comme collection de démarrage dans le fichier de configuration de tout nouveau projet.

Une collection est constituée de sous-éléments (de sous-collections et de game objects) qui définissent les éléments essentiels du jeu. Ces derniers sont à leur tour constitués de sous-éléments constituant ainsi une arborescence. Une collection ouverte dans l'éditeur affiche la hiérarchie de ses éléments dans la vue `Outline`. Une sous-collection peut servir à définir un ensemble de game objects constituant un élément du jeu. Elle peut ensuite être attachée à une collection mère qui constituera un écran de jeu complet.

Un game object est un conteneur à components. Il ne possède par défaut que des propriétés de transformations (position, rotation, échelle). Vous pouvez intégrer des game objects directement dans une collection (*en place*) où les sauvegarder en tant que fichier de ressource ayant l'extension `.go`.

Les components sont les éléments essentiels au jeu. Ce sont eux qui définissent les graphismes, les sons ou les comportements des game objects qui les contiennent.

Enfin, certains components peuvent avoir comme enfants des fichiers ressources particuliers (par exemple, les components `Collision Object` ont en général un élément enfant de type `Shape`).

Tous les fichiers qui ne sont pas des collections sont considérés comme des ressources et peuvent être référencés dans les collections. Il apparaissent alors avec le chemin du fichier écrit en italique à côté de leur nom (`Id`) dans la vue `Outline`.

## Fichiers ressources

En plus des fichiers externes importés, *Defold* vous permet de créer de nombreux fichiers ressources différents. Faites un clic droit dans la vue `Assets` à l'endroit souhaité, sélectionnez l'option `New...` puis choisissez la ressource désirée dans la liste :

![Resources list](defold_resources_list.png)

### Propriétés communes aux components

tous les components attachés en place à un game object ont les propriétés suivantes :

![In place Component common properties](defold_in_place_component_properties.png)

- Le champ `Id` vous permet de définir le nom de référence du component dans l'arborescence.
- Le champ `Url` indique le chemin d'accès du component depuis un script (lecture seule).

tous les fichiers ressources components attachés à un game object ont les propriétés suivantes :

![File Component common properties](defold_file_component_properties.png)

- Le champ `Path` vous permet de définir le fichier ressource correspondant au component. Cliquez sur le bouton `...` pour sélectionner le fichier.
- Le champ `Id` vous permet de définir le nom de référence du component dans l'arborescence.
- Le champ `Url` indique le chemin d'accès du component depuis un script (lecture seule).

### Animation Set

Une ressource `Animation Set` contient une ou plusieurs animations d'un même modèle 3D. Référencez cette ressources depuis la propriété `Animations` d'un component `Model`.

Pour créer un nouveau fichier ressource animation set, faites un clic droit dans la vue `Assets` à l'emplacement désiré puis choisissez l'option `New...` > `Animation Set`. La boîte de dialogue `New Animation Set` apparaît :

![New Animation Set dialog](defold_new_animation_set_dialog.png)

- Le champ `Name` vous permet de définir le nom de l'animation set.
- Le champ `Location` et le bouton `Browse...` vous permettent de définir l'emplacement de l'animation set.
- Le champ `Path` vous indique le chemin complet de l'animation set (lecture seule).

Cliquez sur le bouton `OK` pour créer l'animation set ou le bouton `Cancel` pour annuler. Un nouvel animation set vide apparaît dans la vue `Editor` :

![Animation Set Editor view](defold_animation_set_editor.png)

#### Ajouter une animation à un animation set

Pour ajouter une animation, cliquez sur le bouton `+` dans la vue `Editor` pour ouvrir la boîte de dialogue `Select Resource` :

![Animation Set Select Resource dialog](defold_animation_set_select_resource_dialog.png)

Sélectionnez le fichier ressource animation 3D (au format *Collada* `.dae`) à ajouter à l'animation set puis cliquez sur le bouton `OK` pour valider.

**Remarque :** Vous pouvez également ajouter un autre fichier ressource animation set (`.animationset`) à un animation set plus large pour organiser vos animations en sous-groupes.

#### Supprimer une animation à un animation set

Pour supprimer une des animations de la liste, sélectionnez l'animation à supprimer puis cliquez sur le bouton `-` dans la vue `Editor`.

### Atlas

Pour créer un nouveau fichier ressource atlas, faites un clic droit dans la vue `Assets` à l'emplacement désiré puis choisissez l'option `New...` > `Atlas`. La boîte de dialogue `New Atlas` apparaît :

![New Atlas dialog](defold_new_atlas_dialog.png)

- Le champ `Name` vous permet de définir le nom de l'atlas.
- Le champ `Location` et le bouton `Browse...` vous permettent de définir l'emplacement de l'atlas.
- Le champ `Path` vous indique le chemin complet de l'atlas (lecture seule).

Cliquez sur le bouton `OK` pour créer l'atlas ou le bouton `Cancel` pour annuler. Un nouvel atlas vide apparaît dans la vue `Editor` :

![Atlas Editor view](defold_editor_atlas.png)

La vue `Properties` vous permet de définir les propriétés de l'atlas :

![Atlas Properties](defold_atlas_properties.png)

- Les champs `W` (largeur) et `H` (hauteur) de la section `Size` indiquent les dimensions en pixels de l'atlas (lecture seule).
- Le champ `Margin` vous permet de définir la marge en pixels à ajouter autour des images de l'atlas.
- Le champ `Inner Padding` vous permet de définir l'espacement en pixels à ajouter entre chaque image de l'atlas.
- Le champ `Extrude Borders` vous permet de définir la taille en pixels du débordement à effectuer autour de chaque image de l'atlas. *Defold* reproduit les pixels des images touchant les bords un nombre de pixels spécifié dans cette section. Cela est utile lorsque le fragment shader échantillonne les pixels au bord d'une image, les pixels de l'image voisine peuvent apparaître et causer des problèmes d'affichage. Cette option permet d'éviter ce problème.

#### Ajouter des images à un atlas

Pour ajouter des images à un atlas, faites un clic droit sur l'atlas dans la vue `Outline` et choisissez l'option `Add Images...` :

![Atlas Add Images... menu](defold_outline_atlas_add_images.png)

La boîte de dialogue `Select Images` apparaît :

![Atlas Select Images dialog](defold_outline_atlas_select_images_dialog.png)

Sélectionnez les images à ajouter à l'atlas puis cliquez sur le bouton `OK`. La vue `Editor` affiche les images dans l'atlas et la vue `Outline` affiche la liste des fichiers ressources images (en *italique* suivi de leur chemin complet) :

![Atlas with images added](defold_atlas_with_images.png)

#### Créer un groupe d'animation

Un atlas peut également contenir des groupes d'animation. Ceux-ci sont composées d'une série d'images définissant une animation. Pour ajouter un nouveau groupe d'animation à un atlas, faites un clic droit sur l'atlas dans la vue `Outline` et choisissez l'option `Add Animation Group` (touche `A`) :

![Atlas Add Animation Group menu](defold_outline_atlas_add_animation_group.png)

Dans la vue `Outline`, un nouveau groupe d'animation apparaît :

![Atlas with Animation added](defold_outline_atlas_new_animation_group.png)

**Remarque :** Vous pouvez renommer le groupe d'animation dans la vue `Properties`.

##### Ajouter des images à un groupe d'animation

Pour ajouter des images à un groupe d'animation, faites un clic droit sur celui-ci puis sélectionnez l'option `Add Images...` :

![Atlas Animation Add Images... menu](defold_outline_atlas_animation_add_images.png)

La boîte de dialogue `Select Images` apparaît :

![Atlas Select Images dialog](defold_outline_atlas_select_images_dialog.png)

Sélectionnez les images à ajouter au groupe d'animation de l'atlas puis cliquez sur le bouton `OK`. La vue `Editor` affiche les images dans l'atlas et la vue `Outline` affiche la liste des ressources images (en *italique* suivi de leur chemin complet) sous le groupe d'animation :

![Atlas Animation with Images](defold_atlas_animation_with_images.png)

**Remarque :** Si vos images ne sont pas dans l'ordre, vous devez les importer une à une.

Si vous sélectionnez un groupe d'animation dans la vue `Outline`, la vue `Properties` affiche ses propriétés :

![Atlas Animation properties](defold_atlas_animation_properties.png)

- Le champ `Id` vous permet de définir le nom du groupe d'animation.
- Le champ `Fps` vous permet de définir la vitesse d'animation (en images par secondes).
- L'option' `Flip Horizontal` vous permet de définir si l'animation doit être retournée horizontalement ou non (décoché par défaut).
- L'option' `Flip Vertical` vous permet de définir si l'animation doit être retournée verticalement ou non (décoché par défaut).
- Le menu déroulant `Playback` vous permet de définir la façon dont est lue l'animation :
  - L'option `None` bloque l'animation sur la première image.
  - L'option `Once Forward` lit l'animation en avant une seule fois.
  - L'option `One Backward` lit l'animation à l'envers une seule fois.
  - L'option `Once Ping Pong` lit l'animation en avant puis à l'envers une seule fois.
  - L'option `Loop Forward` (par défaut) lit l'animation en avant indéfiniment.
  - L'option `Loop Backward` lit l'animation en arrière indéfiniment.
  - L'option `Loop Ping Pong` lit l'animation en avant puis en arrière indéfiniment.

**Remarque :** Sélectionnez une animation dans la vue `Outline` et appuyez sur la touche `ESPACE` pour la lire dans la vue `Editor`.

### Camera

#### Créer un fichier ressource Camera

Pour créer un fichier ressource Camera, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Camera`.

**Remarque :** Ce component peut être attaché en place à un game object.

Dans *Defold*, une caméra est un component qui gère la vue dans le jeu. Il n'y a pas besoin de caméra par défaut, mais si votre jeu nécessite de se déplacer dans un niveau, *Defold* fournit un component de base appelé `Camera`. Les caméras ont une position dans l'espace. Elles peuvent être déplacées en positionnant le game object les contenants. Elle incluent un script de rendu avec les données nécessaires pour rendre la vue correctement. *OpenGL* définit les caméras par un système de coordonnées composé d'un observateur (ou oeil), d'une position, et d'un plan limite de vue de près et de loin. Le plan de près est le plan visible (ou l'écran).

#### Plans de caméra 

Une caméra 3D a généralement un volume de vue (un frustum) qui a la forme d'une pyramide rectangulaire tronquée. Les objets les plus éloignés de la caméra apparaissent donc plus petits. La perspective est réaliste. Plus le champ de vision est large, plus la caméra voit de parties de la scène et plus la différence entre des objets éloignés est importante.

#### Champ de vue de caméra

[VIDE]

#### Créer une caméra

Pour créer une caméra, vous pouvez attacher en place un component `Camera` à un game object ou créer un fichier ressource `Camera`. Pour attacher en place un component `Camera` à un game object, dans la vue `Outline` faites un clic droit sur le game object puis choisissez l'option `Add Component` > `Camera`. Pour créer un fichier ressource `Camera` réutilisable, faites un clic droit dans la vue `Assets`, choisissez l'option `New` > `Camera`. *Defold* utilse l'extension `.camera` pour les fichiers ressources `Camera`.

The camera component has a set of properties that defines the camera frustum.

#### Propriétés de caméra

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Camera properties list](defold_camera_properties.png)

- Le champ `Id` vous permet de définir le nom de la caméra.
- Le champ `Url` indique le chemin d'accès à la caméra dans un script (lecture seule).
- Le champ `Aspect Ratio` The ratio between the frustum width and height. 1.0 means that you assume a quadratic view. 1.33 is good for a 4:3 view like 1024x768. 1.78 is good for a 16:9 view.
- Le champ `Fov` The camera field of view expressed in radians. The current default FOV value is misleading. It is not expressed in degrees but in radians. For a 45 degree FOV, change the value to 0.785 (𝛑 / 4).
- Le champ `Near Z` The Z-value of the near clipping plane.
- Le champ `Far Z` The Z-value of the far clipping plane.
- Le champ `Auto Aspect Ratio` Set this to 1 to let the camera automatically set the aspect ratio based on the game’s screen settings.

- **Camera focus :** To activate the camera and have it feed its view and projection matrices, you send the component an `acquire_camera_focus` message:

`msg.post("#camera", "acquire_camera_focus")`

As soon as the camera component has camera focus, each frame it will send a `set_view_projection` message to the `@render` socket, i.e. to your render script:

```
-- example.render_script

function update(self)
    ...
    render.set_view(self.view)
    render.set_projection(self.projection)
    ...
end

function on_message(self, message_id, message)
    if message_id == hash("set_view_projection") then
        -- Camera view and projection arrives here. Store them.
        self.view = message.view
        self.projection = message.projection
    end
end
```

If you use both camera view and projection in your render script you will get a camera view into your game world with 3D perspective, even if your game content is strictly 2D. This is sometimes useful. You can, for instance, move the camera back to reveal more of the level. A simple camera script that measures the current camera move speed and pulls it back relative that speed could look like this:

```
-- camera.script

function init(self)
    msg.post("#camera", "acquire_camera_focus")
    -- Track current position and where someone told us to look at.
    self.pos = go.get_world_position()
    self.look_at = self.pos
end

function update(self, dt)
    -- Calculate a new position based on current pos interpolated towards current
    -- target position.
    self.pos = vmath.lerp(0.03, self.pos, self.look_at)
    -- Measure speed on the 2D plane (zero Z)
    local v1 = go.get_world_position()
    v1.z = 0
    local v2 = self.pos
    v2.z = 0
    local speed = vmath.length(v2 - v1)
    -- Depending on how fast player is moving, pull camera back or push it forward.
    self.pos.z = 500 + speed * speed * 10
    go.set_position(self.pos)
end

function on_message(self, message_id, message, sender)
    -- This camera reacts to "look_at" messages with a position as where
    -- to go.
    if message_id == hash("look_at") then
        self.look_at = message.position
    end
end
```

#### Camera speed distance 

Of course, we’re not limited to moving the camera around. We can also rotate it along its X, Y and Z axis.

```
-- 0.314 radians is about 18 degrees.
go.set_rotation(vmath.quat_rotation_z(0.314) * vmath.quat_rotation_y(0.314))
```

#### Rotated camera

[VIDE]

#### Orthographic projection

For many 2D games, the business of having a camera that can move back and forth becomes a problem, especially if you have content that you would like to render pixel perfect. Instead of trying to place your camera at the perfect Z distance to get the view you want, you should instead set up a camera with orthographic projection. This means that the view of the camera is no longer dictated by a frustum, but by a much simpler box.
 Orthographic projection 

Orthographic projection is unrealistic in that it does not alter the size of objects based on their distance. A person standing 10000 meters away will still render at the same size as the person standing right in front of the camera. However, this method of projecting graphics is sometimes useful and 2D games often benefit from using it. To use orthographic projection you just have to modify your render script:

```
-- example.render_script

function update(self)
    ...
    render.set_view(self.view)
    -- Set up an orthographic projection based on the width and height of the
    -- game window.
    local w = render.get_width()
    local h = render.get_height()
    render.set_projection(vmath.matrix4_orthographic(- w / 2, w / 2, -h / 2, h / 2, -1000, 1000))
    ...
end

function on_message(self, message_id, message)
    if message_id == hash("set_view_projection") then
        -- Camera view and projection arrives here. We only need the view.
        self.view = message.view
    end
end
```

This is almost what the default render script does, with the difference that the above example centers the screen at the camera position.

### Collection

Un jeu ne peut pas fonctionner sans collection. En effet, ces dernières rassemblent tous les éléments nécessaires à un écran du jeu dans une arborescence. Une collection est toujours définie sous forme d'un fichier.

#### Créer une collection

Pour créer une nouvelle collection, dans la vue `Assets`, faites un clic droit à l'emplacement de votre choix, choisissez `New` > `Collection` et donnez-lui un nom. *Defold* utilise l'extension `.collection` pour les fichiers collection. La boîte de dialogue `New Collection` apparaît :

![New Collection dialog](defold_new_collection_dialog.png)

- Le champ `Name` vous permet de définir le nom de la collection.
- Le champ `Location` et le bouton `Browse…` vous permettent de définir l'emplacement de la collection dans votre projet.
- Le champ `Path` indique le chemin complet de la collection.

Cliquez sur le bouton `OK` pour créer la collection ou le bouton `Cancel` pour annuler. La vue `Editor` affiche un onglet contenant la nouvelle collection :

![New Collection Editor view](defold_new_collection_editor_view.png)

La vue `Outline` montre que celle-ci ne possède pour le moment aucun sous-élément :

![New Collection Outline view](defold_new_collection_outline_view.png)

Vous pouvez désormais attacher des sous-collections ou des game objects (en place ou externes) à cette collection par un clic droit dans la vue `Outline`.

#### Attacher un game object en place à une collection

Pour attacher un game object en place à une collection, dans la vue `Outline`, faites un clic droit sur la collection et choisissez l'option `Add Game Object` (touche `A`) :

![New Game Object In Place menu](defold_new_game_object_in_place.png)

Le nouveau game object apparaît dans l'arborescence de la vue `Outline` et ses propriétés s'affichent dans la vue `Properties` :

![New Game Object In Place Outline and Properties](defold_new_game_object_in_place_outline_and_properties.png)

Vous pouvez désormais attacher des components ou des sous-game objects (en place ou externes) à ce game object par un clic droit dans la vue `Outline`.

#### Attacher un fichier ressource game object à une collection

Si vous voulez attacher un fichier ressource game object (préexistant sous la forme d'un fichier) dans la vue `Assets`, faites un clic droit sur la collection dans la vue `Outline`, choisissez l'option `Add Game Object File` puis choisissez le game object désiré.

### Collection Factory

Un component `Collection Factory` sert à générer dynamiquement un collection autant de fois que nécessaire dans le jeu.

#### Créer un fichier ressource Collection Factory

Pour créer un fichier ressource collection factory, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Collection Factory`.  La boîte de dialogue `New Collection Factory` apparaît :

![New Collection Factory dialog](defold_new_collection_factory_dialog.png)

- Le champ `Name` vous permet de définir le nom de la collection factory.
- Le champ `Location` et le bouton `Browse…` vous permettent de définir l'emplacement de la collection factory dans votre projet.
- Le champ `Path` indique le chemin complet de la collection factory (lecture seule).

Cliquez sur le bouton `OK` pour créer la collection factory ou le bouton `Cancel` pour annuler. La vue `Editor` affiche un onglet contenant la nouvelle collection factory :

![New Collection Factory Editor view](defold_new_collection_factory_editor_view.png)

**Remarque :** Ce component peut être attaché en place à un game object.

#### Propriétés de Collection Factory

Les propriétés suivantes sont accessibles dans la vue `Properties` ainsi que dans la vue `Editor` :

![Collection Factory properties list](defold_collection_factory_properties.png)

- Le champ `Prototype` vous permet de définir le fichier collection à utiliser comme modèle de production de la collection factory.
- La case `Load Dynamically` (inaccessible si le component est créé en place) vous permet de définir si la collection à produire devra être chargée dynamiquement (coché) ou si elle est chargée automatiquement dès le chargement de la collection factory (décoché). Par défaut, décoché.

[VIDE]

### Collection Proxy

Un component `Collection Proxy` sert à générer un collection associée dans un nouvel environnement. Utilisez-le pour charger différents niveaux ou écrans de jeu.

#### Créer un fichier ressource Collection Proxy

Pour créer un fichier ressource collection proxy, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Collection Proxy`. La boîte de dialogue `New Collection Proxy` s'affiche :

![New Collection Proxy dialog](defold_new_collection_proxy_dialog.png)

- Le champ `Name` vous permet de définir le nom du collection proxy.
- Le champ `Location` et le bouton `Browse…` vous permettent de définir l'emplacement du collection proxy dans votre projet.
- Le champ `Path` indique le chemin complet du collection proxy (lecture seule).

Cliquez sur le bouton `OK` pour créer le collection proxy ou le bouton `Cancel` pour annuler. La vue `Editor` affiche un onglet contenant le nouveau collection proxy :

![New Collection Proxy Editor view](defold_new_collection_proxy_editor_view.png)

**Remarque :** Ce component peut également être attaché en place à un game object.

#### Propriétés de Collection Proxy

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Collection Proxy properties list](defold_collection_proxy_properties.png)

- Le champ `Collection` vous permet de définir le fichier collection à utiliser comme modèle de production du collection proxy.
- La case `Exclude` vous permet d'exclure la collection spécifiée dans le champ `Collection` du jeu. Vous pourrez par la suite téléchargez cette collection depuis un script de mise à jour live.

### Collision Object

Utilisez un component `Collision Object` pour attribuer un comportement physique à un game object.

#### Créer un fichier ressource Collision Object

Pour créer un fichier ressource collision object, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Collision Object`. La boîte de dialogue `New Collision Object` s'affiche :

![New Collision Object dialog](defold_new_collision_object_dialog.png)

- Le champ `Name` vous permet de définir le nom du collision object.
- Le champ `Location` et le bouton `Browse…` vous permettent de définir l'emplacement du collision object dans votre projet.
- Le champ `Path` indique le chemin complet du collision object (lecture seule).

Cliquez sur le bouton `OK` pour créer le collision object ou le bouton `Cancel` pour annuler. La vue `Editor` affiche un onglet contenant le nouveau collision object :

![New Collision Object Editor view](defold_new_collision_object_editor_view.png)

**Remarque :** Ce component peut également être attaché en place à un game object.

#### Propriétés des collision objects

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Collision Object properties list](defold_collision_object_properties.png)

- Le champ `Collision Shape` vous permet de définir le fichier ressource tile map possédant une collision shape. Ne fonctionne que si le game object associé possède également un component `Tile Map`. Dans le cas contraire, laissez cette propriété vide et attachez des ressources `Shape` au collision object.
- Le menu déroulant `Type` vous permet de définir le type de comportement physique du game object associé :
  - L'option `Dynamic` définit un objet physique qui simule un comportement semi-réaliste d'un objet réel.
  - L'option `Kinematic` définit un objet dont la gestion de la physique est dépendante du programmeur. C'est le type idéal pour un object contrôlé par le joueur.
  - L'option `Static` définit un objet physique immobile (par exemple, un mur) qui ne réagit pas aux contacts des autres objects mais qui a une influence sur leur physique.
  - L'option `Trigger` définit un object sans comportement physique mais qui déclenche un évènement en cas de contact.
- Le champ `Mass` vous permet de définir la masse du collision object. Si son type est `Dynamic` vous devez attribuer une masse non nulle.
- Le champ `Friction` vous permet de définir l'intensité de la friction du game object associé au moment d'un contact avec un autre game object appartenant au groupe de collision défini dans la propriété `Mask`. La valeur doit être comprise entre `0` (pas de friction) et `1` (friction maximale). La propriété de chaque collision object en contact est multipliée pour donner la valeur finale. Ce qui veut dire qu'un objet ayant une friction nulle donnera une valeur finale nulle.
- Le champ `Restitution` vous permet de définir l'intensité du rebond du game object associé au moment du contact avec un autre game object appartenant au groupe de collision défini dans la propriété `Mask`. La valeur doit être comprise entre `0` (pas de rebond) et `1` (rebond maximal). La valeur finale sera celle de l'objet en contact ayant la valeur la plus élevée.
- Le champ `Linear Damping` vous permet de définir l'intensité de la réduction de vélocité du game object associé à chaque affichage. La valeur doit être comprise entre `0` (pas de réduction) et `1` (réduction maximale).
- Le champ `Angular Damping` vous permet de définir l'intensité de la réduction de la rotation du game object associé à chaque affichage. La valeur doit être comprise entre `0` (pas de réduction) et `1` (réduction maximale).
- La case `Locked Rotation` (si cochée) vous permet d'empêcher la rotation du game object associé lors des collisions. Par défaut désactivé.
- Le champ `Group` vous permet de définir le groupe de collision auquel appartient le collision object (inutile pour les tilemaps car la propriété est déjà définie dans la tile source). Vous pouvez définir jusqu'à 16 groupes dans un projet.
- Le champ `Mask` vous permet de définir la liste des groupes de collision qui peuvent intéragir avec le collision object. Séparez les groupes par une virgule. Si ce champ est vide, aucune collision n'est prise en compte.

**Remarque :** Pour plus d'information sur la gestion de la physique dans *Defold*, consultez la section de la documentation sur la [physique](https://www.defold.com/manuals/physics/).

#### Ajouter des ressources Shapes au collision object

Si le game object associé n'a pas de tile map, pour que ce component fonctionne avec le moteur physique, vous devez lui attacher une ou plusieurs ressources `Shape`. Faites un clic droit dans la vue `Outline` sur le collision object, choisissez `Add Shape` puis choisissez la forme `Box` (rectangle), `Capsule` ou `Sphere`. Dans la vue `Editor`, modifiez la position, la taille et/ou l'échelle des shapes. Vous pouvez également utiliser la vue `Properties` pour paramétrer précisément les propriétés.

### Cubemap

[VIDE]

### Display Profiles

[VIDE]

### Factory

#### Créer un fichier ressource Factory

Pour créer un fichier ressource Factory, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Factory`.

**Remarque :** Ce component peut être attaché en place à un game object.

#### Propriétés de Factory

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Factory properties list](defold_factory_properties.png)

[VIDE]

### Font

[VIDE]

### Fragment Program

[VIDE]

### Game Object

Vous pouvez créer un fichier ressource game object réutilisable en faisant un clic droit dans la vue `Assets` et choisissez `New` > `game object` et donnez-lui un nom. *Defold* utilse l'extension `.go` pour les fichiers ressources game object.
Vous pouvez également créer un `game object` intégré en l'attachant à une collection ou à un autre `game object` directement dans la vue `Outline`.

#### Créer un game object en place

[VIDE]

#### Créer un fichier ressource Game Object

Pour créer un fichier ressource `Game Object`, dans la vue `Assets` faites un clic droit à l'endroit où vous souhaitez créer le game object et choisissez l'option `New...` > `Game Object`.

La boîte de dialogue `New Game Object` apparaît :

![Assets New Game Object menu](defold_new_game_object.png)

- Le champ `Name` vous permet de définir le nom du game object.
- Le champ `Location` et le bouton `Browse…` vous permettent de définir l'emplacement du game object dans votre projet.
- Le champ `Path` indique le chemin complet du game object.

Cliquez sur le bouton `OK` pour créer le game object ou le bouton `Cancel` pour annuler. La vue `Editor` affiche un onglet contenant le nouveau game object.

![New Game Object Editor view](defold_new_game_object_editor_view.png)

La vue `Outline` montre que celui-ci ne possède pour le moment aucun component.

![New Game Object Outline view](defold_new_game_object_outline_view.png)

Vous pouvez désormais attacher des sous-collections ou des game objects (en place ou externes) à cette collection par un clic droit dans la vue `Outline`.

#### Attacher un component à un game object

Dans la vue `Editor`, l'onglet actif doit être un game object ou une collection pour que la vue `Outline` en affiche la structure. Pour attacher en place un component à un game object, dans la vue `Outline`, faites un clic droit sur le game object, choisissez l'option `Add Component` puis choisissez un component à attacher (c'est-à-dire directement intégré au fichier ressource contenant le game object) au game object sélectionné.

![Add Component menu](defold_add_component.png)

Le component attaché en place apparaît dans la vue `Outline`.

![Component in place](defold_outline_component_in_place.png)

**Remarque :** Seuls les components de type `Camera`, `Collection Factory`, `Collection Proxy`, `Collision Object`, `Factory`, `Label`, `Model`, `Sound`, `Spine Model` et `Sprite` peuvent être attachés en place à un game object.

![In Place Components list](defold_in_place_components_list.png)

Si vous voulez attacher un fichier ressource component préexistant (par exemple, pour le réutiliser dans plusieurs game objects) dans la vue `Assets`, faites un clic droit sur le game object ouvert dans la vue `Outline` et choisissez l'option `Add Component File` :

![Add Component File menu](defold_add_component_file.png)

La boîte de dialogue `Select Component File` apparaît. Choisissez alors le fichier correspondant à la ressource à attacher au game object selectionné :

![Select Component File dialog](defold_select_component_file_dialog.png)

Contrairement à un component attaché en place, un component défini dans un fichier ressource apparaît en *italique* suivi du chemin du fichier dans la vue `Outline` :

![Component File reference](defold_outline_component_reference.png)

**Conseil :** Utilisez les components définis dans des fichiers ressources lorsque vous souhaitez les réutiliser dans plusieurs game objects.

### Gamepads

[VIDE]

### Gui

[VIDE]

### Gui Script

[VIDE]

### Input Binding

[VIDE]

### Label

#### Créer un fichier ressource Label

Pour créer un fichier ressource Label, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Label`.

**Remarque :** Ce component peut être attaché en place à un game object.

#### Propriétés de Label

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Label properties list](defold_label_properties.png)

[VIDE]

### Lua Module

[VIDE]

### Material

[VIDE]

### Model

#### Créer un fichier ressource Model

Pour créer un fichier ressource Model, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Model`.

**Remarque :** Ce component peut être attaché en place à un game object.

#### Propriétés de Model

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Model properties list](defold_model_properties.png)

[VIDE]

### Particle FX

[VIDE]

### Render

[VIDE]

### Render Script

[VIDE]

### Script

#### Créer un fichier ressource Script

Pour créer un fichier ressource Script, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Script`.

[VIDE]

### Sound

#### Créer un fichier ressource Sound

Pour créer un fichier ressource Sound, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Sound`.

**Remarque :** Ce component peut être attaché en place à un game object.

#### Propriétés de Sound

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Sound properties list](defold_sound_properties.png)

[VIDE]

### Spine Model

#### Créer un fichier ressource Spine Model

Pour créer un fichier ressource Spine Model, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Spine Model`.

**Remarque :** Ce component peut être attaché en place à un game object.

#### Propriétés de Spine Model

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Spine Model properties list](defold_spine_model_properties.png)

[VIDE]

### Spine Scene

[VIDE]

### Sprite

#### Créer un fichier ressource Sprite

Pour créer un fichier ressource Sprite, faites un clic droit dans la vue `Assets` à l'emplacement désiré et choisissez l'option `New...` > `Sprite`.

**Remarque :** Ce component peut être attaché en place à un game object.

#### Propriétés de Sprite

Les propriétés suivantes sont accessibles dans la vue `Properties` :

![Sprite properties list](defold_sprite_properties.png)

[VIDE]

### Texture Profiles

[VIDE]

### Tile Map

[VIDE]

### Tile Source

Un fichier ressource `Tile Source` contient une référence à un seul fichier image constitué d'un groupe d'images placées sur une grille homogène. Utilisez cette ressource pour définir des animations d'une sprite sheet à utiliser avec une ressource `Sprite` ou un jeu de tuiles d'une tile sheet à utiliser avec une ressource `Tile Map`.

#### Créer une tile source

Pour créer un fichier ressource tile source, faites un clic droit dans la vue `Assets` à l'emplacement désiré puis choisissez l'option `New...` > `Tile Source`. La boîte de dialogue `New Tile Source` apparaît :

![New Tile Source dialog](defold_new_tile_source_dialog.png)

- Le champ `Name` vous permet de définir le nom de la tile source.
- Le champ `Location` et le bouton `Browse` vous permettent de définir l'emplacement de la tile source.
- Le champ `Path` affiche le chemin complet de la tile source.

Cliquez sur le bouton `OK` pour créer la tile source ou sur le bouton `Cancel` pour annuler. Une nouvelle tile source vide apparaît dans la vue `Editor` :

![New Tile Source Editor view empty](defold_new_tile_source_editor.png)

La vue `Editor` indique que la tile source nécessite de définir sa propriété `Image` (`'Image' must be specified`).

#### Attacher un fichier ressource image à une tile source 

Dans la vue `Properties`, cliquez sur l'icônes `...` à droite du champ `Image` :

![New Tile Source Outline and Properties view empty](defold_new_tile_source_outline_and_properties.png)

La boîte de dialogue `Select Resource` apparaît :

![Tile Source Select Resource dialog](defold_tile_source_select_resource_dialog.png)

Choisissez le fichier ressource image à utiliser puis cliquez sur le bouton `OK`. La vue `Editor` affiche l'image importée (pour centrer la vue sur l'image appuyez sur la touche `F`). En haut à gauche, un texte indique le numéro de tuile de l'image survolée par la souris :

![Tile Source Editor](defold_tile_source_editor.png)

#### Propriétés d'une tile source

La vue `Properties` vous permet de définir les propriétés de la tile source :

![Tile Source Properties](defold_tile_source_properties.png)

- Le champ `Image` vous permet de définir le fichier ressource image à utiliser dans la tile source.
- Les champs `W` (largeur) et `H` (hauteur) de la section `Size` affichent les dimensions en pixels de l'image utilisée dans la tile source.
- Le champ `Tile Width` vous permet de définir la largeur en pixels des cases de la tile source.
- Le champ `Tile Height` vous permet de définir la hauteur en pixels des cases de la tile source.
- Le champ `Tile Margin` vous permet de définir la marge en pixels à créer autour des cases de la tile source.
- Le champ `Tile Spacing` vous permet de définir l'espacement en pixels existant entre les cases de la tile source dans le fichier d'origine.
- Le champ `Extrude Borders` vous permet de définir la taille en pixels du débordement à effectuer sur les bords des images de la tile source. *Defold* reproduit les pixels des images touchant les bords des cases le nombre spécifié dans cette section. Cela est utile lorsque le fragment shader échantillonne les pixels au bord d'une image, les pixels de l'image voisine peuvent apparaître et causer des problèmes d'affichage. Cette option permet d'éviter ce problème.
- Le champ `Inner Padding` vous permet de définir l'espacement en pixels à ajouter entre les cases de la tile source.
- Le champ `Collision` vous permet de définir un fichier ressource image à utiliser en tant que collision.

#### Définir des animations de tile source

Une tile source permet de définir des animations composées d'images successives dans l'image source. Pour créer une nouvelle animation, dans la vue `Outline` faites un clic droit sur la tile source et choisissez l'option `Add` > `Animation` :

![Tile Source Add Animation menu](defold_tile_source_add_animation_menu.png)

Une nouvelle animation apparaît dans la vue `Outline` :

![Tile Source New Animation Outline view](defold_tile_source_new_animation_outline.png)

##### Propriétés d'animations de tile source

Editez les propriétés de l'animation dans la vue `Properties` :

![Tile Source New Animation Properties view](defold_tile_source_new_animation_properties.png)

- Le champ `Id` vous permet de définir le nom de l'animation.
- Le champ `Start Tile` vous permet de définir l'index de la première tuile de l'animation.
- Le champ `End Tile` vous permet de définir l'index de la dernière tuile de l'animation.
- Le menu déroulant `Playback` vous permet de définir la façon de lire l'animation :
  - L'option `None` bloque la lecture de l'animation sur la première tuile.
  - L'option `Once Forward` lit l'animation en avant une seule fois.
  - L'option `Once Backward` lit l'animation en arrière une seule fois.
  - L'option `Once Ping Pong` lit l'animation en avant puis en arrière une seule fois.
  - L'option `Loop Forward` lit l'animation en avant indéfiniment.
  - L'option `Loop Backward` lit l'animation en arrière indéfiniment.
  - L'option `Loop Ping Pong` lit l'animation en avant puis en arrière indéfiniment.
- Le champ `Fps` vous permet de définir la vitesse de lecture de l'animation (en images par secondes).
- Le champ `Flip Horizontal` vous permet de retourner horizontalement l'animation (décoché par défaut).
- Le champ `Flip Vertical` vous permet de retourner verticalement l'animation (décoché par défaut).

**Remarque :** Appuyez sur la touche `ESPACE` pour lire l'animation sélectionnée.

### Vertex Program

[VIDE]

## Programmation

La programmation de la logique du jeu s'effectue dans des fichiers scripts écrits en langage *Lua* et attachés à des components dans des game objects. La communication entre différents components s'effectue par un système de messages dans *Defold*.

### Portée des variables

Les variables locales à un script (hors de toute fonction) sont communes à toutes les instances contenant ce script :

`local nom_de_propriete = valeur`

Les propriétés associées au paramètre `self` de certaines fonctions sont uniques à chaque instance contenant ce script :

```
function init(self)
    self.nom_de_propriete = valeur
end
``` 

### Définir une propriété visible dans la vue Properties

Pour définir une propriété qui apparaîtra dans la vue `Properties`, utilisez la fonction `go.property` en dehors de toute fonction plutôt que la syntaxe *Lua* habituelle :

```
go.property("nom_de_propriete", valeur)
```

**Remarque :** La valeur attribuée définit le type de la propriété. Cela peut être une valeur de type :
- nombre (entier ou à virgule)
- booléen
- hash
- URL
- vector3
- vector4
- quaternion

Une propriété définie avec la fonction `go.property` est accessible depuis le paramètre `self` des fonctions de rappel :

```
function update(self, dt)
    self.nom_de_propriete = valeur
end
```

Vous pouvez éditer cette propriété dans la vue `Properties`. Si vous modifiez sa valeur, le nom du champ associé devient bleu et un bouton vous permet de réinitialiser la valeur à celle par défaut.

### Adressage

Pour cibler le script courant, utiliser la chaîne `"#"` :

`"#"`

Pour cibler le game object courant, utiliser la chaîne `"."` :

`"."`

Pour cibler un component situé dans le même game object que le script, utilisez l'identifiant du component précédé du signe `#` :

`#component_id`

Pour cibler un component situé dans un autre game object que le script mais dans la même collection, utilisez l'identifiant du game object, suivi du signe `#` puis de l'identifiant du Component :

`go_id#component_id`

Pour cibler un component situé dans un autre game object que le script et dans une autre collection statique, vous devez utiliser l'adressage absolu. Utilisez le caractère `/` pour indiquer que vous commencez l'adressage à la racine suivi de l'identifiant de la collection à cibler suivi du caractère `/` puis de l'identifiant du game object, suivi du signe `#` et enfin de l'identifiant du component :

`/main/go_id#component_id`

**Remarque :** Vous pouvez également cibler une sous-collection :

`/main/sub/go_id#component_id`

Pour cibler un component situé dans un autre game object que le script et dans une collection générée par un component `Collection Proxy`, vous devez utiliser l'adressage absolu en précisant le socket du monde de jeu à cibler. Utilisez l'identifiant de la collection à cibler suivi des caractères `:/` puis de l'identifiant du game object, suivi du signe `#` et enfin de l'identifiant du component :

`main:/go_id#component_id`

**Remarque :** Vous pouvez également cibler une sous-collection :

`main:/sub/go_id#component_id`

#### Envoyer un message

Pour envoyer un message à un script d'un autre game object, utilisez la fonction `msg.post` :

`msg.post(other_game_objet#other_script, "message")`

Chaque game object ou component supporte un certain nombre de messages associés à des fonctions à exécuter. Consultez la section [API](https://www.defold.com/ref/sys/) de la documentation de *Defold*.

### Créer un game object depuis un script

[VIDE]

## Astuces diverses

### Définir la collection principale

Ouvrez le fichier `game.project`. Dans la section `Bootstrap`, affectez le fichier collection de votre choix au champ `Main Collection`.

### Définir les dimensions logiques du jeu

Ouvrez le fichier `game.project`. Dans la section `Display`, saisissez la largeur dans le champ `Width` et la hauteur dans le champ `Height` (en pixels).

### Afficher une image

Attachez à la collection définie comme collection principale un game object et attachez à celui-ci un component `Sprite`. Enfin, attribuez au sprite un atlas contenant des images ou une animation et choisissez une animation.

### Afficher des images en pixel art

N'oubliez pas de configurer le paramètre `Default Texture Mag Filter` de la section `graphics` à la valeur `nearest` dans le fichier de configuration `game.project` pour afficher vos images sans filtre de lissage.

### Quitter le jeu avec la touche Echap

Dans le menu `File` > `Preferences`, dans l'onglet `General`, cochez la case `Escape Quits Game`. Cette option ne fonctionne qu'en phase de test.

### Tester une modification de script sans redémarrer le jeu

Avec la commande `File` > `Hot Reload`, vous pouvez tester les modifications apportées à un script alors que votre jeu s'exécute déjà.

### Détruire un game object depuis un script

Dans la fonction `update`, utilisez la fonction `go.delete` (en général selon une condition particulière) :

```
function update(self, dt)
    if go.get_position().x < 0 then
        go.delete()
    end
end
```

#### Paramétrer les valeurs de configuration au démarrage du moteur

Lorsque le moteur démarre, vous pouvez fournir des valeurs de configuration depuis la ligne de commande pour remplacer le paramètre du fichier `game.project` :

```
# Spécifie une collection bootstap
$ dmengine --config=bootstrap.main_collection=/my.collectionc

# Paramètre la valeur personnalisée "test.ma_valeur"
$ dmengine --config=test.ma_valeur=4711
```

Les valeurs personnalisées peuvent être lues (comme toute autre valeur de configuration) depuis la fonction `sys.get_config()`.