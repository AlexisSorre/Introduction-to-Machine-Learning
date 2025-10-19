# Spectral Clustering sur des données en Anneaux

Ce dossier présente une comparaison entre les méthodes **K-Means** et **Spectral Clustering** appliqués à des données en forme d’anneaux.

L’expérience met en évidence les limites de **K-Means** face à des structures non convexes (anneaux), l’algorithme découpe les anneaux de manière artificielle, sans respecter leur forme réelle.

À l’inverse, le **Spectral Clustering** exploite les relations de voisinage entre points et parvient à isoler correctement chaque anneau comme un cluster distinct.  
Cette approche offre une meilleure séparation visuelle et une interprétation plus fidèle de la structure des données.
