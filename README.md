# ⚖️ YoonuDroit — Portail de Méthodologie Juridique

Plateforme web pédagogique interactive et centralisée, conçue pour accompagner les étudiants en droit dans la maîtrise des exercices méthodologiques fondamentaux : **Dissertation**, **Cas Pratique**, **Commentaire d'Arrêt en droit privé**, et **Commentaire de Texte**.

---

## 📂 Arborescence du Projet

Le projet est structuré sous forme de site multipage statique, hébergé dans un dépôt unique pour un déploiement simplifié :

```text
Dissertation-Juridique/
├── index.html                  # 🏠 Page d'accueil principale du portail
├── Introduction/
│   └── index.html              # 📚 Module : Introduction de dissertation (Entonnoir en 7 étapes)
├── Developpement/
│   └── index.html              # 📚 Module : Développement (Plan binaire, chapeaux & transitions)
├── Conclusion/
│   └── index.html              # 📚 Module : Conclusion (Statut atypique & ouverture)
├── Cas-Pratique/
│   └── index.html              # 📚 Module : Cas pratique & syllogisme juridique
├── Commentaire-Arret/
│   └── index.html              # 📚 Module : Commentaire d'arrêt en droit privé (Fiche d'arrêt & plan)
├── Commentaire-Texte/
│   └── index.html              # 📚 Module : Commentaire de texte (Méthode AD.NA.PI.JA)
└── README.md                   # 📄 Documentation officielle du projet
```

---

## 🎨 Identité Visuelle & Charte Graphique

Le site bénéficie d'une charte graphique immersive, professionnelle et unifiée :
* **Thème Sombre Institutionnel :** Fond principal en `slate-900` pour un confort de lecture optimal lors de longues sessions de révision.
* **Couleur d'Accentuation :** L'ambre (`amber-500` / `#f59e0b`) pour souligner les repères méthodologiques, les boutons d'action et les titres clés.
* **Typographie :** Association de *Playfair Display* (pour des titres élégants et académiques) et d' *Inter* (pour la lisibilité du corps de texte).
* **Curseur Personnalisé :** Intégration d'un curseur SVG vectoriel en forme de **balance de la justice** injecté directement via URI de données CSS.

---

## 🛠️ Stack Technique

* **HTML5 / CSS3** (Sémantique et mise en page moderne)
* **Tailwind CSS** (Chargé via CDN pour un design responsive ultra-rapide)
* **Google Fonts** (*Playfair Display* & *Inter*)
* **Git & GitHub** (Versionnement du code source)
* **Netlify** (Hébergement statique et Continuous Deployment)

---

## 🚀 Installation & Utilisation Locale

Pour cloner et tester le projet en local sur votre machine :

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/babsdevjunior/yoonu-droit.git
   ```

2. **Lancer le site :**
   Ouvrez simplement le fichier `index.html` situé à la racine dans votre navigateur web, ou utilisez une extension de type *Live Server* (sur VS Code) pour une expérience de navigation fluide.

---

## 🌐 Déploiement Continu sur Netlify

Le dépôt est configuré pour un déploiement entièrement automatisé :
1. Poussez vos modifications sur la branche `main` de votre dépôt GitHub :
   ```bash
   git add .
   git commit -m "feat: mise à jour des modules méthodologiques"
   git push origin main
   ```
2. Connectez le dépôt à **Netlify**. Aucun build complexe n'est requis (fichiers statiques purs). Chaque `git push` mettra à jour le site en direct.

---

## 👨‍💻 Auteur & Licence

Développé dans le cadre du parcours en sciences juridiques et ingénierie pédagogique web. Libre d'utilisation pour le partage des connaissances juridiques.
* Fait par **Babacar Seck**.