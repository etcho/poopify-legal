---
layout: default
title: "Politique de confidentialité"
permalink: /fr/privacy-policy/
lang: fr
---

*Ceci est une traduction. En cas de divergence, la [version anglaise](https://etcho.github.io/poopify-legal/privacy-policy/) prévaut.*

# Poopify - Politique de confidentialité

**Date d'entrée en vigueur :** 21 octobre 2026
**Version :** 1.0

La présente Politique de confidentialité explique quelles données personnelles l'application Poopify (l'« Application ») traite, pourquoi, et quels sont vos droits. Elle s'applique à l'Application sur tous les appareils et au service facultatif de Synchronisation cloud.

## Résumé

- **Par défaut, vos données de santé ne quittent jamais votre appareil.** En Mode local, tout ce que vous enregistrez (selles, cycle menstruel, symptômes, notes, profils) est stocké uniquement sur votre téléphone. Nous ne le recevons pas.
- **La Synchronisation cloud est facultative.** Si vous l'activez et donnez votre consentement explicite, une copie de vos enregistrements est stockée dans le cloud (Google Firebase, dans l'Union européenne) afin d'être synchronisée entre vos appareils. La Synchronisation cloud est déployée progressivement et **peut ne pas être disponible dans toutes les régions**.
- **Nous ne vendons jamais vos données, n'utilisons jamais vos données de santé à des fins publicitaires et ne les partageons jamais avec qui que ce soit pour ses propres fins.**
- L'Application affiche des publicités et utilise les outils d'analyse et de rapports de plantage de Google. Ces services reçoivent des identifiants de l'appareil et des informations d'utilisation de l'Application, **mais pas le contenu de vos données de santé.**
- Vous pouvez désactiver la Synchronisation cloud, exporter vos données ou supprimer votre compte cloud à tout moment, directement dans l'Application (Menu > Confidentialité).

---

## 1. Qui est responsable de vos données

Le responsable du traitement de vos données personnelles est :

Everton Carvalho Leite, développeur indépendant, Rio de Janeiro, Brésil
E-mail : **poopify.dev@gmail.com**

- **Contact pour la protection des données / Encarregado (LGPD) :** Everton Carvalho Leite, poopify.dev@gmail.com

## 2. Données stockées uniquement sur votre appareil (Mode local)

Lorsque vous utilisez l'Application sans la Synchronisation cloud, les données suivantes sont stockées **uniquement sur votre appareil**, dans l'espace de stockage privé de l'Application :
- les enregistrements que vous saisissez : date et heure, caractéristiques des selles, symptômes, douleur, notes sur les médicaments et l'alimentation, méthode d'hygiène, informations sur le cycle menstruel, notes en texte libre ;
- les profils que vous créez (nom, icône, date de naissance facultative) et les paramètres de l'Application.

Nous n'avons pas accès à ces données. Elles ne nous sont pas envoyées, ni à aucun tiers, sauf dans les cas suivants, que vous contrôlez :
- **Exports et partage :** lorsque vous exportez une sauvegarde, un fichier CSV, JSON ou PDF, le fichier est créé sur votre appareil et envoyé uniquement là où vous choisissez de le partager.
- **Sauvegarde de l'appareil Android :** selon les réglages de votre appareil, Android peut inclure les données de l'Application dans la sauvegarde de l'appareil sur votre compte Google. Cette sauvegarde est gérée par Google et par les réglages de votre appareil, pas par nous.

## 3. Synchronisation cloud (facultative)

La Synchronisation cloud est une fonctionnalité facultative déployée progressivement. Elle **peut ne pas être disponible dans tous les pays ou toutes les régions**, et là où elle n'est pas disponible, l'Application ne l'affiche pas.

