# readme
readme forencis
Réponse 2
┌──(kali㉿kali)-[~/Desktop/Cluehub-Playground/01-WarmupForensics-Labs/03_Reading_Between_The_Eyes]
└─$ sudo gem install zsteg
[sudo] password for kali: 
Sorry, try again.
[sudo] password for kali: 
Successfully installed zsteg-0.2.13
Parsing documentation for zsteg-0.2.13
Done installing documentation for zsteg after 0 seconds
1 gem installed
┌──(kali㉿kali)-[~/Desktop/Cluehub-Playground/01-WarmupForensics-Labs/03_Reading_Between_The_Eyes]
└─$ zsteg husky.png
b1,r,lsb,xy         .. text: "^5>c[rvyzrf@"
b1,rgb,lsb,xy       .. text: "picoCTF{r34d1ng_b37w33n_7h3_by73s}"
b1,abgr,msb,xy      .. file: PGP Secret Sub-key -
b2,g,msb,xy         .. file: OpenPGP Public Key
b3,abgr,msb,xy      .. text: "t@Wv!Wt\tGtA"
b4,r,msb,xy         .. text: "0Tt7F3Saf"
b4,g,msb,xy         .. text: "2g'uV `3"
b4,b,lsb,xy         .. text: "##3\"TC%\"2f"
b4,b,msb,xy         .. text: " uvb&b@f!"
b4,rgb,lsb,xy       .. text: "1C5\"RdWD"
b4,rgb,msb,xy       .. text: "T E2d##B#VuQ`"
b4,bgr,lsb,xy       .. text: "A%2RTdGG"
b4,bgr,msb,xy       .. text: "EPD%4\"c\"#CUVqa "
b4,rgba,lsb,xy      .. text: "?5/%/d_tO"
b4,abgr,msb,xy      .. text: "EO%O#/c/2/C_e_q"
Réponse 3. picoCTF{r34d1ng_b37w33n_7h3_by73s
Réponse 4. picoCTF{th3__l345t_s1gn1f1c4nT_b1t5_770554193

Réponse 5. PicoCT Fnots3cur3_df59 8569
Réponse 6.Your flag is: "picoCTF{and_thats_how_u_edit_hex_kittos_8BcA67a2}"
Réponse 7.picoCTF{look_in_image_788a182e}
Réponse 8 .picoCTF{now_y0u_533_m3}
Pour trouver la réponse de la question 8 nous avons été sur stageOnloine
Réponse 0xA picoCTF{w4lt3r_wh1t3_2d6d3c6c75aa3be7f42debed8ad16e3b}
Réponse 0xC ![image](https://github.com/user-attachments/assets/29052c40-9368-49ab-8017-d7f677e45aad)

Réponse LAB 2
Les Étapes et Raisonnements Ayant Conduit à la Conclusion 

 

1. Identification des Indices Visuels Initiaux 

Observation : 

En analysant l’image, plusieurs éléments significatifs ont été repérés, notamment : 

Un panneau de signalisation routière indiquant "Rue des Lilas". 

 une enseigne lisible : "Boulangerie Pierre honoré". 

Des éléments environnants comme des arbres, une route principale, et un carrefour visible. 

Raisonnement : 

Ces indices suggèrent une localisation potentiellement identifiable via des outils comme Google Maps ou des recherches spécifiques. 

L'objectif initial est de confirmer si ces éléments existent réellement dans un contexte géographique particulier. 

 

2. Recherche et Validation avec Outils Complémentaires 

Étape 1 : Recherche d’Informations Spécifiques 

Action : Une recherche par mot-clé a été effectuée sur Google avec les termes exacts : 

"Boulangerie Pierre Rue des Lilas". 

Résultat : 

La recherche a produit un lien vers une boulangerie située dans une petite ville, confirmant l’existence d’un établissement correspondant. 

Étape 2 : Validation avec Geoguessr 

Action : Sur Geoguessr : 

Recherche du nom de rue (Rue des Lilas). 

Exploration de la zone à l’aide de Street View pour repérer le bâtiment et les environs. 

Observation : 

L’environnement dans Street View correspond parfaitement à la description : 

Le bâtiment bleu. 

L’enseigne "Boulangerie Pierre". 

Le carrefour visible et les autres éléments de l’image. 

 

3. Documentation des Résultats 

Synthèse des Découvertes : 

Panneau "Rue des Lilas" : Validé par la recherche cartographique et visuelle. 

Bâtiment Bleu avec Enseigne : Correspondance confirmée par Google Maps et Street View. 

Environnement Général : Les éléments supplémentaires (carrefour, arbres, routes) sont en cohérence avec les outils utilisés. 

Hypothèse Validée : 

Les indices visuels correspondent à un emplacement réel, situé dans une ville spécifique (mentionnée dans les recherches). Les outils complémentaires ont permis de valider avec certitude l’hypothèse initiale. 

 

Conclusion et Recommandations 

Conclusion : Les indices observés permettent de localiser précisément l’emplacement avec des outils accessibles comme Google Maps , google street view et des recherches web. 

Recommandation : Dans des situations futures, il est recommandé d'utiliser une combinaison d’outils (cartographiques et bases de données) pour obtenir des confirmations rapides et fiables. 

 ![image](https://github.com/user-attachments/assets/4150e252-5e13-4c1d-951c-2f7bf05a6244)

![image](https://github.com/user-attachments/assets/d03d8f48-92cc-4a1d-ab93-2ecec3a1e09d)

 TP 3 MemoryForensics-Labs 

 

 

 

Une image contenant texte, capture d’écran, Police, menu

Description générée automatiquement 

 

 

 

 

 

Une image contenant texte, capture d’écran, Police

Description générée automatiquement 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

05-ChallengeForensics-Labs 

 

001-ForensicChallenge-pcap_attack_trace 

 

Challenge 1 - Analyse d'une trace réseau d'attaque 

L'objectif est d'enquêter sur une attaque réseau. 

Niveau de compétence : Intermédiaire 

Forme 

Le Challenge : 

Une trace réseau contenant des données d'attaque est fournie. 
(Note : l'adresse IP de la victime a été modifiée pour masquer sa véritable localisation.) 
Analysez cette trace et répondez aux questions suivantes : 

Quels systèmes (c.-à-d. adresses IP) sont impliqués ? 
(2 points) 

Une image contenant Logiciel multimédia, logiciel, texte, capture d’écran

Description générée automatiquement 

 

Que pouvez-vous découvrir sur l'hôte attaquant (par exemple, où est-il situé) ? 
(2 points) 

Une image contenant texte, capture d’écran, logiciel, Page web

Description générée automatiquement 

Combien de sessions TCP sont contenues dans le fichier de capture ? 
(2 points) 

il y a 5 sessions contenues dans ce fichier dump. 

Une image contenant texte, logiciel, Logiciel multimédia, capture d’écran

Description générée automatiquement 

Combien de temps a duré l'attaque ? 
(2 points) 

Une image contenant texte, capture d’écran, logiciel, Logiciel multimédia

Description générée automatiquement 

 

 

 

Quel système d'exploitation a été ciblé par l'attaque ? Quel service ? Quelle vulnérabilité ? 
(6 points) 

Une image contenant texte, Police, capture d’écran, ligne

Description générée automatiquement 

 

Pouvez-vous dresser une vue d'ensemble des actions générales effectuées par l'attaquant ? 
(6 points) 

Quelle vulnérabilité spécifique a été exploitée ? 
(2 points) 

Une image contenant texte, Police, nombre, ligne

Description générée automatiquement 

CVE-2003-0533 

Quelles actions le shellcode effectue-t-il ? Veuillez lister le shellcode. 
(8 points) 

Pensez-vous qu'un honeypot a été utilisé pour simuler une victime vulnérable ? Pourquoi ? 
(6 points) 

Oui 

Un malware était-il impliqué ? Quel est le nom de ce malware ? 
*(Nous ne cherchons pas une analyse détaillée du malware pour ce challenge.) 
(2 points)   ssms.exe 

Une image contenant texte, capture d’écran, Police, logiciel

Description générée automatiquement 

Pensez-vous que cette attaque était manuelle ou automatisée ? Pourquoi ? 
(2 points) 

L'attaque est automatisée, comme le montre le scan de ports initial, les connexions rapides (moins d'une seconde). 

 

 

 

Challenge 3 - Problèmes bancaires 

 

Le Challenge : 

La société X vous a contacté pour réaliser une analyse forensique à la suite d’un incident récent. L’un de leurs employés a reçu un email d’un collègue contenant un lien vers un fichier PDF. Après l’ouverture de ce fichier, l’employé n’a rien remarqué d’inhabituel, mais a récemment constaté une activité inhabituelle sur son compte bancaire. La société X a réussi à obtenir une image mémoire de la machine virtuelle de l’employé après la suspicion d’infection. 

Votre mission est d'analyser cette image mémoire et de produire un rapport d'investigation détaillé. Les questions ci-dessous vous guideront dans cette analyse. 

 

Questions d'investigation : 

Listez les processus qui étaient en cours d'exécution sur la machine de la victime. Quel processus est le plus susceptible d’être à l’origine de l’exploit initial ? (2 points) 

 

Le processus ayant exécuté l'exploit, AcroRd32.exe, a rencontré un problème après l'ouverture du fichier PDF. Son PID est 1752, et son processus parent est firefox.exe, avec le PID 888. 

 

Listez les sockets ouverts sur la machine de la victime pendant l'infection. Y a-t-il des processus suspects qui ont des sockets ouverts ? (4 points) 

 

Le processus avec le PID 1752 (AcroRd32.exe) et le navigateur Firefox avec le PID 888 ont tous deux établi des connexions avec l'adresse IP 212.150.164.203, ce qui indique une activité potentiellement malveillante liée à cette adresse. 

 

Listez les URL suspectes qui pourraient se trouver dans la mémoire du processus suspect. (2 points) 

 

 

 

Y a-t-il d’autres processus contenant des URL qui pourraient indiquer des problèmes bancaires ? Si oui, quels sont ces processus et quelles sont les URL correspondantes ? (4 points) 

Y avait-il des fichiers pouvant être extraits du processus initial ? Comment ces fichiers ont-ils été extraits ? 
(6 points) 

Si un fichier a été extrait du processus initial, quelles techniques a-t-il utilisées pour réaliser l'exploit ? 
(8 points) 

Listez les fichiers suspects qui ont été chargés par les processus sur la machine de la victime. À partir de ces informations, quel pourrait être le payload de l'exploit initial affectant le compte bancaire de la victime ? 
(2 points) 

Si des fichiers suspects peuvent être extraits d’un processus injecté, des produits antivirus détectent-ils l’exécutable suspect ? Quels sont les résultats généraux des antivirus ? 
(6 points) 

Y a-t-il des entrées de registre associées au payload ? 
(4 points) 

Quelle technique a été utilisée dans l'exploit initial pour injecter du code dans d'autres processus ? 
(6 points) 

 

 

 

  
