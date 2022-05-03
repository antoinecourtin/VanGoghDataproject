### Questions 

* Why for https://preprod.vangoghworldwide.org/artwork/F653, the date of the exhibition does not appear online while the info is in the json?
```json
 "timespan": [
        {
          "type": "TimeSpan",
          "end_of_the_begin": "1914-01-01T00:00:00Z",
          "begin_of_the_end": "1914-12-31T23:59:59Z"
        }
      ]
```

* If we filter on the works of orsay, why only "Saint-remy" appears in the filter of "periods" when for example for F445 

```json
  "took_place_at": [
      {
        "id": "http://vocab.getty.edu/tgn/7008775",
        "type": "Place",
        "_label": "Arles" 
      }
    ],
```

* Why doesn't the date appear as for https://preprod.vangoghworldwide.org/artwork/F134 when the info is in the json 

```json
    "timespan": [
      {
        "type": "TimeSpan",
        "end_of_the_end": "1884-12-31T00:00:00",
        "begin_of_the_begin": "1884-01-01T00:00:00"
          }
        ]
```

* Why doesn't the technique appear as for https://preprod.vangoghworldwide.org/artwork/F134 when the info is in the json 

```json
  "technique": [
      {
        "id": "http://vocab.getty.edu/aat/300054216",
        "type": "Type",
        "_label": "painting"
      }
    ],
```
same question for "Artist", "exhibitons"
