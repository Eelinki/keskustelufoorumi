# keskustelufoorumi

Keskustelufoorumilla ylläpitäjät voivat luoda, muokata sekä poistaa lautoja. Käyttäjät voivat aloittaa keskusteluita laudoilla määrittämällä aiheen. Keskustelufoorumia voidaan käyttää esimerkiksi yhteisön tai ryhmän kesken.

Sovellusta voi kokeilla osoitteessa https://stark-ocean-77286.herokuapp.com/.

Käyttäjätunnus: `test`

Salasana: `salis123`

## Dokumentaatio

* [Käyttötapaukset](documentation/user_stories.md)
* [Tietokantakaavio ja SQL-schema](documentation/db_diagram.md)
* [Käyttöohjeet](documentation/user_guide.md)
* [Jatkokehitys](documentation/further_development.md)

## Asennusohje

Ota virtualenv käyttöön

```
python -m venv venv
```

Asenna tarvittavat kirjastot komennolla

```
pip install -r requirements.txt
```

Käynnistä palvelin

```
python ./run.py
```

### Ajaaksesi sovellusta Herokussa

```
heroku create
git push heroku master
```