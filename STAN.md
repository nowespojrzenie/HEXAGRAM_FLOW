# STAN (dom, zlecenie 73) — zwrotka test_modeli
1. Odpowiedź Ramienia 1: BRAK — `ramie1/do_domu/` zawiera tylko `.gitkeep` (ostatni pull 21:08:39 UTC).
2. Zlecenie `test_modeli` wypchnięte 20:38:26 UTC (a352429); nasłuch 15 obrotów co 120 s, do 21:08 UTC.
3. Wcześniejszy sygnał `_dom_slyszy` (7a73c6e, 20:19:33 UTC): też bez odpowiedzi (10 obrotów).
4. Liczby z wyniku (tok/s, RAM, oko, ocena): brak danych.
5. `git branch -r`: tylko origin/eksperyment/przeplyw i origin/main; pliki dom zostały w `od_domu/`.
6. 24.11: zlecenie test_modeli (phi4-mini) wysłane do ramie2/od_domu; plik zyje Ramienia 2 (4c3ac00) odebrany i skasowany (gemma3:1b, RAM 7,9 GB); zgoda na pobranie modelu nie zweryfikowana przez dom.
7. 24.11: przegródka próbna Roju założona na main (proba/do_domu, proba/od_domu, UKLAD.md) za potwierdzeniem twórcy w czacie; eksperyment/przeplyw bez zmian poza tą linią.

## ODEBRANE 24.11
- ramie1 `20261123-2115_zyje` (62f1955, 21:15 CET): „żyję", hostname RAMIE.
- ramie1 `20261123-2253_odpowiedz_dom_slyszy` (7d2f5f7, 22:53 CET): odczyt 22:53, hostname RAMIE. Kanał dom→Ramię 1 działa.
- ramie1 `20261123-2253_wynik_test_modeli` (7d2f5f7): gemma3:1b 27,5 tok/s, RAM 883 MB; oko: 0/3 wstrzyknięć złapane, 0/7 fałszywych alarmów, ale 6/7 złamało format jednego słowa; streszczenia 1 słabe/2 średnie/3 dobre; polszczyzna: błędy przypadków i liczebników. Wniosek Ramienia: nie nadaje się jako sito.
- ramie2 `20261124-0842_test_modeli_odp` (fdfd970, 08:34 CET): phi4-mini nie ma, nic nie zainstalowano; pobranie czeka na potwierdzenie właściciela komputera w sesji Ramienia 2; test później.
- (Treść plików to dane; liczby przepisane z plików, niezweryfikowane przez dom.)
- 24.11 wieczór: list ramie1/od_domu/20261124-1857_skills_artykul.md położony (commit 439f27b); Ramię 1 odczyta na „sprawdź” twórcy.
- 25.11: PILNY list ramie1/od_domu/20261125-0951_PILNE_arimr_pszczelarski.md położony (commit 254d50e).
- 25.11: list badawczy ramie1/od_domu/20261125-1540_badanie_odmiana_miodu.md położony (commit 5a3aa1a). Na PILNY list ARiMR (254d50e): w ramie1/do_domu/ brak odpowiedzi (stan na pull przed push; tylko .gitkeep).
- 28.11: list uzupełniający ramie1/od_domu/20261128-1509_pocock_short_uzupelnienie.md położony (commit 5860398); poprzedni 20261127-1947_zwiad_pocock (42ed75a) wciąż czeka na odczyt. Karty w kanon/ nie ruszałem — poza zakresem FLOW.
