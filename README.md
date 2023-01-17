# Task 1
## Subtask 1

8 / 10 punktów (źle odpowiedziałam na pytanie o testy eksploratacyjne oraz typy testów 🫤 ). 

## Subtask 3

Cześć 🙂 Mam na imię Dorota. Biorę udział w projekcie, ponieważ jestem przekonana, że trzeba wykorzystywać każdą szansę na rozwój nowych umiejętności. Mam także nadzieję, że w niedalekiej przyszłości będę mogła użyć wiedzy wyniesionej z challengu, przy prawdziwym, "żywym" projekcie. 

Póki co pierwsza lekcja za mną - nauczyłam się czym jest i jak używać Markdown 🤟 oraz udało mi się naprawić wyświetlanie litery "ż" w VScode ( my nemesis 😵‍💫 😃). W prawdzie nie są to niebywałe osiągnięcia 😜, ale jak to mówi stare, chińskie przysłowie ( i w tym wypadku to **```NAPRAWDĘ JEST STARE, CHIŃSKIE PRZYSŁOWIE!```** 😅):
>*"A journey of a thousand miles begins with a single step"* 🫶

Dorka

## Subtask 4
**1. Na czym polega ta aplikacja? Do czego służy?**

*Aplikacja Scouts Panel służy to wyszukiwania przez scoutów ( być może również trenerów) potencjalnych talentów piłkarskich, spośród zawodników , których profil widnieje w zakładce GRACZE. Nie jest dla mnie do końca jasne, czy profil gracza zakładają sami "łowcy talentów" i to oni monitorują, oceniają oraz zapisują poczynania i postępy danego zawodnika (zakładka RAPORT), czy może taki profil może stworzyć każdy gracz ( co byłoby jednak nieobiektywne) bądź trener danego zawodnika.*


**2. Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)**



**3. Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?**

*Intrfejs aplikacji w mojej opinii jest dosyć ubogi.* 


**4. Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).**


**5. Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)**

*   *Po wejsciu w konsole, w zakładce PROBLEMS wyświetla się następujący komunikat:*
>A page or script is accessing at least one of navigator.userAgent, navigator.appVersion, and navigator.platform. Starting in Chrome 101, the amount of information available in the User Agent string will be reduced.

*z informacji które odnalazłam m.in. na* https://stackoverflow.com/questions/68924463/a-page-or-script-is-accessing-at-least-one-of-navigator-useragent-navigator-app *oraz*  https://github.com/adobe/react-spectrum/issues/2189, *wynika, iż aplikacja używa starych zasobów tj: __navigator.userAgent__, __navigator.appVersion__,
__navigator.platform__. Wszelkie linie kodu, które w jakikolwiek sposób się do nich odnoszą, po aktualizaji nie będą dostępne. W związku z tym, trzeba będzie dostosować JavaScript tak, aby te dane były jednak dostępne nawet po zmianie;*


*   *W zakładce AKTYWNOŚĆ button'y z linkami są różnie rozmieszczone - część z nich jest wyrównana do lewej, część otrzymała "dziwny" margin; myślę, że nie jest to zamierzony afekt, a błąd deklaracji w jednej z class ( dotyczący justify-content bądź min-width);*
*   *__Raport Lighthouse__:*

       * wskazuje na dosyć niską wydajność aplikacji (51%). W zaleceniach dotyczących poprawy wydajności pojawia się komunikat o skróceniu czasu wykonywania JavaScriptu. 
       
       * W Nawigacji aplikacji elementy nagłówków pojawiają się w nieprawidłowej kolejności.
## Subtask 5

Dołączyłam do grupy projektowej DIT w Jira. 