# HUN

> ⚠️ **FELELŐSSÉGKIZÁRÁS** ⚠️
>- A leírt módszereket saját felelősségére használd.
>- Hozz létre egy tesztprofilt és gyakorolj azon mielőtt egy valódi tárcán hajtod végre a bemutatott lépéseket.
>- A megosztott szólánc csak gyakorlati célokat szolgál. NE HASZNÁLD a kézikönyvből származó szóláncot a való életben.

> ⚠️ **FONTOS MEGJEGYZÉS** ⚠️<br> **Soha ne osszd meg másokkal a tárcát helyreállító titkos szóláncot.**

## Tartalom
- [HUN](#hun)
  * [Tartalom](#tartalom)
  * [Bevezető](#bevezető)
    + [Böngésző](#böngésző)
    + [Fizikai tárca](#fizikai-tárca)
  * [Metamask fiókok létrehozása](#metamask-fiókok-létrehozása)
  * [Metamask fiókok visszaállítása Metamask tárca segítéségvel](#metamask-fiókok-visszaállítása-metamask-tárca-segít-ségvel)
    + [Visszaállítás](#visszaállítás)
    + [Tesztelés 1](#tesztelés-1)
    + [Tesztelés 2](#tesztelés-2)
    + [Konklúzió](#konklúzió)
  * [Metamask fiókok visszaállítása fizikai tárca segítségével](#metamask-fiókok-visszaállítása-fizikai-tárca-segítségével)
    + [Ledger Nano S](#ledger-nano-s)
    + [Metamask használata fizikai tárcán tárolt kulcsokkal](#metamask-használata-fizikai-tárcán-tárolt-kulcsokkal)

## Bevezető
### Böngésző
A bemutató során Brave és Firefox böngészőket használok. Mindkettőhöz elérhető hivatalos Metamask bővítmény.

> ℹ️ INFO <br>Ha meglévő böngészőben létrehozunk egy új profilt az, olyan mintha egy újonnan telepített böngészők lenne alap beállításokkal.

Brave profilok:
- [Metamask 1](../images/A01.png) (piros)
- [Metamask 2](../images/B01.png) (zöld)

### Fizikai tárca
A bemutató során Ledger Nano S fizikai tárcát használok.

## Metamask fiókok létrehozása
Az alábbi lépések során a [_**Metamask 1**_](../images/A01.png) profilt használom.
1. Telepítem a Metamask bővítményt.
2. [Létrehozom az új tárcát, azaz legenerálom a szóláncot.](../images/A02.png)
3. [Papírra kiírom a szóláncot.](../images/A03.png)
```
impulse enable harsh okay blush force face volcano remind absurd burger vault
```
4. [Létrejött az alap fiók (publikus és privát kulcs páros).](../images/A04.png)
```
név: Account 1
publikus kulcs: 0xF7f844FC13f08Ec6B4401e82cD18808E67f6d322
```
5. [Létrehozok egy újabb fiókot.](../images/A05.png)
6. [A létrejött újabb fiók publikus címe.](../images/A06.png)
```
név: Account 2
publikus kulcs: 0xb0ae24074899BA96CcCe285141EB0acD2b315520
```
7. [Létrehozom a harmadik fiókot is.](../images/A07.png)
8. [A harmadik fiók publikus címe.](../images/A08.png)
```
név: Account 3
publikus kulcs: 0xc4A3877F2eC08fF48D28B7526f09A390d3254523
```
7. [A harmadik fióknak lementem a privát kulcsát is.](../images/A09.png)
```
név: Account 3
privát kulcs: 3def70c36df26560bce748476e56b748a8420718b0038aca63c3fbb77a2c8b07
```

## Metamask fiókok visszaállítása Metamask tárca segítéségvel
### Visszaállítás
Az alábbi lépések során a [_**Metamask 2**_](../images/B01.png) profilt használom.
1. Telepítem a Metamask bővítményt.
2. [Ezúttal nem hozok létre új tárcát, hanem a mentett szóláncból állítom vissza.](../images/B02.png)
3. [Megadom a _**Metamask 1**_ profil alatt készült tárcához tartozó szóláncot.](../images/B03.png)
4. [A visszaállított fiók részéetei.](../images/B04.png)
```
név: Account 1
publikus kulcs: 0xF7f844FC13f08Ec6B4401e82cD18808E67f6d322
```
> 👉 Ugyanaz a publikus kulcs jött létre, mint eredetileg.

5. [Ugyanúgy, mint az 1-es profil esetén létrehozok egy új fiókot.](../images/B05.png)
6. [A létrehozott fiók adatai:](../images/B06.png)
``` 
név: Account 2
publikus kulcs: 0xb0ae24074899BA96CcCe285141EB0acD2b315520
``` 
> 👉 Ugyanaz a publikus kulcs jött létre, mint az 1-es profil alatt az "Account 2" létrehozása alkalmával.

7. [Az "Account 3"-at a korábban lementett privát kulcs segítségével állítom vissza.](../images/B07.png)
8. [Közvetlenül megadom a privát kulcsot.](../images/B08.png)
9. [A visszaállított fiók adatai:](../images/B09.png)
```
név: Account 3
publikus kulcs: 0xc4A3877F2eC08fF48D28B7526f09A390d3254523
```
> 👉 Ugyanaz a publikus kulcs jött létre, mint az 1-es profil alatt az "Account 3" létrehozása alkalmával.

> 👉 A menüben az imént visszaállított fiók mellett szerepel az "imported" címke.

### Tesztelés 1
Az alábbi lépések továbbra is a _**Metamask 2**_ profilon hajtom végre.
1. [Tesztelés végett, menüből létrehozok egy újabb fiókot.](../images/B10.png)
2. [Elnevezem "Account 4"-nek.](../images/B11.png)
3. [Létrehozást követően a menüben nem az jelenik meg amit elsőre vártunk.](../images/B12.png)
4. [Amennyiben megpróbálom átnevezni a csatolt képen látható hibaüzenet jelenik meg.](../images/B13.png)
5. [Újabb tesztelés végett, menüből létrehozok még egy fiókot.](../images/B14.png)
6. [Az "Account 5" részletei. Itt is megjelenik a hibaüzenet.](../images/B15.png)

### Tesztelés 2
A soron következő lépést a _**Metamask 1**_ profilon hajtom végre.
1. [Tesztelés végett itt is létrehozok egy újabb fiókot.](../images/B17.png)
2. [Az "Account 5" részletei. Nincs hibaüzenet.](../images/B17.png)
```
név: Account 5
publikus kulcs: 0x85deE2C51718235ac0B0CaD56F267B89bC18ADdF
```

### Konklúzió
- A szóláncból visszaállított tárcában, a fiókokat ismételten egyesével hozzáadva, azok ugyanazon kulcsokkal jönnek létre, mint eredetileg.
- Egy adott fiókot a korábban lementett privát kulcs alapján is vissza lehet állítani (Account 3).
- Amennyiben privát kulcsból állítjuk vissza a fiókot, azt követően, menüből újabb fiókok létrehozása esetén lehetnek gondok. Erre célszerű odafigyelni.

## Metamask fiókok visszaállítása fizikai tárca segítségével
### Ledger Nano S
1. Az eredeti Metamask tárca létrehozása alkalmával mentett szólánc bevitelével a fizikai tárcán létrehozom a kulcsokat.
2. Telepítem az Etehreum alkalmazást a fizikai tárcán.
3. Csatlakoztatom a Ledger Live-ot a fizikai táecához.
4. [A fizikai tárcán is létrejött az alap fiók:](../images/C01.png)
```
név: Ethereum 1
publikus kulcs: 0xF7f844FC13f08Ec6B4401e82cD18808E67f6d322
```
> 👉 Ez ugyanaz a publikus kulcs, mint a Metamaskban az "Account 1".

### Metamask használata fizikai tárcán tárolt kulcsokkal
1. [Telepítem a Metamask bővítményt a Firefix böngészőben is.](../images/C02.png)
2. [Létrehozok egy újabb tárcát, mivel csak így tudok belépni a Metamaskba. Ezt a tárcát semmire sem fogom használni.](../images/C03.png)
3. [Kapcsolódok a fizikai tárcára, amely tárolja a számomra fontos kulcsokat](../images/C04.png)
4. [Kiválasztom a fizikai tárca típusát. Jelen esetben ez a Ledger.](../images/C05.png)
5. [A megjelenő menüben az első publikus cím kivételével az összes többi ismeretlen.](../images/C06.png)
6. [A hullómenüben a használni kívánt protokolt átállítom `BIP44`-re.](../images/C07.png)
7. [Így a listában már az is ismerős címek jelennek meg.](../images/C08.png)
> 👉 Fentebb 4 fiókot hoztam létre. A listában ugyanzok a publikus címek láthatóak, ugyanabban a sorrenben, mint eredetileg a Metamaskban.

> ℹ️ Ebben a listában tudunk lapozgatni. Látható, hogy egy szólánchoz több fiók (kulcspár) is tartozik. 

8. Végül ellenőrizzük a hozzáadott fiókkat:
- [A "Ledger 1" ugyanaz, mint az "Account 1"](../images/C09.png)
```
publikus kulcs: 0xF7f844FC13f08Ec6B4401e82cD18808E67f6d322
```
- [A "Ledger 2" ugyanaz, mint az "Account 2"](../images/C10.png)
```
publikus kulcs: 0xb0ae24074899BA96CcCe285141EB0acD2b315520
```
- [A "Ledger 3" ugyanaz, mint az "Account 3"](../images/C11.png)
```
publikus kulcs: 0xc4A3877F2eC08fF48D28B7526f09A390d3254523
```
- [A "Ledger 4" ugyanaz, mint az "Account 5"](../images/C12.png)
```
publikus kulcs: 0x85deE2C51718235ac0B0CaD56F267B89bC18ADdF
```
