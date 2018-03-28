# kryssrutor
Se till så att alla mellanliggande rutor kryssas i automatiskt om man kryssar i en ruta först, och sedan håller nere skift och kryssar i en till.

Du får inte ändra i HTML-koden, utan måste hålla dig inuti script-taggen.

- undersök hur document.querySelector() och document.querySelectorAll() fungerar. Vilka parametrar tar de?
- undersök det event du får från "click", innehåller det någon information om skift-tangenten? Hur får reda på om den varit nertryckt när besökaren klickade?
- vad är det för typ av objekt du får ut ifrån document.querySelector() och document.querySelectorAll()? Finns det någon metod som låter dig iterera över det?
- istället för att ha en "onclick"-metod på varje checkbox (du får inte ändra i HTML-koden) så kan du använda något som kallas "eventListener", det finns en metod som kallas "addEventListener", kontrollera hur den fungerar.
