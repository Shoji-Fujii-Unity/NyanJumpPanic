# Nyan Jump Panic! / にゃんジャム！パニック

このリポジトリには、スマートフォンとPCの両方で遊べる3D猫アクションゲーム「Nyan Jump Panic! / にゃんジャム！パニック」が含まれています。

ファイルは 1 つの HTML で完結しており、追加のビルドやインストールは不要です。

---

## 日本語

### ゲーム名

Nyan Jump Panic! / にゃんジャム！パニック

### 概要

プレイヤーは猫のキャラクターを操作し、奥行きのある3Dステージを進みながら、リンゴを集め、木箱を壊し、敵を倒し、穴・トゲ・炎・回転障害・動く足場などのギミックを避ける横スクロール的な3Dアクションゲームです。

基本は左右方向への移動ですが、ステージによっては画面奥方向へ進む構造も用意されています。

本作は、以下の一連の流れを短いステージの中で何度も繰り返して攻略することを目的としています。

- ジャンプで足場を渡る
- 箱を壊す
- アイテムを集める
- 敵を倒す
- トラップを避ける

### 遊び方

- プレイヤーは猫を操作してゴールを目指します。
- リンゴを集めることでスコアと収集率が上がります。
- 回転攻撃で木箱を壊せます。
- 木箱の中にはボーナスリンゴが含まれる場合があります。
- 敵キャラクターはジャンプまたは回転攻撃で倒せます。
- 穴に落ちると、直近のチェックポイントから再開します。
- 敵やトゲ、炎、回転棒に触れるとミスになります。
- ステージクリア後に評価と収集率が表示されます。

### 評価について

ステージクリア後の評価は次の条件で決まります。

- 3つ星: 死亡0回、リンゴ収集100パーセント
- 2つ星: リンゴ収集100パーセント、または死亡1回以内
- 1つ星: 通常クリア

スコアはリンゴ収集、箱破壊、敵撃破、タイムボーナス、死亡ペナルティから計算されます。

### ファイル構成

このゲームは次の1つのファイルで動作します。

- index.html

### 遊び方

PCの場合:

1. index.html をブラウザで開きます。
2. スタートボタンを押して開始します。

スマホの場合:

1. index.html をブラウザで開きます。
2. 横画面にしてください。
3. スタートボタンを押して開始します。

初回は通信が必要です。ゲーム内部で外部ライブラリを使用しているため、オフライン環境では正常に動作しない場合があります。

### PCでの操作

移動: WASD または 矢印キー

ジャンプ: Space / Z / K

回転攻撃: X / J

走る: Shift

ポーズ: Esc / P

### スマホでの操作

左下のスティック: 移動

Aボタン: ジャンプ

Bボタン: 回転攻撃

Cボタン: 走る

### サウンド

タイトル画面とゲーム中のHUDで、サウンドをオンまたはオフにできます。

- SOUND ON
- SOUND OFF

### 多言語対応

ゲーム内メニューは次の言語に対応しています。

- 日本語
- English
- Español
- Français
- 简体中文

タイトル画面またはゲーム中メニューの言語ボタンから切り替えられます。

### セーブデータ

セーブデータは端末上のブラウザに保存されます。

保存される内容は次の通りです。

- 解放済みステージ
- ステージごとの最高記録
- 言語設定
- サウンド設定

### データの保存場所

このゲームはサーバーにデータを保存しません。

ブラウザの localStorage に保存されます。

そのため、次の場合はセーブデータが消えることがあります。

- ブラウザのキャッシュやサイトを削除した
- 別のブラウザで開いた
- 別の端末で開いた
- 非公開モードで開いた

### セーブデータの削除

タイトル画面、またはステージ選択画面から、セーブデータを消去できます。

- セーブ消去
- RESET SAVE
- BORRAR
- EFFACER
- 删除存档

### 対応ブラウザ

次のような最近のブラウザでの動作を想定しています。

- Chrome
- Edge
- Firefox
- Safari

PCとモバイルの両方で動作しますが、モバイルでは横画面表示でプレイしてください。

### 動作に必要なもの

このゲームはブラウザでそのまま動作します。

追加のインストールは不要です。

ただし、外部ライブラリを使用しているため、初回はネットワーク接続が必要です。

### 開発メモ

このゲームは次の技術を想定して作られています。

- HTML
- CSS
- JavaScript
- Three.js
- Web Audio API
- localStorage

追加のビルド工程はありません。

---

## English

### Game Name

Nyan Jump Panic! / にゃんジャム！パニック

### Overview

Nyan Jump Panic! is a 3D cat action game that can be played on both smartphones and PCs.

The player controls a cat character moving through a stage with depth, collecting apples, breaking wooden boxes, defeating enemies, and avoiding obstacles such as pits, spikes, fire, rotating bars, and moving platforms.

