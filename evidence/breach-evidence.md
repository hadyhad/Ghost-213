# Incident 04 (Locked Bakery Recipe)

## Vecteur d'attaque
- **Type d'attaque :** Ransomware combiné à une technique de double extension (masquage d'exécutable)
- Fichier malveillant initial :
`Grand_Mother_Secret_Recipes_Pack.zip` téléchargé depuis un forum public non vérifié, contenant un exécutable piégé nommé `Secret_Almond_Baklava_Recipe.pdf.exe`

## Indices & Preuves Numériques (Artifacts EV)
- Artifact EV-01 (Double Extension Disguise) : Un stagiaire a ouvert le fichier piégé le dimanche après-midi, activant le malware
- Artifact EV-02 (Antivirus Désactivé) : Les logs de la station ont montré que la protection antivirus en temps réel avait été désactivée trois semaines auparavant par un employé se plaignant de ralentissements lors du surf sur le web[cite: 5].
- Artifact EV-03 (Disque de Sauvegarde Chiffré) : Un disque dur de sauvegarde externe USB était branché en permanence ; le ransomware a ainsi chiffré simultanément le disque local et la sauvegarde

## Indicateurs & Conséquences
- Chiffrement global : Tous les tableurs d'inventaire, contacts fournisseurs et recettes secrètes renommés avec l'extension `.LOCKED_BAKERY`
- Demande de rançon : Un message d'exaction s'affichant sur le bureau réclamant un paiement en cryptomonnaie
