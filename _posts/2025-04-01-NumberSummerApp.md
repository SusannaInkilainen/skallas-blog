# NumberSummerApp
Tarkoituksena oli tehdä nopea harjoitus hyödyntäen C#:llä tehtävää konsolisovellusta. Sovellus laskee listatut kokonaisluvut yhteen ja ilmoittaa niiden kokonaistuloksen. Jos lista on tyhjä, niin käyttäjälle palautetaan error-viesti, joka kertoo listan olevan tyhjä.

## <a href="https://xunit.net/" target="_blank">xUnit</a>
![image](https://github.com/user-attachments/assets/a5174ad2-53b6-4ac5-b6a5-73de8940b345)

xUnitilla voidaan kirjoittaa yksilötestejä ja tässä tapauksessa testasimme seuraavat asiat:
- Testataan, että lista 1, 2, 3, 4, 5 palauttaa tuloksen 15.
- Testataan, että sama toimii negatiivisillä luvuilla.
- Testataan, että tyhjä lista palauttaa nollan (0).
- Testataan, että nolla palauttaa `ArgumentNullException`-poikkeuksen.

Erityishuomiota tarvitsee kiinnittää siihen, että testien funktiot nimetään riittävän kuvailevasti, jotta tulosten kartoittaminen on helpompaa. xUnit tukee kahta erilaista yksikkötestiä: **Fact** ja **Theory**.

- **Fact**-testit testaavat asioita, jotka ovat aina totta. Esimerkiksi 1+1=2.
- **Theory**-testit ovat testejä, jotka pätevät tietylle datajoukolle. Esimerkiksi parilliset numerot.

Tässä tapauksessa meidän ei tarvitse käyttää ollenkaan Theory-testejä, vaan pärjäämme Facts-testeillä.

Kurkkaa repository <a href="https://github.com/SusannaInkilainen/NumberSummerApp" target="_blank">NumberSummerApp</a>

---

## In English

The goal was to create a quick exercise using a console application built with C#. The app sums the listed integers and displays the total result. If the list is empty, the user is returned an error message stating that the list is empty.

## xUnit

xUnit allows writing unit tests, and in this case, we tested the following things:
- Testing that the list 1, 2, 3, 4, 5 returns the result 15.
- Testing that the same works with negative numbers.
- Testing that an empty list returns zero (0).
- Testing that zero throws an `ArgumentNullException`.

Special attention should be paid to ensuring that the test functions are named descriptively enough to make result mapping easier. xUnit supports two different types of unit tests: **Fact** and **Theory**.

- **Fact** tests check things that are always true. For example, 1+1=2.
- **Theory** tests are tests that apply to a specific data set. For example, even numbers.

In this case, we don't need to use any Theory tests, and Facts tests are sufficient.

Check repository <a href="https://github.com/SusannaInkilainen/NumberSummerApp" target="_blank">NumberSummerApp</a>
