# Cahier des charges MVP : WOYO Match (v1)

## 1. Objectif
Relier des propriétaires de voitures et des chauffeurs VTC pour des collaborations **durables et vérifiées**.

## 2. Acteurs
- **Chauffeur** : cherche une voiture stable. Profil, zone, budget, contrat préféré.
- **Propriétaire** : publie ses voitures, choisit ses chauffeurs.
- **Administrateur** : vérifie les documents, traite les litiges.

## 3. Fonctionnalités du MVP
- Inscription par numéro de téléphone (code SMS).
- Vérification manuelle CNI + permis (badge « vérifié »).
- Publication d'une voiture : modèle, commune, contrat, versement, engagement minimum (3, 6 ou 12 mois).
- Classement par compatibilité : zone 30, contrat 30, budget 20, note 20 (sur 100).
- Candidature, proposition, essai de 7 jours, contact WhatsApp.
- Contrat numérique et évaluation croisée en fin d'essai puis chaque trimestre.

## 4. Règles de notation
- Notes de 1 à 5 sur : ponctualité, conduite, courtoisie, état du véhicule, respect du contrat.
- **Réciproque** : le propriétaire note le chauffeur, le chauffeur note le propriétaire (mêmes poids).
- Note globale = moyenne des évaluations, les 90 derniers jours comptant double. Elle reste entre 1 et 5.
- Statut affiché seulement après **3 évaluations minimum** (avant : « Nouveau »). Vert ≥ 4, jaune ≥ 3, rouge < 3.
- Contestation **gratuite** ; examen par un médiateur sous 72 h.
- Publication des évaluations après 48 h.

## 5. Modèle économique
- Gratuit au lancement.
- Ensuite : forfait payé par le propriétaire pour chaque collaboration conclue (montant à valider sur le terrain).
- Profil chauffeur gratuit.

## 6. Contraintes
- Mobile-first, léger (3G), français puis dioula.
- Données personnelles : conformité à la loi ivoirienne 2013-450 et déclaration auprès de l'ARTCI.
- Hébergement et sauvegardes à définir.

## 7. À décider
- Prix du forfait propriétaire.
- Base de données et hébergement (ex. PostgreSQL managé).
- Processus de vérification des documents et responsable.
- Conditions générales d'utilisation (avis juridique).
