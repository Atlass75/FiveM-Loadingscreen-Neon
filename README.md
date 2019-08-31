
# FiveM Loadingscreen Neon

*I'm the real developer of this loading screen. I decided to share you again this loading screen because I made a new version. As for this one I made some modifications and fixed some bug. Good use 🙃.*
*In case of problem or request: [https://discord.gg/4tpVfDv](https://discord.gg/4tpVfDv)*

### Images :

![Ecran de chargement](https://i.imgur.com/lBaZ5Y8.jpg)

![Lecteur MP3](https://i.imgur.com/pFToa9M.png)

### Features : 
 - Youtube video
 - Mp3 player
  - Loading bar
 
---

### Installation :
To install the loading screen:

 1. Copy the contents of the ZIP folder to your folder "`Ressources`" FiveM (n'oubliez pas de retirer le "-master" dans le nom de dossier)
 2. Add `start loadingscreen` in `the server.cfg`

---

### Configuration :
The configuration file is located in `Assets/JS/config.js`

```JS
var video_ID = "UdB4ytHvX8o" // YouTube video ID
var mp3_player = true // If true, the MP3 player will be used and the youtube video sound cut

var start = 22 // Allow to set how many seconds the Youtube video should start

var img = "Logo.png" // The file name of your server logo (* It must be in the folder: Assets / IMG *)

var Discord_link = "https://discord.gg/4tpVfDv" // Discord link

var red_text = 'California' // Red text
var blue_text = 'Island' // Blue text

// Do not forget to add your music in __resource.lua
// Place your music in the folder: Assets / AUDIO
var tracks
tracks = [{
	"track": 1, // Position in the list
	"name": "Migos - Get Right Witcha", // The name that will appear
	"duration": "",
	"file": "Migos_Get_Right_Witcha_Official_Video" // The name of the MP3 file (It must not contain spaces or special characters.
}]
```
To add music:

 1. Add the MP3 file to the folder : `Assets/AUIDO`.
 2. Open the file : `config.js`.
 3. Add :
 ```JS
 {
	"track": ID,
	"name": "My new music",
	"duration": "",
	"file": "the_name_of_file_of_my_new_music"
}
 ```
To get:
```JS
tracks = [{
	"track": 1, // Position in the list
	"name": "Migos - Get Right Witcha", // The name that will appear
	"duration": "",
	"file": "Migos_Get_Right_Witcha_Official_Video" // The name of the MP3 file (It must not contain spaces or special characters.
}, {
	"track": 2,
	"name": "My new music",
	"duration": "",
	"file": "the_name_of_file_of_my_new_music"
}]
```
4. Add the file to `__rousource.lua`

---
---

*Je suis le vrai développeur de cet écran de chargement. J'ai décidé de vous partager à nouveau cet écran de chargement car j'en ai faits une nouvelle version. Quant à celle-ci j'ai apporté quelques modifications et corrigé quelques bug. Bonne utilisation 🙃*.
*En cas de problème où de demande : [https://discord.gg/4tpVfDv](https://discord.gg/4tpVfDv)*

### Images :

![Ecran de chargement](https://i.imgur.com/lBaZ5Y8.jpg)

![Lecteur MP3](https://i.imgur.com/pFToa9M.png)

---
### Fonctionnalités :
 - Vidéo Youtube
 - Lecteur MP3
 - Barre de chargement

---
### Installation :
Pour installer l'écran de chargement rien de plus simple :

 1. Copier le contenu du dossier ZIP, dans votre dossier "`Ressources`" FiveM (n'oubliez pas de retirer le "-master" dans le nom de dossier)
 2. Ajouter `start loadingscreen` dans le server.cfg
---
### Configuration :
Le fichier de configuration se trouve dans `Assets/JS/config.js`

```JS
var video_ID = "UdB4ytHvX8o" // ID de la video Youtube
var mp3_player = true // Si true, le lecteur MP3 sera utilisé et le son de vidéo youtube coupé

var start = 22 // Permets de définir à partir de combien de secondes la vidéo Youtube doit commencer

var img = "Logo.png" // Le nom de fichier du logo de votre serveur (* Il doit se situer dans le dossier : Assets/IMG *)

var Discord_link = "https://discord.gg/4tpVfDv" // Lien de vôtre server Discord

var red_text = 'California' // Texte en rouge
var blue_text = 'Island' // Texte en bleu

// N'oubliez d'ajouter vos musiques dans le __resource.lua
// Placez vos musiques dans le dossier : Assets/AUIDO
var tracks
tracks = [{
	"track": 1, // Position dans la liste
	"name": "Migos - Get Right Witcha", // Le nom qui va apparaite
	"duration": "",
	"file": "Migos_Get_Right_Witcha_Official_Video" // Le nom du fichier MP3 (Il ne doit pas contenir d'espace ou de caractère spéciaux.
}]
```
Pour ajouter une musique rien de plus simple :

 1. Ajouter le fichier MP3 dans le dossier : `Assets/AUIDO`.
 2. Ouvrez le fichier : `config.js`.
 3. Ajouter :
 ```JS
 {
	"track": ID,
	"name": "Ma nouvelle musique",
	"duration": "",
	"file": "le_nom_de_fichier_de_ma_nouvelle_musique"
}
 ```
Pour obtenir : 
```JS
tracks = [{
	"track": 1,
	"name": "Migos - Get Right Witcha", // Le nom qui va apparête
	"duration": "",
	"file": "Migos_Get_Right_Witcha_Official_Video" // Le nom du fichier MP3 (Il ne doit pas contenir d'espace ou de caractère spéciaux.
}, {
	"track": 2,
	"name": "Ma nouvelle musique",
	"duration": "",
	"file": "le_nom_de_fichier_de_ma_nouvelle_musique"
}]
```
4. Ajouter le fichier dans `__rousource.lua`
