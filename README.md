# Upravljanje znanjem - završni rad

Ak. god. 2021/2022
Nositelji:

- izv. prof. dr. sc. Ana Meštrović  
- dr. sc. Slobodan Beliga  
  
Autor: 
- Andrea Hrelja

## Zadatak

Završni rad iz kolegija Upravljanje znanjem zahtjeva analizu mreže koja je zadana u obliku *edge* i *node* liste. Lista bridova sadrži podatke o početnoj i krajnjoj točki transportne linije/rute te pripadnu težinu (*weight*) koja odgovara broju odrađenih vožnji između pojedina dva odredišta (*ship ports*). Nadalje, lista čvorova sadrži pripadne zemljopisne koordinate za brodske luke zapisane u obliku decimalnih stupnjeva (*decimal degrees*) za latitude i longitude.  

Za interpretaciju rezultata važno je znati i razumjeti na što se dataset odnosi i koje podatke opisuje.
Podatke je potrebno proučiti s ciljem razumijevanja što su čvorovi, veze i težine ako postoje.

## Sažetak

U svrhu analize zadane mreže, svakom je čvoru dodan atribut *country* koji dodatno opisuje svaki čvor. Nakon toga, graf je vizualiziran zbog jednostavnije interpretacije rezultata. Već je u ovoj točki vidljivo da unutar mreže postoji više zajednica. Zatim je svakom čvoru dodijeljena pripadajuća zajednica koristeći Gavin-Newman-ove i Louvaineove metode. Zatim su kreirana problemska pitanja koja će se rješavati i analizirati.  

Dodatno, svakoj je državi i zajednici dodijeljena nasumična boja koja služi za jasniji prikaz atributa čvorova.  

## Zaključak

Za provedenu analizu korištene su razne metode za vizualizaciju koje su uvelike pomogle pri razumijevanju promatrane mreže. Provedena je analiza kroz tri razine, a lokalna je razina proširena atributima koji dodatno opisuju čvorove. Svaki je korak u analizi otvorio nova pitanja, a glavna saznanja iz ove analize su:

- veza Velike Britanije i Francuske najsnažija je veza od sviju ostalih veza  
- Baltičke zemlje koriste morski prijevoz u puno većoj količini od ostalih zemalja  
- promet koji luka u Rimu u Italiji vodi s Baltičkim zemljama je toliko velik da Rim pripada zajednici Baltičkih zemalja  
- Mediteransko područje sadrži mnoge male zajednice brodskog prijevoza  

Mreže i grafovi pružaju dodatnu, širu perspektivu nad značenjem podataka u odnosu na tablične podatke. Uz informacije o svakom promatranom entitetu (čvoru), dostupne su i informacije o njegovim odnosima s preostalim entitetima (čvorovima). Izrađenu je analizu moguće proširiti s raznim pitanjima i dodatnim mjerama grafa. U svrhu pregleda mrežnih struktura i izrade završnog rada, iznesena su prethodno ispisana saznanja.

Analiza: [TransportRoutesAnalysis.ipynb](./TransportRoutesAnalysis.ipynb)