### 3.1 Ce que nous traitons
Si vous activez la Synchronisation cloud, nous traitons :
- **Données du compte :** un identifiant unique du compte et l'adresse e-mail du compte avec lequel vous vous connectez (par exemple votre compte Google), gérés par Firebase Authentication.
- **Vos données de santé :** une copie des enregistrements et profils décrits à la Section 2, **à l'exception des données de localisation**.
- **Données techniques de synchronisation :** un identifiant d'appareil généré par l'Application, l'horodatage des modifications et l'état de la synchronisation.
- **Preuve du consentement :** la version de la présente Politique de confidentialité et des Conditions d'utilisation que vous avez acceptée, et la date.
- **Signaux d'intégrité de l'Application :** des informations confirmant que les requêtes proviennent d'une copie authentique de l'Application (Firebase App Check avec Google Play Integrity).

### 3.2 Finalités et base juridique
- **Finalité :** uniquement stocker vos enregistrements, les synchroniser entre les appareils connectés à votre compte et vous permettre de les restaurer sur un nouvel appareil.
- **Base juridique :** votre **consentement explicite** (RGPD art. 6(1)(a) et art. 9(2)(a) ; LGPD art. 7, I et art. 11, I ; et règles équivalentes dans d'autres juridictions). Les données du compte et les données techniques sont traitées car elles sont nécessaires pour fournir le service que vous avez demandé (RGPD art. 6(1)(b) ; LGPD art. 7, V).
- Vous pouvez **retirer votre consentement à tout moment** en supprimant vos données du cloud dans l'Application (Section 9). Désactiver seulement la Synchronisation cloud arrête la synchronisation : la copie déjà présente dans le cloud y reste jusqu'à ce que vous la supprimiez, et l'Application vous propose de la supprimer lorsque vous désactivez la synchronisation. Le retrait n'affecte pas le traitement effectué avant celui-ci.
- Nous **n'utilisons pas** vos données du cloud à des fins d'analyse, de publicité, de profilage, de recherche, d'entraînement d'intelligence artificielle ni à aucune autre fin que la fourniture de la Synchronisation cloud.

### 3.3 Où vos données sont stockées
Les données de la Synchronisation cloud sont stockées sur des serveurs Google Cloud situés dans l'**Union européenne** (multirégion « eur3 » de Firestore). Google agit en tant que sous-traitant conformément aux Conditions relatives au traitement et à la sécurité des données de Firebase.

### 3.4 Qui peut y accéder
- **Via l'Application, uniquement votre compte.** Les règles de sécurité des serveurs empêchent tout autre compte de lire ou d'écrire vos données.
- **Le développeur, uniquement dans des cas exceptionnels.** Les données sont chiffrées en transit et au repos, mais pas de bout en bout : techniquement, elles peuvent être consultées via la console d'administration du service. Cette console est réservée au compte du développeur, protégée par une validation en deux étapes, et ses accès sont journalisés. Nous ne consultons vos données du cloud que si vous nous demandez expressément de l'aide pour votre compte, ou si la loi nous y oblige.
- **Google**, en tant que fournisseur d'infrastructure, traite les données uniquement pour les héberger pour notre compte.

### 3.5 Disponibilité par région
La Synchronisation cloud peut être indisponible dans certains pays ou régions pour des raisons juridiques ou techniques. Si elle n'est plus disponible là où vous vous trouvez, la synchronisation s'arrête, les données de vos appareils ne sont pas affectées, et vous pouvez toujours supprimer votre compte et vos données du cloud à tout moment dans Menu > Confidentialité.

## 4. Publicité

- L'Application affiche des publicités fournies par **Google AdMob**. AdMob peut traiter l'identifiant publicitaire de votre appareil, votre adresse IP et des informations sur les publicités affichées et cliquées.
- Dans l'Espace économique européen, au Royaume-Uni, en Suisse et partout où la loi l'exige, nous vous demandons votre consentement avant de personnaliser les publicités, à l'aide de l'outil de consentement de Google. Vous pouvez modifier votre choix à tout moment dans le menu de l'Application, sous **Options de confidentialité des publicités** (affiché là où ce choix s'applique).
- Sur Android, vous pouvez aussi réinitialiser ou supprimer votre identifiant publicitaire dans les réglages de l'appareil.
- **Le contenu de vos données de santé n'est jamais partagé avec AdMob ni utilisé pour choisir des publicités.**
- Si vous achetez « Supprimer les publicités », les publicités ne sont plus affichées.
- Plus d'informations : https://policies.google.com/technologies/partner-sites

