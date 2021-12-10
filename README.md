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
| [Aki Sartolahti](https://github.com/donqnr)    | Backend devaaja (Python, Flask, Mongodb)     | 🟦     |
| [Boris Hiltunen](https://github.com/BorisHiltunen)   | Backend devaaja (Python, Flask)       | 🟦      |
| [Sanjiv Rana](https://github.com/eync)   | Opettaja / Projektin asiakas       | 🟢  🟦      |
#### :necktie: Tiimin entiset jäsenet
| Nimi        | Rooli       | Ryhmä       |
| ----------- | ----------- | ----------- |
| [Niklas Larsson](https://github.com/nikkelarsson)    | Backend devaaja (Python, Flask, Mongodb)     | 🟦     |
| [Jouni Heikkinen](https://github.com/heikjou)    | UI-suunnittelija & Frontend (HTML, CSS & Javascript)     | 🟢     |

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

- Back-end
    - Tietokannan luominen (esim. omille koneille paikallisesti, jotta voi testailla turvallisesti)
        - MongoDB tunnusten luominen (Niklas)
        - Interfacen luominen tietokannan kanssa vuorovaikuttamiseen (Niklas) -> Tälle oma branch
        - Collection -objekti, joka pitäisi sisällään työpäivät:
            - Kalenteri merkinnät yms.    
    - API endpointtien "skeletonien" rakentaminen (Aki) -> Tällä oma branch

- Front-end / UI
    - Toiminnallisuuden suunnitteleminen ja/tai toteuttaminen
        - Kalenterimerkintöjen kanssa vuorovaikuttaminen (merkintöjen lisääminen, avaaminen yms.)

### 🥅 Tavoitteet (15.11. - 19.11.)
- Yleistä
  - Puheenjohtaja: Aki
  - Sihteeri: Jouni

- Back-end
   - Kalenterimerkinnän lisäämis-endpointin toiminallisuuden toteuttaminen
   - Tietokannan käyttöliittymän metodien toetuttaminen
      - Kalenterimerkinnän muokkaus
      - Kalenterimerkinnän haku
      - Kalenterimerkinnän poistaminen
   - Jos ehtii, niin muiden endpointtien toiminallisuuden toteuttaminen

- Front-end / UI
  - UI
    - Tämänhetkinen aika- indikaattorin suunnittelu
  - Front-end
    - Layoutin toteutus HTML ja CSS:llä
  

### 🥅 Tavoitteet (22.11. - 26.11.)
- Yleistä
  - Puheenjohtaja: Jouni
  - Sihteeri: Niklas

- Back-end
   - 🔄 Kalenterimerkinnän lisäämis-endpointin toiminallisuuden toteuttaminen jatkuu
   - 🔄 Tietokannan käyttöliittymän metodien toetuttaminen jatkuu
      - Kalenterimerkinnän muokkaus
      - Kalenterimerkinnän haku
      - Kalenterimerkinnän poistaminen
   - 🔄 Jos ehtii, niin muiden endpointtien toiminallisuuden toteuttaminen
   - ✅ Tietokannan rakenne backendin readme tiedostoon json muodossa tyyppien kanssa
   - ✅ Kanban-taulukon läpikäynti maanantaina
   - ✅ Niklas ajaa Akin sisään omiin koodeihinsa
   - ✅ Mahdollinen Niklaksen branchin pull requestin tekeminen

- Front-end
  - ✅ UI
    - Kalenterimerkintöjen hallinta suunnittelu
  - ✅ Front-end
    - Layoutin toteutus HTML, CSS ja Javascriptillä jatkuu

### 🥅 Tavoitteet tulevaisuudelle
- Yleistä
  - Front-end jää tauolle toistaiseksi (26.11.2021 ->)
  - Aki jatkaa siitä, mihin **niklas/feature/add_database_interface** -branchin työstö jäi
    - ✅ Niklas tekee pull-requestin edellämainitusta branchista main -branchiin
    - ✅ Aki tarkistaa pull-requestin ja mergeää tämän main -branchiin
    - 🔄 **niklas/feature/add_database_interface** -branch voidaan poistaa ja Aki voi luoda uuden branchin ja jatkaa työstöä siinä
  - ✅ Backendin readme:hin tekijöiden nimet (esim readme:n loppuun) ja linkit tekijöiden profiileihin näistä nimistä

### 🥅 Tavoitteet (7.12. - 10.12.)
- Yleistä
  - Puheenjohtaja: Aki 
  - Sihteeri: Boris

- Back-end
   - 🔄Kalenterimerkinnän lisäämis-endpointin toiminallisuuden toteuttaminen jatkuu
     - �Interface -> Datasettiä muutetaan niin että "Entries" muuttuu "Array Objektiksi" jolloin voidaan hyödyntää `$push` operaattoria. 
     - �https://docs.mongodb.com/manual/reference/operator/update/push/#examples
   - 🔄Tietokannan käyttöliittymän metodien toteuttaminen jatkuu
      - Kalenterimerkinnän muokkaus
      - Kalenterimerkinnän haku
      - Kalenterimerkinnän poistaminen
   - 🔄Jos ehtii, niin muiden endpointtien toiminallisuuden toteuttaminen
   - 🔄Tietokannan rakenne backendin readme tiedostoon json muodossa tyyppien kanssa
     - Lisätään uudet muutokset 
   - 🔄Kanban-taulukon läpikäynti maanantaina

### 🥅 Tavoitteet (13.12. - 17.12.)
- Yleistä
  - Puheenjohtaja: Boris
  - Sihteeri: Aki

- Back-end
   - Kalenterimerkinnän lisäämis-endpointin toiminallisuuden toteuttaminen jatkuu
     - Interface -> Datasettiä muutetaan niin että "Entries" muuttuu "Array Objektiksi" jolloin voidaan hyödyntää `$push` operaattoria. 
     - https://docs.mongodb.com/manual/reference/operator/update/push/#examples
   - Tietokannan käyttöliittymän metodien toteuttaminen jatkuu
      - Kalenterimerkinnän muokkaus
      - Kalenterimerkinnän haku
      - Kalenterimerkinnän poistaminen
   - Jos ehtii, niin muiden endpointtien toiminallisuuden toteuttaminen
   - Tietokannan rakenne backendin readme tiedostoon json muodossa tyyppien kanssa
     - Lisätään uudet muutokset 
   - Kanban-taulukon läpikäynti maanantaina
   - Tietokanta ongelman ratkaiseminen
     - set -> push

