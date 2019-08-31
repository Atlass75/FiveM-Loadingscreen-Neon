# FiveM Loadingscreen Neon
*Je suis le vrai développeur de cet écran de chargement. J'ai décidé de vous partager à nouveau cet écran de chargement car j'en ai faits une nouvelle version. Quant à celle-ci j'ai apporté quelques modifications et quelque bug. Bonne utilisation 🙃*.
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
	"name": "Migos - Get Right Witcha", // Le nom qui va apparête
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
