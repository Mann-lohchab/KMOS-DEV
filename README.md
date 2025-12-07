# KMOS-DEV - Software Engineering Collective

Brutalist design website for KMOS software engineering collective with portal sales page.

## 🚀 Features

- **Main Page**: KMOS company page with team, portfolio, and contact information
- **Portal Page**: Sales page for Portal Sale with pricing and features
- **Brutalist Design**: Bold, minimalist design with high contrast
- **Responsive**: Mobile-first responsive design

## 🛠️ Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📦 Deployment to GitHub Pages

This project is configured for GitHub Pages deployment using GitHub Actions.

### Setup Instructions:

1. **Push to GitHub** (if not already done):
   ```bash
   git push -u origin main
   ```
   You may need to authenticate using:
   - Personal Access Token (recommended)
   - SSH key
   - GitHub CLI

2. **Enable GitHub Pages**:
   - Go to your repository: https://github.com/Mann-lohchab/KMOS-DEV
   - Navigate to Settings → Pages
   - Under "Source", select "GitHub Actions"
   - The workflow will automatically deploy on push to main branch

3. **Access your site**:
   - Your site will be available at: `https://mann-lohchab.github.io/KMOS-DEV/`

### Manual Deployment:

If you prefer to deploy manually:

```bash
npm run build
# Then upload the contents of the 'build' folder to GitHub Pages
```

## 📁 Project Structure

```
src/
├── routes/
│   ├── +page.svelte      # Main KMOS page
│   ├── +layout.svelte    # Layout wrapper
│   └── portal/
│       └── +page.svelte  # Portal sales page
└── lib/
    └── lib/
        └── utils.ts      # Utility functions
```

## 🎨 Styling

- Tailwind CSS for utility-first styling
- Custom brutalist design system
- Dark mode support

## 📝 License

© 2024 KMOS. All Rights Reserved.
