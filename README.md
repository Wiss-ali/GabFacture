# Générateur de Factures

Une application web moderne pour générer des factures professionnelles en PDF.

## Fonctionnalités

- Interface utilisateur moderne et responsive
- Thème clair/sombre
- Génération de PDF
- Prévisualisation en temps réel
- Formulaire intuitif avec validation

## Prérequis

- Node.js 18+
- npm 9+
- VS Code

## Extensions VS Code Recommandées

```json
{
  "recommendations": [
    "dbaeumer.vscode-eslint",
    "esbenp.prettier-vscode",
    "bradlc.vscode-tailwindcss",
    "formulahendry.auto-rename-tag",
    "dsznajder.es7-react-js-snippets",
    "christian-kohler.path-intellisense"
  ]
}
```

## Installation

1. Clonez le dépôt :
```bash
git clone https://github.com/votre-username/generateur-factures.git
cd generateur-factures
```

2. Installez les dépendances :
```bash
npm install
```

3. Lancez le serveur de développement :
```bash
npm run dev
```

## Structure du Projet

```
src/
  ├── components/        # Composants React
  │   ├── ui/           # Composants UI réutilisables
  │   └── invoice-form/ # Composants du formulaire de facture
  ├── lib/              # Utilitaires et helpers
  ├── hooks/            # Custom React hooks
  └── App.tsx           # Composant principal
```

## Technologies Utilisées

- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- React-PDF
- date-fns
- Lucide Icons

## License

MIT