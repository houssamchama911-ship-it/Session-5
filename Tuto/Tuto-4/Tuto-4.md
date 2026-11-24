 VILLE
-------------
id_ville (PK)
nom_ville

 AUTEUR
--------------
id_auteur (PK)
nom_auteur
prenom_auteur
email_auteur
id_ville (FK)

 CATEGORIE
-----------------
id_categorie (PK)
nom_categorie

 TAG
-----------
id_tag (PK)
nom_tag

 ARTICLE
---------------
id_article (PK)
titre_article
contenu_article
date_publication
statut_article
image_article
id_auteur (FK)
id_categorie (FK)

 ARTICLE_TAG
-------------------
id_article (PK, FK)
id_tag (PK, FK)