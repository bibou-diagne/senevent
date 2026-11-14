# SenEvent

## En ligne

- Application web : https://senevent-1.vercel.app
- Deploiement continu : chaque merge sur main met la production a jour,
  chaque Pull Request recoit une URL de previsualisation.
- Application Android (APK) : https://expo.dev/accounts/bibou_diagne/projects/senevent/builds/884bf25f-b230-42b6-ab31-868134135d30
  (telechargement direct : https://expo.dev/artifacts/eas/6S0lCfThC6aMUkrZC_YZEfah-wEODxTWs8Y_2J9lcMU.apk)
- Version mobile : 1.0.0 (profil EAS "preview")

## Lancer le projet en local

- `npm install` a la racine
- Web : `apps/web`, creer `.env.local` (`VITE_SUPABASE_URL`, `VITE_SUPABASE_ANON_KEY`), `npm run dev`
- Mobile : `apps/mobile`, creer `.env` (`EXPO_PUBLIC_...`), `npx expo start`