The game focuses on a repeating gameplay loop:

- Jump across platforms
- Break boxes
- Collect items
- Defeat enemies
- Avoid traps

Short stages are designed to be replayed and mastered.

### Gameplay

- Reach the goal of each stage.
- Collect apples to increase score and collection rate.
- Break wooden boxes using spin attack.
- Some boxes contain bonus apples.
- Defeat enemies by stomping or using spin attack.
- Falling into a pit returns you to the last checkpoint.
- Touching enemies, spikes, fire, or rotating bars causes failure.
- After clearing a stage, your score and collection rate are shown.

### Ranking

Stage clear evaluation is calculated as follows:

- 3 stars: no deaths, 100 percent apple collection
- 2 stars: 100 percent apple collection, or only one death
- 1 star: normal clear

Score is calculated from apples collected, boxes broken, enemies defeated, time bonus, and death penalty.

### File Structure

The game is contained in a single HTML file:

- index.html

### How to Play

On PC:

1. Open index.html in a web browser.
2. Press the start button.

On mobile:

1. Open index.html in a web browser.
2. Rotate your device to landscape orientation.
3. Press the start button.

The first run requires network access because the game loads external libraries.

### PC Controls

Move: WASD or Arrow Keys

Jump: Space / Z / K

Spin Attack: X / J

Run: Shift

Pause: Esc / P

### Mobile Controls

Left joystick: Move

Button A: Jump

Button B: Spin Attack

Button C: Run

### Sound

Sound can be turned on or off from the title screen or the in-game menu.

- SOUND ON
- SOUND OFF

### Languages

The in-game interface supports the following languages:

- Japanese
- English
- Spanish
- French
- Simplified Chinese

You can switch languages from the language button on the title screen or in-game menu.

### Save Data

Save data is stored locally in your browser.

The following data is saved:

- Unlocked stages
- Best score per stage
- Language setting
- Sound setting

### Save Location

The game does not use a server.

It uses browser localStorage.

Save data may disappear in the following cases:

- You cleared browser cache or site data
- You used a different browser
- You used a different device
- You used private or incognito mode

### Delete Save Data

You can delete saved data from the title screen or stage select screen.

Options include:

- RESET SAVE
- BORRAR
- EFFACER
- 删除存档

### Supported Browsers

The game is intended to run on modern browsers:

- Chrome
- Edge
- Firefox
- Safari

It supports both desktop and mobile, but mobile play requires landscape orientation.

### Requirements

The game runs directly in a browser.

No installation is required.

Network access is required on first load because external libraries are used.

### Technical Notes

The game uses:

- HTML
- CSS
- JavaScript
- Three.js
- Web Audio API
- localStorage

No build step is required.

---

## Español

### Nombre del Juego

Nyan Jump Panic! / にゃんジャム！パニック

### Descripción

Nyan Jump Panic! es un juego de acción 3D con un personaje de gato, diseñado para jugarse tanto en smartphones como en PC.

El jugador controla a un gato que avanza por escenarios tridimensionales recogiendo manzanas, rompiendo cajas de madera, derrotando enemigos y evitando obstáculos como agujeros, pinchos, fuego, barras giratorias y plataformas móviles.

El juego se centra en repetir una secuencia de acción en niveles cortos:

- Saltar entre plataformas
- Romper cajas
- Recoger objetos
- Derrotar enemigos
- Esquivar trampas

Los niveles están pensados para ser repetidos y perfeccionados.

### Cómo Jugar

- Llega a la meta de cada nivel.
- Recoge manzanas para aumentar la puntuación y el porcentaje de recolección.
- Rompe cajas con el ataque giratorio.
- Algunas cajas contienen manzanas bonus.
- Derrota enemigos saltando sobre ellos o usando el ataque giratorio.
- Si caes a un agujero, vuelves al último punto de control.
- Tocar enemigos, pinchos, fuego o barras giratorias provoca fallo.
- Al terminar un nivel se muestran puntuación y porcentaje de recolección.

### Puntuación y Estrellas

La valoración del nivel se calcula así:

- 3 estrellas: sin muertes y recolección del 100 por ciento
- 2 estrellas: recolección del 100 por ciento, o una sola muerte
- 1 estrella: superación normal

La puntuación se calcula a partir de manzanas recogidas, cajas rotas, enemigos derrotados, bonificación por tiempo y penalizaciones por muertes.

### Estructura de Archivos

El juego contiene un único archivo HTML:

- index.html

### Cómo Abrir el Juego

En PC:

1. Abre index.html en un navegador web.
2. Pulsa el botón de inicio.

En móvil:

1. Abre index.html en un navegador web.
2. Gira el dispositivo a orientación horizontal.
3. Pulsa el botón de inicio.

