# Klasyczna Gra Blackjack (Blackjack Web Game) 
Interaktywna gra karciana w przeglądarce, stworzona w czystym **JavaScript (Vanilla JS)**, **HTML5** i **CSS3** w środowisku **Vite**.

https://startling-scone-dedf23.netlify.app/

---

## Funkcjonalności i logika gry

* **Losowanie kart:** System przypisuje wartość 10 dla figur (Walet, Dama, Król) oraz 11 dla Asa.
* **Zarządzanie stanem (Game State):** Dynamiczne sprawdzanie warunków wygranej (Blackjack = 21) lub przegranej (Suma > 21).
* **Guard Clauses:** Zabezpieczenie przed dobieraniem kart po zakończeniu gry (`isAlive`, `hasBlackJack`).

## Zastosowane koncepty JS & CSS

* **Vanilla JS:** Obiekty (dane gracza), tablice (`cards.push()`), pętla `for` (renderowanie kart) oraz instrukcje warunkowe.
* **ES6 Modules:** Świadome użycie obiektu `window` do upublicznienia funkcji ze skryptu modułowego dla zdarzeń `onclick`.
* **CSS3:** Stylizacja stylizowana na stół kasynowy z dopasowaniem tła (`background-size: cover`).

---
