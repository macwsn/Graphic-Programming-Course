# Computer Graphic Programming Course

### Lab 1 - Podstawy Three.js
- **Plik:** `lab1/lab1_implementation.html`
- **Zawartość:** Wprowadzenie do Three.js z prostą sceną zawierającą:
  - Scenę (Scene)
  - Kamerę perspektywiczną (PerspectiveCamera)
  - Renderer WebGL
  - Proste obiekty 3D (choinka, pojazd, dom)
  - Efekty cząsteczkowe (dym)

### Lab 2 - Zaawansowane kontrolki kamery
- **Pliki:** `lab2/*.html`
- **Zawartość:**
  - Kontrolki OrbitControls
  - Zaawansowana nawigacja sceną
  - Wykorzystanie bibliotek pomocniczych (dat.gui, stats)

### Lab 3 - Teksturowanie i oświetlenie
- **Pliki:** `lab3/*.html`
- **Zawartość:**
  - Tekstury (01-basic-texture.html)
  - Bump mapping (02-bump-map.html)
  - Normal mapping (03-normal-map.html)
  - Skybox (04-skybox.html)
  - Refleksja (05-reflection.html)
  - Zaawansowane sterowanie i UI

### Lab 4 - Kontrolki i nawigacja
- **Pliki:** `lab4/*.html`
- **Zawartość:**
  - TrackballControls (01_controls_trackball.html)
  - OrbitControls (02_controls_orbit.html)
  - PointerLockControls (03_controls_pointerlock_solvelab4.html)

### Lab 5 - Fizyka w równoleganu 3D
- **Pliki:** `lab5/*.html`
- **Zawartość:**
  - Symulacja fizyki z biblioteki Ammo.js
  - Kolizje między obiektami
  - Dynamika i grawitacja
  - Obiekty: piłki, łopaty, bryły geometryczne

### Lab 6 - Zaawansowane modele i animacje
- **Katalog:** `lab6/`
- **Zawartość:**
  - Importowanie modeli FBX
  - Animacje szkieletowe (skeletal animation)
  - Przykłady WebGL z Three.js Examples
  - Zaawansowane kontrolki i efekty

### Project - Symulacja płomienia
- **Plik:** `project/Projektv2.html`
- **Zawartość:**
  - Symulacja płomienia z wykorzystaniem systemu cząsteczek
  - Interaktywne lustro z refleksją
  - Zaawansowana fizyka cząsteczek
  - Kontrolki mysząOrbitControls oraz możliwość interakcji

## 🚀 Jak uruchomić

Każde lab i projekt to samodzielny plik HTML. Aby je uruchomić:

1. **Lokalnie z przeglądarki:**
   ```bash
   # Otwórz plik HTML bezpośrednio w przeglądarce
   # np. dla Lab 1: lab1/lab1_implementation.html
   ```

2. **Z lokalnym serwerem (zalecane):**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (http-server)
   npx http-server
   ```
   Następnie wejdź na `http://localhost:8000` i wybierz plik HTML.

## 📚 Technologie

- **Three.js** - Główna biblioteka WebGL
- **Ammo.js** - Fizyka (Lab 5)
- **dat.gui** - Interfejs kontrolny
- **Tween.js** - Animacje (Lab 5)
- **Detector.js** - Detekcja obsługi WebGL
- **OrbitControls** - Kontrola kamery

## 🎮 Sterowanie

### Ogólne (większość scen)
- **Mysz** - Obracanie kamery
- **Scroll** - Przybliżanie/oddalanie
- **Lewy przycisk myszki** - Rotacja
- **Prawy przycisk myszki** - Panorama (niektóre kontrolki)

### Project - Symulacja płomienia
- **Mysz** - Obracanie i przybliżanie sceny
- **Klik na płomień** - Zdmuchnięcie/rozwianie płomienia

## ✨ Przykładowe cechy implementacji

- Systemy cząsteczek
- Odbicia (Reflection/Reflector)
- Textury i normal mapping
- Animacje szkieletowe
- Symulacja fizyki
- Kontrolki kamery
- Interfejsy GUI
