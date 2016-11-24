<h1>Java - Processus légers</h1>
Le code retour d’un programme doit être 0 si le programme se déroule normalement sinon le code retour est un entier positif (distinct selon le problème). Utilisez la méthode statique System.exit(int).
Le site http://java.sun.com/javase/6/docs/api/ contient la description complétée des classes (avec leurs méthodes) 
Vos programmes doivent être stockés dans un github que vous me transmettrez (nous ferons un TP0 pour git et github)
Une variable partagée par plusieurs processus légers est une variable dont la valeur peut être lue et modifiée par plusieurs processus légers.
<pre>
1. Programmez la classe Cpt.
  a. Indiquez le nombre maximum de processus légers co-existants au cours de l’exécution de Cpt. 
  b. Indiquez le nombre d’incrémentation de la variable global _cpt, par chaque processus léger. 
  c. Qu’elle doit être la valeur affichée à la fin de l’exécution du code ? 
  d. Expliquez les résultats obtenus lors de l’exécution de java Cpt (faire plusieurs exécutions).
</pre>
