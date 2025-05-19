

# Guide til Prusa-filamentprintere

![3DPrintImage](Billeder/printer.jpg)

## Indhold

* [Før du printer](#før-du-printer)
* [Hvis du ikke vil lave din egen fil](#hvis-du-ikke-vil-lave-din-egen-fil)
* [Klargøring af fil i PrusaSlicer](#klargøring-af-fil-i-prusaslicer)
* [Skift af filament](#skift-af-filament)

  * [Indsæt filament](#indsæt-filament)
  * [Fjern filament](#fjern-filament)
* [Brug af filter til usunde materialer](#brug-af-filter-til-usunde-materialer)
* [Tips og tricks til bedre print](#tips-og-tricks-til-bedre-print)
* [Materialer](#materialer)

  * [Fjern dit færdige print](#fjern-dit-færdige-print)
* [Design af egne modeller](#design-af-egne-modeller)

  * [Valg af software](#valg-af-software)

---

## Før du printer

Før du bruger lab'ets Prusa Mini+, MK4 eller MK4S, skal du have følgende på plads:

 1. At du har fået undervisning i 3D printerne, eller har snakket med en ansat i lab'et
 2. At du har en 3D-model af filtypen STL eller OBJ, som du gerne vil printe.
 3. En computer med [*PrusaSlicer*](https://www.prusa3d.com/page/prusaslicer_424/) installeret.
 4. Et USB-stik som du kan gemme din fil på (disse sidder allerede i printerne).
5. At du har betalt for det materiale du bruger på vores [*webshop*](http://ddlab.au.dk/webshop).

---

## Hvis du ikke vil lave din egen fil

Det kan være vanskeligt og tidskrævende at designe sin egen fil. Heldigvis findes [*Thingiverse*](https://www.thingiverse.com/), hvor man kan downloade 3D-modeller gratis.

I dette eksempel tages der udgangspunkt i en [*Skak Bonde*](https://www.thingiverse.com/thing:4901226/files) fra sættet *Hexagon Chess Set*.

---

## Klargøring af fil i PrusaSlicer

Næste trin er at importere 3D-modelen til PrusaSlicer. Dette kan gøres ved at trykke på `File ➝ Import ➝ Import STL/OBJ/...`, hvorefter du vælger din fil.

Du kan herefter ændre på størrelsen af printet samt dens orientering ved hjælp af værktøjerne i bjælken til venstre. 
> *Hvis du ikke kan se din fil, kan det ske, at du skal skifte til *"3D editor view"* ved at trykke på kassen i nederste venstre hjørne.*

![](Billeder/01.png)

Hvis dit print vender forkert kan du enten bruge `Rotate` eller `Place on Face` funktionenerne i venstre bjælke til at vende det korrekt. 

Du kan også roterer din model manuelt ved at skrive værdierne ind i tabellen til højre.

> *Place on Face funktionen er især nyttig, hvis man gerne vil at printet skal ligge på en bestemt side.*

![](Billeder/03.png)
![](Billeder/02.png)

Hvis du vil ændre modellens størrelse, kan du bruge ***"Scale"*** værtøjet til venstre eller manuelt skrive værdierne ind i tabellen til højre. 

![](Billeder/07.png)

---

## Vælg de rigtige indstillinger
Når du har klaret ovenstående, skal du herefter vælge hvilke instillinger, du gerne vil printe med. *Du skal her vælge følgende:*

**1. Hvilken printer du ønsker at bruge (Mini+, MK4 eller MK4S)**

Hvis du ikke kan finde den ønskede printer i drop-down menuen, kan du tilføje en ny printer ved at klikke på `Add/Remove printers` og køre PrusaSlicerens Configuration Wizard. Her skan du under `Prusa Research` vælge hvilke printere du ønsker at tilføje. 

  ![](Billeder/10.png)

  >*OBS: Denne guide tager  udgangspunkt i Prusa printeren *"Original Prusa i3 MK3S & MK3S +"*, som ikke længere findes i lab'et.* 

**2. Filamenttypen (PLA, PETG, ASA, FLEX TPU)**

Derefter skal du vælge hvilket filament du gerne vil printe med, så hvis du for eksempel gerne vil printe i PLA bør du vælge `Prusament PLA` eller `Generic PLA` afhængig af fabrikanten. Det er dog en god idé at undersøge, hvilke filamenttyper lab'et har på forhånd inden du vælger dette. 



  >*PLA er ofte et godt sted at starte, men hvis du ønsker at printe med et andet materiale kan du finde yderligere information om de forskellige filamenttyper længere nede i tips og tricks sektionen.* 

Det kan også være en god idé at klikke på tandhjulet ud for filament-indstillingen og sammenligne PrusaSlicers default værdier med de de anbefaligner der står på filamentrullen. Hold specielt øje med at diameteren på filament tråden samt de forskellige temperature er korrekte i overenstemmelse med de anbefalinger der står på rullen.

![](Billeder/06.jpg) ![](Billeder/05.png)


**3. Print settings (tykkelsen på filamenttråden målt i mm).**

Her skal du vælge hvor tyk en filamenttråd du vil printe med (en god default er at bruge 0.20mm QUALITY). Du kan med fordel slice din fil med forskellige print settings for at se, hvor lang tid din model tager at printe samt hvor meget filament der bliver brugt ved de forskellige presets. 

For se hvor lang tid dit print tager,  samt hvor mange gram filament du bruger, skal du klikke på `slice now` i bunden af højre bjælke.

>*Hvis du  vælger *"0.10mm DETAIL"* tager dette print af skakbonden 1 time og 59 min, og bruger 6.62 gram filament, hvorimod *"0.20mm SPEED"* kun tager 1 time og bruger 6.34 gram filament.* 
---

## Andre indstillinger

Udover disse kan du i øverste bjælke justere indstillingerne for printpladen, print-indstillinger, filament, og selve printeren. Herunder finder du instillinger såsom ``temperatur,  infill, support-materiale, ventilation m.m``, som kan være nyttigt at ændre afhængig af dit print. 

>*Dette kan lyde overvældende, men heldigvis kan man komme virkeligt langt med PrusaSlicerens default instillinger*

Du undrer dig måske over, hvorfor det samme print kan bruge mere eller mindre filament, alt efter hvor hurtigt det bliver printet. Det skyldes blandt andet, at fyldet inde i printet, bedre kendt som ``infill``, ændrer sig afhængigt af den valgte preset. Du kan ændre mængden af infill over i højre bjælke, som vist på billedet

![](Billeder/infill.png)

![](Billeder/09.png)

  >*Hvis du gerne vil se, hvor solid din model bliver baseret på den valgte infill, kan du trække i baren til højre for at se et tværsnitsnit af dit print.*

Når din model har de rigtige dimensioner og er placeret korrekt på printpladen (*med den største flade nedad for et stabilt print*) kan du herefter slice din fil ved at klikke på `slice now` i bunden af højre bjælke.

> *Slice transformerer modellen til binære kode, som kan læses af printeren, hvorefter den ved, hvordan printet skal konstrueres.* 

---

Når disse 3 indstillinger er sat rigtigt, er man klar til at slice sin fil en sidste gang og eksportere den som g-code til et SD-kort (eller USB stik hvis man printer på en MINI+). Dette gøres ved sætte SD kort eller USB-stick (alt efter hvilken pritner man bruger) i sin computer og trykke på "export G-code knappen" der hvor "slice" knappen var før. Sørg for at den fil der bliver genereret hedder noget i kan genkende, og overfør den til SD-kortet eller USB-sticken.


Vi er nu næsten klar til at printe, men før man kan sætte printeren igang skal man lige sikre sig at alt er som det skal være:

1. At det filament der er i printeren svarer til det filament man justerede sine indstillinger ud fra i sliceren. (hvis ikke [skal man skifte filament](#hvis-man-skal-skifte-filament))
2. At den stålplade der sidder på printeren er den rigtige for det materiale man printer med. Man bruger den glatte og grønlige "Smooth" til PLA og den lidt texturerede "Satin" til PETG og ASA f.eks. 
  1. Hvis man skifter plade skal man vælge den tilsvarende "Sheet profile" på MK3S+ printerens skærm. På MINI+ printerne anbefales det ikke at skifte plade uden hjælp fra en ansat da det kræver at man indstiller printerens Z-offset manuelt og man kan beskadige printeren hvis man gør det forkert.
3. At pladen er ren. Put en lille smule isopropyl-alkohol (IPA) på noget køkkenrulle agtigt papir (der er en stor rulle ovre ved resin-printeren) og tør pladen af med det.

Man kan nu sætte sit SD-kort (eller USB-stick) med ens fil ind i printeren og begynde sit print. Menuerne navigeres med det sorte hjul der kan roteres for at bevæge sig i menuen og trykkes på for at vælge menupunkter. Hvis ikke ens fil dukker op når man sætter kortet i printeren kan man klikke på hjulet for at gå til hovedmenuen og her gå til "print from SD" som bringer en liste over alle filer på SD-kortet frem. Så vælger man den fil man gerne vil printe. Printeren går så igang med at varme op, kalibrere og printe ens fil. MINI+ pritnernes menuer er lidt anderledes men det er samme overordnede funktionalitet.

## Før du starter print

Tjek følgende:

1. **Filamenttype**: Er det samme, som du valgte i sliceren?
2. **Printplade**:

   * *Smooth (glat, grønlig)* til PLA
   * *Satin (let tekstureret)* til PETG/ASA
   * På MK3S+ skal du vælge korrekt *Sheet profile*
   * På Mini+ bør du få hjælp til at skifte plade (Z-offset skal justeres manuelt)
3. **Rengøring**:

   * Brug isopropyl-alkohol (IPA) og køkkenrulle til at rengøre printpladen.

Sæt herefter dit USB-stik eller SD-kort i printeren og start printet via menuen.

---

## Skift af filament

### Indsæt filament

1. Hvis der allerede sidder filament i, [fjern det først](#fjern-filament).

2. Tjek filamentets ende – klip spidsen ren, hvis den er bulet.

3. Tænd printeren og monter filamentrullen korrekt på holderen.

   ![](Billeder/11.jpg) <img src="Billeder/removeHolder.gif" width="180" height="300"/>

4. Før filamentet forsigtigt gennem indgangen til printhovedet.

   ![](Billeder/12.jpg)

5. Følg instruktioner på skærmen (vælg korrekt filamenttype og vent på opvarmning).

6. Når printeren griber fat i filamentet, slip – og bekræft farven.

> Hvis plastikken ikke har korrekt farve, vælg “No” og lad den extrude lidt mere.
> Hvis den ikke trækker i filamentet, skru evt. bowden-tuben af for at hjælpe det på vej.

![](Billeder/screwOf.gif)

---

### Fjern filament

1. Tænd printeren.
2. Vælg “Unload filament” i menuen.
3. Vælg den filamenttype, der sidder i printeren.
4. Vent på opvarmning → bippet lyder → træk filamentet roligt ud.

> Skru evt. bowden-tuben af for at få bedre fat. Husk at skrue den på igen bagefter.

![](Billeder/screwOf.gif) | ![](Billeder/screwOn.gif)

Sørg for, at filamentets ende ikke snor sig ind under rullen – brug de orange filament-clips.

---

## Brug af filter til usunde materialer

> *Ved print med PLA er filteret ikke nødvendigt.*

Hvis du bruger PETG, ASA, ABS eller lignende materialer, skal filteret i enclosure’et være tændt under hele printet.

---

## Tips og tricks til bedre print

*(Denne sektion kan uddybes med: temperaturjusteringer, support-materiale, brims/rafts, korrekt Z-offset osv.)*

---

## Materialer

Du kan betale for materialer via [DD Labs webshop](http://ddlab.au.dk/webshop). Se prisskiltet ved printeren for korrekte materialetyper og priser.

---

### Fjern dit færdige print

1. Vent til printpladen er kølet af.
2. Løft pladen forsigtigt af printeren.
3. Bøj pladen let – printet løsner sig.

---

## Design af egne modeller

### Valg af software

Nogle gode gratis programmer til 3D-modellering:

* [TinkerCAD](https://www.tinkercad.com/) – Let at bruge
* [Fusion 360](https://www.autodesk.com/products/fusion-360/) – Mere avanceret
* [Blender](https://www.blender.org/) – God til organiske former og figurer

