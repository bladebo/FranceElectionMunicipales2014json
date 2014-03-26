FranceElectionMunicipales2014json
=================================

Données en json des départements, villes et Urls directement du site http://elections.interieur.gouv.fr

-Region
--Liste des premières lettres des villes existantes dans la région
---Liste des Villes
                


Exemple Format decodé en php.
```
["url"]=>
    string(56) "http://elections.interieur.gouv.fr/MN2014/001/index.html"
    ["libelle"]=>
    string(8) "01 - AIN"
    ["ListeVilles"]=>
    array(19) {
      [1]=>
      array(3) {
        ["url"]=>
        string(55) "http://elections.interieur.gouv.fr/MN2014/001/001A.html"
        ["libelle"]=>
        string(1) "A"
        ["villes"]=>
          array(19) {
            [1]=>
            array(3) {
              ["nom"]=>
              string(24) "Ambérieu-En-Bugey"
              ["Listes"]=>
              array(2) {
                ["libelle"]=>
                string(6) "Listes"
                ["url"]=>
                string(59) "http://elections.interieur.gouv.fr/MN2014/001/C1001004.html"
              }
              ["resultat"]=>
              array(2) {
                ["libelle"]=>
                string(38) "Résultats reçus 1er tour"
                ["url"]=>
                string(57) "http://elections.interieur.gouv.fr/MN2014/001/001004.html"
              }
            }
          }
        }
      }
```     
