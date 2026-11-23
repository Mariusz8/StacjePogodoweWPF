🌦️ Stacje Pogodowe – WPA

<p align="center">
**Aplikacja desktopowa do zarządzania i analizy pomiarów pogodowych**

Zbudowana w C# z wykorzystaniem technologii WPF.

</p>

📌 O projekcie

Stacje Pogodowe to aplikacja desktopowa stworzona w ramach projektu WPA. Jej zadaniem jest odczytywanie, przechowywanie i analizowanie pomiarów temperatury pochodzących z różnych stacji meteorologicznych.

Program umożliwia zarządzanie danymi pogodowymi, dodawanie nowych pomiarów, filtrowanie wyników oraz automatyczne wyszukiwanie rekordów z najwyższą i najniższą temperaturą.

Dane przechowywane są w pliku tekstowym, a poszczególne wartości oddzielone są nietypowym separatorem ; (średnikiem).

✨ Funkcjonalności
📂 Odczyt danych – wczytywanie pomiarów z pliku tekstowego data.txt.
💾 Zapis danych – zapisywanie pomiarów do pliku tekstowego.
➕ Dodawanie pomiarów – możliwość wprowadzania nowych danych bezpośrednio z poziomu aplikacji.
🌡️ Temperatura MAX – automatyczne wyszukiwanie najwyższej zarejestrowanej temperatury.
🥶 Temperatura MIN – automatyczne wyszukiwanie najniższej zarejestrowanej temperatury.
🔎 Filtrowanie stacji – wybór konkretnej stacji pogodowej z listy rozwijanej.
🎨 Dynamiczne podświetlanie rekordów – wizualne wyróżnianie najważniejszych i zmienionych pomiarów.
🔄 Aktualizacja danych – odświeżanie wyników po dodaniu pomiaru lub zmianie filtra.
🎨 Legenda kolorów
Kolor	Znaczenie
🟩	Rekord z maksymalną temperaturą (MAX)
🟥	Rekord z minimalną temperaturą (MIN)
🟨	Nowo dodany lub zmieniony pomiar

Podświetlenia są aktualizowane na podstawie aktualnie wyświetlanych pomiarów.

🛠️ Technologie
Technologia	Zastosowanie
C#	Logika aplikacji
WPF	Interfejs graficzny
XAML	Projektowanie widoków
.NET 10	Platforma uruchomieniowa
Visual Studio 2026	Środowisko programistyczne
📁 Struktura projektu
text
StacjePogodoweWPF/
│
├── App.xaml
├── App.xaml.cs
├── data.txt
├── MainWindow.xaml
├── MainWindow.xaml.cs
├── Pomiar.cs
├── README.md
└── StacjePogodoweWPF.csproj

📄 Format pliku danych

Dane pogodowe przechowywane są w pliku data.txt.

Każdy wiersz reprezentuje jeden pomiar i składa się z trzech wartości:

text
NazwaStacji;Data;Temperatura


Przykładowe dane:

text
Warszawa;2026-01-10;15
Krakow;2026-01-10;8
Gdansk;2026-01-10;-5
Poznan;2026-01-11;12
Wroclaw;2026-01-11;10
Lodz;2026-01-12;18


Separator: ;

Format daty: RRRR-MM-DD

Temperatura: stopnie Celsjusza (°C).

🚀 Uruchomienie projektu
Wymagania
Windows
Visual Studio 2026
.NET 10 SDK
Zainstalowany komponent programistyczny WPF
Instalacja
Sklonuj repozytorium:
bash
git clone https://github.com/TWOJ-LOGIN/StacjePogodoweWPF.git

Przejdź do katalogu projektu:
bash
cd StacjePogodoweWPF

Otwórz plik StacjePogodoweWPF.csproj w Visual Studio 2026.
Poczekaj na załadowanie projektu i przywrócenie zależności.
Uruchom aplikację klawiszem F5.
🧪 Przykładowe działanie

Po uruchomieniu aplikacji użytkownik może:

Wczytać przykładowe pomiary z pliku.
Przeglądać wszystkie dostępne rekordy.
Wybrać konkretną stację z listy rozwijanej.
Sprawdzić temperaturę maksymalną i minimalną.
Dodać nowy pomiar, podając stację, datę i temperaturę.
Zapisać zaktualizowane dane do pliku.
🎯 Cel projektu

Celem projektu jest praktyczne wykorzystanie języka C# oraz technologii WPF do stworzenia aplikacji umożliwiającej pracę z danymi pogodowymi.

Projekt pozwala przećwiczyć:

obsługę plików tekstowych,
parsowanie danych z niestandardowym separatorem,
tworzenie interfejsów graficznych,
obsługę zdarzeń i kontrolek WPF,
filtrowanie kolekcji danych,
wyszukiwanie wartości minimalnych i maksymalnych,
dynamiczną aktualizację interfejsu.

<p align="center">
**🌤️ WPA – Stacje Pogodowe**

Projekt edukacyjny |
