---
layout: default
lang: fr
title: Politique de confidentialité
description: Politique de confidentialité de Balora. Vos données financières restent sur votre téléphone.
permalink: /fr/confidentialite/
home: /fr/
alternates:
  en: /privacy/
  es: /es/privacidad/
  fr: /fr/confidentialite/
---

# Politique de confidentialité

<p class="updated">Dernière mise à jour : {{ site.updated.fr }}</p>

<div class="summary" markdown="1">

**En bref :** vos données financières restent sur votre téléphone. Balora n'a pas d'autorisation d'accès à internet,
ni comptes utilisateur, ni publicité, ni outils d'analyse, ni suivi. Le développeur ne reçoit jamais vos opérations,
vos soldes ni vos montants. Les données ne quittent votre téléphone que si vous le décidez : quand vous exportez une
sauvegarde, quand vous transférez vos données vers un nouveau téléphone avec Android, quand vous utilisez la sauvegarde
sur votre compte Google de Balora Plus ou quand vous nous écrivez un e-mail.

</div>

## 1. Responsable

Balora est développée par **{{ site.owner }}** ({{ site.country.fr }}), responsable du traitement décrit dans cette
politique. Contact : [{{ site.email }}](mailto:{{ site.email }}).

## 2. Ce que Balora enregistre sur votre téléphone

Tout ce que vous saisissez est enregistré uniquement dans le stockage privé de l'application, sur votre téléphone :

- Les opérations (dépenses et revenus), les soldes de vos comptes, les catégories, les budgets, les opérations
  récurrentes et les réglages.
- **Profils :** si vous en avez plusieurs (par exemple un personnel et un professionnel), chacun garde ses données et
  ses réglages séparément, y compris sur le téléphone.
- **Import de relevés bancaires :** le fichier que vous choisissez est lu sur le téléphone et n'est pas conservé.
  Balora garde les opérations que vous importez, le numéro de compte (IBAN) et le libellé d'origine de chaque opération
  importée, pour ne pas importer deux fois la même, ainsi que les modèles d'import que vous enregistrez.
- **Sauvegarde automatique interne :** chaque jour, après vos modifications (au plus une fois par heure) et quand vous quittez l'application si vous avez modifié quelque chose, Balora garde
  une copie des données de chaque profil dans son stockage privé pour pouvoir les récupérer si la base de données est
  endommagée. Elle ne quitte le téléphone qu'avec la sauvegarde d'Android (section 3).

Le développeur n'a accès à rien de tout cela. Désinstaller l'application ou effacer ses données les supprime du
téléphone (sauf les sauvegardes que vous avez exportées vous-même).

## 3. Ce qui quitte votre téléphone, et seulement si vous le décidez

