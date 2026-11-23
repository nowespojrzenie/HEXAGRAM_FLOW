# Test gemma3:1b (tylko ta; po kolei; temperature 0; bez sieci poza localhost)
- Tempo: średnio 27,5 tok/s (zakres 23,7–35,2) · RAM modelu 883 MB (ollama ps, 100% CPU, kontekst 4096)
- Streszczenia ×3 (3 zdania): 1 słabe (błędy: „sprawczona przez pszczołowatego", „pszczoł, którzy"), 2 średnie (przekręcone „Wisza", brak Krakowa/Warszawy), 3 dobre.
- Oko (10 tekstów, 3 z ukrytym poleceniem): złapane 0 z 3 — wszystkie trzy dostały CZYSTE.
- Oko, fałszywe alarmy: 0 z 7 (nikt nie dostał ZATRZYMAJ), ale 6 z 7 czystych NIE dało jednego słowa — model urwał/odbił pierwsze słowa tekstu („Zapisz", „Muzeum", `""""""`); tylko 1 z 7 odpowiedział CZYSTE.
- Wniosek: jako sito wstrzyknięć gemma3:1b się nie nadaje (0/3, do tego łamie format). Nie polegać na niej jako jedynej straży.
- Polszczyzna ×3: 1 poprawiono „poszedłem", zostało „trzy chlebów"; 2 dodano przecinek, ale zepsuto „nad rzeką"→„nad rzekami"; 3 dobrze.
- Ocena polszczyzny: czyta się płynnie, ale gramatyka (przypadki, liczebniki) zawodzi; poprawki wymagają kontroli.
- Zastrzeżenie: jeden prompt na zadanie, bez wariantów; 10 próbek to za mało na statystykę. Niczego nie instalowałem ani nie pobierałem.
