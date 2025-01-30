# Super Focus

**Super Focus** är ett nytt generativt AI-verktyg tillgängligt i Photo AI version 3.3.0 som har förmågan att fixa oskärpa och extrahera detaljer. Det här verktyget fungerar som en alternativ lösning för de envisa och svårare bilderna som inte kan förbättras genom Photo AI:s andra skärpningsmodeller.

![image](https://cdn.sanity.io/images/r2plryeu/production/9adca483daeabcd0fbd844447e19c699e0579d90-1920x855.jpg?q=90&fit=max&auto=format)

### **System Requirements**

The Super Focus model has higher requirements for processing than other AI models.

For Windows, 8GB VRAM is required for processing locally.

For Mac, macOS 13 or higher is required. It is currently not supported on Macs with AMD Radeon graphics cards.

---

Så här börjar du använda **Super Focus**:

1. Klicka på knappen **Super Focus** som finns i den högra panelen ovanför knappen "Lägg till förbättringar".
2. I panelen Super Focus, **välj ett skärpningsstyrkeläge och en förhandsgranskningskontrollstorlek**.
3. **Flytta musen** över till huvudförhandsgranskningsfönstret och klicka på ett område du vill förhandsgranska.
4. **Välj knappen Render** längst ner för att bearbeta hela bilden.

![image](https://cdn.sanity.io/images/r2plryeu/production/291cea52b3dc07bff430574ce2030e372a976237-2000x1174.gif?q=90&fit=max&auto=format)

För att avsluta Super Focus utan att göra ändringar klickar du på "X" i det övre högra hörnet.

![image](https://cdn.sanity.io/images/r2plryeu/production/33c9cc865279daf1067193421defcbcb8631e1ba-2048x1205.webp?q=90&fit=max&auto=format)

---

##### Bästa praxis för Super Focus

![Sample image of Super focus and Face recovery used](https://cdn.sanity.io/images/r2plryeu/production/2b3b7a2bf5c0aff4587761614847c540b0a3fcc5-2000x1500.png?q=90&fit=max&auto=format)

- Resultat visas bäst på bilder som är minst 4 megapixlar eller större.
- Fungerar bäst för bilder som är ur fokus och mjuka.
- För bästa resultat, återställ ansikten efter Super Focus, särskilt på små till medelstora ansikten eftersom ansiktsdetaljer ändras av Super Focus.
- För bästa resultat, använd "Bevara text" efter Super Focus på liten till medelstor text eftersom den kan ändras av Super Focus.

I vissa fall kan rörelseoskärpa korrigeras med Super Focus, men verktyget är inte utformat för att hantera extrema fall. Prova att utforska Sharpen AI-modellen för rörelseoskärpa istället.

# Sharpen

Sharpen-filtret producerar tydliga bilder med skarpa detaljer. Till skillnad från traditionell skärpning som mörknar eller ljusar pixlarnas kanter, vänder den på de bakomliggande orsakerna till oskärpa, såsom kameraskakning, rörelseoskärpa och missat fokus.

![Sharpen](https://cdn.sanity.io/images/r2plryeu/production/1c2b1ceb41fbbfd40c8610e83bfa63e12f408a6b-1540x1080.gif?q=90&fit=max&auto=format)

---

#### Controls

Använd fliken **Controls** för att välja AI-modell och justera inställningarna. 

![Sharpen Controls](https://cdn.sanity.io/images/r2plryeu/production/68023adccaa10a616ffdb4ec411a6ecb129aa12e-492x874.png?q=90&fit=max&auto=format)

## Modeller

#### Standard

Använd **Standard**-modellen för allroundskärpning. Den är avsedd för bilder med små mängder lins- och rörelseoskärpa.

![Standard](https://cdn.sanity.io/images/r2plryeu/production/e9382b363387dd589c046e8de91de1c7c1a560bf-1928x1314.png?q=90&fit=max&auto=format)

###### Strong

Använd **Strong**-modellen för mycket suddiga och ur fokus-bilder. Prova **Standard**-modellen före **Strong**-modellen för att undvika överskärpning och generera oönskade artefakter.

![Strong](https://cdn.sanity.io/images/r2plryeu/production/7f83884577ad6280829ef137cad6803ebda0a779-1922x926.png?q=90&fit=max&auto=format)

#### Lens Blur

Använd **Lens Blur**-modellen på bilder som påverkas av defekter orsakade av att kameralinsen inte fokuserar korrekt.

![Lens Blur](https://cdn.sanity.io/images/r2plryeu/production/00c2e6b57447ddebf91def591c546fdfc343d3f1-963x673.png?q=90&fit=max&auto=format)

#### Motion Blur

Använd **Motion Blur**-modellen för att korrigera den randiga eller utsmetade effekten som orsakas av rörelse hos antingen kameran eller motivet under exponeringstiden.

![Motion Blur](https://cdn.sanity.io/images/r2plryeu/production/a8e8f933deb2679ecf7a4f156285da5affb41418-1918x1102.png?q=90&fit=max&auto=format)

#### Natural

Använd **Natural**-modellen för att skärpa objekt och hålla texturen naturlig.

![image](https://cdn.sanity.io/images/r2plryeu/production/b91021fb1937e48779da22e47358848151bd6ee0-2472x1588.png?q=90&fit=max&auto=format)

#### Refocus

Använd **Refocus**-modellen för att betona detaljer och få fram finare linjer eller textur.

![image](https://cdn.sanity.io/images/r2plryeu/production/0c37b3be1e25084df15833f312cebc11ba033902-2462x1572.png?q=90&fit=max&auto=format)

---

### Settings

#### Strength

Använd reglaget **Strength** för att kontrollera graden till vilken AI-modellen skärper bilden. Det ökar tydligheten i detaljerna genom att göra kanterna och fina funktioner mer distinkta.

#### Minor Denoise

Skärpning kan framhäva brus i en bild. Använd reglaget **Minor Denoise** för att ta bort lätt brus så att Sharpen-filtret kan förbättra detaljerna utan att förstärka oönskade artefakter.

# Adjust Lighting

Adjust Lighting-filtret ändrar exponering och kontrast för att producera en väl upplyst och levande bild. Det gör ändringar på pixelnivå baserat på deras unika egenskaper och omgivande sammanhang istället för att justera bilden universellt.

![Adjust Lighting](https://cdn.sanity.io/images/r2plryeu/production/2a432e1505a764713f3736afcf6693ab3133bfc4-744x1080.gif?q=90&fit=max&auto=format)

När Adjust Lighting används med RAW-bilder tvingas utmatningen till TIF-filformat istället för DNG.

---

## Controls

Använd fliken **Controls** för att välja AI-modell och justera inställningarna.

![Adjust Exposure Controls](https://cdn.sanity.io/images/r2plryeu/production/81e0a3c21c8d3bf444c8203a59e10f89d8460eaa-496x446.png?q=90&fit=max&auto=format)

#### Adjustment

Använd reglaget **Adjustment** för att bestämma omfattningen av bearbetning som AI-modellen utför. Det betyder inte att öka eller minska exponeringen.

Till skillnad från andra redigerare resulterar inte en ökning av reglagets värde nödvändigtvis i en ljusare bild. Det tillämpar mer eller mindre av AI-modellens effekt.

Standardjusteringen är 25. Ett reglagevärde på 0 indikerar ingen justering.

- Ställ in reglagevärdet mellan 1 och 25 för att ha mindre justering men i samma riktning.
- Ställ in reglaget på ett negativt värde för att justera i motsatt riktning mot vad Autopilot rekommenderade.

I det här exemplet upptäckte AI-modellen att originalfotot var för mörkt och korrigerade det för att bli ljusare. Att öka reglaget skulle göra det ännu ljusare.

![Underexposed Image](https://cdn.sanity.io/images/r2plryeu/production/5dff829c65f89879cd993ab57a510328a4b9bd70-1869x1236.jpg?q=90&fit=max&auto=format)

Det här exemplet visar motsatt effekt. AI-modellen upptäcker att originalbilden är för ljus och korrigerar den för att bli mörkare. Att öka reglaget skulle göra det ännu mörkare.

![Overexposed Image](https://cdn.sanity.io/images/r2plryeu/production/f1ed63891b5a848867456fdaa4e8e1e8d293b07b-1836x1210.jpg?q=90&fit=max&auto=format)

---

# Balance Color

Balance Color-filtret neutraliserar oönskade färgstick och möjliggör kreativa tonjusteringar genom kallare och varmare förbättringar. Det justerar färger pixel för pixel, anpassar sig till varje pixels omgivande sammanhang istället för att tillämpa universella ändringar på hela bilden.

![Balance Color](https://cdn.sanity.io/images/r2plryeu/production/c260c698394c12b0df57a0f0b0dadb415d6f87a3-1836x1230.png?q=90&fit=max&auto=format)

När Balance Color används med RAW-bilder tvingas utmatningen till TIF-filformat istället för DNG.

---

## Controls

Använd fliken **Controls** för att välja AI-modell och justera inställningarna. 

![Balance Color Controls](https://cdn.sanity.io/images/r2plryeu/production/c4d7bc9d04ac50ecbfd945e9d33f60d8d88a3e7e-496x550.png?q=90&fit=max&auto=format)

### Settings (Inställningar)

#### Temperature (Kallt = blåare nyans, Varmt = mer orange)

Använd reglaget Temperature för att flytta bildfärgen från kallare (vänster) till varmare (höger). Det börjar som standard på 50 som en neutral baslinje för äkta vitt.

![Results](https://cdn.sanity.io/images/r2plryeu/production/c09282477d3751490fb9e193319abfc41dcce649-1920x908.png?q=90&fit=max&auto=format)

#### Opacity (Genomskinlighet - eller styrka i detta fallet)

Använd reglaget Opacity för att diktera hur mycket den AI-genererade bilden ersätter originalet. Inmatningsbilden är oförändrad vid 0 opacitet. Utmatningen är helt AI-genererad vid 100 opacitet. Standarden är 100, men om resultaten verkar övermättade, minska opaciteten för att mjuka upp den.

---

# Recover Faces

Tydlighet i ansiktsdrag förbättrar en bilds kommunikativa värde. Face Recovery-filtret återställer små eller lågupplösta ansikten genom att generera en högkvalitativ version och blanda den med det nuvarande ansiktet.

![Face Recovery](https://cdn.sanity.io/images/r2plryeu/production/8e409967a3cf4fde176dd67a78ca7499be1caffe-1916x1340.png?q=90&fit=max&auto=format)

---

### Face Selection (Val av ansikten)

### Controls

Använd fliken **Controls** för att ändra styrkan för Recover Faces. Standardstyrkan är 80 och kan minskas för att minska bearbetningen.

![Recover Faces Controls](https://cdn.sanity.io/images/r2plryeu/production/a62be077238c53b69767cc2e0d33a6adea2914c7-492x1144.png?q=90&fit=max&auto=format)

### Tillfällen då det ska eller kan användas

#### Low Resolution Faces (Ansikten med låg upplösning)

Använd Face Recovery-filtret på ansikten med låg upplösning, även om det är stort och tar upp större delen av bilden. Upplösning mäts i pixlar.

![Low Resolution Face](https://cdn.sanity.io/images/r2plryeu/production/da3f8c71da27b437ed95155c1318ad61d4a59468-1102x652.png?q=90&fit=max&auto=format)

#### Small Faces

Använd Face Recovery-filtret när ansiktena är små och långt från kameran. Modellen genererar de bästa resultaten när ansiktet fortfarande har tillräckligt med detaljer. Se hela bilden och den inzoomade delen nedan.

![Full Image](https://cdn.sanity.io/images/r2plryeu/production/4c413097a7456c5ce99ee28848019d41eaa36701-3072x2048.jpg?q=90&fit=max&auto=format)

![Zoomed in Portion](https://cdn.sanity.io/images/r2plryeu/production/c381efff09cee1acd00b4ee0a6edf71c37471708-1918x1188.png?q=90&fit=max&auto=format)

### Tillfällen det inte ska användas

#### Porträtt

Att använda Face Recovery-filtret kan överbearbeta ansikten som redan har hög upplösning. Detta orsakar en förlust av detaljer och skapar en "plastig" känsla eftersom det är för jämnt.

![Portrait](https://cdn.sanity.io/images/r2plryeu/production/a48b220079163480ea2419f7775ef482753c386b-1924x1286.png?q=90&fit=max&auto=format)

#### Out-of-Focus Faces (Ansikten ur fokus)

Använd inte filtret för bilder som är ur fokus. Bristen på detaljer hindrar korrekt ansiktsrekonstruktion och genererar orealistiska artefakter.

![Out-of-focus](https://cdn.sanity.io/images/r2plryeu/production/fae2c1b7b1e2e4fa050f02efbb412f0de99bb32b-1926x1290.png?q=90&fit=max&auto=format)

---

# Preserve Text (Bevara Text)

Preserve Text-filtret gör text så läsbar som möjligt. Det optimerar textpresentationen genom att korrigera problem som dåligt fokus, rörelseoskärpa, liten text, låg kvalitet på text och artefakter.

![Preserve Text](https://cdn.sanity.io/images/r2plryeu/production/09257c8dab77a533c3bfca3fc6e61892385d279f-1764x1080.gif?q=90&fit=max&auto=format)

---

#### Mask (Maskera - selektivt välja ut delar av fotot)

Masken är det första som visas när Preserve Text-filtret är aktiverat. Det går inte att hoppa över eftersom det appliceras direkt på inmatningsbilden och skriver över de andra lagerfiltren.

![Mask Settings](https://cdn.sanity.io/images/r2plryeu/production/3d429d4e83379e46648b697ebeed6658725d0c5c-492x466.png?q=90&fit=max&auto=format)

Ingen text är vald som standard. Justera penselstorleken och maskera texten i bilden. Klicka på knappen Subtract för att avmarkera delar av masken och knappen Select None för att rensa den helt.

![Select Text](https://cdn.sanity.io/images/r2plryeu/production/846ee115273a26c21729d930470036348ac33cf0-2522x1492.png?q=90&fit=max&auto=format)

Välj "Select All" för bilder som huvudsakligen består av text. Tänk på att det maskerade området inte påverkas av andra filter.

![Select All](https://cdn.sanity.io/images/r2plryeu/production/67c216f60afef9768e06a6c671267c1e7972e024-2492x1392.png?q=90&fit=max&auto=format)

---

## Controls

Använd fliken **Controls** för att välja AI-modell och justera inställningarna.

![Preserve Text Controls](https://cdn.sanity.io/images/r2plryeu/production/3a4dc1fd6b156a9790ae56f60179ccfa474571a7-496x864.png?q=90&fit=max&auto=format)

### Models

#### Low Resolution (Låg upplösning)

Använd Low Resolution-modellen för att bevara liten text. Den används bäst när texten är en liten del av en större bild.

![Low Resolution](https://cdn.sanity.io/images/r2plryeu/production/02c47c16b8835160cf74c929aa07310f0554ef0b-1918x1348.png?q=90&fit=max&auto=format)

#### Noisy/Compressed (Brusig)

Använd Noisy/Compressed-modellen för att bevara text i brusiga eller komprimerade bilder. Den tar bort bruset för att bevara texten under den.

![Noisy](https://cdn.sanity.io/images/r2plryeu/production/4ee2f48c180c2e9f49de603a3b38bd3a11c61dce-1924x1338.png?q=90&fit=max&auto=format)

![Compressed](https://cdn.sanity.io/images/r2plryeu/production/7b1ee02b63cd7b3bc348b5b8f6e2eecdd093fc7f-1924x1340.png?q=90&fit=max&auto=format)

### Settings

#### Strength

Använd reglaget Strength för att kontrollera graden av generering som AI-modellen kommer att använda för att bevara texten. Auto-select-värdet kommer att börja lågt eftersom att ställa in styrkan för högt gör att texten ser orealistisk ut.

---

# Upscale & Resize (Förstora & ändra storlek)

Upscale-filtret förbättrar upplösningen på bilder med upp till 600 %. Det bevarar också fler intrikata detaljer från originalbilden än andra uppskalningsverktyg.

![image](https://cdn.sanity.io/images/r2plryeu/production/cd2335c74e9c889a3484c5b2bb196db6b5bc3cfa-1540x1080.gif?q=90&fit=max&auto=format)

---

### Controls

Använd panelen **Controls** för att välja AI-modell och justera skala och dimensioner.

![Upscale Settings](https://cdn.sanity.io/images/r2plryeu/production/f505d9db86fb7de4c8d6ba3da8f65b3fb11fb8a5-492x960.png?q=90&fit=max&auto=format)

### Models

AI-modellerna är starkt beroende av befintlig bildkvalitet. De kan generera oönskade artefakter om upplösningen på startbilden är för låg. Uppskala från en originalbild när det är möjligt snarare än en kopia som har komprimerats.

Se till att använda lämplig modell för din bild. Modellerna är inte utbytbara och att använda fel modell kan ge oönskade resultat.

#### Standard

Standardmodellen är det självklara valet för allmän användning om inte bilden tydligt tillhör någon av de andra kategorierna. Den är skräddarsydd för medelkvalitativa bilder från kompaktkameror och äldre smartphones.

Använd Standardmodellen för mycket detaljerade AI-genererade bilder från Midjourney, Dall-E och liknande verktyg.

![Standard](https://cdn.sanity.io/images/r2plryeu/production/95f052956303f94409f0d5fe6bbc77e88be72a69-1926x1340.png?q=90&fit=max&auto=format)

#### Standard V2

Använd Standard V2-modellen för att få en mer generativ utgång än den ursprungliga standardmodellen.

#### High Fidelity

Använd den här modellen för bilder som redan är av hög kvalitet för att bevara intrikata detaljer. Bilder från digitala systemkameror och de flesta moderna smartphones faller inom denna kategori. Använd den även för mycket detaljerad AI-genererad konst.

![High Fidelity](https://cdn.sanity.io/images/r2plryeu/production/b251884bdf822e8d8c283cb13af98ea22cedff86-1928x1086.png?q=90&fit=max&auto=format)

#### High Fidelity V2

Använd High Fidelity V2-modellen för att avsiktligt bevara originalkorn eller brus för estetiska ändamål.

#### **Low Resolution**

Low Resolution-modellen prioriterar att bevara den övergripande kvaliteten snarare än fina detaljer. Använd den för att uppskala bilder med låg kvalitet som har komprimerats mycket.

![Low Resolution](https://cdn.sanity.io/images/r2plryeu/production/f722a0bf1dc8c9d96fbd000156e7a59d26f3971c-1922x1250.png?q=90&fit=max&auto=format)

#### **Graphics**

Graphics-modellen uppskalar enkla illustrationer som tecknade serier.

![Graphics](https://cdn.sanity.io/images/r2plryeu/production/338802bad2d0ef896c966de8b8bb07a8e2ced351-1920x1058.png?q=90&fit=max&auto=format)

---

### Settings

#### Minor Denoise

Svagt ljus, sensorbegränsningar eller komprimeringsartefakter kan orsaka lätt brus. Inställningen Minor Denoise tar bort detta brus innan bilden skalas upp.

#### Minor Deblur

Använd inställningen Minor Deblur för att undvika att betona befintlig oskärpa orsakad av kameraskakning, rörelseoskärpa eller bristande fokus när bilden tas.

**Obs:** Undvik att använda Minor Denoise och Minor Deblur om Remove Noise- och Sharpen-filtren redan är aktiverade. Att använda båda kan resultera i överbearbetning.

#### Fix Compression

Visuella förvrängningar och artefakter kan uppstå när bilder komprimeras för att göra dem mer utrymmeseffektiva.

#### Dimensions

Välj mellan pixlar, tum eller centimeter för att ange dimensioner. Ställ in värden för varje sida eller ange den totala DPI (punkter per tum) eller PPI (pixlar per tum). Använd det här verktyget för att definiera dimensioner för utskriftsändamål.

Textrutorna pixlar/tum och pixlar/centimeter visas bara när dimensionerna är inställda på dessa enheter.
