Hier sollen die Anpassungen sowie die Gründe dafür beschrieben werden.

#Peregrine
1) Anpassung UrlResolver für Multistore Unterstützung
   - *packages/peregrine/lib/Router/resolveUnknownRoute.js*  
      Möglichkeit für Custom Header hinzugefügt, damit bei der Abfrage der Store-Header gesetzt werden kann.
   - *packages/peregrine/lib/Router/magentoRouteHandler.js*  
      Custom Store-Header wird gesetzt, wenn in den Props **storeCode** gesetzt ist.