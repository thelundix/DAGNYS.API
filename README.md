# SQLite Databas och REST API

Kraven för Godkänt:
Returnera JSON-resultat med vilka leverantörer som tillhandahåller respektive råvara och till vilket pris.

Detta uppfylls av endpointen GET /api/rawmaterials i RawMaterialsController.
Den returnerar alla råvaror tillsammans med deras leverantörer och priser.
Sök efter en specifik råvara och returnera ett JSON-resultat som visar råvaran och vilka leverantörer som tillhandahåller produkten.

Detta uppfylls av endpointen GET /api/rawmaterials/{id} i RawMaterialsController.
Den returnerar detaljer om en specifik råvara, inklusive vilka leverantörer som tillhandahåller den och till vilket pris.
