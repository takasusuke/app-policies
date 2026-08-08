# Tietosuojakäytäntö — Simple Timer

Viimeksi päivitetty: 3. elokuuta 2026

Tämä käytäntö voidaan tarjota useilla kielillä, mutta **japaninkielinen versio on sitova (virallinen) versio**. Jos tämän käännöksen ja japaninkielisen version välillä on ristiriita tai poikkeavuus, japaninkielinen versio on ratkaiseva.
[日本語版はこちら](../)

## 1. Johdanto

Simple Timer (jäljempänä "sovellus") on mobiilisovellus, joka tarjoaa ajastimen ja sekuntikellon. Tässä käytännössä selitetään, mitä tietoja sovelluksen käytöstä kerätään ja miten niitä käsitellään.

## 2. Sovelluksen keräämät tiedot

### Vain laitteellesi tallennettavat tiedot

Ajastimen asetukset ja teeman (vaalea/tumma) valinta tallennetaan vain laitteellesi. Näitä tietoja ei koskaan lähetetä ulkopuolelle, ja ne poistetaan, kun poistat sovelluksen asennuksen.

Sovellus ei kerää mitään henkilöä tunnistavia tietoja, kuten nimeäsi, sähköpostiosoitettasi, puhelinnumeroasi tai osoitettasi. Tilin rekisteröintiä ei vaadita.

### Kolmannen osapuolen keräämät tiedot mainostarkoituksiin (Google AdMob)

Sovellus näyttää mainoksia Google AdMobin kautta. AdMob voi Googlen puolesta kerätä ja käsitellä seuraavia tietoja mainosten toimittamista ja petosten estämistä varten:

- Mainostunnisteet (IDFA iOS:ssä, mainostunniste Androidissa)
- Tiedot mainosnäytöistä ja -klikkauksista
- IP-osoitteesta pääteltävä likimääräinen sijainti
- Tekniset tiedot, kuten laitetyyppi ja käyttöjärjestelmän versio

Näitä tietoja käsitellään Googlen oman tietosuojakäytännön mukaisesti. Sovelluksen kehittäjä ei hanki eikä säilytä näitä tietoja erikseen.

**Seurannasta iOS:ssä**: Sovellus ei pyydä App Tracking Transparency -lupaa. Näin ollen IDFA:ta ei käytetä seuraamaan sinua muiden yritysten sovelluksissa tai verkkosivustoilla.

## 3. Mitä sovellus ei käytä

Seuraavat osat sisältyvät sovelluksen koontiversioon, mutta ne **on poistettu käytöstä nykyisessä versiossa eivätkä kerää mitään tietoja**:

- Firebase Analytics / Crashlytics — ei alusteta, koska määrityksiä ei ole toimitettu
- Sovelluksen sisäiset ostokset (RevenueCat) — ei käytössä

Tätä käytäntöä päivitetään ennen kuin jompikumpi näistä osista otetaan käyttöön.

## 4. Tietojen käyttötarkoitus

Kerättyjä tietoja käyttää Google yksinomaan mainosten toimittamiseen ja petosten estämiseen. Kehittäjä ei käytä näitä tietoja käyttöanalyysiin tai muihin tarkoituksiin kuin mainontaan.

## 5. Tietojen luovuttaminen kolmansille osapuolille

Yllä mainittuja tietoja käsittelee Google kunkin palvelunsa oman tietosuojakäytännön mukaisesti.

- [Googlen tietosuojakäytäntö](https://policies.google.com/privacy)
- [Googlen mainoskäytännöt](https://policies.google.com/technologies/ads)

Tietoja ei luovuteta muille kolmansille osapuolille kuin edellä mainituille.

## 6. Lasten yksityisyys

Sovellus ei ole suunnattu alle 13-vuotiaille lapsille. Emme kerää tietoisesti tietoja alle 13-vuotiailta lapsilta.

## 7. Miten rajoittaa mainosten personointia

- **iOS**: Asetukset → Tietosuoja ja turvallisuus → Applen mainokset → poista käytöstä "Kohdennetut mainokset"
- **Android**: Asetukset → Google → Mainokset → "Poista mainostunniste"

## 8. Muutokset tähän käytäntöön

Jos tätä käytäntöä muutetaan, tämä sivu päivitetään ja viimeisimmän päivityksen päivämäärää tarkistetaan. Merkittävistä muutoksista ilmoitetaan myös sovelluksen sisällä.

## 9. Yhteystiedot

Jos sinulla on kysyttävää tästä käytännöstä, ota yhteyttä alla olevaan osoitteeseen:

Yhteystiedot: gendaijin44435@gmail.com
