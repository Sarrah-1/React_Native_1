# about-screen-rn

Lab 2 React Native avec **Expo** : un écran "About" construit avec `View` et `Text`, avec un `AppHeader` et un `AppFooter`.

## Lancer le projet

```
npm install
npx expo install --fix
npx expo start
```

- **Téléphone** : scanner le QR code avec Expo Go
- **Navigateur** : appuyer sur la touche `w`

## Structure

```
about-screen-rn/
├── src/
│   ├── app/
│   │   ├── _layout.tsx      -> configuration de la navigation
│   │   └── index.tsx        -> assemblage header + contenu + footer
│   └── components/
│       ├── AboutScreen.tsx  -> l'écran "About"
│       ├── AppHeader.tsx    -> l'en-tête
│       └── AppFooter.tsx    -> le pied de page
├── app.json
└── package.json
```

## ScreenShots

<img width="296" height="328" alt="image" src="https://github.com/user-attachments/assets/017a2e84-a5b4-4539-ba9f-5fb111cb44e9" />