| Quand | Quoi | Qui le reçoit |
|---|---|---|
| Vous **exportez une sauvegarde** | Toutes vos données Balora, de tous vos profils, dans un fichier chiffré avec votre mot de passe ou en fichiers CSV (au choix) | Uniquement l'endroit que vous choisissez (le stockage du téléphone, une clé USB, un service cloud que vous utilisez…) |
| Vous utilisez la **sauvegarde sur votre compte Google** (Balora Plus, désactivée tant que vous ne l'activez pas) | La sauvegarde automatique de chaque profil et la liste de vos profils, via le service de sauvegarde d'Android | Votre compte Google. Elle n'est envoyée qu'avec Android 9 ou ultérieur et le verrouillage de l'écran activé, chiffrée de bout en bout avec celui-ci : ni Google ni le développeur ne peuvent la lire ; sous Android 8, elle n'est pas envoyée. Si vous la désactivez ou si l'abonnement prend fin, Balora n'envoie plus de nouvelles sauvegardes (au plus tard le lendemain), et Google conserve la dernière selon son service de sauvegarde. Google la traite selon ses [Règles de confidentialité](https://policies.google.com/privacy?hl=fr) |
| Vous **changez de téléphone** avec le transfert de données d'Android | La sauvegarde automatique de chaque profil et la liste de vos profils, copiées directement depuis l'ancien téléphone | Uniquement votre nouveau téléphone |
| Vous **nous écrivez un e-mail** (aussi avec « Envoyer une suggestion », qui ouvre seulement votre messagerie avec notre adresse et un objet) | Ce que vous écrivez et votre adresse e-mail. Balora n'ajoute aucun texte ni aucune donnée à l'e-mail | Le développeur, par e-mail depuis votre propre application de messagerie |

## 4. Achats : Balora Plus et soutien

Les abonnements et les paiements de soutien sont gérés par **Google Play**. Le développeur ne reçoit pas les données de
votre carte ni de votre paiement. Google lui transmet les informations de la commande (numéro de commande, produit,
prix, pays ou région, date et état), utilisées uniquement pour gérer l'achat et respecter les obligations comptables et
fiscales. Google traite votre paiement selon ses propres conditions et règles de confidentialité. Pour savoir si vous avez Balora Plus, Balora interroge l'application
Google Play de votre téléphone à son ouverture et une fois par jour en arrière-plan ; cette vérification n'envoie aucune donnée
de Balora.

## 5. Rapports de plantage

Si vous l'avez autorisé dans les réglages d'Android (*Utilisation et diagnostics*), Android peut envoyer à Google des
rapports sur les plantages et blocages de l'application, que le développeur consulte de façon agrégée dans Google Play
Console (Android Vitals). Balora n'ajoute aucun code pour cela et ces rapports ne contiennent aucune donnée financière.
Vous pouvez le désactiver dans les réglages d'Android.

## 6. Notes

Si Balora affiche la fenêtre de notation de Google Play, elle est affichée et gérée par Google. Balora ne sait pas si
vous avez noté l'application ni ce que vous avez écrit.

## 7. Verrouillage de l'application

Si vous activez le verrouillage, Android vérifie votre empreinte, votre visage, votre code, votre schéma ou votre mot de
passe. Balora reçoit seulement le résultat du déverrouillage : vos données biométriques n'arrivent jamais à
l'application.

## 8. Autorisations

- **Notifications :** pour le rappel mensuel des soldes, les opérations récurrentes à confirmer et les alertes de
  budget. Vous pouvez les désactiver à tout moment.
- **Biométrie :** uniquement pour le verrouillage facultatif de l'application.
- **Achats Google Play :** pour Balora Plus et les paiements de soutien.
- **Autorisations techniques** ajoutées par les bibliothèques d'Android : voir l'état du réseau (demandée par la
  bibliothèque des tâches programmées ; Balora ne se connecte pas à internet), démarrer à l'allumage du téléphone (pour
  reprogrammer les rappels) et garder le téléphone actif un instant pendant qu'une tâche se termine.

Balora ne demande **pas** l'accès à internet, à la position, aux contacts, à l'appareil photo, au micro ni à
l'identifiant publicitaire.

## 9. Ni publicité, ni analyse, ni vente de données

Balora ne contient ni publicité ni outils d'analyse ou de suivi, et le développeur ne vend, ne loue ni ne partage
aucune donnée personnelle.

## 10. Base légale et conservation

- **Suggestions et questions par e-mail :** votre consentement en écrivant et l'intérêt légitime à vous répondre.
  Elles sont conservées le temps nécessaire pour y répondre et au maximum deux ans, sauf si vous demandez leur
  suppression plus tôt.
- **Informations d'achat :** l'exécution du contrat et les obligations légales ; conservées pendant la durée exigée par
  les règles comptables et fiscales.

## 11. Vos droits

Conformément au RGPD, vous pouvez demander l'accès, la rectification ou l'effacement de vos données personnelles, en
limiter le traitement ou vous y opposer, et demander leur portabilité, en écrivant à
[{{ site.email }}](mailto:{{ site.email }}). Vous pouvez aussi introduire une réclamation auprès d'une autorité de
protection des données : en France, la [CNIL](https://www.cnil.fr) ; en Espagne, l'[AEPD](https://www.aepd.es).

Vos données financières se trouvent uniquement sur votre téléphone : vous pouvez les exporter, les modifier ou les
supprimer vous-même dans l'application à tout moment (pour toutes les supprimer : *Paramètres › Profil › Effacer les
données de ce profil*, gratuitement).

## 12. Sécurité

Les sauvegardes chiffrées utilisent AES-256-GCM avec une clé dérivée de votre mot de passe (PBKDF2, 600 000 itérations).
Si vous oubliez le mot de passe, personne ne peut récupérer la sauvegarde. L'application peut être protégée par le
verrouillage de l'écran du téléphone.

## 13. Mineurs

Balora est destinée aux adultes et ne s'adresse pas aux mineurs.

## 14. Modifications de cette politique

Si cette politique change, la nouvelle version sera publiée sur cette page avec sa date. Les changements importants
seront aussi annoncés dans l'application.

## 15. Contact

[{{ site.email }}](mailto:{{ site.email }})