## 5. Analyse et rapports de plantage

- Nous utilisons **Google Analytics pour Firebase** pour comprendre comment l'Application est utilisée (par exemple, quels écrans sont ouverts et quelles fonctionnalités sont utilisées) et **Firebase Crashlytics** pour recevoir des rapports de plantages et d'erreurs.
- Ces services traitent un identifiant d'installation de l'Application, des informations sur l'appareil et le système d'exploitation, une localisation approximative déduite de l'adresse IP (pays et région) et des événements d'utilisation.
- Les événements d'utilisation enregistrent **qu'**une fonctionnalité a été utilisée (par exemple, « un enregistrement a été créé »), **jamais le contenu** de ce que vous avez enregistré.
- **Base juridique :** notre intérêt légitime à faire fonctionner et améliorer l'Application (RGPD art. 6(1)(f) ; LGPD art. 7, IX), ou votre consentement lorsque la loi l'exige.
- Analytics est associé à Google AdMob uniquement pour mesurer les performances et les revenus des publicités affichées dans l'Application. **Les données d'Analytics ne sont pas utilisées pour personnaliser les publicités** (la personnalisation des annonces et les signaux Google sont désactivés dans nos paramètres Analytics) et ne sont pas partagées avec d'autres partenaires publicitaires.
- **Conservation :** les données d'événements d'Analytics sont conservées 2 mois, et les données Analytics au niveau de l'utilisateur jusqu'à 14 mois. Les rapports de plantage sont conservés jusqu'à 90 jours.

## 6. Achats

Les achats (comme « Supprimer les publicités ») sont traités par **Google Play**. Nous recevons uniquement les informations nécessaires pour confirmer l'achat (comme un jeton et l'état de l'achat). Nous ne recevons pas vos informations de paiement. La politique de confidentialité de Google s'applique au paiement.

## 7. E-mails d'assistance

Si vous nous écrivez, nous traitons votre adresse e-mail et le contenu de votre message uniquement pour vous répondre, et nous conservons la conversation comme historique de notre assistance, jusqu'à ce que vous nous demandiez de la supprimer. Merci de ne pas envoyer d'informations de santé par e-mail sauf si nécessaire.

## 8. Avec qui nous partageons des données

Nous ne vendons pas de données personnelles et ne les « partageons » pas à des fins de publicité comportementale inter-contextes.

Nous faisons appel aux prestataires suivants (sous-traitants), qui traitent les données pour notre compte et selon nos instructions, ou en tant que responsables du traitement indépendants lorsque c'est indiqué :

| Prestataire | Service | Données | Rôle |
|---|---|---|---|
| Google (Firebase Authentication, Cloud Firestore, App Check) | Synchronisation cloud | Compte, données de la Synchronisation cloud | Sous-traitant |
| Google (Analytics pour Firebase, Crashlytics) | Analyse et rapports de plantage | Événements d'utilisation, données de l'appareil, identifiants | Sous-traitant |
| Google (AdMob) | Publicité | Identifiant publicitaire, IP, interactions avec les publicités | Responsable indépendant pour les publicités, voir Section 4 |
| Google (Google Play) | Achats | Données d'achat | Responsable indépendant |

Nous pouvons aussi divulguer des données lorsque la loi l'exige, ou pour protéger les droits, la sécurité ou l'intégrité des utilisateurs ou de l'Application, mais uniquement dans la mesure strictement nécessaire, et nous vous en informerons lorsque la loi le permet.

## 9. Vos choix et vos droits

