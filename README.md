# ArchiTerrain V1.8

Suite du travail sur la clarté des prescriptions : connexion entre zonage et règlement écrit officiel.

V1.8 :
- récupère la partition / l'identifiant du document depuis les données GPU de zonage ;
- recherche le document approuvé correspondant via l'API officielle du Géoportail de l'Urbanisme ;
- récupère la liste des pièces écrites et identifie le règlement PDF ;
- utilise PDF.js côté navigateur pour rechercher les passages relatifs à emprise, hauteur, implantation/retraits, pleine terre, espaces verts, stationnement, accès/voirie, clôtures et coefficient de biotope ;
- affiche des extraits avec numéro de page et lien vers le PDF officiel ;
- conserve la synthèse CNIG structurée de V1.7.

Important : les extraits automatiques sont des repères de lecture et non une interprétation juridique. Le règlement opposable reste la référence.
