
# Lekcja 1: Podstawy Git i GitHub

Lokalne repozytorium, tworzenie i edycja plików, praca na gałęziach oraz integracja ze zdalnym repozytorium GitHub.




## Używane komendy:

- cd <sciezka> – przejście do wskazanego folderu
- git init – utworzenie nowego, pustego repozytorium Git w bieżącym folderze.
- ls – wyświetlenie listy plików i folderów w katalogu.
- ls -a – wyświetlenie wszystkich plików, w tym ukrytych (np. folderu .git/).
- mkdir <nazwa> – utworzenie nowego folderu.
- touch <nazwa_pliku> – utworzenie nowego, pustego pliku (np. touch notatnik.txt).
- git config user.name "Imię Nazwisko" – ustawienie podpisów autora dla commitów w danym repozytorium.
- git config user.email email@example.com – przypisanie adresu e-mail do autorstwa commitów.
- git status – sprawdzenie aktualnego stanu repozytorium (nieśledzone pliki, zmodyfikowane pliki, zmodyfikowana poczekalnia).
- git add <nazwa_pliku> – dodanie konkretnego pliku do poczekalni (staging area).
- git add -A – dodanie wszystkich utworzonych i zmodyfikowanych plików do poczekalni.
- git commit -m "wiadomość" – zapisanie zmian znajdujących się w poczekalni jako commit z opisem.
- git log – historia zapisanych commitów (hashe, autorzy, daty i opisy).
- git branch – wyświetlenie listy lokalnych gałęzi (gwiazdka * oznacza aktualną gałąź).
- git checkout -b "<nazwa_gałęzi>" – utworzenie nowej gałęzi i natychmiastowe przełączenie się na nią (np. git checkout -b "logowanie").
- git checkout <nazwa_gałęzi> – przełączenie się na istniejącą gałąź (np. git checkout master).
- git merge <nazwa_gałęzi> – scalenie zmian z wybranej gałęzi do tej, w której obecnie się znajdujesz (np. fast-forward z logowanie do master).
- git remote add origin <URL> – podpięcie zdalnego repozytorium pod nazwą origin.
- git remote set-url origin <URL> – zmiana adresu zdalnego repozytorium
- git ls-remote – testowe pobranie listy referencji ze zdalnego repozytorium (pozwala sprawdzić połączenie).
- git push -u origin main – wysłanie gałęzi do GitHub z ustawieniem śledzenia upstream (-u), dzięki czemu kolejne wypchnięcia wymagają tylko komendy git push.



## Moja strona

- [darkmord.pl](https://darkmord.pl)

