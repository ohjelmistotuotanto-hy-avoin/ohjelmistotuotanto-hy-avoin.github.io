---
layout: page
title: Miniprojekti
inheader: no
permalink: /miniprojekti/
---

## Miniprojekti

### Ajankohtaista

- Voit osallistua minprojektiin siinä vaiheessa kun olet palauttanut vähintään viikkojen 1-3 tehtävät
- Ensimmäinen mahdollisuus miniprojektin suoritukseen käynnistyy **maanantaina 22.2.**
  - Ilmoittautuminen alkaa **maanantaina 15.2.** ja päättyy **perjantaina 19.2. klo 23:59**
  - Ilmoittautuminen tapahtuu [ryhmäytymissovelluksessa](#) <!-- TODO: assembler linkki -->
- Miniprojektien asiakastapaamiset järjestetään virtuaalisesti [zoom](https://helpdesk.it.helsinki.fi/ohjeet/yhteydenpito-ja-julkaiseminen/videokokoukset/zoom)-järjestelmän avulla.
- Ohjaajaan Telegram-käyttäjätunnus on @kalleilv. Ohjaajaan voi ottaa suoraan yhteyttä mihin tahansa miniprojektiin liittyvissä kysymyksissä

### Johdanto

- Kurssin suorittaminen [6 opintopisteen](/osa0#kurssin-arvostelu) laajuisena edellyttää hyväksyttyä osallistumista miniprojektiin tai sen [hyväksilukemista](/osa0#miniprojektin-hyv%C3%A4ksilukeminen)
- Projekti tehdään noin 4-6 hengen ryhmissä
- Projektissa ohjelmoidaan jonkin verran, **pääpaino ei ole ohjelmoinnissa** vaan systemaattisen prosessin (tästä lisää myöhemmin) noudattamisessa.
- Projekti koostuu kolmesta viikon kestoisesta sprintistä
- **Jokaisen ryhmän jäsenen on tarkoitus tehdä kunkin sprintin aikana töitä noin 6 tuntia projektin eteen**
  - Asiakastapaamisiin menevää aikaa ei lasketa viikoittaiseen työaikaan!
- Ryhmä tekee kussakin sprintissä sen minkä se sprinttiin varatussa ajassa pystyy tekemään, ei enempää eikä vähempää
  - Kuuden tunnin työajan reilu ylittäminen siis **ei ole** järkevää, se on suorastaan kiellettyä
- Miniprojektin voi aloittaa kahtena ajankohtana:
  - Ensimmäinen mahdollisuus käynnistyy **maanantaina 22.2.**
  - Toinen mahdollisuus käynnistyy **maanantaina 29.3.**

### Ryhmän muodostaminen

- Ilmoittaudu miniprojektiin viimeistään **perjantaina 19.2. klo 23:59** [täällä](#) <!-- TODO: assembler linkki -->
- Ilmoittautumistietojen perusteella ryhmät muodotostetaan "algoritmisesti", pääasiassa noudattaen ilmoittautumisessa kerrottuja sopivia työskentelyaikoja
- Ryhmäsi aloitustilaisuuden ajankohta selviää ilmoittautumissovelluksesta. Kaikkien ryhmäläisten on **pakko osallistua** tilaisuuteen, jonka kesto on noin 2 tuntia
- Aloitustilaisuuteen tullessa on syytä tuntea materiaalin osien 1 ja 2 asioista ainakin seuraavat:
  - scrum
  - sprintti
  - user story
  - product backlog
  - sprint backlog
  - hyväksymäkriteeri
  - definition of done
- Tämä dokumentti ja miniprojektin [arvosteluperusteet](/miniprojektin_arvosteluperusteet) on myös syytä lukea huolellisesti ennen aloitustilaisuutta
- Ryhmä keksii itselleen nimen, luo Github-repositorion ja rekisteröi itsensä palautussovellukseen <{{site.stats_url}}>
  - **Yksi ryhmäläinen** kirjautuu järjestelmään, menee välilehdelle _miniprojects_
    - Luo projektin _create project_ -napista avautuvasta lomakkeesta
    - Ja jakaa muille ryhmäläisille luodun projektin id:n
  - **Muut ryhmäläiset** kirjautuvat järjestelmään ja liittyvät id:n avulla ryhmään _join project_ -napista avautuvasta lomakkeesta

### Työn eteneminen

Seuraavien viikkojen asiakastapaaminen (sprintin katselmointi ja uuden sprintin suunnittelu) tapahtuu samana viikon päivänä, saman kahden tunnin sisällä, missä aloitustilaisuus pidetään. Tilaisuuden kesto on 30 minuuttia. Tapaamisen tarkka aika ja sen zoom-linkki kerrotaan palautussovelluksen välilehdeltä [miniproject]({{site.stats_url}}/miniproject) viimeistään tapaamista edeltävänä sunnuntaina.

#### Viikko 8 (22-28.2.)

- Ryhmä muodostuvat/muodostetaan
- Ryhmät tapaavat asiakkaan aloitustilaisuuksissa
- Aloitustilaisuudessa pidettävän asiakastapaamisen pohjalta ryhmä tekee alustavan product backlogin ja sopii asiakkaan kanssa ensimmäisen sprintin tavoitteesta
- Ryhmä suunnittelee ensimmäisen sprintin ja aloittaa työskentelyn
  - sprintin suunnittelun tuloksena ryhmä tekee sprint backlogin
  - backlogien sisällöstä enemmän [täällä](/miniprojekti#tekniset-ja-prosessiin-liittyvät-vaatimukset)
- Sprintin 1 [arvosteluperusteet](/miniprojektin_arvosteluperusteet#ensimmäisen-sprintin-arvosteluperusteet) kannattaa lukea huolellisesti

#### Viikko 9 (1-7.3.)

- Sprintin 1 katselmointi ja sprintin 2 suunnittelu
  - Asiakastapaamisen aikataulu selviää palautussovelluksen välilehdeltä [miniproject]({{site.stats_url}}/miniproject)

#### Viikko 10 (8-14.3.)

- Sprintin 2 katselmointi ja sprintin 3 suunnittelu
  - Asiakastapaamisen aikataulu selviää palautussovelluksen välilehdeltä [miniproject]({{site.stats_url}}/miniproject)

#### Viikko 11 (15-21.3.)

- Sprintin 3 katselmointi (eli loppudemot)
  - Aikataulu ilmoitetaan myöhemmin
- Jokainen ryhmä osallistuu yhteen loppudemoon
- Varaa aika [täällä](#) <!-- TODO: linkki -->

### Toteutettava ohjelmisto

- [Aiheen kuvaus](/speksi)

### Tekniset ja prosessiin liittyvät vaatimukset

- Ryhmä laatii yhdessä asiakkaan kanssa _product backlogin_
  - Vaatimukset kirjataan backlogiin user story:inä
- Sprintin suunnittelun yhteydessä ryhmä sitoutuu toteuttamaan sopivan määrän backlogin kärjessä olevista user storyistä
  - Jokaisen ryhmäläisen "työaika" on 6 tuntia viikossa
    - Työajan ylittävä sankarikoodaus ei ole suositeltavaa, se on jopa kiellettyä
  - Ryhmä sitoutuu ainoastaan niihin storyihin, jotka se kuvittelee kykenevänsä toteuttamaan sprintissä **definition of donen** määrittelemällä laatutasolla. Definition of done on määritelty alla
  - Kannattaa huomata, että storyihin sitoutuminen ei tarkoita sitä, että ne on pakko tehdä valmiiksi. Ohjelmistoja tehdessä sattuu ja tapahtuu ennakoimattomia asioita, ja aina suunnitelmat eivät toteudu.
  - Asiakkaalle ei kannata luvata liikaa, ja varsinkin ensimmäisten sprinttien aikana arvioissa on otava varovainen, konfiguroimiseen, testaamiseen ja ryhmän järjestäytymiseen tulee kulumaan paljon aikaa
- Ryhmä ylläpitää _sprint backlogia_
  - User storyt jaetaan sprintin suunnittelussa teknisen tason tehtäviksi eli _taskeiksi_ jotka sijoitetaan sprint backlogiin
  - Ryhmä tekee päivittäin jäljellä olevan työajan arviointia ja dokumentoi tämän sprintin burndown-käyränä
  - Sprint backlogista tulee ilmetä kunkin taskin osalta
    - jäljellä olevan työajan estimaatti
    - taskin tila (esim. aloitettu, ohjelmoitu, testauksessa, valmis)
    - taskin tekijä(t)
- Ryhmä toteuttaa jatkuvaa integraatiota (continuous integration)
  - Oletusarvoisesti kannattaa käyttää laskareista 1 tuttua Github Actionsia, muita vaihtoehtoja esim. TravisCI
- Koodi on talletettu GitHub:iin
- Projektin GitHub-repositoriolla on järkevä README.md

#### Product ja sprint backlog

- Backlogissa vaatimukset ilmaistaan järkevästi muotoiltuna user storyinä
  - **Miniprojektissa ei ole tarvetta estimoida user storya**, ainoastaan sprintissä olevien taskien työmäärä estimoidaan
- Kuten edellä todettiin sprint backlogista tulee ilmetä kunkin taskin osalta
  - Jäljellä olevan työajan estimaatti
  - Taskin tila (esim. aloitettu, ohjelmoitu, testauksessa, valmis)
  - Taskin tekijä(t)
- Backlogit voi toteuttaa esim. Google Docs -spreadsheetinä, mallia voi ottaa seuraavista:
  - Erään ohtuprojektin [backlogit](https://docs.google.com/spreadsheets/d/13RzIZI2NFFuV0zdRjrrfoC-CrootK8AZNuHS571Wlxo/edit#gid=1)
  - <http://www.mountaingoatsoftware.com/scrum/sprint-backlog> (tämä on sikäli huono, että siitä eivät ilmene taskin tekijät)
- Backlogit voi tehdä Google Docsin sijaan myös johonkin backlogien ylläpitämiseen tarkoitettuun työkaluun
  - Kannattaa varmistaa, että työkalu kuitenkin tulee edellä lueteltuja vaatimuksia
  - Eesim. <https://trello.com> ei tue scrum-tyylisiä backlogeja oikeastaan ollenkaan, ja **Trelloa kannattaakin välttää tässä projektissa**

#### Definition of done

Seuraavassa lähtökohta definition donelle. Ryhmän tulee määritellä GitHub-repositorioon oma, omiin lähtökohtiin sopiva DoD

- User storyille tulee määritellä hyväksymiskriteerit, jotka dokumentoidaan [Cucumberin](/cucumber/) featureiksi
  - Hyvänä käytänteenä on laittaa README:stä linkki hyväksymäkriteerit määritteleviin tiedostoihin
- Toteutetun koodin testikattavuuden tulee olla kohtuullinen (esim. noin 70% muiden paitsi triviaalin koodin, kuten gettereiden/settereiden osalta)
- Asiakas pääsee näkemään koko ajan koodin ja testien tilanteen CI-palvelusta
- Koodin ylläpidettävyyden tulee olla mahdollisimman hyvä
  - Järkevä nimeäminen
  - Järkevä/selkeä ja perusteltu arkkitehtuuri
  - Yhtenäinen koodityyli

#### Repositorio ja README

README:ssa tulee löytyä ainakin seuraavat asiat:

- Linkit backlogeihin (backlogeista tulee olla luettavissa olevat versiot julkisessa internetissä)
- Linkki CI-palveluun
- Linkki sovelluksen toimivaan versioon (jos sovellus on verkossa)
- Jos kyse työpöytäsovelluksesta, tulee ohjelmalle olla asennus- ja käyttöohje
- Työlle tulee määritellä lisenssi <https://help.github.com/articles/licensing-a-repository/>

### Teknologisia vihjeitä

- Kokonaan uusien teknologioiden opettelu miniprojektin yhteydessä ei ole järkevää
- Komentoriviltä toimiva sovellus on teknologioiden suhteen riskittömin vaihtoehto ainakin Javaa käytettäessä
- Mahdollisten ulkoisten kirjastojen käyttöönotto, testien tekeminen ja CI:n konfigurointi tulee viemään ainakin alussa todella paljon aikaa
- Jos haluatte käyttää tietokantaa, on Tikapestakin tuttu _sqlite_ hyvä vaihtoehto
  - Tikapen laskareissa käytetyn todo-sovelluksen gradle-versio osoitteessa <https://github.com/ohjelmistotuotanto-hy/tikape-todo>
- Viikon 3 laskareista kannattaa ottaa mallia Cucumberilla tapahtuvaan storyjen testaamiseen
- JavaFX:llä tehtyjen sovellusten automatisoitu testaaminen on mahdollista [TestFX](https://github.com/TestFX/TestFX)-kirjaston avulla. Kirjaston dokumentaatio ei ole parhaasta päästä
  - yksinkertainen gradle+javaFX+cucumber+circle esimerkkikonfiguraatio osoitteessa <https://github.com/ohjelmistotuotanto-hy/fx-testing>
  - Java Swing-sovellusten Cucumberilla tapahtuva käyttöliittymätason testaus on täysi mysteeri
- Edellisinä vuosina on huomattu, että Java Springin konfigurointi (toimimaan yhdessä gradlen, cucumberin ja CircleCI:n kanssa) miniprojektille varatun ajan puitteissa on osoittautunut haastavaksi. Käyttäkää siis springiä omalla vastuulla
  - yksinkertainen gradle+spring+cucumber+circle esimerkkikonfiguraatio osoitteessa <https://github.com/ohjelmistotuotanto-hy/spring-cucumber>

### Työn arvostelu

Arvosteluperusteet löytyvät [täältä](/miniprojektin_arvosteluperusteet/)
