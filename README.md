


### Author
Habib BALIT


### Link
result link : https://balithabib.github.io/dataviz/
source code : https://balithabib.github.io/dataviz/



### Query
    SELECT ?informaticien ?informaticienLabel ?date_de_naissance ?sexe_ou_genre ?sexe_ou_genreLabel ?pays_de_citoyennet_ ?pays_de_citoyennet_Label ?image WHERE {
    SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],en". }
    ?informaticien wdt:P106 wd:Q82594.
    ?informaticien wdt:P569 ?date_de_naissance.
    ?informaticien wdt:P21 ?sexe_ou_genre.
    ?informaticien wdt:P27 ?pays_de_citoyennet_.
    ?informaticien wdt:P18 ?image.
    }
    LIMIT 100
