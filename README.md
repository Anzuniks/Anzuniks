# Moikka, olen Anders

ICT-insinööriopiskelija Metropoliassa. Olen kiinnostunut full-stack-kehityksestä, tekoälysovelluksista ja tietoturvasta. Ennen opintoja olin vartijana, ja se näkyy projekteissani: osa ideoista on lähtöisin suoraan siitä työstä.

Rakennan mieluiten asioita, jotka ratkaisevat jonkun oikean ongelman, esimerkiksi viranomaiskielen kääntämisen ymmärrettäväksi tai epäilyttävän käytöksen tunnistamisen kamerakuvasta.

Käytän tekoälytyökaluja koodatessa, mutta vastaan itse jokaisesta rivistä. Suunnittelen arkkitehtuurin ja ydinlogiikan itse, luen ja testaan tekoälyn tuottaman koodin enkä hyväksy mitään, mitä en ymmärrä. Tietoturvataustani takia katson aina myös, onko koodi turvallista.

## Tech stack

**Kielet ja full-stack**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

**AI/ML ja tietokannat**

![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**Työkalut**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## Tietoturva

Olen suorittanut TryHackMen Jr Penetration Tester -polun ja tehnyt CTF-haasteita. Bug bountyja (HackerOne) opettelen vielä. Käytän päivittäin Kali Linuxia ja Burp Suitea.

Pidän omia muistiinpanoja ja cheatsheet-aineistoa pentestauksen perusteista (footprinting, enumeration, Nmap), web-haavoittuvuuksista (XSS, fuzzing, JavaScriptin deobfuskointi, WordPress), Linuxista, Windowsista ja PowerShellistä sekä SIEM-pohjaisesta valvonnasta.

## Projektit

### Bureaucracy Decoder AI
`Python` `FastAPI` `React` `TypeScript` `NLLB-200` `Tesseract OCR`

Sovellus, joka lukee suomalaisen viranomaisasiakirjan (PDF tai kuva) ja kääntää sen valitulle kielelle. Kaikki pyörii paikallisesti omalla koneella, koska asiakirjat voivat olla arkaluonteisia eikä niitä kuulu lähettää pilveen.

OCR hoidetaan Tesseractilla ja PyMuPDF:llä, käännös tehdään `nllb-200-distilled-600M`-mallilla. Teksti pilkotaan kappaleisiin, jotta konteksti säilyy mallin syöterajan yli. Oikealta vasemmalle kirjoitettavat kielet toimivat myös.

### SecureOps Core
`TypeScript` `React` `Node.js` `Express` `MongoDB` `Socket.IO` `FastAPI`

Demo tietoturvaoperaatiokeskuksen (SOC) työnkulusta: hälytysten triage, tapausten hallinta playbookeilla, threat hunting -haku ja reaaliaikainen kojelauta. Kirjautuminen tehty JWT:llä ja päivitykset kulkevat Socket.IO:lla.

Erillinen Python/FastAPI-palvelu analysoi telemetriaa ja arvioi uhkatasoa. Demoa varten kirjoitin myös oman red team -skriptin, joka tuottaa hyökkäysdataa.

### CCTV AI Security Monitor
`Python` `YOLOv8-pose` `OpenCV` `NumPy` `SQLite` `Telegram Bot API`

Reaaliaikainen työkalu, joka tunnistaa web-kamerakuvasta asentotunnistuksella esimerkiksi lyöntiliikkeitä, äkkinäisiä liikkeitä ja taskusta ottamista. Idea tuli vartijan työstä.

Piirteet lasketaan kehon avainpisteistä ja normalisoidaan kehon koolla, jotta tunnistus toimii eri etäisyyksillä. Tilakone ja havaintohistoria vähentävät vääriä hälytyksiä. Hälytykset menevät Telegramiin ja tapahtumat tallentuvat SQLiteen.

### Quantix Logistics
`TypeScript` `React` `Node.js` `Express` `MySQL`

Logistiikka-alan web-sovellus. Vastasin full-stack-integraatiosta eli REST-rajapinnoista, tietokantasuunnittelusta ja frontendistä.

### Kauppakeskussimulaattori
`Java`

Olio-ohjelmoinnilla tehty simulaatio, jossa keskityttiin tietorakenteisiin ja simulaatiologiikkaan.
