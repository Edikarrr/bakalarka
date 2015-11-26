# bakalarka
Adresar bakalarka obsahuje dva podadresare:
# bakalarka/dokument
    zde jsou:

##  _/dokument/kapitoly_ 
   v tomto podadresari jsou vsechny vnitrni kapitoly dokumentu
  * _/dokument/kapitoly/kapitoly.tex_ (rozdeleni dokumentu do kapitol)
  * _/dokument/kapitoly/*_ (text kapitol (includovany do dokumentu v kapitoly.tex ))

## bakalarka/dokument/img
    zde jsou v podadresarich obrazky pouzivane v dokumentu

## _bakalarka/prace.pdf_ 
    aktualni, prelozena verze bakalarky v pdf


## _bakalarka/bak_prace.tex_ 
    zakladni soubor .tex, preklada se v makefilu

## _bakalarka/Makefile_ 
    po stazeni repozitare je mozne vytvorit _prace.pdf_ spustenim prikazu $make
  
  
# bakalarka/model
    tento adresar slouzi k ukladani prace vytvorene v arisu apod.. jsou zde ulozene:
   * modely ve formatu pro aris
   * pdfka vyexportovana v arisu z tehto modelu
  
