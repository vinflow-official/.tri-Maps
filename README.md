# VINFlow

A lightweight C++ application framework. To utilize the visual check (Line of Sight) features, map geometry files (`.tri`) must be installed locally.

---

## English Setup Guide

### Prerequisites
* Windows 10 / 11
* Administrator privileges (required for system-level operations)

### Map Files Installation
The application requires pre-compiled triangle mesh data (`.tri` files) to calculate visibility checks externally without relying on game engine functions.

1. Download the maps archive containing the `.tri` files.
2. Navigate to the following directory on your system: `C:\VINFlow\maps` (if the folder does not exist, run the application once or create it manually).
3. Paste the downloaded ZIP file into that directory.
4. Unpack/extract the contents directly into `C:\VINFlow\maps`.
5. Ensure the files (e.g., `de_mirage.tri`, `de_inferno.tri`) are placed directly in the `maps` folder, not inside another subfolder.

And you're done! You can now launch the application.

---

## Instrukcja po Polsku

### Wymagania
* System Windows 10 / 11
* Uprawnienia administratora

### Instalacja Plików Map
Program wymaga plików geometrii siatki map (pliki `.tri`) do zewnętrznego obliczania widoczności celów bez wywoływania funkcji silnika gry.

1. Pobierz archiwum z mapami zawierające pliki `.tri`.
2. Przejdź do folderu: `C:\VINFlow\maps` (jeśli folder nie istnieje, uruchom program po raz pierwszy lub utwórz go ręcznie).
3. Wklej pobrany plik ZIP do tego katalogu.
4. Rozpakuj zawartość bezpośrednio w `C:\VINFlow\maps`.
5. Upewnij się, że pliki (np. `de_mirage.tri`, `de_inferno.tri`) znajdują się bezpośrednio w folderze `maps`, a nie w kolejnym podfolderze.

Gotowe! Możesz teraz uruchomić aplikację.
