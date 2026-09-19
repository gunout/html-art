# 🏛️ LA COURSE À L'ÉLYSÉE

**Un logo ASCII-art haute définition du Palais de l'Élysée, rendu en HTML pur.**

Aucun JavaScript, aucune dépendance : juste du `<pre>`, des `<b style="color:#...">` et beaucoup de caractères.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![No Dependencies](https://img.shields.io/badge/Dependencies-none-brightgreen.svg)](#)

---

## 📖 Description

Ce dépôt contient une reproduction **ASCII-art** du **Palais de l'Élysée**, entièrement générée en HTML.

Le projet inclut :

- 🇫🇷 Le **drapeau français tricolore** (bleu / blanc / rouge) intégré au sommet du dôme
- 🏛️ La **façade** détaillée du palais avec ses fenêtres, colonnes et ouvertures
- 🎨 Des **dégradés de couleurs** obtenus grâce à plus de **3 000 balises `<b style="color:#XXXXXX">`**
- ⚪ La mention **« LA COURSE À L'ÉLYSÉE »** en blanc pur au-dessus du logo

Tout tient dans un seul fichier `index.html`, lisible par n'importe quel navigateur moderne, sans aucune installation.

---

## 🖼️ Aperçu

```
                                    LA COURSE À L'ÉLYSÉE

        [LOGO ASCII HAUTE DÉFINITION DU PALAIS DE L'ÉLYSÉE]
        [avec drapeau français, dégradés et détails de la façade]
```

> 💡 Le rendu est bien plus impressionnant en vrai qu'en miniature. Ouvrez `index.html` pour vous en rendre compte.

---

## 🚀 Utilisation

### 1. Cloner le dépôt

```bash
git clone https://github.com/gunout/html-art.git
cd html-art
```

### 2. Ouvrir le fichier

**Méthode simple :** double-cliquez sur `index.html`.

**Méthode développeur :**

```bash
# Avec Python 3
python3 -m http.server 8000
# puis ouvrir http://localhost:8000

# Avec Node.js (si installé)
npx serve .
```

**Méthode intégration :** copiez-collez simplement le contenu de `index.html` dans n'importe quelle page web.

---

## 📁 Structure du projet

```
html-art/
│
├── index.html     # Le logo ASCII-art complet (auto-suffisant)
├── README.md      # Ce fichier
└── LICENSE        # Licence MIT
```

---

## ⚙️ Comment ça marche

Le logo est encodé **caractère par caractère** dans une balise `<pre>` :

```html
<pre id="tiresult" style="font-size: 16px; background-color: #000000; font-weight: bold; color: #FFFFFF;">
  <b style="color:#FFFFFF">       LA COURSE À L'ÉLYSÉE       </b>
  <b style=color:#000000>SAIPSRAIPAPSSIRRPSAIPARRSRPAPSSRSSS...</b>
  <b style=color:#020202>P</b>
  <b style=color:#060606>I</b>
  <b style=color:#09090A>R</b>
  ...
</pre>
```

Chaque caractère possède sa propre couleur hexadécimale, ce qui permet de reproduire fidèlement les dégradés, le drapeau et les détails de la façade.

### 🎨 Palette utilisée

| Couleur | Hex | Utilisation |
|---|---|---|
| Noir | `#000000` | Fond |
| Bleu foncé | `#1A1D2E` | Contours du bâtiment |
| Bleu moyen | `#5E637C` | Détails des fenêtres |
| Gris bleuté | `#858A9E` | Colonnes |
| Rouge | `#FB0002` | Drapeau français |
| Blanc | `#FFFFFF` | Drapeau + titre |

---

## 🎯 Personnalisation

### Changer le titre

Recherchez dans `index.html` :

```html
<b style="color:#FFFFFF">                                    LA COURSE À L'ÉLYSÉE                                    </b>
```

Et remplacez le texte entre les balises.

### Changer la taille

Modifiez `font-size: 16px` dans la balise `<pre>` :

```html
<pre id="tiresult" style="font-size: 24px; ...">
```

### Changer le fond

Modifiez `background-color: #000000` (dans `<body>` et dans `<pre>`).

---

## 🐛 Problèmes connus

### Le logo est tronqué

Le logo fait environ **200 caractères de large**. Utilisez un écran large ou réduisez `font-size`.

### Les couleurs sont fades

Certains navigateurs / thèmes peuvent altérer les couleurs. Essayez en **mode sombre** ou avec un profil de couleurs standard (`sRGB`).

### Le rendu est différent selon l'OS

Le choix de police peut varier. Pour un rendu identique partout, forcez une police monospace :

```css
font-family: 'Courier New', 'Consolas', monospace;
```

---

## 🛠️ Générer son propre ASCII-art

Vous voulez créer votre propre version ? Voici une méthode simple :

1. Convertissez une image en ASCII-art (outils : `ascii-art`, `img2txt`, `jp2a`…)
2. Colorisez chaque caractère avec la couleur dominante du pixel correspondant
3. Enveloppez chaque caractère dans une balise `<b style="color:#XXXXXX">`
4. Placez le tout dans une balise `<pre>`

---

## 🤝 Contribution

Les contributions sont bienvenues !

1. **Forkez** le projet
2. Créez votre branche : `git checkout -b feature/ma-contribution`
3. Committez : `git commit -m "Ajout de ..."`
4. Poussez : `git push origin feature/ma-contribution`
5. Ouvrez une **Pull Request**

Idées d'amélioration :

- 🎨 Thèmes alternatifs (noir & blanc, rétro, néon…)
- 🌍 Traductions du README
- 🧩 Variantes du logo (autres monuments)
- 📱 Adaptation mobile

---

## 📜 Licence

Distribué sous licence **MIT**. Voir [LICENSE](LICENSE) pour plus d'informations.

---

## ⭐ Soutenir le projet

Si ce dépôt vous plaît, laissez une **étoile** ⭐ sur GitHub — ça fait toujours plaisir et ça aide le projet à être découvert.

---

<div align="center">

**🏛️ LA COURSE À L'ÉLYSÉE 🇫🇷**

*Fait avec ❤️, des `<b>` et beaucoup de caractères.*

[⬆ Retour en haut](#-la-course-à-lélysée)

</div>

---

<div align="center">

### 🇫🇷 Gunout · 2026

![Made in France](https://img.shields.io/badge/Made_in-France-002395?style=flat-square&labelColor=FFFFFF&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA5MDAgNjAwIj48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgZmlsbD0iIzAwMjM5NSIvPjxyZWN0IHdpZHRoPSI5MDAiIGhlaWdodD0iNDAwIiB5PSIxMDAiIGZpbGw9IiNmZmYiLz48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjIwMCIgeT0iNDAwIiBmaWxsPSIjZWQyOTM5Ii8+PC9zdmc+)
![GitHub](https://img.shields.io/badge/GitHub-gunout-181717?style=flat-square&logo=github&logoColor=white)
![Year](https://img.shields.io/badge/2026-ED2939?style=flat-square&labelColor=FFFFFF)

<sub>© 2026 <strong>Gunout</strong> — Tous droits réservés.</sub>

</div>
