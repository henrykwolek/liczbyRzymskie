# Liczby rzymskie
1. Podajemy liczbę np. 2563 <br>
- 2563 >= 1000; więc zwiększamy ją o największą możliwość wartość (1000).
- Dzielenie 2563/1000 -> 2 reszta 563. Odpowiadający symbol **M** zostanie powtórzony dwukrotnie.
2. Otrzymujemy liczbę 563 <br>
- 1000 > 563 >= 500; więc zwiększamy ją o największą możliwość wartość (500).
- Dzielenie 563/500 -> 1 reszta 63. Odpowiadający symbol **D** zostanie powtórzony jednokrotnie.
3. Otrzymujemy liczbę 63 <br>
- 100 > 63 >= 50; więc zwiększamy ją o największą możliwość wartość (50).
- Dzielenie 63/50 -> 1 reszta 13. Odpowiadający symbol **L** zostanie powtórzony jednokrotnie.
4. Otrzymujemy liczbę 13 <br>
- 50 > 13 >= 10; więc zwiększamy ją o największą możliwość wartość (10).
- Dzielenie 13/10 -> 1 reszta 3. Odpowiadający symbol **X** zostanie powtórzony jednokrotnie.
5. Otrzymujemy liczbę 3 <br>
- 5 > 3 >= 1; więc zwiększamy ją o największą możliwość wartość (1).
- Dzielenie 3/1 -> 3 reszta 0. Odpowiadający symbol **I** zostanie powtórzony trzykrotnie.
6. Program doszedł do momentu, gdzie liczba osiągnęła wartość 0, więc tu się zatrzyma i wyświetli liczbę:<br>
>2563 = MMDLXIII
