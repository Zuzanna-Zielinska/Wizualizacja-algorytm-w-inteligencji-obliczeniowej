# Wizualizacja algorytmów w inteligencji obliczeniowej

Repozytorium zawiera opis aplikacji pokazującej działanie algorytmu optymalizacji rojem cząstek oraz szarego wilka. Został w Unreal Engine 4 na potrzeby studiów Automatyki i Robotyki w Akademi Górniczo Hutniczej przez Jacka Ankowskiego, Zuzannę Zielińską oraz Mateusza Kowalskiego. Plik wykonwalny do pobrania [tutaj](https://drive.google.com/file/d/16x_TZzQPa83Vd9F1KRvu027RZfsLp43B/view?usp=drive_link).
<p align="center">
<img src="https://github.com/Zuzanna-Zielinska/Wizualizacja-algorytm-w-inteligencji-obliczeniowej/blob/main/images/i1.png" width="700"/>
</p>

https://github.com/user-attachments/assets/44bbb9bd-7bf4-42f3-873d-9d180d576d7d

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

https://github.com/user-attachments/assets/8944ea7a-af52-49d5-85fa-bc68e6f4314d

## Sterowanie
- <b>A, W, S, D</b> - zmiana pozycji w świecie gry
- <b>Ruch myszki</b> - zmiana obrotu kamery
- <b>R</b> - reset kulek w roju
- <b>Shift</b> - teleporatacja nad środek mapy
- <b>Tab</b> - teleporatacja obok mapy
- <b>Esc</b> - schowanie panelu zmiany parametrów algorytmu oraz panelu symulacji

https://github.com/user-attachments/assets/8b949bdb-5145-4e0b-9b17-9408bb13133e
