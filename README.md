# Moikka, olen Anders 👋

ICT-insinööriopiskelija (Metropolia), kiinnostuksen kohteina full-stack-kehitys, tekoälysovellukset ja tietoturva. Rakennan mieluiten asioita, jotka ratkaisevat oikean ongelman, kuten viranomaiskielen kääntäminen ymmärrettäväksi tai epäilyttävän käytöksen tunnistaminen valvontakamerakuvasta.

**Miten käytän tekoälyä:** Käytän tekoälytyökaluja koodatessa aktiivisesti, mutta vastaan itse jokaisesta rivistä. Suunnittelen arkkitehtuurin ja ydinlogiikan itse, luen ja testaan tekoälyn tuottaman koodin enkä hyväksy mitään, mitä en ymmärrä. Tietoturvataustani takia tarkistan aina myös sen, onko koodi turvallista.

## 💻 Tech stack

**Kielet & full-stack**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

**AI/ML & tietokannat**
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**Työkalut & infra**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## 🔐 Tietoturva

- TryHackMe **Jr Penetration Tester** -polku suoritettu
- CTF-haasteet ja bug bounty (HackerOne)
- Päivittäinen ympäristö: Kali Linux · Burp Suite

## 🚀 Projektit

### [Bureaucracy Decoder AI](https://github.com/Anzuniks/REPO-NIMI)
`Python` `FastAPI` `React` `TypeScript` `NLLB-200` `Tesseract OCR`

Paikallisesti ajettava sovellus, joka lukee suomalaisen viranomaisasiakirjan (PDF tai kuva) ja kääntää sen käyttäjän valitsemalle kielelle. Kaikki käsittely tapahtuu omalla koneella, joten arkaluonteiset asiakirjat eivät päädy pilvipalveluihin.

- OCR: Tesseract + PyMuPDF, käännös: `nllb-200-distilled-600M` (Hugging Face Transformers)
- Teksti palastellaan kappaleittain, jotta konteksti säilyy mallin syöterajan yli
- Tukee myös oikealta vasemmalle luettavia kieliä (RTL)

### [SecureOps Core – SOC-työnkulun demo](https://github.com/Anzuniks/defense-detection)
`TypeScript` `React` `Node.js` `Express` `MongoDB` `Socket.IO` `FastAPI`

Full-stack-sovellus, joka simuloi tietoturvaoperaatiokeskuksen (SOC) työnkulkua: hälytysten triage, tapausten hallinta playbookeilla, threat hunting -haku ja reaaliaikainen kojelauta.

- JWT-autentikointi, reaaliaikaiset päivitykset Socket.IO:lla
- Erillinen Python/FastAPI-palvelu analysoi telemetriaa ja arvioi uhkatasoa
- Oma red team -skripti tuottaa hyökkäystelemetriaa demoa varten

### [CCTV AI Security Monitor](https://github.com/Anzuniks/REPO-NIMI)
`Python` `YOLOv8-pose` `OpenCV` `NumPy` `SQLite` `Telegram Bot API`

Reaaliaikainen valvontatyökalu, joka tunnistaa web-kamerakuvasta asentotunnistuksen avulla esim. lyöntiliikkeet, äkkinäiset liikkeet ja taskusta ottamisen. Idea tuli vartijan työstä.

- Avainpisteistä lasketut, kehon kokoon normalisoidut piirteet → tunnistus toimii eri etäisyyksillä
- Tilakone ja havaintohistoria vähentävät vääriä hälytyksiä
- Hälytykset Telegramiin ja lokitus SQLiteen

### [Quantix Logistics](https://github.com/Anzuniks/REPO-NIMI)
`TypeScript` `React` `Node.js` `Express` `MySQL`

Logistiikka-alan web-sovellus. Vastasin full-stack-integraatiosta: REST-rajapinnat, tietokantasuunnittelu ja frontend.

### [Kauppakeskussimulaattori](https://github.com/Anzuniks/REPO-NIMI)
`Java`

Olio-ohjelmoinnilla toteutettu simulaatio, jossa painopisteinä tietorakenteet ja simulaatiologiikka.

## 📜 Sertifikaatit

- [DataCamp: SERTIFIKAATIN NIMI](https://www.datacamp.com/certificate/AIEDA0015567264379)

## 📫 Yhteystiedot

andu.nuri@hotmail.com · [LinkedIn](https://linkedin.com/in/...)
