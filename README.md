<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [3D printer](#3d-printer)
  - [Den nemme måde](#den-nemme-m%C3%A5de)
      - [Find fil på Thingiverse](#find-fil-p%C3%A5-thingiverse)
      - [Gør fil klar til print i Cura](#g%C3%B8r-fil-klar-til-print-i-cura)
        - [Tricks til bedre print](#tricks-til-bedre-print)
  - [Materiale](#materiale)
    - [Skift materiale:](#skift-materiale)
    - [Fjerne færdigt print:](#fjerne-f%C3%A6rdigt-print)
  - [design af egne modeller](#design-af-egne-modeller)
# 3D printer

**Når man bruger Lab'ets Ultimaker 3 så kræver det at man har føglende**:

 0. Hvis det er første gang, skal man have snakket med en ansat i Lab'et
 1. En 3D-fil med filtypen STL.
 2. En computer med [Ultimaker Cura](https://ultimaker.com/en/products/ultimaker-cura-software) installeret.
 3. USB-pen.
 4. Et [link til DD Labs webshop](http://auws.au.dk/forms/frm1Arrangement.aspx?value=636461676799220799&id=17148) til betaling af materiale.

## Den nemme måde

#### Find fil på Thingiverse
Det kan være vanskeligt og tidkrævende at designe sin egen fil. Heldigvis findes [Thingiverse](https://www.thingiverse.com/), som er en delingside for makere, hvor downloade gratis 3D-modeller af alt fra skakbrikker til skelettet til droner.

I dette eksempel vil jeg tage udgangspunkt i en [dørstopper](https://www.thingiverse.com/thing:2642527) (fordi lab'et mangler en).

#### Gør fil klar til print i Cura
Næste trin er at åbne sin 3D-fil i Cura Dette kan gøres ved at trykke på 'File -> open File(s)' og så vælge sin fil.

Filen er importeret og man kan nu ændre på størrelsen på printet og orientering ved hjælp af værktøjerne i venstre side.  
![](https://github.com/DDlabAU/3DPrinter/blob/master/Billeder/01.png)
Som det kan ses på billedet er filen for lille til at virke på som en dørstopper så derfor skal den skaleres op.  
![](https://github.com/DDlabAU/3DPrinter/blob/master/Billeder/02.png)

Når filen har de rigtige dimensioner skal den eksporteres til gcode (som printeren kan læse), ved at trykke på "Save to File" i højre bund af programmet. Ved siden af knappen kan man se hvor langt tid printet tager samt printets vægt som skal bruges til betalling i DD Lab's webshop.  
![](https://github.com/DDlabAU/3DPrinter/blob/master/Billeder/03.png)


![](https://github.com/DDlabAU/3DPrinter/blob/master/Billeder/07.jpg)

![](https://github.com/DDlabAU/3DPrinter/blob/master/Billeder/08.jpg)

##### Tricks til bedre print
**Materiale & extruder**:  
I højre top kan man vælge hvilken "extruder" printeren skal bruge samt hvilket materiale der er tale om. Det er muligt at vælge begge extruders i samme print, men det tager VÆSENTLIG længere tid samt der er større sandsynlighed for fejl-print.  
![](https://github.com/DDlabAU/3DPrinter/blob/master/Billeder/04.png)

**Print Setup**:  
Under indstillinger for for materialer og extruders finder man print setup. Den indstilling der hedder 'recommended' er den der almindeligvis skal bruges, men skal man have lavet noget mere avanceret, så tag fat i en ansat fra lab'et.  
Infill beskriver hvor meget printeren fylder ind i modellen. Hvis man skal printe noget der kan holde til noget, så kan man med fordel sætte infill procenten op. Eksemplet med dørstopperen sætter forsøger jeg med 50% fyld. Man skal være opmærksom på at dette gøre printetiden længere samt printet dyrere da der bruges mere materiale.  
![](https://github.com/DDlabAU/3DPrinter/blob/master/Billeder/05.png)

**Support**:  
Support skal sættes til hvis der frithængende elementer på ens model, da printeren ikke kan lægge plastik ovenpå luft. Support kan ses som et stillads som printeren bruger til at
Jo mere support der skal bruges jo større er sandsynligheden for fejl-print, men der bruges også væsentlig mere materiale. Derfor anbefales det at man roterer sin model så der skal bruges så lidt support som muligt.  
![](https://github.com/DDlabAU/3DPrinter/blob/master/Billeder/06.png)

**Build plate**:  
Det kan tit være en fordel at printe sin model på en bund, så der er et lag mellem printerens byggeplade og ens 3D-model. Hvis man vil have det skal man tjekke 'Build Plate' kassen af.

**Tape på varmepladen**:
Flere guides på nettet anbefaler man putter lim på printerens byggeplade. **Det anbefaler vi ikke!**. Det kan derimod være en fordel at putte den blå tape på byggepladen der kan findes i en kasse under vinylcutteren (der står ved siden af 3D printeren).

## Materiale
**Hvilket materiale bliver der brugt**:  
Vi har flere forskellige typer af materiale-ruller men fællesnævneren er at det hele er PLA, hvilket er en mere miljøvenlig plastik, da den er bionedbrydelig. Dermed ikke sagt at man bare skal printe løs og smide det i naturen, for det kræver særlige forhold at nedbrude materialet. Printer man noget, må det gerne være for sjov, det skal også bare have sted i verden (eksempelvis awesome digital design prototyper).

### Skift materiale:
Der sidder en NFC-chip (Near Field Communication chip) i flere af lab'ets ruller med 3D-printer plast. Fordelen ved at bruge dem  

### Fjerne færdigt print:

## design af egne modeller


**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*
