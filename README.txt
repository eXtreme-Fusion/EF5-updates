Aby dokonać aktualizacji:

1. Wrzuć, poprzez klienta FTP, zawartość katalogu "update" do głównego katalogu strony, nadpisując pliki i katalogi.
2. Przejdź do Panelu admina, zakładki "Zarządzanie stroną", podstrony "Aktualizacja".
3. Dokonaj aktualizacji. Możesz zostać przez to wylogowany. Nie przejmuj się tym.
4. Wrzuć, poprzez klienta FTP, zawartość katalogu "files" do głównego katalogu strony, nadpisując pliki i katalogi.

Uwaga! Komunikat na stronie głównej Panelu admina może zawierać informację, że posiadasz aktualną wersję eXtreme-Fusion.
Należy go zignorować i postępować według instrukcji aż do zakończenia aktualizacji.

Po aktualizacji, zmienia się miejsce, skąd odczytywany jest plik szablonu - znany jako theme.php.
Jeżeli korzystasz z innego niż domyślny szablon dostępny z eXtreme-Fusion 5 lub modyfikowałeś go, przenieś plik /themes/NAZWASZABLONU/core/theme.php do themes/NAZWASZABLONU/
zmieniając nazwę pliku na view.php. Niestety, szablony w wersji 5.0.3 nie są kompatybilne wstecz, dlatego będziesz musiał zmodyfikować swój
theme.php - od teraz view.php - wzorując się na pliku /themes/eXtreme-Fusion-5/view.php, dlatego zachowaj jego kopię.

