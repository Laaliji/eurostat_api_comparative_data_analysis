# Problématique : Analyse comparative des conditions de vie

**Comment les conditions de vie varient-elles en fonction des groupes sociaux ou des régions ?**

## Contributors

- [**Hamza Ouadoud**](https://github.com/hnioua)
- [**Abdessamad Hnioua**](https://github.com/hamzaODprogramer)

---

## Méthodologies à envisager

- **Régressions multiples** :  
  Pour étudier les facteurs influençant les conditions de vie (revenu, éducation, accès aux services).

- **ANOVA / Test d’hypothèse** :  
  Pour comparer les moyennes des conditions de vie entre plusieurs groupes (régions, catégories socio-économiques).

- **Analyse en composantes principales (ACP)** :  
  Pour réduire les dimensions et identifier les principaux facteurs influençant les conditions de vie.

- **Classification / Clustering** :  
  Pour regrouper les populations ayant des conditions de vie similaires.

---

## Dimensions des conditions de vie

Les conditions de vie regroupent plusieurs dimensions :  

- **Revenu et emploi** : accès aux opportunités économiques.  
- **Logement** : qualité et accès au logement.  
- **Santé** : accès aux soins, espérance de vie.  
- **Éducation** : taux de scolarisation, accès à la formation.  
- **Protection sociale** : mécanismes de soutien (allocations, retraites).  
- **Inégalités** : différences entre groupes sociaux, sexes ou régions.

---

## API Choisie : Eurostat Statistics API

### Ressources  
- **Base de données Eurostat** :  
  [https://ec.europa.eu/eurostat/data/database](https://ec.europa.eu/eurostat/data/database)  

- **Documentation API** :  
  [https://wikis.ec.europa.eu/display/EUROSTATHELP/API+-+Getting+started+with+statistics+API](https://wikis.ec.europa.eu/display/EUROSTATHELP/API+-+Getting+started+with+statistics+API)  

---

### Fonctionnement de l'API

**Structure de la requête REST** :  

```plaintext
{host_url}/{service}/{version}/{response_type}/{datasetCode}?{format}&{lang}&{filters}
