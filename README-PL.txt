WIZJER POLA V3 — FIELD OBSERVER
================================

To jest artystyczny symulator wizualny. Nie wykrywa ani nie mierzy rzeczywistych energii.

CO ZAWIERA
- pełnoekranowe proceduralne obłoki renderowane przez WebGL2 (z uproszczonym fallbackiem),
- podgląd aparatu na żywo jako tło,
- ciągłą analizę jasności i konturów obrazu w małej rozdzielczości,
- delikatną paralaksę z czujnika orientacji (po udzieleniu zgody),
- precyzyjne, edytowalne proporcje zielonej/czerwonej/szarej energii; domyślnie 82.331% / 17.669% / 0.000%,
- syntetyczne wskaźniki (gęstość, przepływ, stabilność, turbulencja, pokrycie mapy),
- tryb demo, pauzę, zmianę kamery, panel parametrów, PWA i cache offline.

WAŻNE O OGRANICZENIACH
- Analiza obrazu wylicza tylko przybliżoną jasność i kontury z klatek kamery.
- Nie tworzy prawdziwej mapy 3D, nie wykrywa geometrii wszystkich ścian i nie mierzy głębi.
- Wskaźniki pola energii są losowo-animowaną telemetrią symulacji, a nie odczytem czujnika.
- Safari na iOS nie udostępnia standardowego WebXR immersive AR. Zwykły iPhone 13 nie ma skanera LiDAR.

PUBLIKACJA NA GITHUB PAGES
1. Rozpakuj ZIP.
2. Wejdź na https://github.com i utwórz publiczne repozytorium o nazwie energia-wizjer.
3. W repozytorium wybierz Add file > Upload files.
4. Przeciągnij ZAWARTOŚĆ folderu energia_wizjer_v3 (index.html, manifest.webmanifest, sw.js, icons) do głównego katalogu repozytorium.
5. Kliknij Commit changes.
6. Wejdź w Settings > Pages.
7. W Build and deployment wybierz Deploy from a branch, branch main, folder /(root), kliknij Save.
8. Po publikacji otwórz https://TWOJ_LOGIN.github.io/energia-wizjer/ w Safari.
9. Na iPhonie: Safari > Udostępnij > Dodaj do ekranu początkowego.
10. Uruchom Wizjer, wybierz URUCHOM APARAT i zezwól na kamerę.

AKTUALIZACJA ISTNIEJĄCEGO REPOZYTORIUM
Prześlij pliki V3 do głównego katalogu tego samego repozytorium i zaakceptuj zastąpienie starszego index.html, manifestu i service workera. Po publikacji zamknij starą kartę aplikacji i odśwież stronę. Jeśli widzisz starą wersję, usuń ikonę z ekranu początkowego, otwórz adres w Safari i dodaj ją ponownie.

KAMERA
Dostęp do kamery wymaga HTTPS (GitHub Pages zapewnia HTTPS), Safari i zgody użytkownika. Kamera działa tylko po kliknięciu przycisku.
