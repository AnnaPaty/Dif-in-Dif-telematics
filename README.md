# Dif-in-Dif-telematics
Models Dif-in-dif en dades telemàtiques d’accidents d’automòbil

El projecte analitza com canvia el comportament d’una persona després d’haver tingut un accident de trànsit mitjançant la tècnica estadística Dif-in-Dif (Difference-in-Difference). Concretament es comparen els canvis abans i després de l’accident en dos grups: el grup “tractament” (afectats per l’accident) i el grup “control”
(sense accidents).

S’ha utilitzat diversos tipus de models estadístics, inclosos models de dades de panell, models semiparamètrics i models no paramètrics. Així mateix, s’ha analitzat en primer lloc tots els accidents de forma conjunta, en segon els accidents causats per l’assegurat i finalment els accidents causats per tercers. Els
diferents models s’han aplicat amb diverses covariables.

S’ha usat R com a llenguatge de programació per a realitzar l’anàlisi estadística. Les dades utilitzades han estat recopilades per empreses “insurtech”

Organització del projecte
------------

    ├── README.md                               <- El README de primer nivell per als desenvolupadors del projecte.
    │ 
    ├── TFM_tots (.Rmd i .pdf)                  <- Anàlisi de tots els accidents de forma conjunta (tractant les variables que mesuren el pas del temps binàriament)
    │   
    ├── TFM_tots_nocat (.Rmd i .pdf)            <- Anàlisi de tots els accidents de forma conjunta (tractant les variables que mesuren el pas del temps 
    │                                              numèricament)
    ├── TFM_culpa_nocat (.Rmd i .pdf)           <- Anàlisi dels accidents causats per l'assegurat (tractant les variables que mesuren el pas del temps numèricament)
    │                                              numèricament)
    └── TFM_tercers_nocat (.Rmd i .pdf)         <- Anàlisi dels accidents causats per terceres parts (tractant les variables que mesuren el pas del temps                                                              numèricament)

    Els fitxers .Rmd contenen el codi necessari i tot l'escrit per a crear els seus PDF corresponents. 
