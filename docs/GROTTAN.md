# Grottan – underjordisk koloni

Allt ligger i databasen (Supabase). Klienten anropar bara RPC-funktioner; servern räknar allt.

- 13 rumstyper (Kraftverk, Matsal, Vattenrening, Sovrum, Sjukhus, Verkstad, Laboratorium, Lager, Träningsrum, Kontrollrum, Försvarsrum, Kommunikation, Vardagsrum).
- Invånare med namn, utseende, hälsa, energi, hunger, törst, humör, 6 egenskaper, nivå/erfarenhet, jobb och historia.
- Resurser: el, mat, vatten, byggmaterial, metall, medicin, kristall, forskning.
- Simulering räknas "lat": vid varje öppning räknar servern ikapp (max 12 h bortavaro).
- Pause/hastighet finns inte (spelet är gemensamt och sparas på servern). Tilldelning sker med tryck, inte dra-och-släpp.
- Kommer: händelser, uppdrag, expeditioner, utrustning, ljud, inställningar.
