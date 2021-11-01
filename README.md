# 📅
## Viikkokalenteri - Full-stack projekti
### ✨ Tiivistelmä
Viikkokalenteri projekti on viikkonäkymä kuluvasta työviikosta, näyttäen kellonajan päivänäkymässä. Projekti toteutetaan REST API arkkitehtuurityyliä seuraten. 
Projektissa pitää pystyä tekemään seuraavat asiat:
- Lisäämään, poistaa, ja muokata kalenterimerkintöjä
- Lisätessä kalenterimerkintää, pitää pystyä lisäämään seuraavat tiedot:
  - Otsikko, kategoria (tapahtuman tieto: esimerkiksi kenen järjestämä tapahtuma), päivämäärä, kellonaika, paikka, lisätietoja
- Meneillään oleva kellonaika päivämäärästä tulisi näkyä korostettuna
- Päivän työskentelyaika tulisi näkyä kohotettuna
  - Esimerkiksi mahdollisuus asettaa että 9-15 olisi aktiivinen alue ja tämän kellonajan ulkopuolella muut kellonajat ei välttämättä näkyisi tai jos näkyisi niin olisivat harmaan värisinä
  - Kellonaika aktiiviselle alueelle tulisi pystyä säätäämään
    - Esimerkiksi työpajalla voisi olla poikkeuspäivä jolloin tarvittaisiin aktiivi alueeksi 10-16 kellonaika väli.
- Kalenterimerkintä pitäisi pystyä avaamaan ja näkemään lisätiedot sekä merkitsemään omalla nimellä nähneensä sen ja osallistuvan tapahtumaan (ainoastaan osallistuminen, ei muita merkintöjä).

### 🛠️ Ohjelmointikielet

#### Frontend
- HTML & CSS
- Javascript
- React

#### Backend
- Python 3.10
- Flask
- Mongodb

### 📝 Muuta
- Dokumentointi kieli 🇬🇧 englanti
- Hyödynnetään "Projects" työkalua GitHubissa.
- Backend esisuunnitelma: 

### 👨‍🎤 Tiimin kokoonpano
| Nimi        | Rooli       | Ryhmä       |
| ----------- | ----------- | ----------- |
| [Jouni Heikkinen](https://github.com/heikjou)    | UI-suunnittelija & Frontend (HTML & CSS)     | 🟢     |
| [Aki Sartolahti](https://github.com/donqnr)    | Backend devaaja (Python, Flask, Mongodb)     | 🟦     |
| [Niklas Larsson](https://github.com/nikkelarsson)    | Backend devaaja (Python, Flask, Mongodb)     | 🟦     |
| [Sanjiv Rana](https://github.com/eync)   | Opettaja / Projektin asiakas       | 🟢  🟦      |

### 🚧  Projektinhallinta
Päivittäinen palaveri erikseen ryhmittäin:  
🟦  maanantai-torstai, klo 12:50 (kesto suunnilleen 10min)  
🟢  klo ? (kesto suunnilleen 10min) (ei tarpeeksi porukkaa, sovitaan myöhemmin)

Viikottainen yhteinen isompi tavoite palaveri: 
* perjantai, klo 9:00  (30-60min)

Seuraavat repot projektin käytössä:
* viikkokalenteri (yleiset tiedosto, esim layout suunnitelma sekä projektin tarkemmat suunnitelmat)
* viikkokalenteri-frontend (sis. koodin ja kanban taulun)
* viikkokalenteri-backend (sis. koodin ja kanban taulun)

### 🥅 Ensimmäiset tavoitteet (1.11. - 5.11.)
- Asiakas
    - Määritellä tiivistelmä projektista ja halutuista toiminnallisuuksista

- Frontend
    - Ei mietitä toistaiseksi, ei UI-suunnitelmaa vielä valmiina

- UI esisuunnitelma
    - Inspiraatiota (dribbble)
    - Väripaletin etsiminen (5 väriä)
    - Fonttien miettiminen (2 fonttia)
    - Layout/gridin mallintaminen 

- Backend
    - Rest API materiaalit (https://www.restapitutorial.com/)
    - Käyttötapauksia poimia asiakkaan tiivistelmästä
    - Monta API-endpointtia tarvitaan
    - Monta eri versiota pitää iteroida että saadaan MVP valmiiksi (https://en.wikipedia.org/wiki/Minimum_viable_product)
    - [Google Docs](https://docs.google.com/document/d/1DvK3TIctCRkCBirXf3iipj8yivsy0L3UI9bqZ7ChW44/edit?usp=sharing)
    - Muuta huomioitavaa 

### 🥅 Tavoitteet (1.11. - 5.11.)
- Yleistä
  - Perjantai palaverin järjestys
    - Puheenjohtaja: Jouni
    - Sihteeri: Niklas

### 🥅 Tavoitteet (8.11. - 12.11.)
- Yleistä
  - Perjantai palaverin järjestys
    - Puheenjohtaja: Niklas
    - Sihteeri: Aki
