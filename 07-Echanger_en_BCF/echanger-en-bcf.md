# Introdction au pricinpe du BCF

Pour échanger en utilisant le format BCF, 4 manipulations sont nécessaires: l'export du fichier BCF depuis bimsync, puis l'export de ce fichier dans un logiciel de modélisation (Revit, ArchiCAD ou Allplan), et faire le chemin inverse une fois les modifications apportées.

# Comment exporter un BCF depuis bimsync

Cliquer sur l'onglet Sujet (1), et ouvrir la listes des sujets contenant le sujet que vous voulez exporter en format BCF (2).

![ExportBCFbimsync01](/07-Echanger_en_BCF/echanger-en-bcf-images/ExportBCFbimsync01.PNG)

Cliquer ensuite sur l'icône "..." (3), puis sur "Exporter la liste des sujets" (4). Vous pouvez également choisir l'option "Exporter les sujets filtrés" (5), en ayant choisi des filtres vous convenant au préalable.

![ExportBCFbimsync02](/07-Echanger_en_BCF/echanger-en-bcf-images/ExportBCFbimsync02.PNG)

Bimsync vous indique que l'exportation a commencé, cliquer sur "voir l'état d'avancement" (6).

![ExportBCFbimsync03](/07-Echanger_en_BCF/echanger-en-bcf-images/ExportBCFbimsync03.PNG)

Une fois l'exportation terminée, cliquer sur l'icône flèche pour télécharger (7) le fichier BFC de la liste des sujets exportés. Vous trouverez ce fichier dans votre dossier de téléchargement (8) en format BCFZIP.

![ExportBCFbimsync04](/07-Echanger_en_BCF/echanger-en-bcf-images/ExportBCFbimsync04.PNG)

# Comment importer un BCF dans bimsync

Pour importer un fichier BCFZIP dans bimsync, aller dans l'onglet sujets (1), cliquer sur l'icône "..." (2), puis sur "Importer" (3).

![ImportBCFbimsync01](/07-Echanger_en_BCF/echanger-en-bcf-images/ImportBCFbimsync01.PNG)

Dans l'interface d'import de fichiers BCF, cliquer sur "Envoyer un fichier BCF" (4), parcourez vos documents puis sélectionner le fichier à importer (5), puis cliquer sur "Ouvrir" (6). Veiller à choisir la bonne liste de sujets dans laquelle les sujets seront importés, la même qu'au départ si les fichiers BCF ont été importé initialement depuis bimsync (7).

![ImportBCFbimsync02](/07-Echanger_en_BCF/echanger-en-bcf-images/ImportBCFbimsync02.PNG)

L'importation BCF est lancée (8), dès qu'elle sera fini les nouveau sujets seront visibles dans la liste choisie lors de l'importation, et les sujets existants seront mis à jours (les nouveaux commentaires seront ajoutés automatiquement (9) )

![ImportBCFbimsync03](/07-Echanger_en_BCF/echanger-en-bcf-images/ImportBCFbimsync03.PNG)

![ImportBCFbimsync04](/07-Echanger_en_BCF/echanger-en-bcf-images/ImportBCFbimsync04.PNG)

# Principe des liens

....

# Echanges BCF dans Revit

{% include "/07-Echanger_en_BCF/echanger-en-bcf-revit.md" %}

# Echanges BCF dans ArchiCAD

{% include "/07-Echanger_en_BCF/echanger-en-bcf-archicad.md" %}