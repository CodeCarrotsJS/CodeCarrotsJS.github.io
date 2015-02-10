---
layout: page
title: FAQ
permalink: /faq/
---
###Obsługa polskich znaków w Atomie

Atom dla Windows nie radzi sobie z obsługą niektórych polskich 
znaków. Problem ten dotyczy również dużej części użytowników systemów nieanglojęzycznych
i spowodowany jest obsługą w Windowsie prawego klawisza *Alt (AltGr)*, który, [za Wikipedią:](http://pl.wikipedia.org/wiki/AltGr):
>(...) w układzie klawiatury „Polski programisty” odpowiada kombinacji klawiszy Ctrl + Alt, co jest niekiedy kłopotliwe, gdyż w niektórych aplikacjach, sterownikach i skrótach programów znajdujących się na pulpicie zdefiniowane są skróty klawiaturowe Alt+Ctrl+litera.

Zwykła edycja pliku keymap.cson w tym wypadku nie pomaga, można to obejść przez bezpośrednią edycję pliku win32.json znajdującego się w katalogu: 

C:\Users\\**NazwaUżytownika**\AppData\Local\atom\app-0.176.0\resources\app\keymapsPlik win32.json należy otworzyć dowolnym edytorem tekstu, a następnie wyszukać i zamienić wpisy:

1. `"ctrl-alt-s"` na `"ctrl-alt-9"` (linia 14)
2. `"ctrl-alt-o"` na `"ctrl-alt-8"` (linia 15)
3. `"alt-ctrl-z"` na `"alt-ctrl-7"` (linia 92)

Po zapisaniu zmian i ponownym uruchomieniu Atoma wpisywanie polskich znaków diakrytycznych powinno działać prawidłowo.  
Po aktualizacji Atoma do nowszej wersji (domyśle dzieje się to automatycznie) konieczna może być ponowna edycja pliku win32.json.  
- - - 
### Gdzie będą odbywać sie zajęcia?

Zajęcia odbywać będą się w siedzibie firmy [CKSource](http://cksource.com). Lokal numer 508. Bedąc w budynku dzwonimy domofonem i wjeżdżamy windą na czwarte piętro. Po wyjściu z windy idziemy w prawo.

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2442.31327557718!2d20.987206999999994!3d52.25585600000001!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x471ecb88e1ed5bc5%3A0xd6a4f1da58e2ad25!2sCKSource!5e0!3m2!1spl!2spl!4v1421100308407" width="400" height="300" frameborder="0" style="border:0; width: 100%"></iframe>

![Diagram przepływu](/gfx/diagram-przeplywu.png)