---
layout: post
title:  "Odpowiedzi na pytania z pierwszej pracy domowej"
date:   2015-01-28 21:26:23
author: artur_delura
categories: general
---
> W połowie przypadków źle wpisuję drugą liczbę w `string.substring(0, 1)`, niewiem jak to zapamiętać.

Niestety nie ma prostego sposobu na zapamiętanie, sam gdy potrzebuję użyć tej funkcji, to posiłkuję się dokumentacją: [string.substring](http://www.w3schools.com/jsref/jsref_substring.asp). Jest jeszcze druga podobna funkcja [string.substr](http://www.w3schools.com/jsref/jsref_substr.asp) :)

----

> `var divideByThree = function (number) {};` Taka deklaracja funkcji jest dla mnie mało intuicyjna, spodziewałabym się raczej razem divideByThree(number), bo tak potem tę funkcję wywołuję.

<pre><code>
// Funkcję definiujemy w taki sposób:
function nazwaFunkcji() {}

// Jednak możemy też tak:
var nazwaFunkcji = function () {};

</code></pre>
Na tym etapie wtajemniczenia można uznać, że oba powyższe wykonują to samo. Dla ciekawskich: funkcje w języku JS są traktowane jak zwykłe zmienne.

----
> Zastanawia mnie, kiedy wewnątrz funkcji używa się `console.log()`, a kiedy `return`?

`console.log()` używany aby wypisać coś w konsoli w narzędziach deweloperskich. `return` jest ściśle związane z funkcjami. Po tym słowie kluczowym podajemy wynik działania naszej funkcji:
<pre><code class="javascript">
function sum(a + b) {
    return a + b;
}
// Wynikiem działania funkcji `sum` jest 14.
// Gdybyśmy nie użyli `return` to funkcja nie miałaby żadnego wyniku.
var wynik = sum(4, 10);

</code></pre>

----
> Prawidłowy wynik otrzymuje się, kiedy kod zostanie zapisany tak:
<pre><code class="javascript">
var names = ["one", "two", "3", "4", "5"];
for (i=0; i < names.length; i++) {
    console.log("I know someone called " + names[i]);
}
</code></pre>
> Kiedy zmienię nazwę tablicy na `name` otrzymuję nieprawidłowy wynik - nie wiem dlaczego ?

W pierwszej linijce definiujesz zmienną o nazwie `names`, a w drugiej odwołujesz się do jej właściwości `length`. Zauważ, że gdy zmienisz `names` na `name` w pierwszej linijce, to będziesz odwoływała się do czegoś, co nie istnieje w drugiej i trzeciej.

----
> Problem: Na tym co robiliśmy razem na zajęciach: nie udało mi się zmienić polskich liter.

Przykład z pierwszych zajęć znajduje się [tutaj](http://jsbin.com/zuqaso/1/edit?html,css,output).

----

Podsumowując - Najwięcej problemów było z funkcjami, więc będziemy je niedługo mielić :)