La primera vez se necesita conexión a internet porque se cargan librerías externas.

### Controles en PC

Moverse: WASD o teclas de flecha

Saltar: Space / Z / K

Ataque giratorio: X / J

Correr: Shift

Pausa: Esc / P

### Controles en Móvil

Joystick izquierdo: Moverse

Botón A: Saltar

Botón B: Ataque giratorio

Botón C: Correr

### Sonido

El sonido puede activarse o desactivarse desde la pantalla de título o desde el menú del juego.

- SONIDO ON
- SONIDO OFF

### Idiomas

La interfaz del juego admite los siguientes idiomas:

- Japonés
- Inglés
- Español
- Francés
- Chino simplificado

Puedes cambiar el idioma desde el botón de idioma en la pantalla de título o dentro del juego.

### Datos Guardados

Los datos se guardan localmente en el navegador.

Se guardan:

- Niveles desbloqueados
- Mejor puntuación por nivel
- Idioma seleccionado
- Configuración de sonido

### Ubicación del Guardado

El juego no usa un servidor.

Usa localStorage del navegador.

Los datos pueden desaparecer si:

- Borras la caché o los datos del sitio
- Usas otro navegador
- Usas otro dispositivo
- Usas modo privado o incógnito

### Borrar Datos

Puedes borrar los datos guardados desde la pantalla de título o desde la selección de niveles.

Opciones:

- BORRAR
- RESET SAVE
- EFFACER
- 删除存档

### Navegadores Compatibles

Se espera que funcione en navegadores modernos:

- Chrome
- Edge
- Firefox
- Safari

Es compatible con escritorio y móvil, aunque en móvil debe jugarse en horizontal.

### Requisitos

El juego funciona directamente en el navegador.

No se necesita instalación.

Se requiere conexión a la primera carga porque se usan librerías externas.

### Notas Técnicas

El juego usa:

- HTML
- CSS
- JavaScript
- Three.js
- Web Audio API
- localStorage

No hace falta compilar.

---

## Français

### Nom du Jeu

Nyan Jump Panic! / にゃんジャム！パニック

### Description

Nyan Jump Panic! est un jeu d'action 3D avec un personnage de chat, jouable à la fois sur smartphone et sur PC.

Le joueur contrôle un chat qui progresse dans des décors à profondeur, en collectant des pommes, en cassant des caisses en bois, en battant des ennemis et en évitant des pièges comme des trous, des pics, du feu, des barres rotatives et des plateformes mobiles.

Le jeu repose sur une boucle courte à répéter et à améliorer :

- Sauter sur les plateformes
- Casser des caisses
- Collecter des objets
- Battre les ennemis
- Éviter les pièges

Les niveaux sont courts et pensés pour être rejoués.

### Comment Jouer

- Atteignez l'objectif de chaque niveau.
- Collectez des pommes pour augmenter le score et le taux de collecte.
- Cassez les caisses avec l'attaque tournoyante.
- Certaines caisses contiennent des pommes bonus.
- Battez les ennemis en sautant dessus ou avec l'attaque tournoyante.
- Si vous tombez dans un trou, vous revenez au dernier point de contrôle.
- Toucher un ennemi, des pics, du feu ou une barre rotative cause un échec.
- Après la fin d'un niveau, le score et le taux de collecte sont affichés.

### Étoiles

L'évaluation du niveau est calculée ainsi :

- 3 étoiles : zéro mort et 100 pour cent de collecte
- 2 étoiles : 100 pour cent de collecte, ou une seule mort
- 1 étoile : réussite normale

Le score est calculé à partir des pommes collectées, des caisses cassées, des ennemis battus, d'un bonus de temps et des pénalités dues aux morts.

### Structure du Projet

Le jeu est contenu dans un seul fichier HTML :

- index.html

### Lancer le Jeu

Sur PC :

1. Ouvrez index.html dans un navigateur web.
2. Appuyez sur le bouton de démarrage.

Sur mobile :

1. Ouvrez index.html dans un navigateur web.
2. Tournez l'appareil en mode paysage.
3. Appuyez sur le bouton de démarrage.

La première ouverture nécessite une connexion réseau car des bibliothèques externes sont chargées.

### Commandes PC

Déplacement : WASD ou flèches

Saut : Space / Z / K

Attaque tournoyante : X / J

Course : Shift

Pause : Esc / P

### Commandes Mobile

Joystick gauche : Déplacement

Bouton A : Saut

Bouton B : Attaque tournoyante

Bouton C : Course

### Son

Le son peut être activé ou désactivé depuis l'écran-titre ou le menu du jeu.

- SON ON
- SON OFF

### Langues

L'interface du jeu prend en charge les langues suivantes :

- Japonais
- Anglais
- Espagnol
- Français
- Chinois simplifié

