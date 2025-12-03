## Introduction

Lorsque j'ai voulu faire un algorithme de recommandation, je suis tombé sur Word2Vec et plus particulièrement la version SGNS (Skip-GRAM negativ sampling) et au lieu d'utiliser simplement un modèle tout fait (gensim) que je comprenais à peine, je me suis dis pourquoi pas tout recoder from scratch pour vraiment comprendre ce qu'il y a derrière.
Le challenge était d'autant plus intéréssant que je n'ai trouvé aucune implémentation from scratch du SGNS (seulement un code utilisant pytorch ce qui facilite pas mal de choses...).
Je me suis donc basé majoritairement sur le papier du SGNS, des ébauches sur internet et de ma réfléxion.


