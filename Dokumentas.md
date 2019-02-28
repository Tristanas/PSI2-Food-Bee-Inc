VILNIAUS UNIVERSITETAS 
MATEMATIKOS IR INFORMATIKOS FAKUTLETAS

 “Food Bee Inc.”
Laboratorinis darbas

	Darbą atliko:
	Manfredas Šiurkus
  	Edvinas Šmita
  	Teodoras Šiaulys
  	Tomas Mikna
  	Vilius Minkevičius
	

Vilnius, 2018

# 1. Reikalavimai

## Užsakovo reikalavimai

 1. Pritaikyti programą mobiliesiems telefonams;*
 2. Pranešti dėl atitinkamų produktų galiojimo laiko pabaigos;
 3. Galimybė užsakyti prekes per mobiliąją programą;
 4. Galimybė dalintis šaldytuvo turiniu su kitais naudotojais(grupė);
 5. Pranešimai, komentarai tarp šeimos narių dėl produktų, receptų;
 6. Kalendoriaus integracija į programą, žymint pirktus produktus pagal dienas;
 7. Numatyti galimybę atvaizduoti maisto tiekėjo pateikiamas reklamas;
 8. Aktyviai teikiama pagalba naudotojui programos naudojimo klausimais;
 9. Automatinis programos klaidų perdavimas kokybės užtikrinimo specialistams;
 10. Trumpas programos aprašas/paaiškinimas pirmą kartą ja įsijungus.

## Vartotojiški pasakojimai

<table class="tg">
  <tr>
    <th class="tg-0pky" colspan="3">Aš labai noriu šokti</th>
  </tr>
  <tr>
    <td class="tg-0pky">Kaip noriu? -Labai</td>
    <td class="tg-0pky">Kas nori? -Aš</td>
    <td class="tg-0pky">Ką daryti? - Šokti</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="3">Todėl turiu išmokti šokti.</td>
  </tr>
</table>


# 2. Dalykinės srities modelis

## Žodynas

## Klasių diagrama

# 3. Užduotys

## Pradinė užduočių diagrama

![užduočių diagrama](https://github.com/Tristanas/PSI2-Food-Bee-Inc/blob/master/Nuotraukos/UC-diagrama.jpg "Užduočių diagrama")

## Užduočių scenarijų tekstai

## Pavyzdinis reikalavimas

Padarytas remiantis reikalavimu: "2. Pranešti dėl atitinkamų produktų galiojimo laiko pabaigos;"
Gali būti, kad reikalavimas yra klaidingai suprastas, kadangi dar nepasitikslinome jo.

Jei tai nėra reikalavimas įvesti ar pakeisti galiojimo laiką, kyla tokie klausimai:
 - Ką reiškia galiojimo laiko pabaiga? Tai, kad produktas dabartiniu metu nebegalioja? 
 - Tada vartotojas turi galimybę pranešti, kad produktas baigė galioti? 
 - Ką tada gali padaryti sistema? Kviesti, ką nors išvežti nustojusius galioti produktus?

Taip pat reikia dar pasitikslinti UC formatą. 

### Produktų galiojimo laiko redagavimas:
Vartotojas lange „Mano produktai“ esančiame sąraše pažymi produktą, kurio galiojimo laikas nenurodytas arba klaidingas. Tada jis paspaudžia mygtuką „redaguoti“. Sistema parodo redagavimo langą. Vartotojas įveda jam žinomą galiojimo laiką. Įvedęs paspaudžia „patvirtinti“ arba apsigalvoja ir spaudžia „atšaukti“. Patvirtinus pokyčius sistema atnaujina parinkto produkto galiojimo laiką (minėti kreipimąsi į duomenų bazę?), grąžina vartotoją į produktų langą. Sąraše vartotojas mato pakeitimą.

#### Alternatyvūs scenarijai: (nebaigta pildyti)
Redagavimo lange vartotojas paspaudžia „atšaukti“. Visi pokyčiai panaikinami, sistema grąžina vartotoją į „Mano produktai“ langą.

Jei vartotojas įveda galiojimo laiką, pagal kurį produktas jau nustojęs galioti...

#### Grafinės vartotojo sąsajos eskizas:

![Mano produktai](https://github.com/Tristanas/PSI2-Food-Bee-Inc/blob/master/Nuotraukos/Mano%20produktai%20GUI.jpg "'Mano produktai langas'")
