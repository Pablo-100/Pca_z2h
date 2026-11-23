<div align="center">

# 🛡️ PCA 0→Hero

**Comprendre le Plan de Continuité d'Activité, l'ISO 22301 et le BIA, en partant de zéro.**

Cours interactif en français, avec des explications en darija tunisienne, des schémas animés, des quiz corrigés et un examen blanc.

![HTML](https://img.shields.io/badge/HTML-CSS-JS-e34c26?style=flat-square)
![Dépendances](https://img.shields.io/badge/d%C3%A9pendances-0-2ea44f?style=flat-square)
![Langues](https://img.shields.io/badge/langues-FR%20%2B%20darija-c2410c?style=flat-square)
![Statut](https://img.shields.io/badge/usage-%C3%A9ducatif-blue?style=flat-square)

[**Voir le site**](https://pablo-100.github.io/Pca_z2h/) · [Signaler un problème](https://github.com/Pablo-100/Pca_z2h/issues)

</div>

---

## À propos

PCA 0→Hero est une plateforme d'étude pour les étudiants et professionnels qui découvrent la **continuité d'activité** : PCA, PRA, gestion de crise, norme **ISO 22301:2019**, **BIA** et indicateurs **MTPD / RTO / RPO / MBCO**.

L'idée : expliquer d'abord avec des mots simples et des schémas, puis donner le vocabulaire exact. Chaque module contient une courte histoire en darija tunisienne pour fixer l'idée avant la théorie.

## Fonctionnalités

| | |
|---|---|
| 📚 **14 modules** | Parcours en 3 séances, du « pourquoi » au mini-projet |
| 📊 **Une quinzaine de schémas interactifs** | Chronologie d'un incident (RPO, RTO, MTPD), architecture d'un SMCA, règle de sauvegarde 3-2-1, réplication, matrice de risques, feuille de route… avec bouton *Agrandir* |
| 🗣️ **Darija intégrée** | Histoires courtes, page *Darija 101* (vocabulaire, erreurs fréquentes), affichage activable ou masquable |
| ✅ **Quiz corrigés** | Plus de 60 questions avec explications, sauvegarde de la progression |
| 🧪 **Outils pratiques** | Simulateur MTPD / RTO / RPO, constructeur de BIA, vérificateur de cohérence pour le mini-projet |
| 🔎 **Aide à la révision** | Glossaire, fiche de synthèse, flashcards, examen blanc, recherche plein texte |
| 🌗 **Confort de lecture** | Thème clair et sombre, sommaire de page, barre de progression, responsive mobile |

## Parcours

1. **Séance 1, Introduction** : pourquoi un PCA, concepts fondamentaux, PCA / PRA / crise, menaces et bénéfices, vue d'ensemble de l'ISO 22301
2. **Séance 2, Norme et cadre** : norme, réglementation et régulation, clauses 4 à 10, SMCA, RGPD / DORA / NIS2, les 10 phases de mise en conformité
3. **Séance 3, BIA et solutions** : BIA, MTPD, RTO, RPO, MBCO, architectures de continuité
4. **Pratique** : études de cas corrigées (dont l'incendie OVHcloud de Strasbourg en 2021), mini-projet BioDistrib

## Utilisation

Aucune installation. C'est une page HTML autonome.

```bash
git clone https://github.com/Pablo-100/Pca_z2h.git
cd Pca_z2h
# ouvrez simplement index.html dans votre navigateur
```

La progression, le thème et les réglages sont enregistrés dans le navigateur (`localStorage`). Rien n'est envoyé à un serveur.

### Publier avec GitHub Pages

*Settings → Pages → Deploy from a branch → `main` / `(root)`*

## Technique

- HTML, CSS et JavaScript natifs, sans framework ni dépendance
- Routage par hash, contenu piloté par les données
- Schémas en SVG inline, thémés par variables CSS
- Icônes inline (jeu Lucide, licence ISC)
- Polices Google Fonts : Bricolage Grotesque, Source Sans 3, JetBrains Mono
- Accessibilité : contrastes vérifiés, navigation clavier, `prefers-reduced-motion`

## Structure

```
.
├── index.html   # toute la plateforme (contenu, styles, scripts)
└── README.md
```

## Avertissement

- Outil d'étude **non officiel**, sans lien avec l'ISO ni avec un organisme de normalisation.
- Les passages sur la norme sont **reformulés**. Pour le texte exact, consultez l'exemplaire officiel de l'ISO 22301:2019.
- Le module *Architectures de continuité* est un complément pédagogique. Les coûts et délais indiqués sont des ordres de grandeur, pas des valeurs normatives.
- Le mini-projet fournit une méthode et des outils d'aide. Il ne remplace pas le travail personnel à rendre.
- Les icônes sont génériques : aucun logo de marque n'est reproduit.

## Contribuer

Les corrections et suggestions sont bienvenues : ouvrez une [issue](https://github.com/Pablo-100/Pca_z2h/issues) ou une pull request.

## Auteur

Fait par **[Pablo-100](https://github.com/Pablo-100)**.

Si ce projet vous aide à réviser, mettez-lui une ⭐ : c'est la meilleure façon de le soutenir.
