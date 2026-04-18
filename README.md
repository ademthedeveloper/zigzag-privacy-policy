# Dev360 Developer Website

A modern, professional developer website for Dev360 mobile game studio, created with React, Vite, and Tailwind CSS.

## Features

- **Hero Section**: Studio branding with animated particles background
- **Games Section**: Display your mobile games (currently shows "Coming Soon")
- **About Section**: Information about Dev360 studio
- **Privacy Policy Selection Page**: Choose from different privacy policies
  - 🌐 Website Privacy Policy
  - 🎮 Game 1 Privacy Policy
  - 🎮 Game 2 Privacy Policy
  - 🎮 Game 3 Privacy Policy
- **Contact Section**: Email (ademthedeveloper@gmail.com) and social links
- **Responsive Design**: Mobile-first, works on all devices

## Privacy Policies

The website includes a **Privacy Policy Selection** page where users can choose which privacy policy to view:

1. **Website Privacy Policy** - For the dev360.studio website
2. **Game 1 Privacy Policy** - For your first mobile game
3. **Game 2 Privacy Policy** - For your second mobile game  
4. **Game 3 Privacy Policy** - For your third mobile game

Clicking any policy card opens that specific privacy policy in detail. These policies are fully written and suitable for Google Play Console approval.

## Customization

### Replace the Logo
Find the `StudioLogo` SVG in `src/App.tsx` and replace it with your own logo image or SVG.

### Update Privacy Policy Game Names
The privacy policy page currently shows "Game 1", "Game 2", and "Game 3" as placeholders. You can:
1. Rename these to your actual game names
2. Add or remove game policy cards as needed
3. Customize the content for each game's specific features

### Add Your Logo Later
When you have your logo ready, update the logo SVG in the header, footer, and hero section of `src/App.tsx`.

## Deployment

### GitHub Pages
1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select the main branch as source
4. Your site will be live at `https://yourusername.github.io/repo-name/`

### Other Hosting
The `dist/` folder contains the production-ready files. Upload these to any hosting service (Netlify, Vercel, etc.).

## Google Play Console & App-ads.txt

### Adding app-ads.txt
Create a file named `app-ads.txt` in your project root with your AdSense publisher ID:

```
google.com, pub-xxxxxxxxxxxxxxxx, DIRECT, f08c47fec0942fa0
```

Replace `pub-xxxxxxxxxxxxxxxx` with your actual AdSense publisher ID.

This file should be accessible at: `https://yourdomain.com/app-ads.txt`

### Developer Website Requirements
This website meets Google Play Console requirements:
- ✅ Developer website with studio information
- ✅ Email contact (ademthedeveloper@gmail.com)
- ✅ Privacy Policy for the website and games
- ✅ Professional, trustworthy design
- ✅ Supports app-ads.txt verification

## Build the Project

```bash
npm run build
```

The built files will be in the `dist/` folder, ready for deployment.

## Contact

- **Email**: ademthedeveloper@gmail.com
- **Studio**: Dev360