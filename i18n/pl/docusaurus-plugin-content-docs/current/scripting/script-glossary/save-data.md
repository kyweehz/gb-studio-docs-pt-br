---
sidebar_position: 2
#
# This file is autogenerated. DO NOT MODIFY DIRECTLY
#
---

import ScriptEventPreview from '@site/src/components/ScriptEventPreview';

# Zapis gry

## Stan gry: wczytaj
Polecenie wczytuje zapisany stan gry z wybranego miejsca.
<ScriptEventPreview title={"Stan gry: wczytaj"} fields={[{"label":"Wczytaj dane gry z pamięci."},{"key":"saveSlot","label":"Zapisz plik","description":"Określenie miejsca zapisu.","type":"togglebuttons","options":[[0,"Plik 1","Zapisz plik 1"],[1,"Plik 2","Zapisz plik 2"],[2,"Plik 3","Zapisz plik 3"]],"allowNone":false,"defaultValue":0}]} />

- **Zapisz plik**: Określenie miejsca zapisu.  

## Stan gry: czyść
Polecenie czyści wcześniejszy zapisany stan gry w wybranym miejscu.
<ScriptEventPreview title={"Stan gry: czyść"} fields={[{"label":"Czyści wszystkie wcześniejsze zapisane stany gry z pamięci."},{"key":"saveSlot","label":"Zapisz plik","description":"Określenie miejsca zapisu.","type":"togglebuttons","options":[[0,"Plik 1","Zapisz plik 1"],[1,"Plik 2","Zapisz plik 2"],[2,"Plik 3","Zapisz plik 3"]],"allowNone":false,"defaultValue":0}]} />

- **Zapisz plik**: Określenie miejsca zapisu.  

## Stan gry: zapisz
Polecenie zapisuje stan gry do wybranego miejsca.
<ScriptEventPreview title={"Stan gry: zapisz"} fields={[{"label":"Zapisuje aktualny stan gry do pamięci. Wymagany jest kardridż z baterią."},{"key":"saveSlot","label":"Zapisz plik","description":"Określenie miejsca zapisu.","type":"togglebuttons","options":[[0,"Plik 1","Zapisz plik 1"],[1,"Plik 2","Zapisz plik 2"],[2,"Plik 3","Zapisz plik 3"]],"allowNone":false,"defaultValue":0},{"key":"__scriptTabs","type":"tabs","defaultValue":"save","values":{"save":"Przy zapisie"}},{"key":"true","label":"Przy zapisie","description":"Skrypt do wykonania po zakończeniu zapisu. Funkcja nie zostanie uruchomiona podczas wczytania gry, zatem można użyć tej opcji do wyświetlenia komunikatu np. 'Zapisano stan gry!'.","type":"events"}]} />

- **Zapisz plik**: Określenie miejsca zapisu.  
- **Przy zapisie**: Skrypt do wykonania po zakończeniu zapisu. Funkcja nie zostanie uruchomiona podczas wczytania gry, zatem można użyć tej opcji do wyświetlenia komunikatu np. 'Zapisano stan gry!'.  

## Warunek: stan gry zapisano
Warunkowe uruchomienie części skryptu, jeżeli stan zapisu jest w określonym miejscu zapisu.
<ScriptEventPreview title={"Warunek: stan gry zapisano"} fields={[{"key":"saveSlot","label":"Zapisz plik","description":"Określenie miejsca zapisu.","type":"togglebuttons","options":[[0,"Plik 1","Zapisz plik 1"],[1,"Plik 2","Zapisz plik 2"],[2,"Plik 3","Zapisz plik 3"]],"allowNone":false,"defaultValue":0},{"label":"Uruchom, gdy gracz wykonał zapis gry."},{"key":"true","label":"Prawda","description":"Skrypt do uruchomienia, jeśli warunek jest spełniony (prawda).","type":"events"},{"key":"__collapseElse","label":"W innym wypadku","type":"collapsable","defaultValue":true,"conditions":[{"key":"__disableElse","ne":true}]},{"key":"false","label":"Fałsz","description":"Skrypt do uruchomienia, jeśli warunek jest nie spełniony (fałsz).","conditions":[{"key":"__collapseElse","ne":true},{"key":"__disableElse","ne":true}],"type":"events"}]} />

- **Zapisz plik**: Określenie miejsca zapisu.  
- **Prawda**: Skrypt do uruchomienia, jeśli warunek jest spełniony (prawda).  
- **Fałsz**: Skrypt do uruchomienia, jeśli warunek jest nie spełniony (fałsz).  

## Zmienna: wartość z zapisu do zmiennej
Polecenie odczytuje wartość zmiennej z określonego miejsca zapisu, a następnie zapisuje ją do zmiennej.
<ScriptEventPreview title={"Zmienna: wartość z zapisu do zmiennej"} fields={[{"key":"variableDest","label":"Ustaw zmienną","description":"Zmienna do aktualizacji.","type":"variable","defaultValue":"LAST_VARIABLE"},{"type":"group","fields":[{"key":"variableSource","label":"Dodaj do zmiennej","description":"Zmienna do odczytania wartości.","type":"variable","defaultValue":"LAST_VARIABLE"},{"key":"saveSlot","label":"Zapisz z pliku","description":"Określenie miejsca zapisu.","type":"togglebuttons","options":[[0,"Plik 1","Zapisz plik 1"],[1,"Plik 2","Zapisz plik 2"],[2,"Plik 3","Zapisz plik 3"]],"allowNone":false,"defaultValue":0}]}]} />

- **Ustaw zmienną**: Zmienna do aktualizacji.  
- **Dodaj do zmiennej**: Zmienna do odczytania wartości.  
- **Zapisz z pliku**: Określenie miejsca zapisu.  
