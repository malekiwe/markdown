---
title: "Comment gérer les modèles (utilisation des balises) ?"
date: "2018-10-05"
categories: 
  - "gestion-administration"
---

\[vc\_row padding\_top\_multiplier="" padding\_bottom\_multiplier=""\]\[vc\_column\]\[vc\_column\_text\]Le gestionnaire de modèles est un outil permettant aux utilisateurs autorisés, de gérer depuis l’interface d’administration iWE, les modèles de documents et d’e-mails. Les fonctionnalités de base sont décrites dans l'article [**Comment gérer les modèles (1ers pas) ?**](https://learn.iwecloud.com/gestion-administration/comment-gerer-modeles-1e-pas/) Le présent article a pour but d'apporter des détails quant à la gestion des propriétés d'un modèle et à certaines techniques de publipostage word pouvant être utiles pour créer des modèles avancés.

1. [La fonction de publipostage de Word](#fonction-publipostage)
2. [L'utilisation des champs de fusion par iWE](#utilisation-champs-fusion)
3. [Accéder aux balises disponibles dans votre application](#acceder-balises)
4. [Présentation des balises](#presentation-balises)
5. [Utilisation des balises pour composer un modèle](#utilisation-balises)
6. [Détecter les erreurs de balises](#detecter-erreurs-balises)

\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="fonction-publipostage"\]\[vc\_column\]\[vc\_column\_text\]

### 1\. La fonction publipostage de Word

Le publipostage est une fonctionnalité de Microsoft Word permettant de créer plusieurs documents à partir d’un même modèle de document et d’une source de données.

Chaque document créé par publipostage est une fusion de :

- La disposition, la mise en forme, le texte statique et les graphiques du modèle de document
- Les valeurs issues de la source de données. Ces valeurs venant alimenter des zones de texte dynamique, appelées champs de fusion insérés dans le modèle de document.

Un cas très courant de publipostage est l’envoi d’un courrier type à une liste de destinataires. Le modèle contient le texte, la mise en forme, etc. du courrier type identique pour l’ensemble des destinataires et, à l’emplacement du nom et de l’adresse du destinataire, le modèle contient des champs de fusion nom et adresse du destinataire.

Lors de la fusion et du publipostage Word, autant de courriers types qu’il existe de destinataires dans la source de données sont générés. Leurs noms et adresses apparaissent à la place des champs de fusion du modèle.

Vous trouverez une documentation plus complète de cette fonctionnalité sur le [**_site de Microsoft_**](https://support.office.com/fr-fr/article/fusion-et-publipostage-%C3%A0-l-aide-d-une-feuille-de-calcul-excel-858c7d7f-5cc0-4ba1-9a7b-0a948fa3d7d3).\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="utilisation-champs-fusion"\]\[vc\_column\]\[vc\_column\_text\]

### **2\. L’utilisation des champs de fusion par iWE**

IWE exploite les champs de fusion du publipostage de Word afin de générer des documents dont les champs de fusion sont remplacés par les données iWE.

Pour cela, les champs de fusion insérés dans le modèle de document doivent porter le nom des balises mises à disposition par l’application iWE.

Une balise = Une donnée de votre application

**Exemples de balises iWE :**

- numero\_facture : numéro de la facture pour laquelle le document ou l’e-mail est généré
- date\_du\_jour : date du jour au moment de la génération du document ou de l’e-mail
- loyer\_cc : montant du Loyer Charges Comprises du dossier à partir duquel le document ou l’e-mail est généré

\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="acceder-balises"\]\[vc\_column\]\[vc\_column\_text\]

### **3\. Accéder aux balises disponibles dans votre application**

La liste des balises mises à votre disposition est accessible via la page d’administration de votre application. Cette liste est limitée. Si des balises manquent, veuillez vous rapprocher de l’équipe iWE afin de l’enrichir.\[/vc\_column\_text\]\[movedo\_single\_image image="16907" el\_class="capture-img"\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="presentation-balises"\]\[vc\_column\]\[vc\_column\_text\]

### **4\. Présentation des balises**

\[/vc\_column\_text\]\[movedo\_single\_image image="16869" el\_class="capture-img"\]\[movedo\_single\_image image="16623" el\_class="capture-img"\]\[vc\_column\_text\]

 

**(1)** Les balises sont classées par catégories fonctionnelles. Par exemple, Facture, Assuré, Participant - Tiers, etc.

**(2)** Chaque catégorie possède une description et des balises.

**(3) (6)** Il existe différents types de balises : balises simples, balises tableaux.

Chaque balise possède un nom **(4)** et une description **(5)**.

Les balises tableaux possèdent en plus un nom de balise tableau **(7)** et une description de balise tableau **(8)**.\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="utilisation-balises"\]\[vc\_column\]\[vc\_column\_text\]

### **5\. Utilisation des balises pour composer un modèle**

**Pré-requis** **:** composer votre modèle (texte statique, mise en forme, etc.) en prévoyant les zones de textes dynamiques qui devront être remplacées par les données du dossier.

#### **Insertion des balises simples**

Pour chaque zone de texte simple, c’est-à-dire hors tableaux, à remplacer rechercher la balise correspondant à la donnée dans iWE et copier le nom de la balise.

**Exemple avec le numéro de facture :**\[/vc\_column\_text\]\[movedo\_single\_image image="16624" el\_class="capture-img"\]\[vc\_column\_text\]Puis dans le document sous Word, insérer la balise en tant que champ de fusion, avec le nom de la balise copiée précédemment, à l’emplacement souhaité.\[/vc\_column\_text\]\[movedo\_single\_image image="16625" el\_class="capture-img"\]\[vc\_column\_text\]

#### **Formater les champs date**

Pour afficher dans le document les dates dans un format particulier, il faut modifier le champ de fusion inséré.

Pour cela, il faut tout d’abord basculer l’affichage en code de champ en utilisant les touches **Alt+F9** \[/vc\_column\_text\]\[movedo\_single\_image image="16626" align="left" el\_class="capture-img"\]\[vc\_column\_text\]Puis modifier le code pour obtenir le format souhaité.

**Avant formatage :**\[/vc\_column\_text\]\[movedo\_single\_image image="16627" align="left"\]\[vc\_column\_text\]**Après ajout du formatage :**\[/vc\_column\_text\]\[movedo\_single\_image image="16628" align="left"\]\[vc\_column\_text\]**Exemples de formats de dates :**

- \\@ "dddd d MMMM" affiche samedi 26 novembre
- \\@ "dd/mm/yyyy" affiche 26/11/2015
- \\@ "dd MMMM yyyy" affiche 26 novembre 2015

**Exemple de format de date et heure :**

- \\@ "dd/mm/yyyy" à "hh:mm" affiche 26/11/2015 à14h30

Attention, pour afficher l’heure en plus de la date, il faut s’assurer au préalable que le champ dans IWE est bien un champ au format date/heure.

Pour plus d’informations sur cette fonctionnalité Word, rechercher sur internet des articles dédiés aux **commutateurs** de champ Word.\[/vc\_column\_text\]\[vc\_column\_text\]

#### **Insertion de balises tableaux**

Cette fonction permet de répéter dans le document une valeur multiple dans IWE comme par exemple une liste de biens, de documents, de participants,….

Elle peut être utilisée dans un tableau ou dans le corps même du document.

Pour obtenir par exemple, sous forme de tiret, la liste des documents avec la date du fichier et le numéro de version, insérer un 1er champ de fusion avec le nom du tableau en commençant par « TableStart: » puis faire un champ de fusion pour chaque valeur à reporter (nom du doc, date, version) et terminer par un champ portant sur le nom du tableau commençant par « TableEnd: »\[/vc\_column\_text\]\[movedo\_single\_image image="16629" align="left"\]\[vc\_column\_text\]

Pour obtenir le même résultat sous forme de tableau, insérer un tableau avec éventuellement des en-têtes et mettre les champs dans chacune des cases correspondantes.\[/vc\_column\_text\]\[movedo\_single\_image image="16871" align="left"\]\[vc\_column\_text\]

#### **Champs avec conditions**

Pour reporter dans le document une valeur relative à une case à cocher dans IWE (Oui si cochée, Non si pas cochée), il faut utiliser un champ avec condition.

Exemple de champ avec condition **IF** et utilisation d'une balise nommée **garantie\_acquise**\[/vc\_column\_text\]\[movedo\_single\_image image="16873" align="left"\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="detecter-erreurs-balises"\]\[vc\_column\]\[vc\_column\_text\]

### **6\. Détecter les erreurs de balises**

Une fois un modèle chargé via le gestionnaire de modèles d'iWE (voir comment charger un modèle dans l'article 1ers pas), l'interface indique le nombre de balises utilisées dans le modèle et également si une erreur de balise est détectée. Les erreurs courantes sont :

- erreur de nommage de balise
- balise tableau sans tableStart et/ou sans tableEnd
- conditions de formatage word des champs de fusion mal placées

Si, malgré la vérification de ces erreurs courantes, l'erreur persiste, nous vous invitons à contacter l'équipe iWE afin de trouver une solution.\[/vc\_column\_text\]\[movedo\_single\_image image="16875" el\_class="capture-img"\]\[/vc\_column\]\[/vc\_row\]
