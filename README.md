# PSP-Polski-Motyw-CXMB
 (WIP) Motyw CXMB spolszczający menu PSP, pierwsze tłumaczenie z polskimi znakami!


# Jak to działa?
(wip) Więcej tutaj: https://strefapsx.pl/forum/psp-ps-vita-homebrew/polonizacja-xmb-z-polskim-fontem/

# Co jest w folderach?
- `/resources` zawiera wypakowane zasoby .rco, tekst który trzeba przetłumaczyć jest w `/nazwa_modułu_xmb/Text/English.xml`, wszystkie zmianny powinny być w tych plikach .xml
- `/original_rco` zawiera oryginalne zdekompresowane .rco wyciągnięte z Flash0 na FW 6.60
- `/backup` - kopia zapasowa wersji testowych, tak na zapas
- `/stuff` - zawiera progsy odpalane przez PSP-XMBTranslTool które składaja motyw do kupy
- `/ltn0.pgf` - polska czcionka mojego autorstwa zrobiona na bazie oryginalnej
- `/base.ptf` - bazowy motyw .ptf który będzie użyty do stworzenia .ctf
- `/PSP-XMBTranslTool.exe` - program mojego autorstwa który składa motyw w plik .ctf

# Ile zostało przetłumaczone?
- `sysconf_plugin` - z 80% przetłumaczone przez Jabu dawno temu, reszta Kruszec
- `topmenu_plugin` - większość przetłumaczone przez Jabu dawno temu, reszta Kruszec
- `game_plugin` - więszkość przetłumaczona poza tekstami o aktualizacjach przez Jabu, reszta Kruszec
- `ps3scan_plugin` - 100%, Kruszec
- `adhoc_transfer` - 100%, Kruszec
- `photo_browser_plugin` - 100%, Kruszec
- `photo_player_plugin` - 100%, Kruszec
- `camera_plugin` - 100%, Kruszec
- `osk_plugin` - 100&, Kruszec
- `opening_plugin` - 100%(Funfact, ten plugin ma aż jedną linijke tekstu xD), Kruszec
- `system_plugin` - 100%, Kruszec
- `auth_plugin` - 100%, Kruszec
- `update_plugin` - 100%, Kruszec
- `music_player_plugin` - 100%, Kruszec
- `netplay_plugin` - 100%, Kruszec

# Gdzie można to pobrać?
Gotowy motyw będzie dostępny za jakiś czas w repo, gdy będzie już większość tekstu przetłumaczona.
Ci którzy chcą już teraz przetestować tłumaczenie mogą motyw zbudować samemu dzięki załączonemu niżej programowi.

# Jak zbudować motyw z spolszczeniem?
To proste dzięki mojemu programikowi(na szybciocha pisanego, miał być skryptem batch ale jakoś nie wyszło)
o nazwie PSP-XMBTranslTool, składa wszystkie luźne xml'my do RCO po czym pakuje wszystko do CTF.
W skrócie:
1. Pobieramy i wypakowujemy lub klonujemy repo
2. Odpalamy PSP-XMBTranslTool.exe
3. Klikamy "Kompiluj Motyw", wybieramy gdzie chcemy zapisać .ctf
4. Program po ukończeniu można zamknąć a motyw wrzucić na PSP

# Jak zainstalować motyw?
Tak jak każdy motyw CXMB, czyli wrzucamy plik .ctf do MS0:/PSP/THEME/, a potem wybieramy go w ustawieniach konsoli.


# Trochę więcej o PSP-XMBTranslTool
{wip)

# Jak przenieść spolszczenie do innych motywów CXMB?
(wip)

# Credits'y
Jabu - Pomysł i wprowadzenie go w życie, polska czcionka, PSP-XMBTrnaslTool, troche tłumaczenia
Kruszec - Za odkopanie pomysłu, tłumaczenie wiekszości tekstu, bez niego projekt nie poszedł by do przodu

rcomage - (?)
ctf.exe/unctf.exe - (?)