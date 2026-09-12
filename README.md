# Atlas Belt Admin – Android

Application Android dédiée à l'administration d'Atlas Belt.

## Fonctionnement

La V1 ouvre directement l'espace administrateur officiel :

`https://atlasbelt-dz.netlify.app/#atlas-admin-7k2q9x`

Elle utilise donc exactement les mêmes commandes, produits, statuts, comptes administrateurs et données Supabase que le site web. Aucune base parallèle n'est créée.

## Fonctions incluses

- accès direct à l'espace admin Atlas Belt ;
- conservation de la session Web/Supabase ;
- JavaScript et stockage local activés ;
- bouton d'actualisation ;
- bouton Retour Android géré dans l'application ;
- HTTPS uniquement ;
- liens externes ouverts dans le navigateur ;
- aucune clé `service_role` intégrée dans l'application.

## Construire l'APK avec Android Studio

1. Installer Android Studio.
2. Ouvrir le dossier `AtlasBeltAdminAndroid`.
3. Laisser Android Studio synchroniser Gradle et installer le SDK Android 35 si demandé.
4. Pour tester : Run > Run 'app'.
5. Pour créer un APK : Build > Build App Bundle(s) / APK(s) > Build APK(s).
6. Pour une version distribuable : Build > Generate Signed App Bundle or APK > APK, puis créer/conserver une clé de signature privée.

## Identifiant Android

`dz.atlasbelt.admin`

## Version

1.0.0
