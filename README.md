<p align="center">
  <img src="https://zupimages.net/up/26/43/pkwx.png" alt="Logo de MSSCMP Editor" width="128">
</p>

<h1 align="center">MSSCMP Editor</h1>

<p align="center">
  Parcourez, écoutez, extrayez et <b>remplacez les sons</b> de Minecraft PS3<br>
  directement dans sa banque <b>Minecraft.msscmp</b>, avec un outil rapide, fiable et moderne.
</p>

<p align="center">
  <a href="https://github.com/INF3CONxR7/MSSCMP_Editor/releases/latest"><img src="https://img.shields.io/github/v/release/INF3CONxR7/MSSCMP_Editor?label=t%C3%A9l%C3%A9charger&color=22D3EE" alt="Télécharger"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white" alt="Windows 10 et 11">
  <a href="https://discord.gg/TbFYvqsh5z"><img src="https://img.shields.io/badge/Discord-rejoindre-5865F2?logo=discord&logoColor=white" alt="Serveur Discord"></a>
</p>

---

## Fonctionnalités

- **Navigation** : les 1 402 sons de la banque rangés par dossiers (ambient, block, mob…), comme dans le jeu ; recherche
  et tri (nom, taille, durée, ordre du fichier).
- **Écoute** : un double-clic (ou ▶) décode et joue le son aussitôt, avec sa forme d’onde, la lecture en boucle et le
  déplacement dans le son.
- **Remplacement** : choisissez un WAV (ou glissez-le sur la ligne du son) : il est encodé en BinkA, avec une **qualité**
  réglable de 1 à 9, et s’écoute aussitôt. Un BinkA est repris tel quel. Chaque remplacement peut être annulé tant que
  la banque n’est pas enregistrée.
- **Import d’un dossier** : un dossier de WAV rangés comme à l’extraction remplace d’un coup tous les sons du même nom.
- **Extraction** : un son, un dossier ou toute la banque, en WAV (décodés à la bonne longueur) ou en BinkA d’origine,
  en recréant les dossiers de la banque.
- **Enregistrement sûr** : la banque est reconstruite puis relue et vérifiée avant d’être écrite ; une copie du fichier
  d’origine (`Minecraft.msscmp.bak`) est faite avant le premier enregistrement.
- **Mises à jour automatiques** (versions signées) et **présence Discord**.

## Installation

1. Ouvrez la [dernière version](https://github.com/INF3CONxR7/MSSCMP_Editor/releases/latest) et téléchargez
   **`MSSCMPEditor-win-x64.zip`** (le fichier `.zip.sig` sert au programme de mise à jour).
2. Extrayez l’archive à l’endroit de votre choix : vous obtenez le dossier **`MSSCMPEditor-win-x64`**. Gardez ensemble
   tous les fichiers qu’il contient : l’application en a besoin pour décoder et encoder les sons
   (`MSSCMP Editor Encoder.exe`, `binka_encode.exe`, `mss32.dll`, `binkawin.asi`) et se mettre à jour
   (`MSSCMP Editor Update.exe`).
3. Lancez **`MSSCMP Editor.exe`**.

Il faut un PC sous **Windows 10 ou 11 (64 bits)**. Rien d’autre à installer : le runtime .NET est inclus dans
l’exécutable, et le moteur BinkA utilise le .NET Framework 4.8 déjà présent dans Windows.

> **Windows SmartScreen** : l’exécutable n’est pas signé Authenticode, Windows peut donc afficher « Windows a protégé
> votre ordinateur ». Cliquez sur **Informations complémentaires**, puis sur **Exécuter quand même**.

## Utilisation

1. **Ouvrez la banque** : *Fichier › Ouvrir* (ou glissez le fichier sur la fenêtre), `Minecraft.msscmp` se trouve dans
   le dossier `PS3\Sound` du jeu (avec RPCS3 : `dev_hdd0\game\<identifiant du jeu>\USRDIR\PS3\Sound`).
2. **Choisissez un dossier** à gauche, puis **écoutez** les sons (double-clic, ▶, Entrée ou Espace).
3. **Remplacez** un son : *Remplacer* sur sa ligne, ou glissez un WAV dessus. Le son remplacé passe en ambre.
4. **Enregistrez** (*Enregistrer*, ou Ctrl+S), puis lancez le jeu. Fermez le jeu avant d’enregistrer : il garde la
   banque ouverte.

Le menu **« … »** de chaque son l’écoute, le remplace, annule son remplacement, l’extrait en WAV ou en BinkA, ou copie
son nom. **Paramètres** règle la qualité BinkA, la copie de sauvegarde, la réouverture du dernier fichier et l’activité
Discord.

## Crédits

Développé par **INF3C7ONxR7**. Les outils BinkA (`binka_encode.exe`, Miles Sound System `mss32.dll` et
`binkawin.asi`) sont de **RAD Game Tools** (Epic Games).

## Support

Une question, un bug : rejoignez le [serveur Discord](https://discord.gg/TbFYvqsh5z).
