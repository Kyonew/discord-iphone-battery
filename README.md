# Système qui envoie un message Discord à chaque charge de votre iPhone
Ce sytème utilise l'application `Raccourcis` présente nativement sur iOS. Lorsque vous brancherez votre iPhone sur secteur, un message embed Discord sera automatiquement envoyé 
avec des informations telles le niveau de charge acutel de votre batterie ainsi que le temps de la dernière fois où vous avez mis votre iPhone à charger. À l'inverse, lorsque vous débranchez 
votre iPhone, un message embed sera envoyé avec le niveau de charge actuel ainsi que la durée de la charge.

# Création du webhook sur Discord. 
1. Allez dans les paramètres du serveur dans lequel vous voulez que les messages s'envoient. 
2. Trouvez l'onglet `Intégrations`.
3. Cliquez sur "Consulter les webhooks" puis créez-en un nouveau.
4. Configurez-le avec son nom, le salon dans lequel vous voulez que les messages s'envoient, sa photo de profil puis **Copier l'URL du webhook** et conservez-la précieusement.

# Installation et configuration de Raccourcis.
 1. Vérifiez que `Raccourcis` est bien présent sur votre iPhone. ([ou installez-la ici](https://apps.apple.com/fr/app/raccourcis/id915249334)).
 2. Ajoutez les raccourcis suivants à votre galerie :
 - [Raccourci lors du branchement]()
 - [Raccourci lors du débranchement]()
 3. Ouvrez ces raccourcis à l'aide des `...` et changez les informations suivantes : 
 - Insérez l'URL de votre Webhook dans l'avant dernière ligne des **deux raccourcis**
 - Dans le `Texte` un peu plus haut, modifiez notamment votre nom *([...] vient de brancher son téléphone !)*
 - Changez accessoirement les couleurs et emojis.
 4. Cliquez sur `Ok` puis allez dnas l'onglet `Automatisation`.
 5. Appuyez sur  `+` puis **Créer une automatisation perso.**
 6. Choisissez **Adaptateur secteur** puis **Est branché** ou **Est debranché**.
 7. Cliquez sur `Ajoutez une action` et trouvez `Exéctuer le raccourci`.
 8. Ajoutez-la puis cliquez sur le *"Raccourci"* écrit en bleu.
 9. Choissisez entre *branché-discord* ou *débranché-discord* en fonction de l'automatisation choisie (**Faites les deux**).
 10. Cliquez sur `Suivant`.
 11. Décochez la case *Demander avant d'exéctuer*. Puis confirmez votre choix.
 12. Cliquez sur `OK` pour valider votre choix. 

Si tout est bon, que vous avez **deux** automatisations (une au branchement et l'autre lors du débranchement) vous devriez obtenir un message à chaque branchement/débranchement de votre iPhone ! (ou iPad)

# Illustations et exemples 
**Lors du branchement de l'iPhone :**

![illustration-lors-du-branchement](https://cdn.discordapp.com/attachments/930864932067610704/1107734738292199555/image.png)

Lors du débranchement :
![illustration-lors-du-debranchement](https://cdn.discordapp.com/attachments/930864932067610704/1107734833293168670/image.png)
