# SQL_Data_Cleaning

On a effectué du __data cleaning__ à cette source de données qui a permis de:  

-Imputation univariée  
-Décomposer l'adresse PropertyAddress en colonnes individuelles (adresse, ville, état) en utilisant __SUBSTRING, PARSENAME__  
-Remplacez Y et N par Yes et No dans le champ "Sold as Vacant" avec l'instruction __CASE When__  
-détecter les entrées dupliquées en utilisant __une CTE et une partition by__  
-Supprimer les colonnes inutilisées