### 9.1 Disponibles dans l'Application à tout moment
- **Désactiver la Synchronisation cloud :** vos données restent sur votre appareil et l'Application continue de fonctionner en Mode local.
- **Supprimer votre compte et vos données du cloud :** dans l'Application (Menu > Confidentialité > Supprimer un compte de Synchronisation cloud, ou Menu > Synchronisation cloud > Supprimer le compte et les données du cloud), ou sur [https://etcho.github.io/poopify-legal/fr/delete-account/](https://etcho.github.io/poopify-legal/fr/delete-account/).
- **Exporter vos données** (sauvegarde SQL, CSV, JSON, PDF), pour l'accès et la portabilité.
- **Corriger ou supprimer des enregistrements** directement dans l'Application.

### 9.2 Vos droits
Selon votre lieu de résidence, vous pouvez avoir le droit : d'accéder à vos données ; de les rectifier ; de les effacer ; de limiter le traitement ou de vous y opposer ; à la portabilité des données ; de retirer votre consentement ; de ne pas faire l'objet de décisions fondées exclusivement sur un traitement automatisé ; et d'être informé des personnes avec qui les données sont partagées.
- **Union européenne / EEE / Royaume-Uni (RGPD / UK GDPR) :** tous les droits ci-dessus. Vous pouvez aussi introduire une réclamation auprès de l'autorité de protection des données de votre pays.
- **Brésil (LGPD, art. 18) :** confirmation de l'existence du traitement, accès, correction, anonymisation, blocage ou suppression des données inutiles, portabilité, suppression des données traitées avec consentement, information sur le partage, information sur la possibilité de refuser le consentement et ses conséquences, et révocation du consentement. Vous pouvez aussi introduire une réclamation auprès de l'ANPD (autorité brésilienne de protection des données).
- **États-Unis :** voir les Sections 11 et 12.
- **Autres pays :** nous respectons les droits équivalents prévus par votre législation locale.

Pour exercer tout droit qui n'est pas disponible directement dans l'Application, écrivez à **poopify.dev@gmail.com**. Nous répondrons dans le délai prévu par la loi pour chaque type de demande (par exemple, jusqu'à 15 jours pour une confirmation complète et l'accès à vos données selon la LGPD, et un mois selon le RGPD, que le RGPD permet de prolonger dans certains cas). Nous pourrons avoir besoin de vérifier que la demande émane du titulaire du compte.

## 10. Durée de conservation des données

| Données | Conservation |
|---|---|
| Données du Mode local | Sur votre appareil, jusqu'à ce que vous les supprimiez ou désinstalliez l'Application |
| Données de la Synchronisation cloud | Jusqu'à ce que vous supprimiez votre compte ou vos données du cloud ; ou, au plus tard, jusqu'à ce que le compte n'ait été utilisé par aucun appareil pendant 24 mois consécutifs ; ou jusqu'à l'arrêt de la Synchronisation cloud. Les données de vos appareils ne sont affectées dans aucun de ces cas |
| Données du cloud supprimées | Retirées immédiatement de nos systèmes actifs ; les copies résiduelles dans les systèmes de sauvegarde de Google sont supprimées dans les délais fixés par les conditions de suppression des données de Google Cloud |
| Preuves du consentement (quelles versions de ces documents vous avez acceptées, et quand) | Conservées avec votre compte de Synchronisation cloud et supprimées avec lui, ou lorsque vous supprimez vos données du cloud |
| Analyse / rapports de plantage | Voir Section 5 |
| E-mails d'assistance | Voir Section 7 |

## 11. Informations complémentaires pour les résidents des États-Unis

