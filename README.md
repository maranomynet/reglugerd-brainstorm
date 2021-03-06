# Reglugerðasafn stjórnarráðsins

Reglugerðasafn stjórnarráðsins á XML+HTML formi með fullri breytingasögu, og
áhrifum breyingagreglugerða felldum inn í texta viðkomandi stofnreglugerðar.

_**ATH:** Þetta er bara proof-of-concept högun. Form XML skjalanna mun taka gagngerum breytingum._

## Form breytingasögunnar

Í hvert skipti sem skrifað er í breytingasöguna eru notuð stöðluð skilaboð á
eftirfarandi formi:

Stofnreglugerð gefin út:

    Ný reglugerð: 866/2017 – Reglugerð um för yfir landamæri.

Vandræðaleg innsláttarmistök leiðrétt stuttu eftir útgáfu:

    Leiðrétting á: 866/2017

Breytingareglugerð gefin út:

    Ný reglugerð: 586/2020 – Reglugerð um breytingu á reglugerð um för yfir landamæri, nr. 866/2017.

Uppfærsla á texta stofnreglugerðarinnar sem er breytt (sett á branch að nafni
`ahrif/2020-06-15/568-2020`):

    Áhrif: 586/2020 (tekur gildi: 2020-06-15)

Daginn sem breytingareglugerð tekur gildi (oftast samdægurs) er áhrifa-branch
hennar fellt inn (e. merged) á aðal-branchið:

    Gildistaka: 586/2020

**Ath** að ef Stofnreglugerð ógildir aðrar reglugerðir, þá verður til
samsvarandi "áhrifa" breyting á `ahrif/YYYY-MM-DD/xxx-yyyy` branchi og í
framhaldi af því "gildistöku" innfelling (merge) daginn sem stofnreglugerðin
tekur gildi.

**Ath 2:** Ef breytingareglugerð tekur gildi í tveimur eða fleiri skrefum,
þarf að útbúa aðskilin áhrifa-brönch – `ahrif/YYYY-MM-DD/xxx-yyyy-a`,
`ahrif/YYYY-MM-DD/xxx-yyyy-b`, `ahrif/YYYY-MM-DD/xxx-yyyy-c`

---

Tæknilegar breytingar sem snúa _ekki_ að útgáfu reglugerðanna:

    Admin: Uppfæra upplýsingar í README.md

## Dagsetningar fyrir 2. janúar 1970

Tæknilegar ástæður valda því að elstu mögulegu dagsetningarnar eru 1.
janúar 1970.

Því eru öllum dagsetningum á bilinu frá byrjun árs 1800 til og með 1. janúar
1970 varpað niður á 1. janúar 1970.

Fyrir hverja dagsetningu á þessu tímabili er reiknaður fjöldi heilla
almanaksdaga frá 1. janúar 1800 og dagsetningin táknuð með sama fjölda heilla
sekúndna frá miðnætti 1. janúar 1970.

Tímakóðinn `1970-01-01T00:00:41` táknar þannig "11. febrúar 1800", og kóðinn
`1970-01-01T14:39:22` táknar "17. júní 1945"

Tímabilið frá og með `1970-01-01T17:14:52` fram að miðnætti þann dag er ekkert
notað.
