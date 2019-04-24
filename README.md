kodune_nr_3

# Address Book

<img src="https://i.imgur.com/cFZaSDE.png" height="450">      <img src="https://i.imgur.com/1VwZ6pZ.png" height="450">                               
<img src="https://i.imgur.com/AmpfsJc.png" height="450">      <img src="https://i.imgur.com/kSYHyOS.png" height="450">

### 7. Git projektis on README.md, mis kirjeldab projekti seadmistamist ja viide juhendile.

Esiteks proovisin Ionic Cordova äppi rakendada, kasutasin 2 õpetust mis olid üks aasta vana, seadistasin kõik Ionicu kasutamise jaoks, aga ei saanud mõlemat õpetust kasutada kuna teatud osa koodist oli aegunud ja ei toiminud korrektselt.

Seejärel valisin kolmanda juhendi. Seadistamise käigus laadisin alla ja paigaldasin palju erinevaid pluginaid Cordova töötamise jaoks.
Kuna arenduskeskond asub virtuaalmasinas, siis mul ei ole võimalust kasutada Android studio emulaatorit. Kasutasin füüsilist telefoni juhtmevabas debug režiimis(Honor 5x).

Juhendina kasutasin - https://ccoenraets.github.io/cordova-tutorial/create-cordova-project.html

### 8. Git projektis on README.md, kus asub arvamus juhendist (min 2 lõiku).

Juhend oli sisukas aga aegunud. Palju parandusi ma leidsin kommentaaridest teiste lugejate poolt. Mõned vead jäid parandamata. Võrreldes teiste juhenditega, mis ma olen enne leidnud, siis see vähemalt kompileerus. Väga ei aidanud ka see, et ei olnud võimalust vaadata lähtekoodi tervukuna.

### 9. Git projektis on README.md, kus kirjeldatakse vajalikest muutustest seoses SDK versiooni muutustega.

Ei leidnud sellist muutust

### 10. Git projektis on README.md, kus kirjeldatakse juhendi muudest muutustest rakenduse terviklikumaks muutmise nimel.

Olen lisanud esilehel vihje mida äppiga peaks üldse teha. Pidin ära kustutama koodi mis oli seotud paragrahvi "Using Hardware Acceleration" - kuna see osa ei töötanud korrektselt ja tekitas lisamuret äppi kasutamisel (otsinguriba jäi rippuma kontakti lehel, puudus võimalus tagasi liikuda). Pärast ebavajaliku eemaldamist oli probleem liikuda kontakti info peale, aga selle probleemi lahendas route´i ülekirjutamine.
