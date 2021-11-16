# Palvelintenhallinta tehtävät viikko 3
Tähän tulevat tehtäviät.

## Tehtävät
z) [Commonmark contributors: Markdown Reference](https://commonmark.org/help/)

Yllä olevan linkin takaa löytyy markdown perussyntakseja
- Vinkkeja md tiedoston kirjoittamiseen ja tiettyjen tekstityyppien muunteluun
- Saa tietoa miten muuttaa kirjoitus asua, luoda linkkejä tai kuvia tiedostoon.

a) MarkDown. Tee tämän tehtävän raportti MarkDownina. Helpointa on tehdä raportti GitHub-varastoon, jolloin md-päätteiset tiedostot muotoillaan automaattisesti. Tyhjä rivi tekee kappalejaon, risuaita ‘#’ tekee otsikon, sisennys merkitsee koodinpätkän.

Luotuun MD tiedostoon tehdään tehtävät jotka tehdään nanolla ja linuxin terminalissa. Ajellaan etäyhteyden avulla githubiin.

b) Pull first. Tee useita muutoksia git-varastoosi. Tee muutama muutos, jossa yksi commit koskee useampaa tiedostoa. Anna hyvä kuvaukset (commit message), yksi englanninkielinen lause imperatiivissa (määräysmuodossa) "Add top level menu to Foobar synchronizer"

Tehdään muutoksia, tämä on yksi muutos tähän tiedostoon. Tämän jläkeen luotu uusi md päätteinen tiedosto jonne syötetty tekstiä.

![Image](file:///home/atte/Pictures/Screenshot_2021-11-16_20-56-33.png)

Lisätty muutetut ja uudet tiedostot ja katsottu mikä status. git commit komennolla annettu jokin komentti ja pushattu muutokset. Tämän jälkeen tarkasteltu logista jälkeä.

![Image](file:///home/atte/Pictures/Screenshot_2021-11-16_20-58-03.png)

![Image](file:///home/atte/Pictures/Screenshot_2021-11-16_20-58-25.png)

b) Kaikki kirjataan. Näytä omalla git-varastollasi esimerkit komennoista ‘git log’, ‘git diff’ ja ‘git blame’. Selitä tulokset.

Tässä tehdään ensin muutoksia ja annetaan komento "git diff". Tämä komento näyttää mitä muutoksia on tehty. git log komento näyttää lokitieston mitä kaikkea ollaan muutettu/committeja. git blame komennolla saadaan selville tehtyjä muokkauksia ja kuka ne on tehnyt eli ketä voidaan syyttää.

![Image](file:///home/atte/Pictures/muutoksetDIFF.png)
![blameKomento](file:///home/atte/Pictures/blame.png)

c) Huppis! Tee tyhmä muutos gittiin, älä tee commit:tia. Tuhoa huonot muutokset ‘git reset --hard’. Huomaa, että tässä toiminnossa ei ole peruutusnappia.

Luodaan uusi tiedosto sekoilua.md ja tuhotaan se. git status komennolla saatiin tieto, että luotu tiedosto odottaa committia, mutta sitä ei tehty vaan annettu komento "git reset --hard" jolloin HEAD palasi edelliseen oikeaan tekemääni muutokseen. 
![RESEThard](file:///home/atte/Pictures/resetKova.png)

ja "git status" komennolla näimme että se ei enään odota committia.

d) Formula. Tee uusi salt-tila (formula, moduli, infraa koodina). (Eli uusi tiedosto esim. /srv/salt/terontila/init.sls). Voit tehdä ihan yksinkertaisen parin funktion (pkg, file...) tilan, tai edistyneemmin asentaa ja konfiguroida minkä vain uuden ohjelman: demonin, työpöytäohjelman tai komentokehotteesta toimivan ohjelman. Käytä tarvittaessa ‘find -printf “%T+ %p\n”|sort’ löytääksesi uudet asetustiedostot.

