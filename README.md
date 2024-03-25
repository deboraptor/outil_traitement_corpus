# Outils Traitement Corpus
## Le projet que je veux réaliser
J'aimerais bien me lancer dans un projet d'analyse de sentiments car ça m'intéresse beaucoup et j'ai envie de comprendre mieux comment ça fonctionne. 

![image](https://github.com/deboraptor/outils_traitement_corpus/assets/145542205/bc3a2483-1f69-4aad-8514-7444fda1e554)

### Le dataset que j'ai choisi
J'ai trouvé un dataset sur _Kaggle_ qui correspond totalement à mon projet ! Le dataset se nomme <a href="https://www.kaggle.com/datasets/nelgiriyewithana/emotions">Emotions</a> et permet d'analyser de courts messages postés en ligne selon 6 types d'émotions :
* tristesse (0)
* joie (1)
* amour (2)
* colère (3)
* peur (4) 
* surprise (5)

Ces émotions sont classées de 0 à 5 selon l'émotion primaire qui ressort du message.

### Comment ont été collectées les données ?
Les données ici ont été récoltées sur _Twitter_, le réseau social très populaire. Il y a 416 808 phrases au total et elles ont toutes la même forme : "I [VERB] [..]". Voici un exemple du début du document que j'ai pu télécharger sur _Kaggle_.

![image](https://github.com/deboraptor/outils_traitement_corpus/assets/145542205/0e56f652-54ef-4524-9269-35a587ca3b01)

### À quoi peut servir ce corpus ?
* Analyse de sentiment
* Classification des émotions
* Analyse textuelle

### À quel modèle a-t-il servi ?
J'ai pu voir que ce dataset a été réutilisée par 39 autres personnes, c'est aussi l'un des plus populaire de ce site. Ces notebooks vont m'être très utiles par la suite. Je crois que c'est un dataset assez récent car il a été modifié pour la dernière fois il y a 2 mois, donc il n'y a pas encore beaucoup de modèles qui ont pu l'utiliser. 

### Exemple
Voici un exemple de comment ça fonctionne.

![image](https://github.com/deboraptor/outils_traitement_corpus/assets/145542205/e04facce-d28b-4522-b2fc-83380b759a57)

On voit bien qu'il y a le message sous forme de chaînes de caractères et la classification de l'émotion sous forme de chiffre de 0 à 5 comme on l'avait vu au-dessus. 

### À moi de jouer ! 
Comme les données sont en anglais, je vais donc aussi récupérer des données en anglais ou alors chercher plus tard pour le faire en français.
