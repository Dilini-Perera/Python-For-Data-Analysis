# Python-For-Data-Analysis
## Final project of the course. 

#### DataSet
Default of credit card clients

##### Source :  UCI Machine Learning Repository 

#### Contexte 
Nous avons des informations sur les paiements en retard, les facteurs démographiques, les données de crédit, l'historique des paiements et les relevés de factures des clients de cartes de crédit à Taïwan d'avril à septembre 2005

#### Target 
La colonne cible correspond à « default payment next month ». La variable (booléen) précise si le client a effectivement payé ou non sa facture. 

#### But 
Prédire si le client X paiera ou non la prochaine facture 

#### Colonnes 
1. ID : Id du client
2. LIMIT_BAL : Montant du crédit donné en dollars
3. SEX : Genre
- 1 = Homme
- 2 = Femme
4. EDUCATION : Niveau d’étude
- 1 = Troisième cycle universitaire
- 2 = Université
- 3 = Lycée
- 4 = Autres
5. PAY_0, PAY_2, PAY_3, PAY_4, PAY_5, PAY_6 : respectivement le statut de paiement de septembre 2005 à avril 2005 (ordre antéchronologique)
- -1 si paiement sans retard
- Sinon variable = nombre de mois de retard
6. BILL_AMT1, BILL_AMT2, BILL_AMT3, BILL_AMT4, BILL_AMT5, BILL_AMT6 : montant de la facture (de septembre à avril)
7. PAY_AMT1, PAY_AMT2, PAY_AMT3, PAY_AMT4, PAY_AMT5, PAY_AMT6 : montant du paiement précédent (de septembre à avril)
8. default payment next month : retard de paiement 
- 1 = Oui
- 2 = Non

#### ! Imports info !

Les imports dans ce notebook :
- pandas 
- numpy
- seaborn
- sklearn
- catboost (pip3 command)
- lightgbm
- xgboost
