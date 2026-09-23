RESELL RADAR — PRVÁ FUNKČNÁ VERZIA
=====================================

Čo je v balíku
--------------
- index.html = kompletná responzívna stránka
- api/analyze.js = serverová AI analýza cez Gemini
- package.json = potrebná knižnica
- Tento súbor = návod

DÔLEŽITÉ
--------
Samotný index.html vie fungovať aj po otvorení v počítači ako demo.
Aby verejná stránka skutočne posielala fotku do AI, musí byť nasadená
na hostingu so serverovou funkciou a musí mať GEMINI_API_KEY ako tajný
environment variable. API kľúč NESMIE byť vložený priamo do index.html.

Odporúčaný bezplatný štart
--------------------------
1. Vytvor si účet na GitHub.
2. Nahraj obsah tohto priečinka do nového repozitára.
3. Vytvor účet na Vercel.
4. Importuj GitHub repozitár do Vercel.
5. V projekte pridaj environment variable:
   GEMINI_API_KEY = tvoj Gemini API key
6. Deploy.
7. Vercel ti dá verejný odkaz na stránku.

AI
--
Kód používa Gemini API. Google aktuálne uvádza bezplatný tier pre Gemini API
s obmedzenými modelmi a limitmi. Pred verejným spustením si skontroluj aktuálne
limity a podmienky používania.

TRHOVÉ CENY
-----------
Toto ešte NIE JE napojené na reálne predané položky z Vinted/eBay/Depop.
Preto aplikácia zámerne neprezentuje odhad ako garantovanú live cenu.
Ďalšia fáza projektu je napojiť legálny a spoľahlivý zdroj trhových dát.

BEZPEČNOSŤ
----------
- API kľúč drž iba v serverových environment variables.
- Neskôr pridaj rate limiting, autentifikáciu, logovanie a ochranu proti
  zneužitiu endpointu.
- Pred verejným plateným produktom pridaj validáciu obrázkov a veľkosti súborov.

ĎALŠIA VERZIA
-------------
1. Reálnejšie trhové dáta.
2. História analýz.
3. Účet používateľa.
4. Inventory.
5. Pro plán.
6. Analytics.
