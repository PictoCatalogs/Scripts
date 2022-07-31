# Scripts used to extract data from exhibition catalogues and to produce visualisations
___

## Repository

`extractionCatalogs`: contains the Python program created by Juliette Janès and updated by Esteban Sánchez Oeconomo, the ALTO files (`data_alto`) from the catalogues to be processed, the ODD to use in TEI files (`ODD_Artlas.rng`) and the XSLT stylesheet to transform the TEI file into CSV (`XMLtoCSV.xsl`).
`visualisation`: contains the Python notebooks used to make maps (`cartographie_folium_city.ipynb` and `cartographie_folium_street.ipynb`) and word clouds (`wordcloud.ipynb`), and the TSV files to be processed.

## How to run the extractionCatalogs program

The program is still being modified, for the moment the command to use to run it is the following:

`python3 run.py path_input path_output title_of_output type_of_catalogue_entry -v`

For example : 
`python3 run.py data_alto/PCP_1894/ data_alto/ PCP_1894_TEI.xml Double -v`

## Credits

This repository is developed by Frédérine Pradier, University of Geneva. This work has benefited greatly from the datasets and workflows provided by Juliette Janès, Esteban Sánchez Oeconomo and Caroline Corbières for the [Artl@s project](https://artlas.huma-num.fr).

Esteban Sánchez Oeconomo, Juliette Janès, Simon Gabay, Béatrice Joyeux-Prunel, *extractionCatalogs: Python data extractor for exhibition catalogs*, 2022, Paris: ENS Paris, IMAGO / Geneva: Université de Genève, [https://github.com/IMAGO-Catalogues-Jjanes/extractionCatalogs](https://github.com/IMAGO-Catalogues-Jjanes/extractionCatalogs) 

Juliette Janès, *Du catalogue papier au numérique : Une chaîne de traitement ouverte pour l’extraction d’informations issues de documents structurés*, mémoire de master « Technologies numériques appliquées à l’histoire »,dir. Thibault Clérice et Béatrice Joyeux-Prunel, École nationale des chartes, 2021, [https://github.com/Juliettejns/Memoire_TNAH](https://github.com/Juliettejns/Memoire_TNAH).

Caroline Corbières, Simon Gabay and Béatrice Joyeux-Prunel, *Worklow to encode exhibition catalogues*, 2020, [https://github.com/carolinecorbieres/ArtlasCatalogues](https://github.com/carolinecorbieres/ArtlasCatalogues).

## Thanks to

This project greatly benefited from the active help of Simon Gabay, Béatrice Joyeux-Prunel and Esteban Sánchez Oeconomo. 

## Licence

[CC-BY](https://creativecommons.org/licenses/by/2.0/fr/)


## Cite this repository

Frédérine Pradier, Simon Gabay, Béatrice Joyeux-Prunel, *PictoCatalogs : Scripts to extract data from exhibition catalogues and to produce visualisations*, 2022, Geneva: University of Geneva

## Contacts

frederine.pradier@etu-unige.ch

