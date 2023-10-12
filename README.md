# all-quality-image-converter
import matplotlib.pyplot as plt

# Création des données pour le graphique
x = [1, 2, 3, 4, 5]
y = [2, 4, 6, 8, 10]

# Tracé du graphique
plt.plot(x, y)

# Ajout de labels aux axes
plt.xlabel('Axe des X')
plt.ylabel('Axe des Y')

# Ajout d'un titre au graphique
plt.title('Mon graphique')

# Sauvegarde de l'image en tant que fichier exécutable
plt.savefig('mon_graphique.png', dpi=300, format='png')
