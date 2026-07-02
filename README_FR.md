<p align="center">
  <img src="docs/images/Palks_Studio.png" alt="Palks Studio" width="1200">
</p>

> 🇫🇷 Français | [🇬🇧 English](./README.md)

![Automation](https://img.shields.io/badge/Automation-0095b1?style=flat)
![Static-first](https://img.shields.io/badge/Static--first-2c3e50?style=flat)
![Minimal dependencies](https://img.shields.io/badge/Minimal%20dependencies-27ae60?style=flat)
![Deterministic systems](https://img.shields.io/badge/Deterministic%20systems-8e44ad?style=flat)
[![Malt](https://img.shields.io/badge/Malt-Profile-FF4F8B?style=flat)](https://www.malt.fr/profile/anthonyleignel)
[![YouTube](https://img.shields.io/badge/YouTube-@Palks__Studio-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@Palks_Studio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-@Palks__Studio-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/palks-studio/)

<p align="center">
  <a href="https://palks-studio.com">
    <img src="https://img.shields.io/badge/Palks%20Studio-Website-0095b1?style=for-the-badge" />
  </a>
</p>

# Palks Studio

> Ce dépôt constitue une présentation.  
> Il ne contient pas de code source téléchargeable ni de fichiers de production.

## Systèmes backend autonomes

Facturation électronique, automatisation, outils internes et infrastructures légères déployés directement chez le client, sans SaaS ni dépendances externes.

Conception de systèmes techniques autonomes, maintenables et adaptés à des usages réels : traitement documentaire, workflows métier, génération PDF, archivage structuré et automatisations backend.

---

## À propos

Éditeur / intégrateur indépendant spécialisé dans les systèmes backend autonomes et la facturation électronique.

Je développe des outils techniques conçus pour fonctionner durablement en production, avec une approche centrée sur la simplicité, la stabilité, la maintenabilité et le contrôle des données.

---

## Ce que je déploie

Je développe des systèmes techniques autonomes utilisés dans des contextes réels : systèmes backend autonomes, systèmes de facturation électroniques autonomes, automatisation et outils internes.

### Billing System

Système de facturation électronique complet, déployé directement sur l’infrastructure du client :

- devis → signature → facture → acquittement  
- génération de factures conformes Factur-X / EN16931  
- génération PDF (client + serveur)  
- archivage structuré sans base de données  
- numérotation sécurisée et traçabilité  
- envoi automatique des emails  
- interface bilingue FR / EN

Conçu pour remplacer un SaaS de facturation tout en conservant un contrôle total sur les données et l’infrastructure.

[![Facturation sans SaaS](https://img.shields.io/badge/Facturation%20sans%20SaaS-0095b1?style=flat)](https://palks-studio.com/fr/facturation-sans-saas)

### Candidate System

Système de recrutement par scoring automatique, déployé directement sur l'infrastructure du client :  

- formulaire candidat → scoring → dashboard → export  
- scoring déterministe à 3 niveaux : section, question, réponse  
- malus configurables par campagne  
- gestion multi-campagnes sans intervention sur le code  
- stockage JSON sans base de données  
- emails automatiques (accusé de réception + clôture)  
- interface bilingue FR / EN

Conçu pour remplacer le tri manuel des candidatures tout en conservant un contrôle total sur les critères, les données et l'infrastructure.

[![Recrutement sans SaaS](https://img.shields.io/badge/Recrutement%20sans%20SaaS-0095b1?style=flat)](https://palks-studio.com/fr/recrutement-sans-saas)

### Data Collection System

Système de collecte de données autonome fonctionnant localement ou sur infrastructure dédiée :

- recherches multi-sources (DuckDuckGo, Bing, Qwant)  
- extraction de sites web, emails et numéros de téléphone  
- nettoyage, normalisation et validation des données  
- suppression automatique des doublons  
- suivi des prospects déjà contactés  
- exports CSV et JSON  
- interface web intégrée  
- fonctionnement local sans SaaS ni API payante

Conçu pour centraliser et exploiter des données structurées tout en conservant un contrôle total sur l'infrastructure et les données collectées.

Livraison possible :

- archive ZIP avec documentation d'installation  
- déploiement serveur sur demande

[![Système de Collecte de Données FR](https://img.shields.io/badge/Collecte%20de%20Données-FR-0095b1?style=for-the-badge)](https://palks-studio.com/fr/collecte-de-donnees)

### Autres systèmes backend sur mesure

- outils internes et workflows métier  
- automatisation de traitements et tâches récurrentes  
- génération et traitement de documents PDF  
- systèmes documentaires et archivage structuré  
- intégration Stripe et traitements sécurisés  
- systèmes backend sans base de données  
- interfaces internes et traitements batch  
- déploiement serveur autonome sans SaaS

#### Automation Finance

Système de facturation batch PDF :

- génération automatique depuis CSV  
- production de factures structurées  
- archivage et traçabilité complète  
- livraison sécurisée par token  
- traitement en lot reproductible

Utilisé pour automatiser des volumes de facturation récurrents.

[![Facturation batch Factur-X](https://img.shields.io/badge/Batch%20Invoicing%20(Factur--X)-0095b1?style=flat)](https://github.com/Palks-Studio/automation-system)

#### Outils complémentaires

**Moteur d’acquittement PDF**  
Outil permettant de traiter des factures en lot, intégré dans les workflows Automation Finance.

- import ZIP  
- détection automatique des PDF  
- génération de factures acquittées  
- export individuel ou batch

[![Invoice Stamper](https://img.shields.io/badge/Invoice%20Stamper-GitHub-0095b1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Palks-Studio/invoice-stamper)

---

### Autres outils

- générateur de devis (100 % navigateur)  
- démonstrateur de facturation électronique Factur-X  
- socles de sites statiques HTML/CSS  
- chatbots locaux (Flask)  
- frameworks de documentation  
- configurations de développement

[![Ressources techniques](https://img.shields.io/badge/Ressources%20techniques-0095b1?style=flat)](https://palks-studio.com/fr/ressources)

---

Chaque déploiement comprend :  

- installation sur serveur (mutualisé ou VPS)  
- configuration complète (emails, chemins, identité)  
- adaptation aux données existantes  
- tests et validation  
- documentation utilisateur

Objectif : un système autonome, stable et maintenable dans le temps.

[![Contact](https://img.shields.io/badge/Contact-0095b1?style=flat)](https://palks-studio.com/fr/contact)

---

## Pour qui

- freelances et indépendants  
- artisans et petites structures  
- PME et équipes métier  
- entreprises souhaitant des systèmes autonomes sans SaaS  
- projets techniques nécessitant des outils simples, fiables et maintenables

---

## Approche

- systèmes autonomes, sans SaaS  
- dépendances minimales  
- architecture lisible  
- fonctionnement prévisible  
- maintenance long terme

Les outils publiés ici privilégient la clarté, la stabilité et l’autonomie.  
L’objectif n’est pas d’ajouter de la complexité, mais d’en retirer.

Les systèmes privilégient l'exécution locale lorsque cela est possible  
afin de réduire les dépendances externes et garantir la portabilité.

- https://palks-studio.com
