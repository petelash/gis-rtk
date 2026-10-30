# gis-rtk
GIS RTK - politika privatnosti
GIS RTK – Politika privatnosti

Vrijedi od: 29. listopada 2026.

GIS RTK je aplikacija za prikaz katastarskog plana i iskolčenje pomoću vanjskog GNSS RTK prijemnika (u-blox ZED-F9P) spojenog USB-om.
Autor i voditelj obrade: Marinko Vrbanić, marinko.vrbanic@gmail.com.

Ukratko

Aplikacija nema korisničkih računa, oglasa ni analitike i ne šalje podatke autoru.
Svi vaši podaci (postavke, preuzete katastarske općine, označene točke) ostaju na uređaju.
Aplikacija traži dozvolu za lokaciju uređaja. GPS mobitela koristi samo kao zamjenski položaj na karti dok GNSS prijemnik nije spojen, i samo dok je aplikacija otvorena. Taj se položaj ne sprema i ne šalje autoru.
Podaci koji se šalju trećim stranama
Da bi aplikacija radila, šalje se samo ono što je nužno, i to izravno pružateljima usluga, ne autoru:

CROPOS (Državna geodetska uprava): kad uključite NTRIP, aplikacija se spaja s vašim korisničkim imenom i lozinkom na poslužitelj koji upišete i za VRS korekcije mu periodično šalje približni položaj prijemnika (NMEA GGA poruka).
Državna geodetska uprava (oss.uredjenazemlja.hr, api.uredjenazemlja.hr, geoportal.dgu.hr): preuzimanje katastarskih općina i ortofoto podloge. Zahtjevi za podlogu otkrivaju područje karte koje gledate. Kad dodirnete „KO na mom položaju”, šalje se trenutni položaj radi pronalaska katastarske općine.
Google Play: ako koristite pretplatu ili kupite trajnu licencu, plaćanje obrađuje Google prema svojoj politici privatnosti; autor ne vidi podatke o plaćanju.
Na te prijenose primjenjuju se pravila privatnosti navedenih pružatelja. Sva veza ide preko interneta; NTRIP veza koristi protokol koji odabere caster.

Podaci spremljeni na uređaju

NTRIP pristupni podaci: šifrirano (Android Keystore).
Postavke, preuzete katastarske općine i spremljeni ortofoto.
Označene točke iskolčenja (koordinate, vrijeme, napomene). Iz aplikacije izlaze samo kad ih sami izvezete kao CSV.
Neobavezni zapis sirovih podataka prijemnika, samo ako ga uključite.
Sve to brišete u aplikaciji ili deinstalacijom aplikacije.

Djeca
Aplikacija je stručni alat i nije namijenjena djeci.

Vaša prava i kontakt
Budući da autor ne prikuplja vaše osobne podatke, nema ih ni što izdati ni obrisati na zahtjev. Za pitanja pišite na marinko.vrbanic@gmail.com. Promjene ove politike objavljuju se na ovoj stranici.

Summary in English
GIS RTK has no accounts, ads or analytics and sends no data to the developer. It requests device location only to show the phone’s GPS position on the map while no GNSS receiver is connected and the app is open; this position is not stored or sent to the developer. To work, it sends the approximate receiver position to the NTRIP caster you configure (CROPOS, for VRS corrections) and map/cadastre requests to the Croatian State Geodetic Administration (DGU). NTRIP credentials are stored encrypted on the device. Stakeout records stay on the device unless you export them. Subscription payments are handled by Google Play. Contact: marinko.vrbanic@gmail.com.
