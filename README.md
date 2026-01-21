# Yle.fi Testing Suite

Kattava testausohjelma Yle.fi-nettisivuston toiminnallisuuden, suorituskyvyn ja interaktiivisuuden testaamiseen.

## Ominaisuudet

### 📋 Perus Testit (HTTP-pyynnöt)
- Sivuston saavutettavuuden tarkistus
- Sivun latausajan mittaus
- HTML-sisällön analyysi (otsikot, linkit, kuvat)
- Meta-tietojen tarkistus
- Sivun kuvauksen lukeminen

### 🤖 Selenium Testit (Interaktiiviset)
- Chrome-selaimen automaattinen avaaminen
- Sivuston lataus selaimessa
- Sivun otsikon ja linkkien tarkistus
- Artikkelien etsiminen
- JavaScript-virheiden konsoli-analyysi
- Automaattinen screenshot-kuvan ottaminen
- Selaimen dimensioiden mittaus

### ⚡ Suorituskyky Testit
- Useita peräkkäisiä latauksia
- Keskiarvo-, minimi- ja maksimiaikojen laskeminen
- Sivun koon mittaus megatavuissa

## Vaatimukset

- Python 3.7+
- requests
- beautifulsoup4
- selenium
- webdriver-manager

## Asennus

```bash
pip install requests beautifulsoup4 selenium webdriver-manager
```

## Käyttö

```bash
python test_yle.py
```

Ohjelma kysyy, haluatko suorittaa Selenium-testit (ne avaa selaimen ja kestävät pidempään).

## Tulokset

Ohjelma tulostaa yksityiskohtaisen raportin:
- ✓ Onnistuneet testit
- ✗ Epäonnistuneet testit
- Latausajat ja suorituskykytiedot
- Screenshot tallennetaan yle_screenshot.png-tiedostoksi

## Tekijä

Pyrykivil
