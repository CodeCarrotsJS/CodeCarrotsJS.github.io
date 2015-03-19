---
layout: page
title: Plan Zajęć
permalink: /schedule/
---

#### Zajęcia pierwsze (20 stycznia 2015) - wprowadzenie

[Prezentacja](http://codecarrotsjs.github.io/prezentacja-pierwsza/)

1. Przełamujemy lody i się poznajemy, ustalamy zasady
2. Prezentacja
    * Niewiedza to normalny stan
    * Do czego można użyć JavaScript
        * Stronki
        * Firefox OS
        * Aplikacje na Windows 8
        * Aplikacje mobilne
        * node.js
    * Przykłady użycia języka JS
    * Gdzie szukać informacji i odpowiedzi na pytania
4.  Narzędzia
    * Instalacja i prezentacja narzędzi (IDE: Atom + Chrome)
    * Przedstawienie Chrome Developer Tools
5. Niespodzianka

##### Praca domowa

* Zrobienie przynajmniej początku - ścieżki [JavaScript z Codecademy](http://www.codecademy.com/en/tracks/javascript) i napisanie nam swoich wrażeń - co było łatwe, trudne, co nie było jasne.
* Dodatkowo: [Podstawowy tutorial na Scratchu](http://scratch.mit.edu/projects/editor/?tip_bar=getStarted).
* Dodatkowo: Początek kursu z [Narzędzi deweloperskich](http://discover-devtools.codeschool.com/).

----

#### Zajęcia drugie (27 stycznia 2015) - zmienne
----

#### Zajęcia trzecie (3 lutego 2015) - funkcje 1
----

[Prezentacja](http://codecarrotsjs.github.io/prezentacja-funkcje/)

1. Czym jest funkcja?
2. Deklaracja funkcji (deklaracja "klasyczna")
3. Argumenty funkcji
4. Zwracanie wartości z funkcji

##### Praca domowa

[Paczka do zad. 1](http://codecarrotsjs.github.io/files/Funkcje-Zad1.zip)

1. Otwórz dokument index.html znajdujący się w paczce dołączonej do zadania i wywołaj załączoną funkcję zrobBeczke w Chrome Developer Tools. Rozwiązanie napisz w mailu zwrotnym.
2. Napisz funkcję, która doda do dokumentu tekst "Witaj świecie" lub inny, wybrany przez Ciebie, następnie wywołaj ją kilka razy.
3. Napisz funkcję czyMogeProwadzicSamochod z argumentem wiek, która w okienku powiadomienia (alert) wyświetli "Tak, możesz prowadzić samochód" jeśli wiek jest większy lub równy 18 i "Niestety musisz jeszcze podrosnąć", jeśli wiek jest mniejszy niż 18.
4. Napisz funkcję, która przy wywołaniu zwróci ciąg "Witaj świecie".
5. Napisz funkcję, która zwróci resztę dzielenia pierwszego argumentu przez drugi.
6. *Napisz funkcję o nazwie czyParzysta, która dla podanej w argumencie liczby zwróci wartość true, jeśli jest parzysta lub false, jeśli jest nieparzysta.
7. *Uruchom w konsoli wszystkie przykłady użycia funkcji i napisz, czemu w konsoli widzisz takie, a nie inne wyniki (zinterpretuj je).

#### Zajęcia czwarte (10 lutego 2015) - funkcje 2

[Prezentacja](http://codecarrotsjs.github.io/prezentacja-funkcje-2/)

----

#### Zajęcia piąte (17 lutego 2015) - pętle

[prezentacja](http://codecarrotsjs.github.io/loops/)

----

#### Zajęcia szóste (24 lutego 2015) - DOM

[prezentacja](http://codecarrotsjs.github.io/prezentacja-dom/#/).

----

#### Zajęcia siódme (3 marca 2015) - DOM (warsztaty)

----

#### Zajęcia ósme (10 marca 2015) - DOM (warsztaty)

1. Praca nad grą [zgadnij liczbę](https://gist.github.com/adelura/7b18b2d5707ecc3b7ba9).
2. Zasięg deklarowanych zmiennych:
    * Zmienna zadeklarowana w funkcji jest dostępna tylko w jej obrębie i tylko w czasie jej wykonywania.
    * Jeżeli zmienna jest zadeklarowana poza funkcją, to jest dostępna ona globalnie.
3. Narzędzia deweloperskie chrome (chrome dev tools) i debugowanie kodu. Polecany [artykuł do przeczytania](https://developer.chrome.com/devtools/docs/javascript-debugging)

##### Praca domowa

Zastanowić się nad poniższym kodem i odpowiedzieć na pytania:

    var a = 5;

    function b() {
        var a = 10;
    }
    b();

    console.log(a); // [ co tutaj będzie? ]

-

    var a = 5;

    function b() {
        a = 10;
    }
    b();

    console.log(a); // [ co tutaj będzie? ]

-

    var a = 5;

    function b(a) {
        a = 10;
    }

    b(a);

    console.log(a); // [ co tutaj będzie? ]

Zadanie z gwiazdką:

    var a = 5;

    function b() {
        a = 10;
    }
    b(a);

    console.log(a); // [ co tutaj będzie? ]


Przerobić grę Rock Papers Scissors wg podanego [wzorca](https://github.com/CodeCarrotsJS/rpsls). Zakodowane już jest pobieranie wyboru użytkownika z guzików, trzeba dodać wybór komputera i znalezienie wygranej - i umieszczenie tego we właściwym miejscu na stronie. CSS strony oparty jest na [Bootstrapie](http://getbootstrap.com/) - dla tych, którzy chcą żeby ładnie wyglądało, a nie chcą zagłębiać się w CSSY - polecam, dużo ułatwia :).



W pierwszej kolejności robimy zadania z poprzednich zajęć jeśli ktoś nie zrobił.

----
