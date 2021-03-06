# Astro

En physique et en astronomie, le rayon de Schwarzschild est le rayon de l'horizon d'un trou noir de Schwarzschild, lequel est un trou noir dont la charge électrique et le moment cinétique sont nuls. Cela signifie qu'en dessous de ce rayon tous les photons (circulant à la vitesse de la lumière), ont (en oubliant qu'on est dans un cadre relativiste) des trajectoires elliptiques et ne peuvent s'échapper.

Ce programme vise à calculer le rayon de Schwarzschild d'un astre. Si le rayon d'une étoile devient inférieur ou égal à son rayon de Schwarzschild, alors elle devient un trou noir, et tout objet qui s'approche en deçà du rayon de Schwarzschild d'un trou noir ne peut plus s'en échapper. Sa formule, sans entrer dans la géométrie de Schwarzschild, est la suivante : Rs = 2GM / c2.

RS est le rayon de Schwarzschild, G la constante de gravitation, M la masse de l'astre en kilogrammes et c la vitesse de la lumière (constante qui peut être modifiée dans le code source). Le programme prend en entrée une masse et calcule son rayon de Schwarzschild. La fonction de calcul est placée dans le fichier astro.c qui devra être testé. Elle renvoie le résultat selon certaines conditions : la masse, la vitesse et un paramètre booléen fictif.
