Aby dokonać aktualizacji:

1. Przejdź przy użyciu przeglądarki pod adres http://TWOJASTRONA.PL/admin i zaloguj się.
2. Wrzuć, poprzez klienta FTP, zawartość katalogu "update" do głównego katalogu strony, nadpisując pliki i katalogi.
   Strona przestanie działać i może wyświetlać błędy aż do zakończenia aktualizacji. Nie dotyczy to Panelu admina. Ten powinien działać stabilnie.
3. Usuń zawartość katalogu "cache" na serwerze FTP.
4. Przejdź do Panelu admina, zakładki "Zarządzanie stroną", podstrony "Aktualizacje".
   Uwaga! Komunikat na stronie głównej Panelu admina może zawierać informację, że posiadasz aktualną wersję eXtreme-Fusion.
   Należy go zignorować i postępować według instrukcji aż do zakończenia aktualizacji.
5. Dokonaj aktualizacji. Możesz zostać wylogowany. Nie przejmuj się tym.
6. Wrzuć, poprzez klienta FTP, zawartość katalogu "files" do głównego katalogu strony, nadpisując pliki i katalogi.

Po aktualizacji, zmienia się miejsce, skąd odczytywany jest plik szablonu - znany jako theme.php.
Jeżeli korzystasz z innego niż domyślny szablon dostępny z eXtreme-Fusion 5 lub modyfikowałeś go, przenieś plik /themes/NAZWASZABLONU/core/theme.php do themes/NAZWASZABLONU/
zmieniając nazwę pliku na view.php. Niestety, szablony w wersji 5.0.3 nie są kompatybilne wstecz, dlatego będziesz musiał zmodyfikować swój
theme.php - od teraz view.php - wzorując się na pliku /themes/eXtreme-Fusion-5/view.php, dlatego zachowaj jego kopię.

