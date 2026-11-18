# Moikka, olen Anders 👋

ICT-insinööriopiskelija (Metropolia) ja entinen vartija. Rakennan full-stack-sovelluksia, tekoälyratkaisuja ja tietoturvatyökaluja, jotka ratkaisevat oikean ongelman: viranomaiskielen kääntäminen ymmärrettäväksi, epäilyttävän käytöksen tunnistaminen valvontakamerakuvasta tai SOC-analyytikon työnkulun sujuvoittaminen.

Etsin parhaillaan harjoittelu- ja työpaikkoja tietoturvan, tekoälyn ja ohjelmistokehityksen parista.

## 🤖 Miten käytän tekoälyä

Käytän tekoälytyökaluja koodatessa aktiivisesti, mutta vastaan itse jokaisesta rivistä.

- Suunnittelen arkkitehtuurin ja ydinlogiikan itse
- Luen ja testaan kaiken tuotetun koodin, enkä hyväksy mitään mitä en ymmärrä
- Tietoturvataustani takia tarkistan aina myös, onko koodi turvallista

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

### 🌍 Bureaucracy Decoder AI
`Python` `FastAPI` `React` `TypeScript` `NLLB-200` `Tesseract OCR`

Paikallisesti ajettava sovellus, joka lukee suomalaisen viranomaisasiakirjan (PDF tai kuva) ja kääntää sen valitulle kielelle. Kaikki käsittely tapahtuu omalla koneella, joten arkaluonteiset asiakirjat eivät päädy pilvipalveluihin.

- **OCR:** Tesseract + PyMuPDF
- **Käännös:** `nllb-200-distilled-600M` (Hugging Face Transformers)
- Teksti palastellaan kappaleittain, jotta konteksti säilyy mallin syöterajan yli
- Tukee myös oikealta vasemmalle luettavia kieliä (RTL)

### 🛡️ SecureOps Core – SOC-työnkulun demo
`TypeScript` `React` `Node.js` `Express` `MongoDB` `Socket.IO` `FastAPI`

Full-stack-sovellus, joka simuloi tietoturvaoperaatiokeskuksen työnkulkua: hälytysten triage, tapausten hallinta playbookeilla, threat hunting -haku ja reaaliaikainen kojelauta.

- JWT-autentikointi ja reaaliaikaiset päivitykset Socket.IO:lla
- Erillinen Python/FastAPI-palvelu analysoi telemetriaa ja arvioi uhkatasoa
- Oma red team -skripti tuottaa hyökkäystelemetriaa demoa varten

### 📹 CCTV AI Security Monitor
`Python` `YOLOv8-pose` `OpenCV` `NumPy` `SQLite` `Telegram Bot API`

Reaaliaikainen valvontatyökalu, joka tunnistaa web-kamerakuvasta asentotunnistuksen avulla esimerkiksi lyöntiliikkeet, äkkinäiset liikkeet ja taskusta ottamisen. Idea syntyi vartijan työstä.

- Avainpisteistä lasketut, kehon kokoon normalisoidut piirteet, joten tunnistus toimii eri etäisyyksillä
- Tilakone ja havaintohistoria vähentävät vääriä hälytyksiä
- Hälytykset Telegramiin ja lokitus SQLiteen

### 🚚 Quantix Logistics
`TypeScript` `React` `Node.js` `Express` `MySQL`

Logistiikka-alan web-sovellus. Vastasin full-stack-integraatiosta: REST-rajapinnoista, tietokantasuunnittelusta ja frontendistä.

### 🛍️ Kauppakeskussimulaattori
`Java`

Olio-ohjelmoinnilla toteutettu simulaatio, jonka painopisteinä ovat tietorakenteet ja simulaatiologiikka.
