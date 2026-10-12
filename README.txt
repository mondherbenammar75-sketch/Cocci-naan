COCCI NAAN - projet Android Studio

Ce projet place l'interface de commande COCCI NAAN dans une application Android autonome : l'interface ne s'ouvre plus dans Chrome.
Pour imprimer en Bluetooth, le projet ouvre Star PassPRNT, qui reste nécessaire dans cette version. Après impression, PassPRNT peut revenir à l'application COCCI NAAN.

IMPORTANT : ce dossier est le CODE SOURCE du projet, pas un APK déjà compilé. Il faut Android Studio pour fabriquer le fichier APK.

Pour créer l'APK :
1. Installer Android Studio sur un ordinateur.
2. Décompresser COCCI_NAAN_Android.zip.
3. Dans Android Studio, choisir Open et sélectionner le dossier COCCI_NAAN_Android.
4. Laisser Gradle synchroniser le projet.
5. Choisir Build > Build APK(s).
6. Copier l'APK généré sur la tablette et l'installer.

Sur la tablette, garder Star PassPRNT installé et vérifier que l'imprimante TSP100-G2307 est configurée. Cette version n'imprime pas directement avec le SDK natif Star : elle utilise le schéma URL officiel de PassPRNT.
