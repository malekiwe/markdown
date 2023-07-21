---
title: "Comment gérer les utilisateurs de l’application ?"
date: "2020-09-09"
categories: 
  - "gestion-administration"
---

\[vc\_row padding\_top\_multiplier="" padding\_bottom\_multiplier=""\]\[vc\_column\]\[vc\_column\_text\]Tout utilisateur de l’application doit avoir été préalablement invité pour pouvoir créer son compte et se connecter. La gestion des utilisateurs et des invitations se fait via la page Administration de l’application réservée à certains profils utilisateurs.

1. [Gérer les invitations](#invitation-1)
2. [Durée de validité d’une invitation](#validite-2)
3. [Gérer les utilisateurs](#utilisateurs-2)
4. [Définir la politique de mot de passe par profil utilisateur](#password-3)
5. [Activer l’authentification multifacteur par email](#MFA)

\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="invitation-1"\]\[vc\_column\]\[vc\_column\_text\]

### **1\. Gérer les invitations**

Via la page dédiée, les utilisateurs ayant les droits d’invitation peuvent inviter, renvoyer une invitation et annuler les invitations qui n’ont pas encore été acceptées.

Il est également possible d’appliquer des filtres sur la liste des invitations.\[/vc\_column\_text\]\[movedo\_single\_image image="17154" el\_class="capture-img"\]\[vc\_column\_text\]Pour aller plus loin, l’article suivant présente l’ensemble des méthodes pour inviter un utilisateur à l’application : [Comment inviter un utilisateur à se connecter à l’application iWE ?](https://learn.iwecloud.com/gestion-administration/comment-inviter-user-iwe/)\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="validite-2"\]\[vc\_column\]\[vc\_column\_text\]

### **2\. Durée de validité d’une invitation**

Une invitation a une durée de validité limitée à 7 jours mais il est possible de paramétrer cette durée différemment par application et par profil de sécurité. Par exemple : 1 jour pour un administrateur, 10 jours pour un invité extranet. Pour modifier la durée de validité par défaut d’une invitation, nous vous invitons à contacter votre interlocuteur iWE.

Passé ce délai de validité, l’invitation devient expirée. Elle peut être renvoyée via l’interface d’administration.\[/vc\_column\_text\]\[movedo\_single\_image image="17292" el\_class="capture-img"\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="utilisateurs-2"\]\[vc\_column\]\[vc\_column\_text\]

### **3****. Gérer les utilisateurs**

Via la page d’administration des utilisateurs, les administrateurs de l’application peuvent changer le profil de sécurité, suspendre ou supprimer un compte utilisateur. Ces actions peuvent être réalisées simultanément sur plusieurs comptes utilisateurs. La page des utilisateurs peut être filtrée pour faciliter la recherche d’un ou d’un ensemble d’utilisateurs.

#### Présentation de la page d’administration des utilisateurs

\[/vc\_column\_text\]\[movedo\_single\_image image="17293" el\_class="capture-img"\]\[vc\_column\_text\]**(1)** Filtres actifs sur la liste des utilisateurs **(2)** Nom complet du contact **(3)** Adresse email utilisée comme login par l’utilisateur **(4)** Organisation sécurisée dont fait partie l’utilisateur **(5)** Etat du compte : Actif / Suspendu / Bloqué **(6)** Profil de sécurité du compte **(7)** Date et heure de dernière connexion **(8)** Adresse ip de la dernière connexion **(9)** Etat de synchronisation du calendrier externe : Jamais connecté / Déconnecté / Synchronisé **(10)** Authentification multifacteur : Activé / Non activé. Cf. [Activer l’authentification multifacteur](#MFA) **(11)** Suppression des filtres actifs **(12)** Rafraîchissement de la liste des utilisateurs **(13)** Accès au panneau de filtres **(14)** Accès à la fonction d’export de la liste au format Excel\[/vc\_column\_text\]\[vc\_column\_text\]

#### Changer le profil de sécurité d’un utilisateur

\[/vc\_column\_text\]\[movedo\_single\_image image="17294" el\_class="capture-img"\]\[vc\_column\_text\]

#### Suspendre / Réactiver un utilisateur

Cette action peut être effectuée sur une ou plusieurs utilisateurs simultanément.\[/vc\_column\_text\]\[movedo\_single\_image image="17295" el\_class="capture-img"\]\[vc\_column\_text el\_id="user-delete"\]

#### Suspendre / Supprimer un utilisateur

Seul un utilisateur suspendu peut être supprimé. La suppression est définitive. Cette action peut être effectuée sur une ou plusieurs utilisateurs simultanément.\[/vc\_column\_text\]\[movedo\_single\_image image="17296" el\_class="capture-img"\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="password-3"\]\[vc\_column\]\[vc\_column\_text\]

### **4\. Définir la politique de mot de passe par profil utilisateur**

La politique de mot de passe peut différer selon le profil d’un utilisateur. Il est par exemple possible et conseillé d’utiliser des règles plus complexes pour les profils administrateurs de l’application, contrairement à d’autres utilisateurs ayant moins de droits sur les données de l’application.

La politique de mot de passe définie pour un utilisateur s’applique dès la création de son compte, lors d’un changement de mot de passe via la page de son compte iWE ou encore lors de l’utilisation de la fonctionnalité mot de passe oublié.

Les politiques de mot de passe disponibles sur iWE sont les suivantes :\[/vc\_column\_text\]\[vc\_column\_text\]

#### **Niveau de sécurité: Très Faible / Faible / Moyen / Fort**

Il s’agit de la configuration par défaut de la politique de mot de passe des utilisateurs. Le niveau minimum requis pour valider le mot de passe est “Faible”. Il est possible, pour un profil, de relever le niveau de sécurité minimum requis à Moyen ou Fort. A noter qu’il n’est pas possible de diminuer le niveau de sécurité requis à Très faible.\[/vc\_column\_text\]\[movedo\_single\_image image="17252" el\_class="capture-img"\]\[vc\_column\_text\]

#### **Règles de complexité explicites**

Les règles suivantes sont facultatives et utilisables indépendamment les unes des autres :

- Pouvoir imposer un nombre de caractères minimum.
- Pouvoir imposer la présence de caractères spéciaux, de nombres et/ou de majuscules.
- Empêcher la répétition consécutives de caractères.

Dans l’exemple ci-après, un mot de passe valide doit avoir au moins 12 caractères, contenir au moins une majuscule, un chiffre et un caractère spécial et ne pas contenir plus de 2 caractères identiques consécutifs.\[/vc\_column\_text\]\[movedo\_single\_image image="17253" el\_class="capture-img"\]\[vc\_column\_text\]Si vous souhaitez configurer ou modifier votre politique de mot de passe, nous vous invitons à prendre contact avec votre interlocuteur iWE.\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]\[vc\_row padding\_top\_multiplier="" section\_id="MFA"\]\[vc\_column\]\[vc\_column\_text\]

### **5\. Activer l’authentification multifacteur par email**

La double authentification par email est une fonctionnalité de sécurité qui ajoute une étape supplémentaire de protection à votre compte. Elle peut être activée par profil de sécurité. Il est par exemple possible et conseillé de l’activer pour les profils administrateurs de l’application.

Après une première authentification, c’est-à-dire après avoir saisie un mail et un mot de passe valide, un email contenant un code est automatiquement envoyé à votre adresse mail. Vous devrez entrer ce code de vérification afin de pouvoir accéder à votre compte.

**Fonctionnement** 

- Vous recevez un code par email après avoir saisie un mot de passe valide
- Le code expire après 10 min
- Si vous générez un nouveau code, le code précédent ne fonctionnera plus 
- Lorsque vous recevez le code de vérification par email, entrez-le dans la champ prévue à cet effet sur la page de connexion. Si le code est correct, vous serez redirigé vers votre compte.

Les politiques de mot de passe disponibles sur iWE sont les suivantes :\[/vc\_column\_text\]\[movedo\_single\_image image="17270" el\_class="capture-img"\]\[vc\_column\_text\]Nous vous encourageons à activer la double authentification par email pour protéger votre compte et vos données. Si vous avez des questions, n'hésitez pas à contacter notre équipe d'assistance IWE.\[/vc\_column\_text\]\[/vc\_column\]\[/vc\_row\]