- **Catégories collectées :** identifiants (ID du compte, ID d'installation de l'Application, identifiant publicitaire, adresse IP) ; activité internet ou électronique (événements d'utilisation de l'Application) ; géolocalisation approximative (à partir de l'IP, pour l'analyse) ; **informations personnelles sensibles / données de santé des consommateurs** (uniquement avec la Synchronisation cloud, voir Section 12) ; informations commerciales (état de l'achat).
- Nous ne vendons pas d'informations personnelles et ne les partageons pas à des fins de publicité comportementale inter-contextes, et ne l'avons pas fait au cours des 12 derniers mois.
- Nous utilisons les informations personnelles sensibles uniquement pour fournir le service que vous avez demandé ; le droit d'en limiter l'utilisation est donc appliqué par défaut.
- **Californie, Colorado, Connecticut, Virginie, Oregon, Texas et autres États dotés de lois sur la protection de la vie privée des consommateurs :** vous avez le droit de savoir, d'accéder, de corriger et de supprimer vos informations personnelles, et de ne pas faire l'objet de discrimination pour avoir exercé ces droits. Vous pouvez faire appel de toute décision concernant votre demande en répondant à notre réponse.
- Nous ne collectons pas sciemment d'informations personnelles d'enfants de moins de 13 ans via des comptes de Synchronisation cloud (voir Section 13).

## 12. Politique de confidentialité des données de santé des consommateurs (Washington, Nevada, Connecticut et lois similaires)

{% include fr/consumer-health-data.md %}

## 13. Enfants

- L'Application est un journal de santé personnel et ne s'adresse pas aux enfants.
- **Les comptes de Synchronisation cloud sont réservés aux adultes** (18 ans ou l'âge de la majorité là où vous vivez).
- Les parents et tuteurs peuvent utiliser l'Application pour tenir des enregistrements concernant leurs enfants, dans des profils séparés. Dans ce cas, le parent ou le tuteur est responsable de ces informations et consent au nom de l'enfant.
- Si vous pensez qu'un enfant a créé un compte de Synchronisation cloud, contactez-nous et nous le supprimerons.

## 14. Sécurité

Nous protégeons vos données par des mesures techniques et organisationnelles adaptées à leur sensibilité, notamment :
- le chiffrement en transit (TLS) et au repos ;
- des règles côté serveur qui ne permettent à chaque compte d'accéder qu'à ses propres données ;
- la vérification que les requêtes proviennent de l'Application authentique ;
- un accès administratif restreint, protégé par une validation en deux étapes et journalisé ;
- la minimisation des données (par exemple, les données de localisation ne sont jamais synchronisées) ;
- des tests automatisés de nos règles de sécurité.

Aucun système n'est totalement sûr. Si un incident de sécurité touche vos données personnelles, nous en informerons les autorités compétentes et vous-même, quand et comme la loi l'exige (par exemple, dans les 72 heures auprès de l'autorité de contrôle selon le RGPD).

## 15. Transferts internationaux

Nous sommes établis au Brésil, et nos prestataires peuvent traiter des données dans d'autres pays. Les données de la Synchronisation cloud sont stockées dans l'Union européenne. Lorsque des données personnelles sont transférées vers d'autres pays, nous nous appuyons sur des garanties appropriées, telles que les clauses contractuelles types de la Commission européenne, le cadre de protection des données UE-États-Unis le cas échéant, et les mécanismes prévus à l'art. 33 de la LGPD, tels que proposés par Google dans ses conditions de traitement des données.

## 16. Modifications de la présente politique

Nous vous informerons dans l'Application des modifications importantes avant leur entrée en vigueur. Si une modification affecte la manière dont nous traitons les données de la Synchronisation cloud, nous vous redemanderons votre consentement. Les versions précédentes restent disponibles à l'adresse de la version anglaise suivie du numéro de version (par exemple, https://etcho.github.io/poopify-legal/privacy-policy/1.0/).

La présente politique peut être traduite dans d'autres langues. En cas de conflit entre une traduction et la version anglaise, la version anglaise prévaut, sauf si la loi de votre pays en dispose autrement.

## 17. Contact

E-mail : **poopify.dev@gmail.com**

## Historique des versions

| Version | Date d'entrée en vigueur | Modifications |
|---|---|---|
| 1.0 | 21 octobre 2026 | Première version |
