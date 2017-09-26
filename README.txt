MOJE DODATKOWE SPERSONALIZOWANE USTAWIENIA (WYGLĄD, ZACHOWANIE) W LINUX MINT CINNAMON:

Kolory w tle
w program dconf editor ustawić:
org->cinnamon->desktop->interface->gtk-color-scheme base_color:#abc5d7;

Motyw systemowy: polar-night
Motyw ikon: Numix
Motyw kursora: MacOSXe

Ramki okna:
OS X El Capitan

Ikonka menu:
Prawy klawisz myszy na "Menu"->konfiguruj->Użyj własnej ikony
/usr/share/cinnamon/theme/menu-symbolic.svg (trybik)

Powiększony i przeźroczysty panel (bardziej w stylu windowsa):
prawy klawisz myszy na panelu->ustawienia panelu->"Użyj wlasnego rozmiaru panelu"-> suwak ponad połowę
Przeźroczystość: ~/.themes/<wybrany_motyw>(NumixDarkRed)/cinnamon/cinnamon.css (pokazana w pliku .css, tag: krynieski)
- dla uzyskania efektu po zmianach w tym pliku, konieczny jest reset cinnamona (Alt+F2: r i enter)

Aplety:
1. "Window List with App Grouping": grupowanie aplikacji na panelu podobnie jak w Windowsie (te same aplikacje pod jedną ikonką):
- instalacja: Aplety -> Dostępne aplety (w sieci) -> wyszukać "Window List with App Grouping" -> zainstalować -> przejść do "Zainstalowane aplety" -> wyszukać wszystkie "window list" -> samo "Window List" usunąć z panelu (prawy przycisk myszy), a "Windows List with App Grouping" dodać do panelu
2. Cairo-dock: panel na pulpicie z ikonkami/odnośnikami do aplikacji w stylu Maca
3. Conky (Gotham conky) - godzina, data i inne informacje wyświetlane na pulpicie
4. Everpad - desktopowy klient Evernote
5. Messenger for Desktop - desktopowy messenger faceobooka
6. Yakyak - desktopowy messenger google hangouts
7. Skype
8. Double Commander - linuxowy Total Commander
9. Notepadqq - linuxowy Notepad++
10. Glipper - aplet pamięci podręcznej (wklejanie z historii)
11. Dropbox

PROBLEMY:
1. Biały kolor czcionki systemowej (default w Numixie) niewidoczny w firefoxie:
- niektóre strony internetowe nie definiują własnych czcionek tylko korzystają z systemowych
- naprawa: trzeba zmienić konfigurację firefoxa (na podstawie instrukcji z https://ubuntuforums.org/showthread.php?t=1715679):
        a) przekopiować plik userContent.css (lub zmergować z istnięjącym) do katalogu "chrome" w ~/.mozilla/firefox/*.default (jeśli nie ma katalogu chrome trzeba go stworzyć)
        b) można ewentualnie wyłączyć albo zmodyfikować któreś z ustawień, wg uznania
        b) z1ować firefoxa

