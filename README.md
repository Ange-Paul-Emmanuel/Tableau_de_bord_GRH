# Gestion des Ressources Humaines – Dashboard Power BI  

## Contexte du projet  
Ce projet a pour objectif de **concevoir un tableau de bord interactif de suivi des Ressources Humaines** à partir de données internes.  
Le but est d’aider la Direction RH à :  
- Suivre la répartition des employés (genre, ancienneté, niveau de compétence, etc.)  
- Identifier les tendances (promotions, départs à la retraite, turnover)  
- Évaluer la satisfaction et la performance des collaborateurs  
- Anticiper les besoins en recrutement et en formation  

---

## Objectifs du dashboard  
- Fournir une **vue globale** sur l’effectif et sa composition.  
- Identifier les employés en **attente de promotion** et ceux **proches de la retraite**.  
- Suivre les **indicateurs de performance** et de **satisfaction**.  
- Analyser la **répartition des salaires et heures supplémentaires**.  
- Permettre une **exploration interactive** par département, poste ou employé.  

---

## Indicateurs clés (KPIs) suivis  
- **Effectif total** : 1 470 employés  
- **Répartition H/F** : 60 % hommes (882), 40 % femmes (588)  
- **Promotions** : 72 employés en attente (4,9 %)  
- **Retraite** : 117 départs prévus (8 %)  
- **Satisfaction** : 569 très satisfaits, 459 satisfaits, 442 pas satisfaits  
- **Performance** : 84,6 % très performants, 15,4 % peu performants  
- **Heures supplémentaires** : 28,3 % d’employés concernés  
- **Salaire max observé** : 19 999 $  

---

## Structure du dashboard  
Le rapport est organisé en plusieurs pages :  

1. **Accueil** – Informations générales et navigation.
   
<img width="1294" height="740" alt="Page 1" src="https://github.com/user-attachments/assets/ed3983cf-1e7b-40f5-8abf-fd99d8a669fc" />

2. **Vue Globale** – Effectifs, promotions, retraites, satisfaction, performance.
<img width="1301" height="740" alt="Page 2" src="https://github.com/user-attachments/assets/01695b18-9cf9-4b1e-b131-4cb9415979b0" />
    
3. **Employés** – Détails individuels par nom, poste, département (avec photo et statut).
<img width="1307" height="746" alt="Page 3" src="https://github.com/user-attachments/assets/beeed6cd-da77-4ae0-b781-d09669fb1d5f" />


---

## Outils & Technologies  
- **Power BI Desktop** : création des visualisations, mesures DAX, et navigation interactive.  
- **Excel** : préparation et nettoyage des données brutes RH (effectifs, salaires, ancienneté, etc.).  
- **Python** :  
  - Génération automatisée de données fictives (UUID pour chaque employé).  
  - Création d’un pipeline pour associer à chaque employé une **photo générée aléatoirement** depuis [thispersondoesnotexist.com](https://thispersondoesnotexist.com).  
  - Export des données enrichies (CSV) pour intégration dans Power BI.  
