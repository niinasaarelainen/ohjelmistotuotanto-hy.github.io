---
layout: page
title: tehtävät
inheader: yes
permalink: /tehtävät/
---

# tehtävät ja deadlinet

Deadlinet ovat aina merkittynä päivänä kello 23:59. Tehtävät kannattaa kuitenkin palauttaa hyvissä ajoin, jotta välttyy yllättäviltä ongelmilta.

| Viikko    | Deadline |
| --------- | --------:|
| [Viikko 1](#viikko-1)  | 1.12     |
| [Viikko 2](#viikko-2)  | 2.12     |
| [Viikko 3](#viikko-3)  | 3.12     |
| [Viikko 4](#viikko-4)  | 4.12     |
| [Viikko 5](#viikko-5)  | 5.12     |
| [Viikko 6](#viikko-6)  | 6.12     |
| [Viikko 7](#viikko-7)  | 7.12     |

## Suositeltavat ja vapaaehtoiset tehtävät, tehtävien vaikuttaminen arvosteluun

Osa tehtävistä on seuraavaan osaan etenemisen kannalta suositeltavia ja osa vapaaehtoisia. Vapaaehtoiset on merkattu tähdellä. 

Voit toki jättää tähdellä merkkaamattomiakin tehtäviä tekemättä, mutta niiden tekemättä jättäminen saattaa aiheuttaa haasteita seuraaviin osiin. Huomaa myös, että kaikkien osien 0-3 tähdellä merkkaamattomien tehtävien tekeminen on edellytyksenä 3 opintopisteen laajuiseen suoritukseen.

Arvosana ja opintopistemäärä lasketaan _kaikkien_ tehtävien summan perusteella. Katso tarkemmin osan 0 luvut [suoritustapa](/osa0#suoritustapa) ja [arvosteluperusteet](/osa0#arvosteluperusteet). 

## Palauttaminen

Olethan lukenut huolellisesti kurssimateriaalin osan 0 luvun [Suoritustapa](/osa0/#Suoritustapa)?

Tehtävät palautetaan GitHubin kautta ja merkitsemällä tehdyt tehtävät [palautussovellukseen](https://studies.cs.helsinki.fi/fullstackopen/).

Jos palautat eri osien tehtäviä samaan repositorioon, käytä järkevää hakemistojen nimentää.

Tehtävät palautetaan yksi osa kerrallaan. **Kun olet palauttanut osan tehtävät, et voi enää palauttaa saman osan tekemättä jättämiäsi tehtäviä.**

GitHubiin palautettuja tehtäviä tarkastetaan [MOSS](https://theory.stanford.edu/~aiken/moss/)-plagiaattitunnistusjärjestelmän avulla. Jos GitHubista löytyy kurssin mallivastausten koodia tai useammalta opiskelijalta löytyy samaa koodia, käsitellään tilanne yliopiston [vilppikäytäntöjen](http://blogs.helsinki.fi/alakopsaa/opettajalle/epailen-opiskelijaa-vilpista-mita-tehda/) mukaan.

Suurin osa tehtävistä on moniosaisia, samaa ohjelmaa pala palalta rakentavia kokonaisuuksia. Tälläisissä tehtäväsarjoissa ohjelman lopullisen version palauttaminen riittää, voit toki halutessasi tehdä commitin jokaisen tehtävän jälkeisestä tilanteesta, mutta se ei ole välttämätöntä.

## Viikko 1

### 1 komentorivi

Graafisten käyttöliittymien olemassaolosta huolimatta ohjelmistoalalla on edelleen erittäin tärkeää hallita komentorivin eli terminaalin käyttö. Itse asiassa komentorivin merkitys on jopa nousussa. 

Varmista, että osaat käyttää "riittävästi" komentoriviä (ks. alla oleva lista). 

Jos osaamisessasi on puutteita (ks alla oleva lista) kertaa haluamastasi resurssista:
https://www.codecademy.com/learn/learn-the-command-line online-kurssin kaksi ensimmäistä osaa _Navigating the File System_ ja _Viewing and Changing the File System_

https://ryanstutorials.net/linuxtutorial/ oppaasta 4 osaa _1. The Command Line_, _2. Basic Navigation_, _ 3.More About Files_ ja _5. File Manipulation_

Myös kurssin Tietokone työvälineenä tämän syksyn [komentorivimateriaali](https://tkt-lapio.github.io/command-line/) käsittelee myös suurta osaa tehtävän komennoista.

*HUOM. Codecademy vaatii kirjautumisen Facebook, Google tai GitHub -tunnuksella. Kurssilla käytetään muutenkin GitHubia, niin se tunnus pitäisi kaikilla vähintään olla olemassa, jotta pääsee kirjautumaan.*

Tämän tehtävän jälkeen sinun tulisi hallita seuraavat asiat:
* käsitteet
  * root directory
  * home directory
  * parent directory
  * child directory
  * working directory
  * .. ja *
* ja osata käyttää komentoja
  * pwd
  * cd
  * ls, ls -a, ls -l, ls -t
  * mkdir
  * touch
  * cp
  * rm, rm -r
  * mv

Tulet tarvitsemaan komentorivin käyttötaitoja tällä kurssilla ja muutenkin opinnoissasi.

Tehtävää ei palauteta mitenkään. Voit merkitä tehtävän tehdyksi kun osaat yllä luetellut asiat.

### 2 Githubiin [versionhallinta]

Jos sinulla ei jostain syystä ole vielä tunnusta [GitHubiin](https://github.com), luo se nyt.

Luo githubiin repositorio nimellä ohtu-viikko1 

* klikkaa yläpalkin oikeassa reunassa olevaa  "Create a new repo"-ikonia 
* **laita rasti** kohtaan Initialize this repository with a README 

![README-tiedoston alustusrasti](https://github.com/mluukkai/ohtu2017/raw/master/images/lh1-1.png)

Jos et ole vielä luonut koneellesi _ssh-avainta_, tee se nyt

* Ohje avaimen luomiseen esim. [täällä](https://www.howtoforge.com/linux-basics-how-to-install-ssh-keys-on-the-shell) riittää että teet stepit 1 ja 2 tai viime kevään [OTM](https://github.com/mluukkai/Ohjelmistotekniikka2018/blob/master/tehtavat/viikko1.md#julkinen-avain)-materiaalista

Lisää julkinen avain githubiin:

* https://github.com/settings/ssh

Näin pystyt käyttämään GitHubia ilman salasanan syöttämistä koneelta, josta juuri luodun avaimen salainen pari löytyy

Jos et ole jo aiemmin niin tehnyt, konfiguroi nimesi ja email-osoitteesi paikallisen koneesi git:iin antamalla komennot:

    git config --global user.name "Your Name"
    git config --global user.email my.address@gmail.com

Oletuseditoriksi kannattaa Linuxilla ja OSX:lla (eli Macillä) konfiguroida _nano_

    git config --global core.editor nano
    
ja Windowsilla  _notepad_

    git config --global core.editor notepad    

Tosin jos olet vimin käyttäjä, voit jättää edellisen tekemättä.

Kloonaa nyt githubiin tehty repositorio **paikalliselle koneelle**. Tämä tapahtuu antamalla komentoriviltä komento

    git clone git@github.com:omatunnustahan/ohtu-viikko1.git

missä komennon <code>git clone</code> parametrina on repositoriosi sivulta selviävä 'clone URL' (huomaa, että formaatin on oltava SSH):

![ssh-kloonausurlin sijainti](https://github.com/mluukkai/ohtu2017/raw/master/images/lh1-2.png)

Nyt paikalliselle koneellesi syntynyt hakemisto <code>ohtu-viikko1</code>, joka on on githubissa olevan repositorion klooni.

### 3 Gitin alkeet [versionhallinta]

Olet jo todennäköisesti käyttänyt Gitiä aiemmilla kursseilla. Tässä tehtävässä harjoitellaan seuraavia komentoja:

* git add
* git commit
* git status
* git checkout -- file
* git reset HEAD
* .gitignore

* Jos et vielä hallitse komentoja, käy läpi kevään 2018 OTM:n [Git-tutoriaali](https://github.com/mluukkai/Ohjelmistotekniikka2018/blob/master/tehtavat/viikko1.md#gitin-alkeet) Pelkän lukemisen sijaan kannattanee myös tehdä itse tutoriaalin git-operaatiot.

Lisää git-ohjeita löytyy runsaasti internetistä, esim:
  * [Pro Git -opas](http://git-scm.com/book), kannattaa lukea näin alkuun luku 2
  * [Githubin helpit](https://help.github.com/articles/)
  * <https://www.atlassian.com/git/tutorials>
  * <https://we.riseup.net/debian/git-development-howto>
  * <http://www.ralfebert.de/tutorials/git/>


**tee nyt seuraavat:**

* mene edellisessä tehtävässä luotuun repositorion klooniin (eli komennon <code>git clone</code> luomaan hakemistoon)
* lisää ja committaa repositorioon kaksi tiedostoa ja kaksi hakemistoa, joiden sisällä on tiedostoja
  * muista hyödyllinen komento git status
* muuta ainakin kahden tiedoston sisältöä ja committaa muutokset repositorioon
* tee .gitignore-tiedosto, jossa määrittelet, että repositorion juurihakemistossa olevat tiedostot, joiden pääte on _tmp_ ja hakemisto jonka nimi on _build_ ignoroidaan
  * huomaa, että ainoastaan hakemisto nimeltä _build_ pitää ignoroida, tiedostot joiden nimi alkaa sanalla build, esim tehtävässä 7 lisättävä _build.gradle_ eivät saa ignoroitua!
* lisää tmp-päätteisiä tiedostoja hakemistoon ja varmista että git jättää ne huomioimatta
  * saat asian tarkastettua komennolla _git status_
* lisää myös hakemisto nimeltä _build_  ja hakemiston sisälle joku tiedosto. Varmista että build sisältöineen ei mene versionhallinnan alaisuuteen
* lisää ja commitoi .gitignore repositorioosi
* tee muutos johonkin tiedostoon. Älä lisää tiedostoa "staging"-alueelle
  * peru muutos (git status -komento antaa vihjeen miten tämä tapahtuu)
* tee muutos ja lisää tiedosto "staging"-alueelle
  * peru muutos (git status -komento antaa vihjeen miten tämä tapahtuu)

**git add -p**

* tutoriaaleissa ei valitettavasti käytetä git add -komennon hyödyllistä muotoa <code>git add -p</code> 
* tee muutoksia muutamiin tiedostoihin ja lisää muutokset staging-alueelle komennon git add -p avulla
* jos lisäät projektiin uusia tiedostoja, ei git add -p huomaa niitä, eli ne on lisättävä staging-alueelle erikseen 
* _käytä jatkossa komentoa git add -p aina kun se on suinkin mahdollista!_

komennolla man git add saat lisätietoa optiosta ja mm. vastausvaihtoehtojen selitykset. 

### 4 Tiedostojen lisääminen GitHubiin [versionhallinta]

Tehtävässä 2 tehtiin GitHubiin repositorio, joka liitettiin paikalliselle koneelle luotuun repositorioon "remote repositoryksi". Synkronoidaan paikallisen repositorion ja githubin tilanne:

* "pushaa" nämä GitHubissa olevaan etärepositorioon antamalla komento <code>git push</code>
* varmista selaimella, että lisätyt tiedostot menevät GitHubiin


### 5 Monta kloonia samasta repositoriosta [versionhallinta]

Yleensä on tapana pitää GitHubissa olevaa repositorioa tiedostojen "keskitettynä" sijoituspaikkana ja liittää paikallisella koneella oleva repositorio GitHubissa olevan repositorion etärepositorioksi, kuten teimme tehtävässä 1. 

Jos työskennellään useammalta koneelta, on githubissa olevasta repositoriosta monta kloonia ja kloonien tila on pidettävä ajantasalla.

Luodaan nyt harjoituksen vuoksi paikalliselle koneelle repositoriosta toinen klooni:

* mene komentoriville ja esim. kotihakemistoosi  (tai johonkin paikkaan, joka ei ole git-repositorio) 
* anna komento `git clone git@github.com:githubtunnus/repositorionNimi.git nimiKloonille`
  * githubtunnus ja repositorionNimi selviävät  GitHubista repositoriosi tehtävän 2 toisen kuvan osoittamasta paikasta
  * *nimiKloonille* tulee olemaan kloonatun repositorion nimi, varmista että annat nimen, jonka nimistä tiedostoa tai hakemistoa ei jo ole kansiossa
* mene kloonattuun repositorioon ja lisää sinne jotain tiedostoja. Committaa lopuksi
* "pushaa" muutokset GitHubiin
* varmista selaimella, että lisätyt tiedostot menevät GitHubiin

**Mene nyt tehtävässä 1 tehtyyn GitHub-repositorion klooniin.**

* alkuperäinen paikallinen klooni ei ole enää ajantasalla, "pullaa" sinne muutokset komennolla <code>git pull</code>
* varmista että molempien paikallisten repositorioiden sisältö on nyt sama
* lisää alkuperäiseen kopioon joitain tiedostoja ja pushaa ne GitHubiin
* mene jälleen kloonattuun kopioon ja pullaa

### 6 Repositorion siivous [versionhallinta]

Valmistaudutaan seuraavaan tehtävään siivoamalla repositoriostamme ylimääräiset tiedostot

* mene repositoriosi alkuperäiseen, tehtävässä 2 tekemääsi klooniin
  * voit poistaa tehtävää 5 varten tekemäsi harjoituskloonin
* poista repositorioistasi kaikki hakemistot sekä muut tiedostot paitsi _.gitignore_ ja _README.md_  
* committaa muutokset 
  * varmista komennolla _git status_ että kaikki muutokset ovat versionhallinnassa, eli että git ei ilmoita joidenkin tiedostojen olevan _Changes not staged for commit_ 
  * joudut ehkä kertaamaan tehtävän 3 linkittämistä tutoriaaleista sitä miten tiedostojen poistaminen gitistä tapahtuu
* pushaa muutokset githubiin katso selaimella, että GitHubissa kaikki on ajan tasalla, eli että repositiossa ei ole mitään muuta kuin tiedostot _.gitignore_ ja _README.md_ 

Haetaan sitten seuraavissa tehtävissä käytettävä koodi

* hae osoitteesta https://github.com/mluukkai/ohjelmistotuotanto2018/blob/master/koodi/ohtuvarasto.zip?raw=true löytyvä zipattu paketti
* pura paketti sopivaan paikkaan 
* siirrä paketin sisällä olevat tiedostot kloonattuun repositorioon siten, että **paketissa olevat tiedostot ja hakemistot tulevat repositorion juureen**

* repositoriosi sisältävän hakemiston tulee nyt näyttää seuraavalta

![](https://github.com/mluukkai/ohjelmistotuotanto2017/raw/master/images/lh1-3a.png)

* lisää ja committoi zipistä puretut tavarat repositorioosi ja pushaa ne githubiin
* katso vielä kerran selaimella, että GitHubissa kaikki on ajan tasalla

**Huomaa, että repositoriosi tulee näyttää tehtävän jälkeen suunnilleen seuraavalta:**

![]({{ "/images/ex-1-3.png" | absolute_url }})

**Jos hakemisto _src_ ja tiedostot _build.gradle_ ym. eivät ole repositorion juuressa, siirrä ne sinne ennen kuin siirryt eteenpäin.**

### 7 Gradle

[Gradlen](https://gradle.org) GitHub-repositorio sisältää seuraavan kuvauksen 

> Gradle is a build tool with a focus on build automation and support for multi-language development. If you are building, testing, publishing, and deploying software on any platform, Gradle offers a flexible model that can support the entire development lifecycle from compiling and packaging code to publishing web sites. Gradle has been designed to support build automation across multiple languages and platforms including Java, Scala, Android, C/C++, and Groovy, and is closely integrated with development tools and continuous integration servers including Eclipse, IntelliJ, and Jenkins.

Olet todennäköisesti käyttänyt aiemmilla kursseilla "buildaustyökaluna" mavenia. Gradle on uuden generaation buildaustyökalu, jonka on tarkoitus korvata maven. Gradle toimii pitkälti samojen periaatteiden mukaan kuin maven, mutta on kuitenkin huomattavasti helpommin konfiguroitavissa ja myös nopeampi kuin edeltäjänsä. Maven on vielä erittäin laajalti käytössä, mutta valtaosassa uusista projekteista käytetään nykyään gradlea. Gradle on myös oletusarvoinen buildinhallintatyökalu Android-sovelluskehityksessä. 

* edellisessä tehtävässä lisättiin repositorioon gradle-muodossa oleva projekti, joka sisältää aikoinaan [ohjelmoinnin perusteissa](http://www.cs.helsinki.fi/u/wikla/ohjelmointi/materiaali/02_oliot/#15) olleen luokan <code>Varasto</code>, sen käyttöä demonstroivan pääohjelman ja muutaman JUnit-testin
* tutki gradle-muotoisen projektin hakemistorakennetta esim. antamalla komento <code>tree</code> projektin sisältävän hakemiston juuressa (_tree_ ei ole gradleen liittyvä käsky vaan normaali shell-komento)
  * Windowsissa komennosta käyttökelpoisin muoto on <code>tree /F</code>
  * Jos käytössäsi on Windowsissa _git bash_ komento on muotoa <code>cmd //c tree</code>
  * HUOM: OSX:ssä ei ole oletusarvoisesti tree-komentoa
  * mikäli koneellasi on [HomeBrew](http://mxcl.github.com/homebrew/) asennettuna, saat tree:n asennettua <code>brew install tree</code>
  * myöskään kaikissa linuxeissa ei komento _tree_ ole  oletusarvoisesti asennettu. debian-pohjaisissa linuxeissa (esim ubuntussa) saat asennettua tree:n komennolla <code>sudo apt-get install tree</code>
* tarkastele projektin määrittelevän tiedoston _build.gradle_ sisältöä
  * tiedosto määrittelee mm. pääohjelman sijainnin `mainClassName = 'ohtu.ohtuvarasto.Main'`  

**avaa edellisen tehtävän projekti suosikki-idelläsi**

* Huomaa, että NetBeans ei tue oletusarvoisesti Gradlea, ja joudut asentamaan gradle-pluginin valitsemalla _tools -> plugins -> available plugins_
* HUOM: jos et ole aiemmin kääntänyt koneellasi gradle-muotoisia projekteja, saattaa IDE valittaa tässä vaiheessa joidenkin kirjastojen (mm. JUnit) puuttumisesta. Asia korjaantuu "buildaamalla" tai kääntämällä projekti komentoriviltä (ohjeet alla) 

Ohjelmakoodin editointi kannattaa tehdä IDE:llä kuten usein myös ohjelman ja testien ajaminenkin, mutta **gradlea kannattaa kuitenkin ehdottomasti totutella käyttämään myös komentoriviltä.** 

**Kokeillaan nyt gradlen käyttöä komentoriviltä:**
 
Gradle on siinä mielessä mielenkiintoinen työkalu, että sitä ei ole pakko asentaa ennen käytön aloittamista. Gradle-projektit sisältävät skriptit _gradlew_ (Linuxille) ja _gradlew.bat_ (Windowsille), jotka osaavat tarvittaessa asentaa Gradlen koneellesi.
* **HUOM** OSX:llä (eli Macilla) automaattinen asentuminen ei ole ainakaan kaikilla toiminut. Eli OSX-käyttäjien kannattaa aloittaa asentamalla _gradle_ [homebrew:illa](https://gradle.org/install#with-homebrew). Jos et jo käytä [homebrewia](https://brew.sh), kannattaa aloittaa nyt.
* **HUOM2** Linuxillakaan automaattinen asentuminen ei ole ainakaan kaikilla toiminut. Automaattinen asennus on toiminut ainakin vuoden 2016 Linux -fuksiläppärissä SDKMAN!:lla (SDKMANin asennus: `$ curl -s "https://get.sdkman.io" | bash`) [tämän](https://gradle.org/install#with-a-package-manager) ohjeen mukaan. Asennus Linuxiin manuaalisesti voidaan tehdä [tämän](https://gradle.org/install#manually) ohjeen mukaan. **ÄLÄ** asenna gradlea apt-get:illä, sillä paketinhallinnasta asentuu todella vanha versio.

Suorita projektin juuressa (eli samassa hakemistossa missä tiedosto _build.gradle_ sijaitsee) komento <code>./gradlew build</code> (Linux) <code>gradlew.bat build</code> (Windows). Gradle asentuu koneellesi. 

Jos komento ei päädy ilmoitukseen _BUILD SUCCESSFUL_ on todennäköisesti Javan konfiguraatiossa jotain häikkää. Koneellasi tulee olla _Java Development Kit_ (eli JDK) asennettuna ja ympäristömuuttuja *JAVA_HOME* tulee olla asetettu siten, että sen arvona on JDK:n sijainti, ks. esim. <http://www.robertsindall.co.uk/blog/setting-java-home-variable-in-windows/>. JAVA_PATH:in asettamisen jälkeen komentorivi tulee käynnistää uudelleen. 

Jos saat JDK:n asennuksesta ja *JAVA_HOME*:n asettamisesta ja komentorivin uudelleenkäynnistämisestä  huolimatta virheen _Could not find tools.jar_,
tee projektiisi tiedosto _gradle.properties_ ja määrittele sinne JDK:n sijainti seuraavaan tyyliin (polun kohdalle siis tulee oman koneesi JDK:n polku):

<pre>
org.gradle.java.home=C:\\Program Files\\Java\\jdk1.8.0_45
</pre>

Lisää tiedostoon _.gitignore_ rivi 

<pre>
gradle.properties
</pre>

Emme halua laittaa määrittelyä versionhallintaan asti, sillä kyseessä on konekohtainen asetus.

Jos jouduit tekemään tämän ratkaisun, on todennäköistä, että joudut toimimaan samoin jatkossa kaikkien gradle-projektien kohdalla.

Kun komento <code>./gradlew build</code> (Linux, OSX) tai <code>gradlew.bat build</code> (Windows) toimii, olet valmis siirtymään seuraavaan kohtaan.

**HUOM:** voit jatkossa (eli kun gradle on asentunut koneelle) käyttää kumpaa tahansa komentoa <code>gradle</code> tai <code>./gradlew</code>. Joissain windowseissa ja Linuxeissa on tosin havaittu että vain <code>./gradlew</code> toimii.
* jos gradle on asennettu koneelle komento <code>./gradlew</code> kutsuu komentoa <code>gradle</code>

* aloita nyt puhtaalta pöydältä komennolla <code>gradle clean</code>
  * käytä siis komennosta muotoa <code>./gradlew</code> jos <code>gradle</code> ei toimi
* tee juuressa komento <code>tree</code>
* käännä koodi: <code>gradle build</code>
  * tee jälleen juuressa komento tree. Mitä muutoksia huomaat?
* suorita pääohjelma komennolla <code>gradle run</code>
* tee <code>gradle clean</code>
  * suorita cleanin jälkeen tree-komento. Mitä clean tekee?
* aja testit komennolla <code>gradle test</code>
  * suorita jälleen komento <code>tree</code>
  * huomaat, että testien ajaminen luo hakemiston _build/reports/tests/test_. Testien diagnostiikka tulee tähän hakemistoon
* avaa selaimella testien tuloksen raportoiva tiedosto _build/reports/tests/test/index.html_

Tehdään seuraavaksi projektista [jar](https://en.wikipedia.org/wiki/JAR_(file_format))-tiedosto, joka paketoi projektin käännetyn koodin yhdeksi tiedostoksi, joka voidaan suorittaa millä tahansa koneella, mille on asennettu java.

* Lisää tiedostoon _build.gradle_ seuraava:

```groovy
jar {
    manifest {
        attributes 'Main-Class': 'ohtu.ohtuvarasto.Main'
    }
}
```

Lisätty konfiguraatio siis kertoo, mikä ohjelman luokista on pääohjelma, eli sisältää metodin _main_

* generoi jar-tiedosto komennolla <code>gradle jar</code>
  *  komennolla tree näet minne hakemistoon jar tulee
* suorita jar-tiedosto komennolla <code>java -jar tiedoston_nimi.jar</code>
  * komento tulee suorittaa hakemistosta, jossa jar-tiedosto sijaitsee 
* voit nyt suorittaa ohjelman millä tahansa koneella kopioimalla jar-tiedoston koneelle ja suorittamalla edellä mainitun komennon. 


### 8. JUnit

* kertaa tarvittaessa JUnitin perusteet OTM:n [JUnit-ohjeesta](https://github.com/mluukkai/Ohjelmistotekniikka2018/blob/master/web/junit.md) 

* täydennä Ohtuvaraston testejä siten, että luokan Varasto testien rivikattavuudeksi (line coverage) tulee 100%
  * Joudut huomioimaan ainakin tapaukset, joissa varastoon yritetään laittaa liikaa tavaraa ja varastosta yritetään ottaa enemmän kuin siellä on
  * edellinenkään ei vielä riitä

* testauskattavuuden saat selville Gradlen [JaCoCo](https://docs.gradle.org/current/userguide/jacoco_plugin.html#gsc.tab=0)-pluginin avulla
* ota plugin projektissasi käyttöön lisämäällä tiedostoon _build.gradle_ seuraava rivi:

```groovy
apply plugin: "jacoco" 
```

ja suorittamalla komento <code>gradle test jacocoTestReport</code>
* näet html-muodossa olevean testien rivikattavuusraportin avaamalla selaimella tiedoston _build/reports/jacoco/test/html/index.html_
  * pääset klikkailemalla luokkien ja metodien nimiä näkemään mitkä rivit ovat vielä testien ulottumattomissa
  * **HUOM** jos jacoco aiheuttaa virheilmoituksen _Could not resolve all files for configuration ':jacocoAgent'._ , vaihda tiedostosta _build.gradle_ merkkijono _jcenter()_ muotoon _mavenCentral()_
  * **HUOM2** jos gradle ilmoittaa _:jacocoTestReport SKIPPED_, suorita komento <code>gradle clean</code> ja yritä uudelleen.

* kun luokan <code>Varasto</code> testien rivikattavuus (line coverage) on 100%, pushaa tekemäsi muutokset GitHubiin


### 9. CircleCI, osa 1

[https://circleci.com/](https://circleci.com/) on jatkuvaan integrointiin ja käyttöönottoon tarkoitettu web-palvelu. 

Konfiguroidaan seuraavaksi Circle huolehtimaan projektistamme. 

* mene osoitteeseen [https://circleci.com/](https://circleci.com/) ja valitse _Sign Up_ ja _Sign Up with GitHub_
* palvelu kysyy käyttölupia, tässä tapauksessa pääsy repositorioihin riittää.
* avaa palvelun vasemmassa reunasta "ADD PROJECTS" välilehti ja valitse "Set Up Project" repositorion vierestä

Tästä aukeaa ohjeistus, seuraamme sitä, mutta hyppäämme 3. kohdan yli.

* valitaan configuraatioksi Linux ja Gradle (Java)
* lisää repositoriosi juureen kansio nimeltään _.circleci_
  * huomaa, että kansion nimen pitää alkaa pisteellä!
* tee tiedosto _config.yml_ kansion _.cirleci_ sisälle ja kopioi sinne CircleCI antama _Sample .yml file_ sisältö.
* commitoi ja pushaa repositorio GitHubiin.
* paina _Start Building_

nyt Circle alkaa tarkkailla jokaista muutosta, jonka teet repositorioon.

* sivulle avautuu näkymä, joka kertoo siitä, että Circle yrittää _buildata_ koodin, jonka repositorio sisältää

![]({{ "/images/ex-9-1.png" | absolute_url }})

### 10. CircleCI, osa 2

Mitä Circlessä oikeastaan tapahtuu?

* Kun Circleen rekisteröity projekti pushataan GitHubiin, ilmoittaa GitHub-asiasta Circlelle
* CircleCI käynnistää [Docker kontin](https://www.docker.com/resources/what-container), jonne se vaiheessa kloonaa muuttuneen repositorion (komennolla git clone ...)
* CircleCI lukee repositoriossa olevan konfiguraatiotiedoston .circleci/config.yml ja toimii tiedostossa olevien ohjeiden mukaan.
* Circle 
* Jos testit menevät läpi on Circlen buildin tila _Success_.

CircleCI-buildien toimintaa on mahdollista [konfiguroida](https://circleci.com/docs/2.0/configuration-reference/) melko vapaasti.

* Muuta jotain testiä siten, että testi ei mene läpi ja pushaa koodi GitHubiin
* Tarkkaile projektin CircleCI _JOBS_-näkymää. Lisätiedot avautuvat painamalla punaista "Failed" painiketta. Lue näkymään alaosassa avautuva loki kokonaisuudessaan läpi.
* Korjaa testi ja pushaa muutokset uudelleen GitHubiin
* Tarkkaile jälleen CircleCI-näkymää ja lue loki läpi

### 11. CircleCI, osa 3

Laita repositiossa olevaan tiedostoon _README.md_ koodin tilasta kertova [Status Badge](https://circleci.com/docs/2.0/status-badges/). Ohjeissa näkyvän asetussivun saa auki mm. _JOBS_ näkymästä:

![]({{ "/images/ex-11-1.png" | absolute_url }})

Editoi tiedostoa README.md suoraan GitHubissa:

![]({{ "/images/ex-11-2.png" | absolute_url }})

Tee nyt jokin muutos repositorioosi ja yritä pushata koodi GitHubiin. Toimenpiteestä seuraa virhe:

<pre>
To github.com:mluukkai/ohtu-viikko1.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'git@github.com:mluukkai/ohtu-viikko1.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
</pre>

Tulet todennäköisesti törmäämään vastaavaan virheeseen usein. Syynä virheelle on se, että yrität pushata muutoksia GitHubiin vaikka GitHub on "edellä" paikallista repositorioasi (ts. sinne lisättiin tiedosto README.md).

Ongelma ratkeaa, kun teet ensin komennon <code>git pull</code> ja pushaat koodin vasta sen jälkeen. 

Pullauksen yhteydessä syntyy ns. merge commit ja git avaa oletuseditorisi ja haluaa että määrittelet commit messagen. Jos et ole muuttanut gitin käyttämää oletuseditoria, on käytössä _vim_ joka toimii hieman erilaisilla periaatteilla kuin monet muut editorit. Joudut ehkä googlaamaan että pääset vimistä ulos... 

### 12. Codecov

Tehtävässä 8 määrittelimme projektin testauskattavuuden _JaCoCo:n_ avulla. https://codecov.io -palvelu mahdollistaa projektien koodikattavuuden julkaisemisen verkossa.

* kirjaudu [Codecoviin](https://codecov.io) (GitHub signin)
* lisää repositorio Codecoviin alaisuuteen: 

![](https://raw.githubusercontent.com/mluukkai/Ohjelmistotuotanto2018/master/images/lh1-5.png)

Saat Codecov:in tarkkailemaan projektisi koodikattavuutta lisäämällä tiedoston _build.gradle_ loppuun seuraava:

```groovy
jacocoTestReport {
    reports {
        xml.enabled true
        html.enabled true
    }
}
```

Sekä lisäämällä circlelle tiedoston <code>.circleci/config.yml</code> loppuun seuraavat rivit:

```yml
  - run: ./gradlew check
  - run: ./gradlew jacocoTestReport
  - run: bash <(curl -s https://codecov.io/bash)
```

**HUOM** et tarvitse Codecovin tarjoamaa _upload tokenia_ mihinkään:

![](https://raw.githubusercontent.com/mluukkai/Ohjelmistotuotanto2018/master/images/lh1-6.png)

Kun seuraavan kerran pushaamme koodin Githubiin, ilmestyy Codecov:iin koodin testikattavuusraportti:

![](https://raw.githubusercontent.com/mluukkai/Ohjelmistotuotanto2018/master/images/lh1-8a.png)

Klikkaailemalla sivun alalaidassa olevasta kohdasta _Files_ tiedostojen nimiä, pääset katsomaan yksittäisten luokkien testauksen kattamat rivit:

![](https://raw.githubusercontent.com/mluukkai/Ohjelmistotuotanto2018/master/images/lh1-7a.png)

Käytännössä pyydämme Circleä suorittamaan onnistuneen buildin (eli komennon <code>gradle check</code>) jälkeen gradle-komennon, joka ensin suorittaa testien kattavuusanalyysin JaCoCo:lla ja sen jälkeen lähettää tiedot Codecoviin.

Pushaa nyt muutokset GitHubiin ja seuraa _sekä_ CircleCI-buildin lokia, että repositorion Codecov-sivua.

Lisää projektin _readme badge_ repositoriosi README.md-tiedostoon. Löydät badgen Codecovin settings-valikosta.

Projektisi GitHub-sivun tulisi lopulta näyttää suunnilleen seuraavalta:

![]({{ "/images/ex-12-4.png" | absolute_url }})

Huomaa, että CircleCIn ja Codecovin badget eivät päivity täysin reaaliajassa. Eli vaikka projektin testikattavuus nousisi, kestää hetken, ennen kuin badge näyttää tuoreen tilanteen.

### 13. Parempi testauskattavuus

Projektin testauskattavuutta häiritsee nyt se, että myös pääohjelma _Main_ lasketaan testikattavuuteen.

Voimme määritellä, että joidenkin pakkausten sisältö jätetään huomioimatta kattavuusraportin generoinnissa.

Luo projektiin uusi pakkaus nimeltä _main_ samalle tasolle kuin _ohtu_, siirrä pääohjelma luomaasi pakkaukseen ja muuta _build.gradle_:n _jacocoTestReport_ muotoon:

```
jacocoTestReport {
    reports {
        xml.enabled true
        html.enabled true
    }
    afterEvaluate {
        classDirectories = files(classDirectories.files.collect {
            fileTree(dir: it,
                    exclude: ['main/**'])
        })
    }
}
```

Muuta myös saman tiedoston muut viitteet pääohjelmaan oikeaan muotoon ja varmista, että 
[tehtävässä 7](https://github.com/mluukkai/ohjelmistotuotanto2018/blob/master/laskarit/1.md#7-gradle) mainitut ohjelman suoritus komennolla _gradle run_ ja generoidun jar-tiedoston suorittaminen edelleen toimivat.

Pushaa koodi Githubiin ja varmista, että Codecov generoi raportin siten, että _Main_ jätetään huomioimatta.


### 14. riippuvuuksien injektointi osa 1

* Tutustu riippuvuuksien injektointiin lukemalla https://github.com/mluukkai/ohjelmistotuotanto2018/blob/master/web/riippuvuuksien_injektointi.md
* hae esimerkkiprojekti kurssirepositorion hakemistosta [koodi/viikko1/RiippuvuuksienInjektointi1](https://github.com/mluukkai/ohjelmistotuotanto2018/tree/master/koodi/viikko1/RiippuvuuksienInjektointi1) ja kokeile että se toimii
  * järkevintä lienee että kloonaat repositorion paikalliselle koneellesi
  * **tämän jälkeen kannattaa kopioida projekti tehtävien palautukseen käyttämäsi repositorion sisälle**


Tutustu riippuvuuksien injektointiin esimerkin avulla.

### 15. riippuvuuksien injektointi osa 2: NHL-tilastot

* Kurssirepositorion hakemistossa [koodi/viikko1/NHLStatistics1](https://github.com/mluukkai/ohjelmistotuotanto2018/tree/master/koodi/viikko1/NhlStatistics1) on ohjelma, jonka avulla on mahdollista tutkia [http://nhl.com](http://nhl.com)-sivulla olevia, vuoden 2013-14 tilastotietoja
  * Kopioi projekti edellisen tehtävän reposiotorion alle omaksi hakemistoksi
* Ohjelma koostuu kolmesta luokasta.
  * <code>Statistics</code> on palvelun tarjoava luokka, se tarjoaa metodit yhden pelaajan tietojen näyttämiseen, pistepörssin näyttämiseen ja yhden joukkueen pelaajien tietojen näyttämiseen
  * <code>Player</code>  on luokka, jonka olioina Statistics käsittelee yksittäisen pelaajan tietoja
  * <code>PlayerReader</code>  on luokka, jonka avulla ohjelma käy hakemassa pelaajien tiedot internetistä
* Ohjelma on nyt ikävästi struktoroitu ja esim. yksikkötestaus on kovin hankalaa
 * **HUOM:** kun suoritat koodin ensimmäisen kerran, kestää hetken ennen kuin ohjelman käyttämä palvelin herää. Seuraavat suorituskerrat ovat nopeampia

**itse tehtävä:**

* Määrittele rajapinta <code>Reader</code>, jolla on samat julkiset metodit kuin PlayerReaderilla, eli ainoastaan metodi <code>List<Player> getPlayers()</code>. Laita PlayerReader toteuttamaan rajapinta.
  * HUOM: NetBeansissa on automaattinen refaktorointiominaisuus, jonka avulla luokasta saa helposti generoitua rajapinnan, jolla on samat metodit kuin luokalla. Klikkaa luokan kohdalla hiiren oikeaa nappia, valitse refactor ja "extract interface"
* Muokkaa ohjelman rakennetta siten, että Statictics saa konstruktoriparametrina <code>Reader</code>-tyyppisen olion.
* Muokkaa pääohjelma siten, että se injektoi Statistics-oliolle PlayerReaderin ja kokeile että ohjelma toimii edelleen:

``` java
Statistics stats = new Statistics( new PlayerReader("http://nhlstats-2013-14.herokuapp.com/players.txt") );
```

### 16. NHLStatistics-ohjelman yksikkötestaus

* tee yksikkötestit luokalle Statistics
  * testien kattavuuden (sekä instructions että branches) tulee (Statistics-luokan osalta) olla 100% (mitataan JaCoCo:lla, ks. [tehtävä 8](https://github.com/mluukkai/ohjelmistotuotanto2018/blob/master/laskarit/1.md#8-junit))
  * testit eivät saa käyttää verkkoyhteyttä
  * verkkoyhteyden tarpeen saat eliminoitua luomalla testiä varten rajapinnan Reader-toteuttavan "stubin", jonka sisälle kovakoodaat palautettavan pelaajalistan
  * voit luoda stubin testin sisälle anonyyminä sisäluokkana seuraavasti:

``` java
public class StatisticsTest {
 
    Reader readerStub = new Reader() {
 
        public List<Player> getPlayers() {
            ArrayList<Player> players = new ArrayList<Player>();
 
            players.add(new Player("Semenko", "EDM", 4, 12));
            players.add(new Player("Lemieux", "PIT", 45, 54));
            players.add(new Player("Kurri",   "EDM", 37, 53));
            players.add(new Player("Yzerman", "DET", 42, 56));
            players.add(new Player("Gretzky", "EDM", 35, 89));
 
            return players;
        }
    };
 
    Statistics stats;

    @Before
    public void setUp(){
        // luodaan Statistics-olio joka käyttää "stubia"
        stats = new Statistics(readerStub);
    }  
}
```

Kun injektoit readerStub-olion testissä Statistics-oliolle, palauttaa se aina saman pelaajalistan.

### 17. Repositorion forkkaaminen [versionhallinta]

Forkkaa repositorio https://github.com/ohjelmistotuotanto-hy/ohjelmistotuotanto-hy.github.io

* forkkaaminen tapahtuu seuraavasti:
  * kun olet kirjautuneena GitHubiin, mene yo. osoitteeseen
  * paina oikeassa yläkulmassa olevaa nappia "fork"
* saat näin oman "forkatun" kopion repositoriosta ohjelmistotuotanto-hy.github.io
* kloonaa forkattu repositorio paikalliselle koneellesi
* tee repositorioon joku muutos ja pushaa muutos githubiin
* tee forkkaamastasi repositoriosta "pull request":
  * mene selaimella forkkaamaasi repositorioon
  * paina oikeassa kulmassa olevaa nappia "pull request"
  * anna tehtävistä palautetta avautuvaan lomakkeeseen

### Tehtävien palautus

Palauta tehtävät ...?
