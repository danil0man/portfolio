---
Title: Load
Template: rapport
---

# Utvärdering av webbplatsers prestanda

&nbsp;

Uppgiften handlar om att analysera 3 olika subsidor på 3 olika webbplatser. Webbplatserna skall sedan ragnordnas beroende på generel prestanda.

&nbsp;

## Urval

Vi har valt webbplatser med ett försäljnings syfte. Vi tyckte att det kunde vara intressant att mäta prestandan i webbplatser som visar upp produkter i form av bilder.
&nbsp;

-   **NetOnNet**

![NetonNet](../image/load/netonet.png?w=830 "NetonNet website") {.rapport-img}

&nbsp;

-   **Ikea**

![Ikea](../image/load/ikea.png?w=830  "Ikea website") {.rapport-img}

&nbsp;

-   **Clas Ohlson**

![Clas Ohlson](../image/load/clas.png?w=830 "Clas Ohlson website") {.rapport-img}

&nbsp;

## Metod

&nbsp;

Vi har använt oss utav devtools i firefox och google page insights.

&nbsp;

## Resultat

&nbsp;

<iframe style="width: 100%; height: 180px;"src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQbROV2rrZ5g8XRCaJuA5JkkwBX6X5D-HTIzveZnmU_aRTVYEo1K07qn9UhpqBajgzP6v4YY-zilg9b/pubhtml?widget=true&amp;headers=false" title="rapport"></iframe>

&nbsp;

1. Clas Ohlson
2. NetOnNet
3. Ikea

&nbsp;

Resultatet visar att Clas Ohlson har bäst prestanda när det gäller mobil och desktop medan NetOnNet har en snabbare laddningstid.

&nbsp;

## Analys

&nbsp;

När det gäller förbättring av prestanda så kan alla sidorna se över LCP. Largest Contentful Paint (LCP) mäter hur lång tid det tar att rendera det största synliga objektet i viewport.

Den webbplats som behöver förbättras mest är Ikea. Där sidan har för mycket "request" samt totala storleken på sidan spelar en stor roll i prestandan.

En faktor som påverkar prestandan är hur många request sidan gör. Om vi tar Ikea som exempel så sparar de inte allting cache vilket gör att sidan skickar request på samma saker varje gång man laddar om/går in på sidan. Om de skulle använda sig av cache mer så skulle prestandan förbättras.

&nbsp;


Gränsen för laddningstid utan cache går vid 5 sekunder, under 5 sekunder är snabbt och över 5 är långsamt. Värdet som vi får av verktygen som mäter prestandan mäter inte bara det vi ser utan hela sidan. Det viktigaste på sidan är det man först ser när man går in på sidan (above the fold).
Generellt så tycker vi att sidorna vi valt har en relativt bra laddningstid baserat på deras syfte.

&nbsp;

## Övrigt

&nbsp;

-   **Danny Castillo**
-   **Kim Svensson**