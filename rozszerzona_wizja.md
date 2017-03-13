# Rozszerzona wizja

### Kalendarz

##### Widok kalendaraza
Aplikacja będzie importowała dane z kalendarza Google i wyświetlała ich kiedy użytkownik będzię ustawiać czas obudzenia. 
To będzie główny widok aplikacji. Po otwórzeniu aplikacji na ekranie pojawia się widok podobny do tego, co jest w Google Calendar, na którym są wyświetlane wszystkie zaplanowane zdarzenia na następny dzień. Ten widok będzie miał kilka stron - każdy dzień ma swoją stronę. Strony można zmieniać przeciągając z jednej strony do drugiej. W prawym dolnym rogu będzie przycisk, nacisnięcię na który powoduje stworzenie nowego budzika. Czas budzika będzie ustawiony na tą godzinę, na którą użytkownik przeciągnie budzik. Jeśli użytkownik nie przeciągnął budzik a zostawił go na przycisku, to stworzenie budzika zostanie odwołane. Istnejące budziki są wyświetlane jak paski na planie dnia. Istniejące budziki też można przeciągiwać i usuwać, przeciągając z powrotem na przycisk. 

##### Widok ustawień budzika
Jednorazowe nacisnięcie na pasek budzika powoduje otworzenie nowego widoku, w którym można w tradycyjny sposób zmienić ustawienia budzika: czas, dzwięk, głosność, powtórzenia, imię, dni tygodnia.

1. Czas - tradycyjne pole, gdzie można wprowadzić czas.

2. Dzwięk - tutaj użytkownik może wskazać, którą piosenka czy dzwonek musi zagrać.

3. Głosność - ustawienie głosnośći tego budzika.

4. Powtorzenia - tutaj użytkownik może zmienić ile razy budzik będzie się powtarzał jeśli nie będzie wyłączony, oraz ile czasu musi czekać pomiędzy powtórzeniami.

5. Imię - pole, gdzie użytkownik będzie mógł ustawić imię budzika.

6. Dni - tutaj użytkownik może ustawić, żeby budzik się odpalał tylko w określone dni tygodnia.

##### Widok ustawień ogólnych:
Ten widok zawiera ogólne ustawienia budzików.
Dostępne ustawienia:

1. Domyślne ustawienia dla budzików (głosność, dzwięk, powtórzenia).

2. Aktywacja funkcji automatyczny budzik - budzik który automatycznie się ustawia przed pierwszym zdarzeniem dnia.

3. Czas przed pierwszym zdarzeniem dla automatycznego budzika.

4. Czas przed ustawionym czasem budzenia, kiedy pojawia się przypomnienie o rekomendacji pójścia spać (domyślnie 8 godzin)

#### Widok konfiguracji zadań:
TODO

#### Zadania wyłączające alarm:
Opisy zadań i konfiguracji:

1. Rozwiązywanie wyrażeń.
Jak wskazuje nazwa, zadanie te polega na rozwiązaniu losowych (wygenerowanych) niepowtarzających się (z dużym prawdopodobieństwem) wyrażeń arytmetycznych (typu 12 + 1897 = ? lub ? * 102 = 1224). W widoku konfiguracji zadań będzie dostępna możliwość konfiguracji poziomu trudności tych wyrażeń w postaci drop-down menu z trzema (może się zmienić) wartościami (np. uczeń, student i student MIMu). Interfejs w tym zadaniu jest prosty, bo widok tego zadania zawiera tylko jedne pole dla wpisu odpowiedzi.

2. Potrząsanie komórką.
Te zadanie jest bardzo proste, bo polega na prostym potrząśnięciu komórką co najmniej określoną ilość razy, która pojawia się na ekranie głównym pod teskstem "Potrząśnij komórką", na dole będzie teks "razy". Ze względu na łatwość, co oznacza małą skuteczność obudzenia tego zadania, standardowo ono będzie dodatkowym zadaniem. W widoku konfiguracji zadań będzie dostępna możliwość konfiguracji zakresu, z którego w losowy sposób wybiera się liczba potrząśnięć. Widok konfiguracji będzie zawierał 2 pola: dla wpisania minimalnej i maksymalnej liczby potrząśnięć.


#### Minimalna wersja
W minimalnej wersji nie będzie dodatkowego widoku dla zmiany ustawień budzika oraz możliwości zobaczyć inne dni oprócz następnego.
W minimalnej wersji będzie drag'n'drop oraz widok, pokazujący wszystkie zdarzenia następnego dznia. Też będzie widok ustawień ogólnych, gdzie będzie można tylko włączyć/wyłączyć automatyczny budzik przed pierwszym wydarzeniem dnia.
