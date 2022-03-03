# Saaremaa kodutute loomade andmebaasi infosüsteemi analüüs

## Ajakava planeerimine

### Kolmapäev - Mis ja miks?

- 13.30 - Tiimiga kohtumine, tööriistade valimine ja üles seadmine, infosüsteemi valimine
- 14.00 - Ajakava planeerimine
- 15.30 - Kohtumine kliendiga
- 16.00 - Homse päeva planeerimine, edasine funktsionaalsuse arutelu

### Neljapäev - Kuidas?

- 9.00 - Hommikukohvi, töö algab, analüüsime kasutajate rolle ja vajadusi
- 11.00 - Koosolek - kasutajate vajadused jne
- 11.45 - Lõuna
- 12.45 - Kasutuslugude analüüs
- 15.00 - Koosolek - kasutuslood
- 15.30 - Karl-M teeb wireframe, teised tegelevad andmemudeliga ja andmebaasi mudeliga

### Reede - Lõpulihv

- 9.00 - Hommikukohvi ja koosolek - andmemudel, andmebaasi mudel, wireframe
- 9.30 - GitLabi seadistamine, issuede tegemine
- 11.45 - Lõuna
- 12.45 - Esitlused

## Soovitud funktsionaalsus

- Anda ja võtta loomi
- Annetamine
- Hulkuvad/kadunud loomad
- Kõik varjupaigad
- Live cat cam
- Kuulutused
- Looma kohta info
- Filtreerimine

## Kasutajad ja rollid

- Annetada süüa/mänguasju/raha
- Hoolitseda ja tegelda loomadega
- Igakuine annetus
- Panna kuulutusi ülesse
- Panna pilte ja kirjutada hulkuvatest loomadest
- 
- MTÜ Kodutud Loomad raamatupidaja - tegeleb finantspoolega
- Admin - haldab andmeid, kasutajaid
- Veebilehe administraator - jälgib toimimist ja korrektsust
- Tarkvaraarendaja - uuendab välimust  ja funktsionaalsust
- Turvakodu admin - haldab oma asutuse andmeid
- Registreeritud kasutaja - saab panna ja eemaldada oma kuulutusi
- Külaline - saab tutvuda kõigi andmebaasis olevate loomadega

## User Stories

### Admin

- Olles admin user ma tahan hallata kasutajaid
- Adminina ma tahan kasutajatele õigusi anda ja neid muuta
- Siis ma saan neid eemaldada kui vaja või õigusi anda

### Varjupaiga haldaja
- Saan teha samu asju mis töötaja
- Saan anda ja võtta töötajalt õigused
- Saan online nõustada töötajaid ja looma võtnud inimesi

### Varjupaiga töötaja

- Olles varjupaiga töötaja, saan postitada pilte ja lugusid loomadest kes otsib endale kodu, sest siis on suurem võimalus loomal leida enda õige kodu
- Olles varjupaiga töötaja, saan kirjutada igast loomast loo mis moodi ta on sattunud varjupaika
- Olles varjupaiga töötaja, saan postitada pilte loomadest kes on leidnud endale kodu
- Olles varjupaiga töötaja, saan postitada lugusid lahkunud loomadest
- Olles varjupaiga töötaja, saan postitada lugusid loomadest keda on väärkoheldud, et inimestele panna südamele mida tähendab endale looma võtmine
- Olles varjupaiga töötaja, saan postitada lugusid loomadest keda on maha jäetud või hüljatud inimeste poolt, et inimestele panna südamele mida tähendab endale looma võtmine
- Olles varjupaiga töötaja, saan käia vaatamas looma kes on võtud, et olla kindel selles, et loom oleks kindlates kätes
- Olles varjupaiga töötaja, saan annetuste eest loomadele ise asju tellida või osta
- Olles varjupaiga töötaja, saan ära tuua loomi kes vajavad abi üle eestiliselt
- Olles varjupaiga töötaja, saan ära tuua loomikes vajavad abi naaberriikides
- Olles varjupaiga töötaja, saan kustutada loomadest pilte
- Olles varjupaiga töötaja, saan kustutada loomadest lugusi
- Olles varjupaiga töötaja, saan võtta ühendust looma võtnud inimestega
- Olles varjupaiga töötaja, saan pakkuda varjupaiga loomadele transporti ühest linnast teise, kui loomal on vaja meditsiinilistabi mida ei ole eelnevas linnas olemas 

### Sisselogitud kasutaja
- Registreeritud kasutajana soovin, et mul oleks lihtne juurdepääs annetustele, et saaksin tasuta asju kinkida
- Registreeritud kasutajana soovin looma näha, et ei peaks kaugele reisima
- Registreeritud kasutajana soovin võtta kassi, kuid ma ei saa sinna minna, sest see on kaugel
- Registreeritud kasutajana soovin looma ära andmist postitada
- Registreeritud kasutajana soovin postitada foorumitesse
- Registreeritud kasutajana soovin muuta oma enda postitusi ja kustutada neid
- Registreeritud kasutajana sooviksin saada loomi jalgida

### Külaline
* Olles külaline, tahan ma näha loomi, kes on varjupaikades adopteerimiseks vabad
    * Ma tahan loomi filtreerida liigi, värvi, asukoha, soo jms järgi
    * Listivaates tahan näha liiki, nime, pilti, asukohta
    * loomale klikkides tahan näha detailsemat infot, lisapilte, lühikirjeldust
* Olles külaline, tahan ma näha loomi, kes on kasutajate poolt adopteerimiseks välja pandud
    * sarnaselt ülaltoodule
* Olles külaline, tahan ma erinevate varjupaikade kohta infot saada
    * asukoht, kontaktid
* Olles külaline, tahan ma erinevatele varjupaikadele annetusi jagada
    * Olles külaline, tahan ma annetada erinevate kanalite kaudu - pangalingid, tasuline kõne, mTasku, PayPal, Wise, SEPA, krüpto
* Olles külaline, tahan ma kindlate loomade heaks annetada
* Olles külaline, tahan ma näha loomatarvetega seonduvaid ostu-müügikuulutusi
    * foorumilaadne keskkond
* Olles külaline, tahan ma näha livestreame kassitubadest
    * Ideaalis mitu erinevat kassituba
* Olles külaline, tahan ma saada infot loomade adopteerimise kohta
    * Millised on tingimused adopteerimiseks?
    * Kuidas näeb välja adopteerimisprotsess?
    * 
* Olles külaline, tahan ma näha loomadega seotud postitusi, mida kasutajad või varjupaigad on postitanud
* Olles külaline, tahan ma infot loomade, annetamise või muu kohta ka sotsiaalvõrgustikes jagada


## Kasutatud tööriistad

Projektihaldus: Linear, GitHub
Kommunikatsioon: Slack, häälepaelad
Märkmed: GitHub, VS Code, Notes, notes.io, paber&pastakas

## Tiim
[Karl-Mihkel Truu](github.com/krlmhkl/)
[Gendro Umber](github.com/GendroU/)
[Kaur Luhaäär](github.com/Kaurluhaaar/)
[Karl-Patric Rohi](github.com/Karl-Patric/) 
[Olev Kuris](github.com/olevkuris/)
