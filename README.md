# Vaja11-LCD2x16-STM32F0

Vprašanja:

Za RS in E priključkana LCD zaslonu izberite in aktivirajteustrezna pina ___PB0___ in ___PB2___ kot GPIO_Output

Tudi za priključke D4do D7 na LCD zaslonu aktivirajte 4 ustrezne pine _PB4_, _PB5_, _PB6_ in _PB7_ kot GPIO_Output. 

V Clock Configuration spremenite frekvenco na vrednost, dabopolovica najvišjemožne: Nova frekvenca bo _40_MHz.

V  zavihku Pinout  & Configuration pod  rubriku System  Core kliknite  gumb GPIO. Kakšna je nastavljena hitrost podatkov na vodilih(max. output speed) ? __Very High__.


Kaj počne funkcija itoa? Funkcija itoa spremeni int v string.
Zakaj jo moramo uporabiti?  Ker lahko sprejme DECIMALNE, HEX ali DECIMALNI..

Komentar: 
Pri tej nalogi sva imela težave s lcd knjižnicami. Poskusila sva na druge načine, vendar nama na koncu ni uspelo. Največji problem je bila funkcija #include"stm32fxxx_hal.h".

