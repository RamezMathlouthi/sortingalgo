dans cet algorithme,on a fait une procédure SWAP qui dépend du arr[i] et arr[min_index],après ça on a déclaré une autre variable de type entier qu'on va l'appleler "tmp".
Ensuite,la variable "tmp" va prendre la valeur de arr[i],après la variable arr[i] va prendre la valeur de min_index et pour finir la variable arr[min_index] va prendre la valeur du variable tmp.

concernant la deuxième procédure "select_sort",dont l'entrée ou (input) est un tableau de type entier.après on va utiliser un boucle "for" où on ecrit:
 pour chaque Index(i) dans le tableau sauf le dernier faire chercher le minimum des élements de i jusquà la fin du tableau et après la variable min_index prend la valeur du petit element de[i].
 Après avoir vérifié le premier resultat,on fait un autre boucle "for" pour vérifier l'index suivant càd(i+1=j) jusqu'à la fin du tableau et on veriifie la condition si  la valeur de "min_index" > à la valeur de l'index de "j" alors la variable de min_index prend la valeur de j 