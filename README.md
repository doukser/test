# Algorytm wyznaczania liczb pierwszych


![Algorytm](https://drive.google.com/file/d/1m_7TsZXI1ZClBnbVURPZHv0rBlbEN8IY/view?usp=sharing)
Na początku ja stworzył projekt i zacząłem pisać, stworzył 4 zmiany, pierwsza nazywa się „countTime”, ta zmiana znaczy, ile liczb pokazać, druga zmiana „lp”, ta zmiana znaczy, obecny rachunek, trzecia „countl”, ta zmiana znaczy, ile są dzielników dla liczby, a ostatnia „nextl”, to jest liczba pierwsza. Potem ja napisał na konsole „Podaj ile chcesz wygenerować liczb:”, potem wpisz ile razy wygenerować liczb. Idziemy dalie, stworzył pętla while, i sprawdzam czy zmiana „lp” mniej countTime, jeżeli tak to idzie dalie lub koniec, potem używam pętla for і pisze coś takiego, jak „for(int d = 2; d <= nextl - 1; d++)”, zmiana „d” będzie przechować dzielnik do liczby „nextl”, potem w tej pętle sprawdzam czy liczba „d” może podzielić przez „nextl”, coś takiego „if(nextl % d == 0)”, jeżeli to jest prawda to w zmianą „countl” dodaję 1 to znaczy że jest nowy dzielnik, potem sprawdzam jeżeli dzielników równo 0 to pisze liczbę w konsole, i robię następny ruch „lp++”, inaczej następna liczba „nextl++”, i zeruję „countl”, to dopóki „lp” będzie równe „countTime”. 