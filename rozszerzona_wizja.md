# Rozszerzona wizja

### Kalendarz

##### Widok kalendaraza
Aplikacja będzie importowała dane z kalendarza Google i wyświetlała je, kiedy użytkownik będzie ustawiać czas obudzenia. 
To będzie główny widok aplikacji. Po otworzeniu aplikacji na ekranie pojawia się widok podobny do tego, jaki jest w Google Calendar, na którym są wyświetlane wszystkie zaplanowane zdarzenia na następny dzień. Ten widok będzie miał kilka stron - każdy dzień ma swoją stronę. Strony można zmieniać przeciągając z jednej strony do drugiej. W prawym dolnym rogu będzie przycisk, nacisnięcie na który powoduje stworzenie nowego budzika. Czas budzika będzie ustawiony na tą godzinę, na którą użytkownik przeciągnie budzik. Jeśli użytkownik nie przeciągnął budzika, a zostawił go na przycisku, to stworzenie budzika zostanie odwołane. Istnejące budziki są wyświetlane jak paski na planie dnia. Istniejące budziki też można przeciągać i usuwać, przeciągając z powrotem na przycisk. 

##### Widok ustawień budzika
Jednorazowe nacisnięcie na pasek budzika powoduje otworzenie nowego widoku, w którym można w tradycyjny sposób zmienić ustawienia budzika: czas, dzwięk, głosność, powtórzenia, nazwę, dni tygodnia.

1. Czas - tradycyjne pole, gdzie można wprowadzić czas.

2. Dzwięk - tutaj użytkownik może wskazać, którą piosenka dzwonek musi zagrać.

3. Głosność - ustawienie głosności tego budzika.

4. Powtórzenia - tutaj użytkownik może zmienić ile razy budzik będzie się powtarzał jeśli nie będzie wyłączony, oraz ile czasu musi czekać pomiędzy powtórzeniami.

5. Nazwa - pole, gdzie użytkownik będzie mógł ustawić nazwę budzika.

6. Dni - tutaj użytkownik może ustawić, żeby budzik się odpalał tylko w określone dni tygodnia.

##### Widok ustawień ogólnych:
Ten widok zawiera ogólne ustawienia budzików.
Dostępne ustawienia:

1. Domyślne ustawienia dla budzików (głosność, dzwięk, powtórzenia).

2. Aktywacja funkcji automatyczny budzik - budzik który automatycznie się ustawia przed pierwszym zdarzeniem dnia.

3. Czas przed pierwszym zdarzeniem dla automatycznego budzika.

4. Czas przed ustawionym czasem budzenia, kiedy pojawia się przypomnienie o rekomendacji pójścia spać (domyślnie 8 godzin)

#### Widok konfiguracji zadań:
Widok konfiguracji zadań umożliwia wybór zadań, spośród których w trakcie alarmu będzie losowane zadanie. W podstawowym widoku konfiguracji wyświetlana będzie lista dostępnych zadań. Użytkownik będzie mógł zaznaczyć checkboxy przy dowolnej liczbie zadań. Przy każdym będzie znajdował się przycisk ustawień, który pozwala na konfigurację opcji specyficznych dla danego zadania. Po jego kliknięciu otwierać się będzie widok konfiguracji konkretnego zadania. Żeby zwiększyć prawdopodobieństwo rozbudzenia, możliwe będzie także ustawienie większej niż jeden liczby zadań, które trzeba będzie wykonać, żeby wyłączyć alarm.
Jeśli do sprawdzenia zadania potrzebny jest czujnik, w który telefon nie jest wyposażony (na przykład akcelerometr lub GPS), to zadanie nie będzie dostępne do zaznaczenia. W takim wypadku będzie ono wyświetlane na szaro z informacją o brakujących wymaganiach.

#### Zadania wyłączające alarm:
Opisy zadań i konfiguracji:

1. Rozwiązywanie wyrażeń.
Jak wskazuje nazwa, zadanie te polega na rozwiązaniu losowych (wygenerowanych) niepowtarzających się (z dużym prawdopodobieństwem) wyrażeń arytmetycznych (typu 12 + 1897 = ? lub ? * 102 = 1224). W widoku konfiguracji zadań będzie dostępna możliwość konfiguracji poziomu trudności tych wyrażeń w postaci drop-down menu z trzema (może się zmienić) wartościami (np. uczeń, student i student MIMu). Interfejs w tym zadaniu jest prosty, bo widok tego zadania zawiera tylko jedne pole dla wpisu odpowiedzi.

2. Potrząsanie komórką.
Te zadanie jest bardzo proste, bo polega na prostym potrząśnięciu komórką co najmniej określoną ilość razy, która pojawia się na ekranie głównym pod teskstem "Potrząśnij komórką", na dole będzie tekst "razy". Ze względu na łatwość zadania, co oznacza małą skuteczność budzenia tego zadania, standardowo będzie ono dodatkowym zadaniem. W widoku konfiguracji zadań będzie dostępna możliwość konfiguracji zakresu, z którego w losowy sposób wybiera się liczba potrząśnięć. Widok konfiguracji będzie zawierał 2 pola: dla wpisania minimalnej i maksymalnej liczby potrząśnięć.

3. Pytanie o litery alfabetu.
Zadanie polega na kilkukrotnym pytaniu o pewną literę alfabetu. Konfiguracja zadania sprowadza się do podania liczby pytań oraz zaznaczenia języków, o których alfabety użytkownik chce być pytany. Pytania mogą być postaci "Podaj czwartą literę alfabetu angielskiego", "Podaj trzecią od końca literę alfabetu rosyjskiego" lub "Podaj piątą literę po 'ń' w alfabecie polskim". Każdorazowe błędne podanie litery będzie skutkowało zwiększeniem liczby pozostałych pytań o 2, więc zgadywanie nie będzie opłacalne.

4. Przepisywanie tekstu.
Celem zadania jest bezbłędne przepisanie wyświetlonego tekstu do pola tekstowego poniżej. Teksty do przepisania będą pochodziły z różnych dzieł literackich. Użytkownik będzie mógł skonfigurować język oraz długość tekstów oraz liczbę błędów, po przekroczeniu której nastąpi wygenerowanie nowego tekstu. Wprowadzany przez użytkownik tekst będzie na bieżąco monitorowany pod kątem błędów, a po każdym popełnionym błędzie nastąpi sygnał ostrzegawczy. Żeby uniemożliwić oszukiwanie, po wykryciu wklejenia lub użycia podpowiadania zostanie wygenerowany nowy tekst.


#### Minimalna wersja
W minimalnej wersji nie będzie dodatkowego widoku dla zmiany ustawień budzika oraz możliwości zobaczyenia innych dni oprócz następnego.
W minimalnej wersji będzie drag'n'drop oraz widok pokazujący wszystkie zdarzenia następnego dnia. Będzie też widok ustawień ogólnych, gdzie będzie można tylko włączyć/wyłączyć automatyczny budzik przed pierwszym wydarzeniem dnia.
