```turtle
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix wikipedia: <https://en.wikipedia.org/wiki/> .
@prefix wikidata: <http://www.wikidata.org/entity/> .
@prefix vcard: <http://www.w3.org/2006/vcard/ns#> .

<#me>
    a foaf:Person ;
    foaf:name "Albin Larsson"@sv ;
    foaf:homepage <https://byabbe.se/> ;
    foaf:based_near wikipedia:Stockholm ;
    vcard:language: "sv", "en", "nb" ;
    foaf:weblog <https://byabbe.se/blog/> ;
    foaf:account <https://codeberg.org/abbe98> ,
                 <https://gitlab.gnome.org/Abbe98> ;
    owl:sameAs wikidata:Q107864180 .
```

See my [Codeberg account](https://codeberg.org/abbe98) 🏔 for new projects. 
