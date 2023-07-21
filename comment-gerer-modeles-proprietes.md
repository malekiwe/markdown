---
title: "Comment gérer les modèles (édition des propriétés) ?"
date: "2018-10-08"
categories: 
  - "gestion-administration"
---

\[vc\_row padding\_top\_multiplier="" padding\_bottom\_multiplier=""\]\[vc\_column\]\[vc\_column\_text\]Le gestionnaire de modèles est un outil permettant aux utilisateurs autorisés, de gérer depuis l’interface d’administration iWE, les modèles de documents et d’e-mails. Les fonctionnalités de base sont décrites dans l'article [**Comment gérer les modèles (1ers pas) ?**](https://learn.iwecloud.com/gestion-administration/comment-gerer-modeles-1e-pas/)  L'utilisation des balises iWE pour construire un modèle est décrite dans l'article **[Comment gérer les modèles (utilisation des balises) ?](https://learn.iwecloud.com/gestion-administration/comment-gerer-modeles-balises/)**

Le présent article a pour but d'apporter des détails quant à la gestion des propriétés d'un modèle. Les propriétés d'un modèle servent à définir finement la façon dont il sera accessible dans l'application.

1. [Accéder aux propriétés du modèle](#acceder-modele)
2. [Fenêtre des propriétés d’un modèle de document](#fenetre-modele-document)
3. [Fenêtre des propriétés d’un modèle de communication](#fenetre-modele-communications)
4. [Champs avancés et variables dans les propriétés des modèles](#champs-avances-et-variables)
5. [Propriétés spécifiques par application](#proprietes-specifiques)

\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="acceder-modele" el\_wrapper\_class="acceder-modele"\]\[vc\_column\]\[vc\_column\_text\]

### **1.** **Accéder aux propriétés du modèle**

Les propriétés du modèle sont accessibles pour les modèles publiés et les modèles non publiés.\[/vc\_column\_text\]\[movedo\_single\_image image="16908" el\_class="capture-img"\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="fenetre-modele-document"\]\[vc\_column\]\[vc\_column\_text\]

### **2\. Fenêtre des propriétés d’un modèle de document**

\[/vc\_column\_text\]\[movedo\_single\_image image="16909" el\_class="capture-img"\]\[vc\_column\_text\]**(1) Nom du modèle en cours de configuration**

**(2) Propriétés du modèle et des fichiers générés à partir de ce modèle**

**(3) Propriétés d'affichage du modèle dans le dossier**

**(4) Autres propriétés d'affichage du modèle spécifiques à chaque application iWE**

**(5) Accès aux champs avancés**

**(6) Boutons d'action de la page Annuler/Enregistrer**\[/vc\_column\_text\]\[vc\_column\_text\]

#### A. Propriétés du modèle et des fichiers générés à partir de ce modèle

**1 - Nom du modèle**

Nom proposé lors de la génération du document dans l'application\[/vc\_column\_text\]\[movedo\_single\_image image="16912" el\_class="capture-img"\]\[vc\_column\_text\]**2 - Nom du document, Type, Description du document, Afficher l'extension du document**

Propriétés des fichiers générés à partir du modèle de document\[/vc\_column\_text\]\[movedo\_single\_image image="16914" el\_class="capture-img"\]\[vc\_column\_text\]**3 - Formats de génération**

Formats disponibles pour générer un fichier à partir du modèle (docx ou pdf)\[/vc\_column\_text\]\[movedo\_single\_image image="16913" el\_class="capture-img"\]\[vc\_column\_text\]

#### B. Propriétés d'affichage du modèle dans le dossier

**1 - Sinistre / Catégorie**

Pour rendre accessible un modèle à partir de la page Documents des dossiers de l'application, choisir l'option Sinistre = Oui et, de façon optionnelle, une catégorie dans laquelle classer le modèle.\[/vc\_column\_text\]\[movedo\_single\_image image="16915" el\_class="capture-img"\]\[vc\_column\_text el\_id="modele-documents-taches"\]**2 - Tâches du dossier**

Pour restreindre le modèle à certaines tâches spécifiques du dossier, sélectionner Tâches Spécifiques puis ajouter dans le tableau dessous une restriction sur une ou plusieurs tâches, voire sur une ou plusieurs étapes du formulaire d'une tâche en particulier.\[/vc\_column\_text\]\[movedo\_single\_image image="16918" el\_class="capture-img"\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="fenetre-modele-communications"\]\[vc\_column\]\[vc\_column\_text el\_id="fenetre\_proprietes\_modele"\]

### **3\. Fenêtre des propriétés d’un modèle de communication**

\[/vc\_column\_text\]\[movedo\_single\_image image="16919" el\_class="capture-img"\]\[vc\_column\_text\]**(1) Nom du modèle en cours de configuration**

**(2) Propriétés du modèle et des e-mails générés à partir de ce modèle**

**(3) Propriétés d'affichage du modèle dans le dossier**

**(4) Autres propriétés d'affichage du modèle spécifiques à chaque application iWE**

**(5) Accès aux champs avancés**

**(6) Boutons d'action de la page Annuler/Enregistrer**\[/vc\_column\_text\]\[vc\_column\_text\]

#### A. Propriétés du modèle et des e-mails générés à partir de ce modèle

**1 - Nom du modèle**

Nom proposé lors de la génération de l'e-mail dans l'application\[/vc\_column\_text\]\[movedo\_single\_image image="16920" el\_class="capture-img"\]\[vc\_column\_text\]**2 - A, CC, CCI (contacts), Objet**

Destinataires directs, en copie et en copie cachée ainsi que l'objet de l'e-mail généré à partir du modèle. Les champs destinataires peuvent contenir plusieurs e-mails. Il faut les remplir à l'aide d'individus et/ou de sociétés présents dans le carnet d'adresses.

Les destinataires configurés dans ces champs (contacts) sont destinataires de chaque e-mail généré à partir de ce modèle, quel que soit le dossier à partir duquel l'e-mail est créé.

Pour que le ou les destinataires soient relatifs aux participants du dossier, il est nécessaire de passer par les [champs avancés](#champs-avances-et-variables) pour le moment.\[/vc\_column\_text\]\[movedo\_single\_image image="16921" el\_class="capture-img"\]\[vc\_column\_text\]

#### B. Propriétés d'affichage du modèle dans le dossier

**1 - Sinistre**

Pour rendre accessible un modèle à partir de la page Communications des dossiers de l'application, choisir l'option Sinistre = Oui.

**2 - Tâches du dossier**

Pour restreindre le modèle à certaines tâches spécifiques du dossier, procéder de la même façon que pour un [modèle de document](#modele-documents-taches). Pour le moment, les e-mails ne peuvent pas être générés depuis le formulaire d'une tâche, la restriction peut donc uniquement porter sur le nom de la tâche et non une étape du formulaire d'une tâche contrairement aux modèles de documents.

Ainsi configuré, le modèle d'e-mail sera accessible depuis la barre latérale de tâche, dans l'onglet Communications.\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="champs-avances-et-variables"\]\[vc\_column\]\[vc\_column\_text\]

### **4\. Champs avancés et variables dans les propriétés des modèles**

Les propriétés Ancre, Expression d'applicabilité et, pour les modèles de communications, les destinataires (A, CC, CCI) exprimés sous forme d'expression sont des informations avancées qui ne sont pas modifiables sans connaître le langage de développement spécifique et le modèle technique de l'application.

Pour modifier ces propriétés, il est indispensable pour le moment, de vous adresser à l'équipe iWE qui vous accompagnera dans la configuration avancée de vos modèles.

Il est possible, avec une expression, par exemple, de rendre accessible un modèle de document ou d'e-mail en fonction de critères précis du dossier tels qu'un montant supérieur à une certaine valeur, le type de dossier, etc.

Il est également possible de rendre dynamique une partie du nom d'un document ou de l'objet d'un e-mail afin, par exemple, d’indiquer une référence ou un nom de participant dans le nom du document ou dans l'objet de l'e-mail généré.\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="proprietes-specifiques"\]\[vc\_column\]\[vc\_column\_text\]

### **5\. Propriétés spécifiques par application**

Il est possible que des propriétés supplémentaires non citées précédemment vous soient également accessibles telles que le processus ou le mandant par exemple. Ces propriétés dépendent de votre application.

Nous vous invitons à consulter la documentation spécifique à votre application ou à vous rapprocher de l'équipe iWE afin d’en prendre connaissance.\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]
