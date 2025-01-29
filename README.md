# Wizualizacja algorytmów w inteligencji obliczeniowej

Repozytorium zawiera plik wykonywalny aplikacji pokazującej działanie algorytmu optymalizacji rojem cząstek oraz szarego wilka. Został w Unreal Engine 4 na potrzeby studiów Automatyki i Robotyki w Akademi Górniczo Hutniczej przez Jacka Ankowskiego, Zuzannę Zielińską oraz Mateusza Kowalskiego.

## Działanie aplikacji

Na górnym pasku jest napisana nazwa badanej funkcji oraz współrzędne aktualnie znalezionego najmniejszego punktu. W świecie gry ten punkt reprezentuje złota kula wstrzeliwująca w górę strumień światła.

W lewym dolnym rogu jest widok rzutu z góry. U dołu po środku prezentuje się panel z możliwością zmiany algorytmu optymalizacji oraz jego parametrów. Dodatkowo pokazane są wzory sterujące jego działaniem.

W prwym dolnym rogo znajduje się panel sterujący parametrami symulacji. Można w nim zmienić: 
 - jak cząstki obchodzą się z granicą. Do wyboru jest odbicie, przejście na drugą stronę płaszczyzny, zatrzymanie i ignorowanie granicy.
 - średnicę płaszczyzny. Płaszczyzna zawsze jest kwadratem, którego środek znajduje się w punkcie (0, 0, 0). Minimalna szerokość płaszczyzny to 400 a maksymalna 2200.
 - liczbę kulek w rzędzie i kolumnie. Na począstku symulacji rój przyjmuje kształt kwadratu, którego środkiem jest punkt (0, 0, 0). Cząstki są w odległości 10 od siebie w osi X i Y.
 - wzór badanej funkcji. Można wspisać samemu lub wybrać jedną z predefiniowanych.
 - prędkość symulacji. Największa to 1, czyli bez sztucznego spowolnienia a najmniejsza to 0,001.
 - przycisk stop, zatrzymujący lub wznawiajacy symulację.
 - przycisk wyjścia z aplikacji.


## Sterowanie
- <b>A, W, S, D</b> - zmiana pozycji w świecie gry
- <b>Ruch myszki</b> - zmiana obrotu kamery
- <b>R</b> - reset kulek w roju
- <b>Shift</b> - teleporatacja nad środek mapy
- <b>Tab</b> - teleporatacja obok mapy
- <b>Esc</b> - schowanie panelu zmiany parametrów algorytmu oraz panelu symulacji
