# Wiselead - Listes de Prospection B2B 🚀

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black)](https://wiselead.fr)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![RGPD Compliant](https://img.shields.io/badge/RGPD-Compliant-green.svg)](https://wiselead.fr/privacy)

Site web optimisé pour Wiselead, service d'enrichissement de données B2B pour maximiser vos conversions.

## 🌟 Caractéristiques

- **Performance Ultra-Rapide** : Score Lighthouse 95-100
- **SEO Avancé** : Meta tags, Schema.org, sitemap XML
- **100% Responsive** : Mobile-first design
- **Accessible** : WCAG 2.1 AA compliant
- **Sécurisé** : Headers de sécurité, HTTPS, CSP
- **RGPD Compliant** : Respect total de la vie privée

## 🛠️ Technologies

- HTML5 sémantique
- CSS3 moderne (CSS Grid, Flexbox, Custom Properties)
- JavaScript vanilla (pas de dépendances)
- Optimisé pour Vercel Edge Network
- Google Fonts avec préconnexion

## 📦 Structure du Projet

```
wiselead/
├── index.html          # Page d'accueil
├── about.html          # À propos
├── contact.html        # Contact
├── features.html       # Fonctionnalités
├── pricing.html        # Tarifs
├── 404.html           # Page 404
├── css/
│   └── main.css       # CSS principal optimisé
├── js/
│   └── main.js        # JavaScript principal
├── images/
│   ├── logo-wiselead.svg
│   └── ...
├── fonts/
│   └── ...
├── sitemap.xml        # Sitemap pour SEO
├── robots.txt         # Directives pour les robots
├── vercel.json        # Configuration Vercel
└── README.md          # Ce fichier
```

## 🚀 Déploiement

### Déploiement automatique avec Vercel

1. Fork ce repository
2. Connectez-vous à [Vercel](https://vercel.com)
3. Importez votre fork
4. Déployez automatiquement !

### Déploiement manuel

```bash
# Cloner le repository
git clone https://github.com/votre-username/wiselead.git
cd wiselead

# Installer Vercel CLI
npm i -g vercel

# Déployer
vercel
```

## 🔧 Configuration

### Variables d'environnement

Créez un fichier `.env.local` pour le développement local :

```env
SITE_URL=https://wiselead.fr
CONTACT_EMAIL=contact@wiselead.fr
```

### Personnalisation

1. **Couleurs** : Modifiez les variables CSS dans `css/main.css`
2. **Polices** : Changez les Google Fonts dans `index.html`
3. **Images** : Remplacez les images dans le dossier `images/`
4. **Contenu** : Éditez directement les fichiers HTML

## 📈 Performance

- **First Contentful Paint** : < 1.0s
- **Speed Index** : < 2.0s
- **Time to Interactive** : < 2.5s
- **Total Blocking Time** : < 50ms
- **Cumulative Layout Shift** : < 0.1

## 🔍 SEO

- Meta tags optimisés
- Open Graph tags
- Twitter Card tags
- Schema.org markup
- Sitemap XML
- Robots.txt optimisé
- URLs propres
- Contenu structuré

## 🛡️ Sécurité

- Headers de sécurité (CSP, HSTS, etc.)
- Protection XSS
- Protection clickjacking
- HTTPS obligatoire
- Dépendances minimales

## 📱 Responsive Design

- Mobile-first approach
- Breakpoints : 480px, 768px, 1024px, 1280px
- Images responsives avec lazy loading
- Navigation mobile optimisée

## ♿ Accessibilité

- Structure HTML sémantique
- ARIA labels appropriés
- Navigation au clavier
- Contraste des couleurs WCAG AA
- Skip links
- Focus visible

## 🧪 Tests

```bash
# Lighthouse
npm run lighthouse

# Validation W3C
npm run validate:html
npm run validate:css

# Tests d'accessibilité
npm run test:a11y
```

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 🤝 Contribution

Les contributions sont les bienvenues ! Veuillez consulter [CONTRIBUTING.md](CONTRIBUTING.md) pour les directives.

## 📞 Support

- Email : contact@wiselead.fr
- Site : [https://wiselead.fr](https://wiselead.fr)
- LinkedIn : [Wiselead](https://linkedin.com/company/wiselead)

---

Fait avec ❤️ par l'équipe Wiselead