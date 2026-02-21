
# Guide til Bambu Lab X1 Carbon-filamentprinter

<img src="https://sw16865.sfstatic.io/upload_dir/shop/Bambu-Lab-X1--Carbon-Combo-X1CC-29184_2.png" alt="3DPrintImage" width="200"/>

## Indhold

* [Før du printer](#før-du-printer)
* [Hvis du ikke vil lave din egen fil](#hvis-du-ikke-vil-lave-din-egen-fil)
* [Klargøring af fil i Bambu Studio](#klargøring-af-fil-i-bambu-studio)
* [Før du starter print](#før-du-starter-dit-print)
    * [Indsæt filament](#indsæt-filament)
* [Efter dit print er færdigt](#efter-dit-print-er-færdigt)
    * [Fjern filament](#fjern-filament)
    * [Fjern dit færdige print](#fjern-dit-færdige-print)
* [Brug af filter til usunde materialer](#brug-af-filter-til-usunde-materialer)
* [Tips og tricks til bedre print](#tips-og-tricks-til-bedre-print)
* [Materialer](#materialer)
* [Build Plates](#build-plates)
* [Design af egne modeller](#design-af-egne-modeller)
    * [Valg af software](#valg-af-software)

---

## Før du printer


Før du bruger lab'ets Bambu Lab X1 Carbon printer, skal du have følgende på plads:

1. At du har fået undervisning i Bambu Lab X1 Carbon, eller har snakket med en ansat i lab'et.
2. At du har en 3D-model af filtypen STL eller 3MF, som du gerne vil printe.
3. En computer med [*Bambu Studio*](https://bambulab.com/software/bambu-studio) installeret.
4. Et microSD-kort eller adgang til Bambu Cloud (printeren kan modtage filer trådløst).
5. At du har betalt for det materiale du bruger på vores [*webshop*](http://ddlab.au.dk/webshop).

---

## Hvis du ikke vil lave din egen fil

Der findes 3D-model-databaser med millioner af gratis 3D-modeller, som andre brugere har lavet. Måske kan du finde det print du overvejede at lave, eller du kan finde modeller som du kan bygge videre på!

[*Printables*](https://www.printables.com/)

[*Thingiverse*](https://www.thingiverse.com/)

[*MakerWorld*](https://makerworld.com/) – Bambu Labs egen modelplatform.

---

## Klargøring af fil i Bambu Studio

Importér din 3D-model til Bambu Studio ved at trykke på `File ➝ Import ➝ Import STL/3MF/...`, og vælg din fil.

Du kan ændre størrelse og orientering af modellen med værktøjerne til venstre. 
> *Hvis du ikke kan se din fil, kan det være nødvendigt at skifte til "3D editor view" nederst til venstre.*

![](Billeder/01.png)

Brug `Rotate` eller `Place on Face` for at vende modellen korrekt. Du kan også rotere manuelt i tabellen til højre.

> *"Place on Face" er nyttig, hvis du vil have printet til at ligge på en bestemt side.*

![](Billeder/03.png)
![](Billeder/02.png)

Ændr størrelsen med ***"Scale"*** værktøjet til venstre eller skriv værdierne ind manuelt.

![](Billeder/07.png)

---

## Vælg de rigtige indstillinger

Når modellen er klar, skal du vælge indstillinger for printet:


**1. Vælg printermodel (X1 Carbon)**

Hvis X1 Carbon ikke vises, kan du tilføje den via `Add/Remove printers` i Bambu Studio.

![](Billeder/10.png)

**2. Filamenttype (PLA, PETG, ABS, TPU, osv.)**

Vælg det filament du vil bruge, fx `Bambu PLA Basic` eller `Generic PLA`. Tjek hvilke filamenttyper lab'et har på lager.

> *PLA er et godt sted at starte. Se tips og tricks for info om andre filamenttyper.*

Sammenlign Bambu Studios filamentindstillinger med anbefalingerne på filamentrullen, især diameter og temperatur.

![](Billeder/06.jpg) ![](Billeder/05.png)


**2b. Multifilament-print**

Bambu Lab X1 Carbon understøtter multifilament-print via AMS (Automatic Material System). Det betyder, at du kan printe med flere farver eller materialer i samme print.

1. Indsæt op til 4 forskellige filamentruller i AMS. Se hvordan længere nede
2. Vælg multifilament-funktion i Bambu Studio, og tildel farver/materialer til de ønskede dele af modellen.
3. Tjek at alle filamenttyper er kompatible og korrekt indsat.
4. Slice modellen – Bambu Studio genererer automatisk farveskift og materialeskift.

> *Multifilament-print kræver ekstra tid til skift mellem materialer/farver. Tjek printtid og filamentforbrug før du starter.*


**3. Print settings (lagtykkelse i mm)**

Vælg lagtykkelse, fx 0.20mm for god kvalitet. Slice din fil for at se printtid og filamentforbrug.

> *Forskellige lagtykkelser påvirker både tid og filamentforbrug.*

---

## Andre indstillinger

Du kan justere printplade, printindstillinger, filament og printer i topmenuen. Her finder du indstillinger som temperatur, infill, support, ventilation m.m.

> *Bambu Studios standardindstillinger fungerer fint til de fleste prints.*

Infill-mængden kan ændres i højre bjælke.

![](Billeder/infill.png)
![](Billeder/09.png)

> *Træk i baren til højre for at se et tværsnit af dit print baseret på infill.*

Når modellen har de rigtige dimensioner og er placeret korrekt (største flade nedad), slice filen og eksporter som G-code til microSD-kort eller send direkte til printeren via Bambu Cloud.

Navngiv filen med dit ***AU-ID*** + ***gram vægt***.

---

## Før du starter print

### Indsæt filament

1. Find det ønskede filament under 3D-printerne.
2. Pak filamentet ud og klip spidsen på skrå.
3. Tænd printeren, vælg `Filament` i menuen og vælg filamenttype.
4. Placer filamentrullen korrekt i AMS (Automatic Material System) eller direkte på printeren.

![](https://wiki.bambulab.com/ams/ams-load-unload-failure/10-%E6%AD%A3%E5%B8%B8%E7%9A%84%E9%A2%84%E4%B8%8A%E6%96%99%E8%BF%87%E7%A8%8B%E5%8A%A8%E5%9B%BE.gif)

5. tryk den grå tab frem og Før tråden ind i AMS indgang til du møder modstand.
![](https://wiki.bambulab.com/x1/manual/ams-setup-filament-loading/push_ams_feeder.jpeg)

> *Skub filamentet ind i AMS-feederen, indtil du mærker modstand.*

6. Følg instruktionerne på printerens skærm for at loade filamentet.

7. Bekræft at filamentet har den rigtige farve, når det kommer ud af hotenden.

Du er nu klar til at printe. Dobbelttjek:

1. At filamentet i printeren matcher det valgte i Bambu Studio.
2. At printpladen passer til filamenttypen (fx tekstureret plade til TPU).
3. At pladen er ren – brug isopropylalkohol (IPA) på papir.

Start printet via printerens skærm eller Bambu Cloud. Hvis filen ikke vises, brug menuen til at finde den på microSD-kortet eller i skyen.

---

## Efter dit print er færdigt

### Fjern filament

1. Tænd printeren.
2. Vælg `Filament` og `Unload filament` i menuen.
3. Vælg filamenttype.
4. Vent til printeren er varm, og træk filamentet ud.
5. Læg filamentet tilbage i den rigtige kasse.

---

### Fjern dit færdige print

1. Vent til printpladen er kølet af.
2. Løft pladen forsigtigt af printeren.
3. Bøj pladen let, så printet løsner sig.

---

## Brug af filter til usunde materialer

Ved brug af PETG, ABS, ASA eller lignende skal filteret i enclosure’et være tændt under hele printet.

> *Ved print med PLA er filteret ikke nødvendigt.*

---

## Materialer

Det koster 25 kr per 100g at 3D-printe. Betal via [DD Labs webshop](http://ddlab.au.dk/webshop) – indtast antal gram og betal 0.25 kr per gram.

---
## Build Plates

Brug disse plader kun i bemandingstiden, da det kræver at man har erfaring og avanceret kendskab til Bambu Lab printeren. 
Vi har 4 3D effect build plates fra Bambu - **Kun kompatible med vores Bambu X1 Carbon**. 
3D-effekten slides gradvist ved brug. For at forlænge levetiden **bør emnerne placeres forskellige steder** på arket.
**Undgå at påføre lim på buildpladen!**
Vælg pladetypen _Smooth PEI / High Temp Plate_ i Bambusliceren.
Overhold de anbefalede heatbed-indstillinger ved brug af Bambu 3D Effect Plate - Temperaturen omkring 60-65º fungerer bedst.
Anvend kun **PLA og TPU**.
For bedste resultat skal overfladen være helt ren
God ide at sætte hastigheden lavere - Vælg enten "silent 50%" eller sæt hastigheden for det første lag 'manuelt' ned til 10 mm/s og infill til 30 mm/s. 
Slå alle LIDAR funktioner fra (flow calibration, first layer inspection og detection of build plate position)

Mere info på vej. Vi er stadig i gang med at teste og optimere processen. 
---

## Design af egne modeller

### Valg af software

Gode gratis programmer til 3D-modellering:

* [TinkerCAD](https://www.tinkercad.com/) – Let at bruge
* [Fusion 360](https://www.autodesk.com/products/fusion-360/) – Avanceret (gratis for studerende)
* [Blender](https://www.blender.org/) – God til organiske former og figurer



<details>
<summary><strong>Carbon-fiber forstærket filament</strong> (klik for at folde ud)</summary>

## Carbon-fiber forstærket filament

Carbon-forstærket (CF) filament kan bruges på Bambu X1 Carbon (MÅ IKKE BRUGES PÅ ANDRE PRINTERE!).

#### Fordele / ulemper
- Fordele: bedre varmebestandighed og øget stivhed.  
- Ulemper: ofte lavere brudstyrke end PETG; meget abrasivt — slider på almindelige messinglyser/dyser. Se test: https://www.youtube.com/watch?v=lfztVplTBQc

#### Sikkerhed
- Må ikke bruges til spiselige emner eller dele med direkte/vedvarende hudkontakt — små kulfiberpartikler kan løsne sig og irritere huden. Se sikkerhed: https://www.youtube.com/watch?v=RLt9l6YxvHk&t=347s

#### Klargøring og indlæsning (X1 Carbon)
1. Fjern AMS-plastikrøret fra bagsiden af maskinen (afkobl forsigtigt).  
2. Monter PET-CF-rullen på metalholderen på bagsiden.  
3. Før filamentet ind gennem plastikrøret/indføringskanalen, indtil det når feederen.  
4. På printeren: vælg "Filament" → "Load/Unload" og følg skærminstruktionerne (vælg EXT-spool hvis påkrævet).  
5. I Bambu Studio: vælg den tilsvarende filamentprofil.

</details>

