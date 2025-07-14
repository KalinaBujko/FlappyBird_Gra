# Flappy Bird – Projekt w Flutterze z logiką w C++

Ten projekt to implementacja klasycznej gry Flappy Bird zrealizowana w **Flutterze**, z wykorzystaniem **Flame** – lekkiego silnika 2D do gier – oraz z dodatkowymi komponentami napisanymi w **C++**, odpowiedzialnymi za logikę gry. Aplikacja została przygotowana z myślą o wielu platformach (web, desktop, mobile).

## Opis gry

Gracz steruje postacią ptaka, którego zadaniem jest przelatywanie między przeszkodami w postaci rur. Gra kończy się po kolizji z przeszkodą. System punktacji opiera się na liczbie ominiętych przeszkód.

### Funkcje:
- Prosta mechanika oparta na jednym przycisku (tap lub spacja),
- Proceduralnie generowane przeszkody,
- Ekran startowy i ekran końcowy z wynikiem,
- Obsługa kolizji i detekcja stanu gry.

## Technologie

- **Flutter** – interfejs użytkownika i zarządzanie stanem gry,
- **Flame** – 2D game engine oparty na Flutterze,
- **C++** – część logiki gry (np. kolizje, fizyka, punkty),
- **Dart FFI** – integracja kodu natywnego C++ z aplikacją Flutter.

Projekt został zrealizowany samodzielnie. Odpowiadałam za:
- implementację mechaniki gry,
- integrację Fluttera z logiką w C++,
- stworzenie layoutów ekranów oraz obsługę zdarzeń wejściowych,
- zapewnienie działania na wielu platformach (Android/Web/Desktop).



