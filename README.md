# SQLite Databas och REST API

## Beskrivning

Detta projekt syftar till att skapa en SQLite-databas enligt **Code-First-principen** med korrekta relationer mellan entiteterna. Databasen fylls automatiskt med data vid applikationens start om tabellerna är tomma. Ett REST API utvecklas för att hantera **råvaror** och deras **leverantörer**.

## Funktionalitet

- **SQLite Databas**: Skapas enligt Code-First-principen med korrekta relationer mellan entiteter.
- **Automatisk datainmatning**: Vid applikationsstart fylls tabellerna med data om de är tomma.
- **REST API**: Hanterar CRUD-operationer för råvaror och leverantörer.
  - Returnerar JSON-resultat med leverantörer och pris för respektive råvara.
  - Endpoint för att söka råvaror och returnera tillhörande leverantörer.