Vous pouvez changer la langue depuis le bouton de langue sur l'écran-titre ou pendant le jeu.

### Données Sauvegardées

Les données sont sauvegardées localement dans le navigateur.

Les informations sauvegardées sont :

- Niveaux débloqués
- Meilleur score par niveau
- Langue choisie
- Réglage du son

### Emplacement de la Sauvegarde

Le jeu n'utilise pas de serveur.

Il utilise le localStorage du navigateur.

Les données peuvent disparaître si :

- Vous effacez le cache ou les données du site
- Vous utilisez un autre navigateur
- Vous utilisez un autre appareil
- Vous utilisez la navigation privée

### Effacer la Sauvegarde

Vous pouvez supprimer les données depuis l'écran-titre ou la sélection des niveaux.

Options :

- EFFACER
- RESET SAVE
- BORRAR
- 删除存档

### Navigateurs Pris en Charge

Le jeu est conçu pour fonctionner dans les navigateurs modernes :

- Chrome
- Edge
- Firefox
- Safari

Il fonctionne sur ordinateur et mobile, mais le mode paysage est nécessaire sur mobile.

### Prérequis

Le jeu fonctionne directement dans le navigateur.

Aucune installation n'est requise.

Une connexion est nécessaire au premier chargement car des bibliothèques externes sont utilisées.

### Notes Techniques

Le jeu utilise :

- HTML
- CSS
- JavaScript
- Three.js
- Web Audio API
- localStorage

Aucune étape de compilation n'est nécessaire.

---

## 简体中文

### 游戏名称

Nyan Jump Panic! / にゃんジャム！パニック

### 简介

Nyan Jump Panic! 是一款可在智能手机和电脑浏览器中游玩的 3D 猫动作游戏。

玩家操作一只猫，在具有纵深结构的关卡中前进，收集苹果，破坏木箱，消灭敌人，并躲避坑洞、尖刺、火焰、旋转障碍和移动平台等机关。

游戏强调在短关卡中反复进行以下流程：

- 跳跃通过平台
- 破坏木箱
- 收集道具
- 消灭敌人
- 避开陷阱

关卡设计为短流程，鼓励玩家反复挑战并提高成绩。

### 玩法说明

- 前往每个关卡的终点。
- 收集苹果提高分数和收集率。
- 使用旋转攻击破坏木箱。
- 有些木箱内含奖励苹果。
- 可通过踩踏或旋转攻击消灭敌人。
- 掉入坑洞会从最近的检查点继续。
- 碰到敌人、尖刺、火焰或旋转杆会导致失败。
- 通关后会显示成绩和收集率。

### 星级评价

关卡评价如下：

- 3星：无死亡，苹果收集率100%
- 2星：苹果收集率100%，或仅死亡一次
- 1星：普通通关

分数由苹果收集、木箱破坏、敌人消灭、时间奖励和死亡扣分计算。

### 文件结构

游戏包含一个 HTML 文件：

- index.html

### 如何开始游戏

电脑端：

1. 在浏览器中打开 index.html。
2. 点击开始按钮。

手机端：

1. 在浏览器中打开 index.html。
2. 将设备横屏。
3. 点击开始按钮。

首次运行需要网络连接，因为游戏会加载外部库。

### 电脑操作

移动：WASD 或方向键

跳跃：Space / Z / K

旋转攻击：X / J

奔跑：Shift

暂停：Esc / P

### 手机操作

左摇杆：移动

A按钮：跳跃

B按钮：旋转攻击

C按钮：奔跑

### 音效

可在标题界面或游戏内菜单中开启或关闭音效。

- 音效开
- 音效关

### 多语言支持

游戏内界面支持以下语言：

- 日语
- 英语
- 西班牙语
- 法语
- 简体中文

可通过标题界面或游戏内菜单中的语言按钮切换语言。

### 存档数据

存档保存在本地浏览器中。

会保存：

- 已解锁关卡
- 每关最高成绩
- 语言设置
- 音效设置

### 保存位置

游戏不使用服务器。

使用浏览器 localStorage 保存数据。

以下情况可能导致存档丢失：

- 清除浏览器缓存或站点数据
- 使用其他浏览器
- 使用其他设备
- 使用无痕或隐私模式

### 删除存档

可在标题界面或关卡选择界面删除存档。

选项包括：

- 删除存档
- RESET SAVE
- BORRAR
- EFFACER

### 支持浏览器

适用于较新的浏览器：

- Chrome
- Edge
- Firefox
- Safari

支持电脑和移动端，但移动端需要横屏游玩。

### 运行要求

游戏直接在浏览器中运行。

无需安装。

首次加载需要网络连接，因为使用了外部库。

### 技术说明

游戏使用：

- HTML
- CSS
- JavaScript
- Three.js
- Web Audio API
- localStorage

无需编译步骤。