---
sidebar_position: 2
#
# This file is autogenerated. DO NOT MODIFY DIRECTLY
#
---

import ScriptEventPreview from '@site/src/components/ScriptEventPreview';

# Kolor

## Warunek: urządzenie obsługuje kolor
Warunkowe uruchomienie części skryptu, jeżeli gra jest uruchomiona na urządzeniu lub emulatorze obsługującym gry kolorowe.
<ScriptEventPreview title={"Warunek: urządzenie obsługuje kolor"} fields={[{"key":"true","label":"Prawda","description":"Skrypt do uruchomienia, jeśli warunek jest spełniony (prawda).","type":"events"},{"key":"__collapseElse","label":"W innym wypadku","type":"collapsable","defaultValue":true,"conditions":[{"key":"__disableElse","ne":true}]},{"key":"false","label":"Fałsz","description":"Skrypt do uruchomienia, jeśli warunek jest nie spełniony (fałsz).","conditions":[{"key":"__collapseElse","ne":true},{"key":"__disableElse","ne":true}],"type":"events"}]} />

- **Prawda**: Skrypt do uruchomienia, jeśli warunek jest spełniony (prawda).  
- **Fałsz**: Skrypt do uruchomienia, jeśli warunek jest nie spełniony (fałsz).  

## Warunek: tryb GBA jest aktywny
Warunkowe uruchomienie części skryptu, jeżeli gra jest uruchomiona na urządzeniu lub emulatorze obsługującym gry GBA.
<ScriptEventPreview title={"Warunek: tryb GBA jest aktywny"} fields={[{"key":"true","label":"Prawda","description":"Skrypt do uruchomienia, jeśli warunek jest spełniony (prawda).","type":"events"},{"key":"__collapseElse","label":"W innym wypadku","type":"collapsable","defaultValue":true,"conditions":[{"key":"__disableElse","ne":true}]},{"key":"false","label":"Fałsz","description":"Skrypt do uruchomienia, jeśli warunek jest nie spełniony (fałsz).","conditions":[{"key":"__collapseElse","ne":true},{"key":"__disableElse","ne":true}],"type":"events"}]} />

- **Prawda**: Skrypt do uruchomienia, jeśli warunek jest spełniony (prawda).  
- **Fałsz**: Skrypt do uruchomienia, jeśli warunek jest nie spełniony (fałsz).  

## Warunek: tryb Super GB jest aktywny
Warunkowe uruchomienie części skryptu, jeżeli gra jest uruchomiona na urządzeniu lub emulatorze obsługującym gry Super GB.
<ScriptEventPreview title={"Warunek: tryb Super GB jest aktywny"} fields={[{"key":"true","label":"Prawda","description":"Skrypt do uruchomienia, jeśli warunek jest spełniony (prawda).","type":"events"},{"key":"__collapseElse","label":"W innym wypadku","type":"collapsable","defaultValue":true,"conditions":[{"key":"__disableElse","ne":true}]},{"key":"false","label":"Fałsz","description":"Skrypt do uruchomienia, jeśli warunek jest nie spełniony (fałsz).","conditions":[{"key":"__collapseElse","ne":true},{"key":"__disableElse","ne":true}],"type":"events"}]} />

- **Prawda**: Skrypt do uruchomienia, jeśli warunek jest spełniony (prawda).  
- **Fałsz**: Skrypt do uruchomienia, jeśli warunek jest nie spełniony (fałsz).  

## Paleta: ustaw paletę tła
Polecenie nadpisuje niektóre lub wszystkie palety tła bieżącej sceny.
<ScriptEventPreview title={"Paleta: ustaw paletę tła"} fields={[{"key":"palette0","label":"Palety","description":"Nowy zestaw palet do użycia.","type":"palette","defaultValue":"keep","paletteType":"background","paletteIndex":0,"canKeep":true},{"key":"palette1","type":"palette","defaultValue":"keep","paletteType":"background","paletteIndex":1,"canKeep":true},{"key":"palette2","type":"palette","defaultValue":"keep","paletteType":"background","paletteIndex":2,"canKeep":true},{"key":"palette3","type":"palette","defaultValue":"keep","paletteType":"background","paletteIndex":3,"canKeep":true},{"key":"palette4","type":"palette","defaultValue":"keep","paletteType":"background","paletteIndex":4,"canKeep":true},{"key":"palette5","type":"palette","defaultValue":"keep","paletteType":"background","paletteIndex":5,"canKeep":true},{"key":"palette6","type":"palette","defaultValue":"keep","paletteType":"background","paletteIndex":6,"canKeep":true},{"key":"palette7","type":"palette","defaultValue":"keep","paletteType":"background","paletteIndex":7,"canKeep":true}]} />

- **Palety**: Nowy zestaw palet do użycia.  

## Paleta: ustaw paletę emotek
Polecenie zastąpi palętę dla emotek (paleta #8).
<ScriptEventPreview title={"Paleta: ustaw paletę emotek"} fields={[{"key":"palette","label":"Paleta","description":"Nowa paleta do użycia.","type":"palette","defaultValue":"","paletteType":"emote"}]} />

- **Paleta**: Nowa paleta do użycia.  

## Paleta: ustaw paletę obiektów
Polecenie zastąpi niektóre lub wszystkie palety dla bieżącej.
<ScriptEventPreview title={"Paleta: ustaw paletę obiektów"} fields={[{"key":"palette0","label":"Palety","description":"Nowy zestaw palet do użycia.","type":"palette","defaultValue":"keep","paletteType":"sprite","paletteIndex":0,"canKeep":true},{"key":"palette1","type":"palette","defaultValue":"keep","paletteType":"sprite","paletteIndex":1,"canKeep":true},{"key":"palette2","type":"palette","defaultValue":"keep","paletteType":"sprite","paletteIndex":2,"canKeep":true},{"key":"palette3","type":"palette","defaultValue":"keep","paletteType":"sprite","paletteIndex":3,"canKeep":true},{"key":"palette4","type":"palette","defaultValue":"keep","paletteType":"sprite","paletteIndex":4,"canKeep":true},{"key":"palette5","type":"palette","defaultValue":"keep","paletteType":"sprite","paletteIndex":5,"canKeep":true},{"key":"palette6","type":"palette","defaultValue":"keep","paletteType":"sprite","paletteIndex":6,"canKeep":true},{"key":"palette7","type":"palette","defaultValue":"keep","paletteType":"sprite","paletteIndex":7,"canKeep":true}]} />

- **Palety**: Nowy zestaw palet do użycia.  

## Paleta: ustaw paletę UI
Polecenie zastąpuje paletę użytą przez interfejs użytkownika UI (paleta tła #8).
<ScriptEventPreview title={"Paleta: ustaw paletę UI"} fields={[{"key":"palette","label":"Paleta","description":"Nowa paleta do użycia.","type":"palette","defaultValue":"","paletteType":"ui"}]} />

- **Paleta**: Nowa paleta do użycia.  
