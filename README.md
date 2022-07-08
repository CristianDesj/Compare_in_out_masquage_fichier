# Compare_in_out_masquage_fichier
REQUI:
*C'est un script python, il fonctionne actuellement correctement sur Jupyter_notebook et Anaconda

Version 1 - Le script crée un document de comparaison pour chaque fichier 
dans les dossiers d'entrée et de sortie, avec 3 onglets:
- In : Les fichiers de test du client
- Out : Fichiers anonymisés
- Comparaison : Matrice de comparaison, indiquant True si les valeurs sont égales, la valeur " - " si la valeur est Nan, et s'il y a des changements dans les données, elle affiche la valeur initiale et la valeur anonymisée.

Version 2 - (en développement), créez un .bat pour exécuter directement le script py


1. Sur votre PC, créer le répertoire C:\temp\comp_masque, C:\temp\comp_masque\in, C:\temp\comp_masque\out

2. Copier les fichiers respectives de ce répertoire C:\temp\comp_masque\in, C:\temp\comp_masque\out

3. Exécutez le fichier py (compare_In_Out.py)
    
4. Les fichiers de comparation sont créé, C:\temp\comp_masque
