# 3D printer

Når man bruger Lab'ets Ultimaker 3 så kræver det at man har føglende
 1. En 3D-fil med filtypen STL.
 2. En computer med [Ultimaker Cura](https://ultimaker.com/en/products/ultimaker-cura-software) installeret.
 3. USB-pen.
 4. Et [link til DD Labs workshop](http://auws.au.dk/forms/frm1Arrangement.aspx?value=636461676799220799&id=17148) til betaling af materiale.

## Den nemme måde

#### Find fil på Thingiverse
Det kan være vanskeligt og tidkrævende at designe sin egen fil. Heldigvis findes [Thingiverse](https://www.thingiverse.com/), som er en delingside for makere, hvor downloade gratis 3D-modeller af alt fra skakbrikker til skelettet til droner.

I dette eksempel vil jeg tage udgangspunkt i en [dørstopper](https://www.thingiverse.com/thing:2642527) (fordi lab'et mangler en).

#### Gør fil klar til print i Cura
Næste trin er at åbne sin 3D-fil i Cura
* File -> open File(s)

Filen er importeret og man kan nu ændre på størrelsen på printet og orientering ved hjælp af værktøjerne i venstre side.
Som det kan ses på billedet er filen for lille til at virke på som en dørstopper så derfor skal den skaleres op.

Når filen har de rigtige dimensioner skal den eksporteres til gcode (som printeren kan læse), ved at trykke på "Save to File" i højre bund af programmet. Ved siden af knappen kan man se hvor langt tid printet tager samt printets vægt som skal bruges til betalling i DD Lab's webshop.

##### Tricks til bedre print
**Materiale & extruder**:  
I højre top kan man vælge hvilken "extruder" printeren skal bruge samt hvilket materiale der er tale om. Det er muligt at vælge begge extruders i samme print, men det tager VÆSENTLIG længere tid samt der er større sandsynlighed for fejl-print

**Print Setup**:  
Under indstillinger for for materialer og extruders finder man print setup. Den indstilling der hedder 'recommended' er den der almindeligvis skal bruges, men skal man have lavet noget mere avanceret, så tag fat i en ansat fra lab'et.  
Infill beskriver hvor meget printeren fylder ind i modellen. Hvis man skal printe noget der kan holde til noget, så kan man med fordel sætte infill procenten op. Eksemplet med dørstopperen sætter forsøger jeg med 50% fyld. Man skal være opmærksom på at dette gøre printetiden længere samt printet dyrere da der bruges mere materiale.  

**Support**:  
Support skal sættes til hvis der frithængende elementer på ens model, da printeren ikke kan lægge plastik ovenpå luft. Support kan ses som et stillads som printeren bruger til at
Jo mere support der skal bruges jo større er sandsynligheden for fejl-print, men der bruges også væsentlig mere materiale. Derfor anbefales det at man roterer sin  

 ## udskiftning af materiale

 ## design af egne modeller
