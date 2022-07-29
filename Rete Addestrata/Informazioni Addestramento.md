# **INFORMAZIONI**

## *Dataset utilizzato*:
### [AdultContentsv6](https://app.roboflow.com/ds/y7SboyIfdH?key=z5382FXYZl)

Training set    : 4K    immagini

Validation set  : 500   immagini

## *Label usata*:
 ### *porn* - ano, seno, natiche, masturbazione (maschile e femminile), sesso orale (maschile e femminile), atto della penetrazione con focus sui genitali, genitali maschili, genitali femminili

 ## *Augmentation Steps*:
 - ### *flip*       - orizzontale
 - ### *rotation*   - tra +20° e -20°
 - ### *shear*      - +-20° orizzontale, +-20° verticale
 - ### *exposure*   - tra +25% e -25%
 - ### *blur*       - 1px

#

 ## *Cartelle caricate*:
    v2_150m6_wm6: modello yolov5m6, 	peso    yolov5m6.pt,	epoche 150 (addestramento fermatosi autonomamente alla 120esima epoca perchè non riscontrava miglioramenti nella mAP)