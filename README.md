# Zarządzanie projektami informatycznymi

Przedmiot: **ZPI**

Semestr: **Zima 2022**

Temat: **System wspomagający działanie urzędu stanu cywilnego**

Zespół:
```
Brzozowski Mateusz
Krawczyk Bartłomiej
Topczewska Gabriela
```

## Założenia

Dokumentacja analityczna powstająca w ramach projektu informatycznego stanowi środek komunikacji i efekt porozumienia pomiędzy przyszłym użytkownikiem tego systemu a zespołem informatycznym: projektantami i programistami.

Dokumentacja powinna zostać przygotowana w taki sposób, aby:
1. Użytkownicy posiadający wiedzę specyficzną dla dziedziny zastosowań byli w stanie potwierdzić, że dokumentacja ta prawidłowo opisuje procesy, których realizację będzie wspomagał system informatyczny oraz właściwie określa funkcje tego systemu.
2. Projektanci i programiści byli w stanie, jedynie na podstawie tej dokumentacji, zaproponować zgodną z oczekiwaniami użytkownika implementację opisanych w dokumentacji analitycznej funkcji systemu.

# Modelowanie procesów biznesowych

## Cel

Rozdział dokumentu powinien opisywać kluczowe procesy biznesowe zachodzące w przedsiębiorstwie.

Przedsiębiorstwo lub organizacja pełnią rolę środowiska, w którym działał będzie projektowany system informatyczny.

Należy uwzględnić tylko te procesy, które na jakimś etapie (jedna lub więcej czynności w ramach procesu) będą wspierane przez system informatyczny. Można ograniczyć liczbę procesów do 3–5 (nietrywialnych).

## Wyniki prac

### Lista wykonawców czynności
lista wszystkich `wykonawców czynności` w ramach procesów biznesowych wraz z ich zwięzłym i precyzyjnym opisem.


### 1. Zmiana imienia/nazwiska
<!-- Mateusz Brzozowski -->
Wykonawcy czynności:
- osoba zmieniająca imię lub nazwisko
    - chce zmienić imię lub nazwisko
    - kto może:
        - pełnoletni obywatel polski
        - pełnoletni cudzoziemiec niemający obywatelstwa żadnego państwa, jeżeli ma w Polsce miejsce zamieszkania
        - pełnoletni cudzoziemiec, który uzyskał w Polsce status uchodźcy
        - osoba małoletnia, której rodzice zmienili nazwisko
        - osoba niepełnoletnia, która ukończyła 13 rok życia na wniosek jednego z rodzica
- rodzic
    - składa wniosek o zmianę nazwiska albo imienia osoby niepełnoletniej
    - wyraża zgodę na wniosek drugiego rodzica, jeżeli niepełnoletni ukończył 13 rok życia
- kierownik urzędu stanu cywilnego
    - odbiera wniosek o zmianę imienia lub nazwiska
    - akceptuje bądź odrzuca wniosek
    - przekazuje informacje do innych kierowników urzędów stanu cywilnego w celu nasienia zmiany do aktu urodzenia  i aktu małżeństwa
    - wprowadza zmiany w aktach stanu cywilnego osób

### 2. Narodziny
<!-- Bartłomiej Krawczyk -->

Wykonawcy czynności:
- rodzic / pełnomocnik
    - może to być:
        - matka lub ojciec dziecka, którzy mają ukończone 16 lat i nie zostali pozbawieni zdolności do czynności prawnych,
        - w pozostałych sytuacjach, na przykład jeśli matka dziecka ma mniej niż 16 lat lub została pozbawiona zdolności do czynności prawnych – dla przedstawiciela ustawowego (na przykład rodzica) lub opiekuna matki dziecka.
        - Urodzenie dziecka można zgłosić samodzielnie lub może zrobić to pełnomocnik.
    - należy przygotować:
        - dokument tożsamości
        - pełnomocnictwo (w przypadku skorzystania z pełnomocnika)
    - ma 21 dni na rejestrację dziecka w urzędzie
- osoba, która odebrała poród
    - lekarz lub położna
    - wystawia kartę urodzenia
    - ma 3 dni na przekazanie jej do urzędu stanu cywilnego
- kierownik urzędu stanu cywilnego
    - rejestruje urodzenie dziecka
    - przygotowuje protokół, który zawiera dane rodziców
    - rejestruje urodzenie dziecka, deklaruje zameldowanie oraz przydziela numer PESEL

### 3. Ślub cywilny
<!-- Gabriela Topczewska -->

Wykonawcy czynności:
- narzeczeni
    - osoby planujące zawarcie związku małżeńskiego
    - dokonują opłaty skarbowej
    - przygotowują wymagane dokumenty:
        - dokumenty tożsamości
        - jeśli jest potrzebne – zezwolenie sądu na zawarcie małżeństwa,
        - dowód opłaty skarbowej
        - zezwolenie sądu na zawarcie małżeństwa - jeśli wymagane
        - pełnomocnictwo - w przypadku korzystania z pełnomocnika
        - akta stanu cywilnego
    - udają się do urzędu dopełnić formalności na co najmniej miesiąc przed planowaną datą ślubu
    - ustalają datę ślubu
    - składają pisemne zapewnienie o nieistnieniu okoliczności wykluczających zawarcie małżeństwa
    - pobierają się
- urzędnik USC
    - sprawdza poprawność i prawdziwość danych na dokumentach zaręczonych
    - przygotowuje wymagane dokumenty i formularze do wypełnienia przez zaręczonych
    - sprawdza dostępność dat ślubu
    - rejestruje wybraną datę ślubu
- organ sądowy
    - udziela zgody sądu na zawarcie małżeństwa, kiedy prawdziwy jest którykolwiek z poniższych przypadków:
        - kobieta jest niepełnoletnia, ale ukończyła 16 lat,
        - osoby są ze sobą spowinowacone,
        - osoba jest dotknięta chorobą psychiczną albo niedorozwojem umysłowym
- tłumacz
    - w przypadku obcojęzyczności któregoś z przyszłych małżonków obowiązkowo udziela tłumacznia w urzędzie
    - w przypadku dokumentó osobistych obcojęzycznych
- urzędnik udzielający ślubu
    - udziela ślubu zaręczonym po wcześniejszym spełnieniu wszystkich wymogów formalnych przez małżonków

### 4. Zgon
<!-- Bartłomiej Krawczyk -->

Wykonawcy czynności:
- lekarz
    - lekarz może stwierdzić zgon na podstawie osobiście wykonanych badań i ustaleń, zaś w uzasadnionych przypadkach lekarz (z wyłączeniem lekarza dentysty) może uzależnić wystawienie karty zgonu od przeprowadzenia sekcji zwłok
    - wystawia kartę zgonu
- osoby związane ze zmarłą osobą
    - może to być:
        - współmałżonek osoby, która zmarła,
        - pozostała rodzina zmarłej osoby, na przykład dzieci, wnuki, prawnuki, rodzice, dziadkowie, brat, siostra, siostrzenica, bratanek, teściowie,
        - pełnomocnik jednej z powyższych osób.
    - zgłaszają śmierć osoby zmarłej do urzędu stanu cywilnego
    - we wniosku powinni zawrzeć:
        - kartę zgonu - od lekarza, który stwierdził zgon
        - dowód osobisty zmarłej osoby,
        - własny dokument tożsamości do okazania (potwierdzenie pełnomocnictwa)
- kierownik urzędu stanu cywilnego
    - rejestruje zgon - sporządzi akt zgonu - w dniu zgłoszenia
    - po rejestracji dostarcza bezpłatny odpis aktu zgonu
    - wnioski należy składać we właściwym urzędzie dla miejsca zgonu
    - po zgłoszeniu zgonu unieważniany jest dowód osobisty oraz następuje automatyczne wymeldowanie zmarłej osoby z miejsca pobytu stałego lub czasowego
- administracja cmentarza
    - na podstawie aktu zgonu decyduje o pochowaniu zmarłego

### Specyfikacje procesów biznesowych
zwięzły opis poszczególnych procesów biznesowych oraz specyfikacje czynności wykonywanych w ramach poszczególnych procesów zapisane jako diagramy aktywności (ang.activity diagram) w notacji UML. Na diagramach należy podać wykonawców czynności, korzystając z torów (ang. swimlanes) lub boksów. Ponadto, należy w szczególny sposób oznaczyć czynności (węzły diagramów), które wspierać będzie projektowany system informatyczny, np. opatrując je stereotypem **\<\<system\>\>**.

<!-- https://mermaid-js.github.io/mermaid/#/stateDiagram -->


<div style="page-break-after: always;"></div>

### 1. Zmiana imienia/nazwiska
<!-- Mateusz Brzozowski -->

```mermaid
stateDiagram
    [*] --> z1 : osoba pełnoletnia
    state "Osoba zmieniająca imię lub nazwisko" as zmieniający{
        direction LR
        state "Złożenie wniosku" as z1
        state "<<\system>>" as z1
        state "Wskazanie miejsca sporządzenia aktu urodzenia" as z2
        state "<<\system>>" as z2
        state "Wskazanie miejsca sporządzenia aktu małżeństwa" as z3
        state "<<\system>>" as z3
        state if_mmalzenstwa <<choice>>
        state if_pol <<choice>>
        state "Złożenie wniosku o przeniesienie zagranicznych dokumentów stanu cywilnego" as z4
        state "<<\system>>" as z4
    }

    [*] --> p1 : osoba niepełnoletnia
    p1 --> z2
    z1 --> z2
    z2 --> if_mmalzenstwa
    if_mmalzenstwa --> z3 : posiadanie aktu małżeństwa
    if_mmalzenstwa --> if_pol : brak aktu małżeństwa
    if_pol --> z4 : brak polskiego obywatelstwa
    if_pol --> k1 : obywatel polski
    z4 --> k1
    z3 --> if_pol

    state "Pierwszy przedstawiciel ustawowy" as przedstawiciel1{
        direction LR
        state "Złożenie wniosku dotyczącego małoletniego dziecka" as p1
    }

    state "Kierownik urzędu realizujący zmianę imienia/nazwiska" as kierownik1{
        direction LR
        state "Sprawdzenie poprawności dokumentów" as k1
        state "<<\system>>" as k1
        state if_akcept <<choice>>
        state "Wydanie zgody" as k2
        state "<<\system>>" as k2
        state "Przekazanie informacji o zmianie do pozostałych kierowników urzędu" as k3
    }

    k1 --> if_akcept
    if_akcept --> k2 : zaakceptowanie wniosku
    if_akcept --> [*] : odrzucenie wniosku
    k2 --> k3
    k3 --> k11

    state "Kierownik urzędu zarządzający aktami" as kierownik2{
        direction LR
        state "Wprowadzenie zmian w akcie urodzenia" as k11
        state if_malzenstwo <<choice>>
        state "Wprowadzenie zmian w akcie akcie małżeństwa" as k12
    }

    k11 --> if_malzenstwo
    if_malzenstwo --> k12 : posiadanie aktu małżeństwa
    if_malzenstwo --> [*] : brak aktu małżeństwa

    k12 --> [*]
    k11 --> [*]
```

<div style="page-break-after: always;"></div>

### 2. Narodziny
<!-- Bartłomiej Krawczyk -->

```mermaid
stateDiagram
    [*] --> l1
    state Lekarz {
        direction LR
        state "Odbiór porodu" as l1
        state "Przygotowanie karty urodzenia" as l2
        state "<<\system>>" as l2
        state "Przesłanie karty urodzenia do urzędu stanu cywilnego" as l3
        state "<<\system>>" as l3

        l1 --> l2
        l2 --> l3
    }

    state Bliscy {
        state "Wstępne wypełnienie wniosku" as b0
        state "<<\system>>" as b0
        state "Wizyta w urzędzie" as b1
        state "Odbiór dokumentów" as b2

        b0 --> b1
    }
    state "Kierownik urzędu" as kierownik {
        state "Przygotowanie protokołu" as k1
        state "<<\system>>" as k1
        state if_accept <<choice>>
        state "Wybór imienia prze urzędnika" as choice
        state "Zarejestrowanie urodzenia dziecka" as k2
        state "<<\system>>" as k2
        state "Zameldowanie dziecka" as k3
        state "<<\system>>" as k3
        state "Nadanie numeru PESEL" as k4
        state "<<\system>>" as k4
        state "Przygotowanie aktu urodzenia" as k5
        state "<<\system>>" as k5
        state "Przekazanie dokumentów rodzicom" as k6

        k1 --> if_accept
        if_accept --> k2: Zatwierdzenie imienia wybranego przez rodziców
        if_accept --> choice: Nie zatwierdzenie nietypowego imienia
        choice --> k2
        k2 --> k3
        k3 --> k4
        k4 --> k5
        k5 --> k6
    }

    state fork_state <<fork>>
      l3 --> fork_state
      fork_state --> b0

    state join_state <<join>>
      b1 --> join_state: 21 Dni
      join_state --> k1
      fork_state --> join_state: 3 Dni

    k6 --> b2: Skrócony akt urodzenia, numer PESEL, potwierdzenie zameldowania
    b2 --> [*]: Rejestracja dziecka
```

<div style="page-break-after: always;"></div>

### 3. Ślub cywilny
<!-- Gabriela Topczewska -->

```mermaid
stateDiagram
    [*] --> a
    state Narzeczeni {
        direction LR;
        state "Pobranie akt stanu cywilnego" as a
        state "<<\system>>" as a
        state if_sad_state <<choice>>
        state "Złożenie wniosku o uzyskanie pozwolenia sądu" as wsa
        state "Uzyskanie decyzji sądu" as sa
        state if_zgoda <<choice>>
        state if_pol_state <<choice>>
        state "Złożenie dokumentów do przetłumaczenia" as p1
        state "Odebranie przetłumaczonych dokumentów" as p2
        state "Dokonanie opłaty skarbowej" as o
        state "<<\system>>" as o
        state "Złożenie dokumentów w urzędzie" as u
        state "Zaproponowanie daty ślubu" as zd
        state if_data_state <<choice>>
        state "Potwierdzenie daty ślubu" as pd
        state "Złożenie pisemnego oświadczenia o braku czynności wyłączających zawarcie małżeństwa" as osw
        state "Odwołanie ślubu" as odw

        a --> if_sad_state
        if_sad_state --> if_pol_state : Czy zgoda sądu wymagana? - Nie
        if_sad_state --> wsa : Czy zgoda sądu wymagana? - Tak
        sa --> if_zgoda
        if_zgoda --> if_pol_state : Czy zgoda wydana? - Tak
        if_zgoda --> odw : Czy zgoda wydana? - Nie
        if_pol_state --> o : Czy obie osoby polskojęzyczne? - Tak
        if_pol_state --> p1 : Czy obie osoby polskojęzyczne? - Nie
        p2 --> o
        o --> u
        if_data_state --> pd : Czy data pasuje? - Tak
        if_data_state --> zd : Czy data pasuje? - Nie
        odw --> [*]
    }

    state Urzędnik {
        direction LR
        state "Sprawdzenie poprawności dokumentów narzeczonych" as pdok
        state "<<\system>>" as pdok
        state if_popr <<choice>>
        state "Sprawdzenie dostępności daty" as d
        state "<<\system>>" as d
        state "Poinformowanie o dostępności daty" as dd
        state "Zarejestrowanie daty ślubu" as zdat
        state "<<\system>>" as zdat
        state "Przydzielenie urzędnika do zawarcia ślubu" as um
        state "<<\system>>" as um

        pdok --> if_popr
        d --> dd
        zdat --> um
    }
    state Organ_sądowy {
        direction LR
        state "Otrzymanie wniosku o wydanie zgody sądu na zawarcie małżeństwa" as wzg
        state "Wydanie decyzji sądu" as dec
        wzg --> dec

    }
    state Tłumacz {
        direction LR
        state "Otrzymanie dokumentów do przetłumaczenia" as odok
        state "Tłumaczenie i odesłanie przetłumaczonych dokumentów" as tdok

        odok --> tdok

    }
    state Urzędnik_udzielający_ślubu {
        direction LR
        state "Otrzymanie przydziału do udzielenia ślubu" as op
        state "<<\system>>" as op
        state "Udzielenie ślubu" as slub
        state "Zarejestrowanie nowego małżeństwa" as rej
        state "<<\system>>" as rej

        slub --> rej
    }


    state fork_state <<fork>>
        pd --> fork_state
        fork_state --> osw
    state join_state <<join>>

    wsa --> wzg
    dec --> sa
    p1 --> odok
    tdok --> p2
    u --> pdok
    if_popr --> u : Czy dokumenty poprawne? - Nie
    if_popr --> zd : Czy dokumenty poprawne? - Tak
    zd --> d
    dd --> if_data_state
    fork_state --> zdat
    um --> op
    op --> join_state
    osw --> join_state
    join_state --> slub
    rej --> [*]
```

### 4. Zgon
<!-- Bartłomiej Krawczyk -->


```mermaid
stateDiagram
    [*] --> b
    state Lekarz {
        direction LR
        state "Badania" as b
        state "Sekcja zwłok" as sz
        state "Wystawienie karty zgonu" as kz
        state "Decyzja o powodzie śmierci" as d
        b --> sz
        sz --> kz
        kz --> d: Karta zgonu

        state if_state <<choice>>
        d --> if_state
        if_state --> Nie: Zmarł na skutek choroby zakaźnej
        if_state --> Tak: Zmarł na skutek choroby zakaźnej
    }
    state Bliscy {
        state "Dostarczenie karty zgonu oraz dokumentów do urzędu stanu cywilnego" as w
        state "Odbiór odpisu od aktu zgonu" as b2
        state "Przekazanie aktu zgonu do administracji cmentarza" as b3

        b2 --> b3
    }
    state "Kierownik urzędu" as kierownik {
        state "Zarejestrowanie zgonu" as k1
        state "Wprowadzenie zgonu do systemu" as k2
        state "<<\system>>" as k2
        state "Przygotowanie aktu zgonu" as k3
        state "<<\system>>" as k3
        state "Automatyczne wymeldowanie oraz unieważnienie dokumentów" as k4
        state "<<\system>>" as k4
        state "Przygotowanie odpisu do Aktu zgonu" as k5

        k1 --> k2
        k2 --> k3
        k3 --> k4
        k4 --> k5
    }
    state "Administracja cmentarza" as administracja {
        state "Wypełnienie formalności oraz zajęcie się zmarłym" as c1
    }

    Nie --> w : 3 Dni
    Tak --> w : 24h

    w --> k1: Karta zgonu, Dowód zmarłego, Własny dowód tożsamości

    k5 --> b2: Odpis aktu zgonu
    b3 --> c1: Odpis aktu zgonu

    c1 --> [*]: Pogrzeb
```

# Modelowanie przypadków użycia

## Cel
Rozdział dokumentu powinien opisywać specyfikację interakcji (dialogu) użytkowników z projektowanym systemem informatycznym, umożliwiając zaprojektowanie jego interfejsu i sporządzenie makiety tego systemu.

## Wyniki prac

### Lista aktorów systemowych
lista użytkowników i systemów informatycznych `podejmujących interakcję` z projektowanym systemem.

<!-- Do opisania -->
Lista aktorów systemu informatycznego:
- osoba zmieniająca imię lub nazwisko
- przedstawiciel ustawowy
- rodzice nowo narodzonego dziecka
- personel szpitala - lekarze / położne
- narzeczeni
- Urzędnik rejestrujący narodziny dziecka
- Urzędnik rejestrujący zgon
- Urzędnik realizujący zmianę imienia/nazwiska
- Urzędnik zatwierdzający zawarcie ślubu
- Urzędnik udzielający ślubu

### Diagramy przypadków użycia systemu
sporządzone zgodnie z notacją UML diagramy ilustrujące przypadki użycia systemu i ich związki z odpowiednimi aktorami, oraz zależności pomiędzy przypadkami użycia (**\<\<include\>\>**,**\<\<extend\>\>**, generalizacja/specjalizacja).

Funkcje systemowe:
1. Logowanie użytkownika
2. Przeglądanie katalogu z dostępnymi wnioskami
3. Wyszukiwanie wniosku
4. Zgłoszenie porodu dziecka
5. Zgłoszenie narodzin dziecka
6. Zatwierdzenie narodzin dziecka
7. Rejestracja zgonu
8. Złożenie wniosku o wzięcie ślubu cywilnego
9. Rozpatrzenie wniosku o wzięcie ślubu cywilnego
10. Generacja harmonogramu odprawianych ślubów
11. Rejestracja nowego małżeństwa
12. Złożenie wniosku o zmianę imienia/nazwiska
13. Rozpatrzenie wniosku o zmianę imienia/nazwiska

![](./use-case.png)

### Specyfikacje przypadków użycia systemu
specyfikacje przebiegu interakcji w obrębie poszczególnych przypadków użycia w postaci opisu scenariusza głównego (podstawowego), scenariuszy alternatywnych i punktów rozszerzeń.

**FU1**: Logowanie użytkownika

> Logowanie następuje poprzez urzędowy system - profil zaufany / bank / aplikacja mObywatel / eDowód

Scenariusz główny:
1. Użytkownik wybiera metodę logowania
2. System pokazuje formularz z wybraną metodą
3. Użytkownik wypełnia dane logowania
4. System przenosi zalogowanego użytkownika do strony głównej

Scenariusz alternatywny - użytkownik wybrał metodę uwierzytelnienia przez zewnętrzny system np. bank:
1. Użytkownik wybiera metodę logowania przez zewnętrzny system
2. System przekierowuje użytkownika do zewnętrznej strony
3. Użytkownik loguje się
4. Zewnętrzna strona przekierowuje ponownie do strony urzędu poprawnie zalogowanego użytkownika

Scenariusz alternatywny - błędne dane logowania:

1. takie jak w scenariuszu głównym
2. takie jak w scenariuszu głównym
3. Użytkownik podaje błędne dane logowania
4. System sygnalizuje błędnie wypełnione dane
5. Powrót do kroku 2.

Scenariusz alternatywny - logowanie urzędnika
- kroki 1-3 takie same jak w scenariuszu głównym
4. System wykrywa podwyższone uprawnienia użytkownika i przenosi go do strony z większymi dostępami

**FU2**: Przeglądanie katalogu z dostępnymi wnioskami
1. Logowanie użytkownika - FU1
2. Urzędnik przechodzi do widoku nieobsłużonych wniosków
3. System wyświetla w przystępny sposób najnowsze nie obsłużone jeszcze zgłoszenia w danym urzędzie
4. Urzędnik określa jakiego typu zgłoszenia mają być wyświetlane
5. System filtruje nadmiarowe wyniki wyszukiwania

**FU3**: Wyszukiwanie wniosku
1. Logowanie użytkownika - FU1
2. Urzędnik przechodzi do trybu wyszukiwania
3. Urzędnik wpisuje frazę w okno wyszukiwania
4. System zwraca wszystkie wnioski z dostępną frazą

**FU4**: Zgłoszenie porodu dziecka przez personel medyczny

Scenariusz główny:
1. Logowanie użytkownika - FU1
2. Personel wybiera wypełnienie karty urodzenia dziecka
3. System pokazuje formularz z kartą urodzenia do wypełnienia
4. Lekarz odbierający poród wypełnia formularz
5. Lekarz sprawdza poprawność formularza
6. System wysyła kartę urodzenia do urzędu

**FU5**: Zgłoszenie narodzin dziecka

Scenariusz główny:
1. Logowanie użytkownika - FU1
2. Rodzice wybierają w systemie formularz zgłoszenia narodzin
3. System prosi o zaznaczenie oświadczenia o byciu rodzicem
4. Użytkownik potwierdza wybór
5. System wyświetla formularze z informacjami do uzupełnienia o rodzicach dziecka
6. Użytkownik uzupełnienia informacje o ojcu dziecka
7. Użytkownik uzupełnienia informacje o matce dziecka
8. Użytkownik uzupełnienia informacje o dziecku
9. Wybiera adres zameldowania dziecka
10. System pyta o preferowany sposób kontaktu
11. Użytkownik uzupełnienia informacje o preferowanym kontakcie
12. System wyświetla podsumowanie wniosku
13. Użytkownik weryfikuje poprawność
14. Wysłanie wniosku do urzędu

Scenariusz alternatywny (rodzic nie pełnoletni)
1. Logowanie użytkownika - FU1
2. System wykrył, że użytkownik nie jest pełnoletni
3. System wyświetla informację o konieczności wypełnienia wniosku w urzędzie wraz z pełnomocnikiem

Scenariusz alternatywny (użytkownik nie jest rodzicem)
1. Logowanie użytkownika - FU1
2. System prosi o zaznaczenie oświadczenia o byciu rodzicem
3. Użytkownik nie jest rodzicem
4. System informuje o konieczności pójścia do urzędu z pełnomocnikiem

**FU6**: Zatwierdzenie narodzin dziecka

Scenariusz główny:
1. Urzędnik przyjmuje rodziców i wyszukuje odpowiedni wniosek - FU3
2. System oznacza zgłoszenie jako w trakcie obsługi
3. System wyświetla wprowadzone dane dziecka oraz jego rodziców
4. Urzędnik weryfikuje poprawność danych oraz czy wybrane imię jest poprawne dla dziecka
5. Urzędnik zatwierdza formularz
6. Urzędnik wprowadza dane zameldowania dziecka
7. System generuje kolejny numer PESEL
8. Urzędnik zatwierdza formularz
9. System generuje protokół zgłoszenia dziecka, który musi być podpisany przez kierownika urzędu, rodziców oraz obecnych tłumacza oraz biegłego (jeśli brali udział w czynności)
10. System generuje akt urodzenia

Scenariusz alternatywny (urzędnik nie zatwierdza imienia dziecka)
- kroki 1-4 oraz 6-10 są takie same
5. Urzędnik wymyśla nowe imię oraz wprowadza je do systemu

Scenariusz alternatywny (mija 21 dni od zgłoszenia narodzin dziecka, a rodzice nie pojawili się w urzędzie)
- kroki 3 - 10 takie same
1. Urzędnik przegląda dostępne zgłoszenia i filtruje nieobsłużone zgłoszenia sprzed 21 dni - FU2

**FU7**: Rejestracja zgonu

1. Logowanie urzędnika - FU1
2. Urzędnik wybiera opcję wprowadzenia zgonu do systemu
3. Urzędnik wprowadza dane dotyczące zgonu
4. System generuje akt zgonu
5. Urzędnik weryfikuje dane oraz zatwierdza formularz
6. System automatycznie wymeldowuje zmarłego oraz unieważnia dokumenty

**FU8**: Złożenie wniosku o wzięcie ślubu cywilnego

Scenariusz główny:
1. Logowanie użytkownika - FU1
2. Wybranie opcji złożenia wniosku o wzięcie ślubu cywilnego.
3. System wyświetla formularze dotyczące osób chcących zawrzeć związek małżeński.
4. Użytkownik wypełnia informacje o sobie oraz przyszłym współmałżonku.
5. Użytkownik wysyła prośbę o dołączenie aktów stanu cywilnego swojego oraz przyszłego współmałżonka do wniosku o zawarcie małżeństwa.
6. System dołącza akta do wniosku.
7. Weryfikacja poprawności danych przez użytkownika.
8. System pyta, czy użytkownik chce dokonać opłaty za wniosek teraz.
9. Użytkownik dokonuje opłaty.
10. System informuje użytkownika o kolejnych krokach, które ten musi podjąć po złożeniu wniosku.
11. Wniosek zostaje złożony w urzędzie.

Scenariusz alternatywny - przynajmniej 1 osoba jest obcokrajowcem:
1. Logowanie użytkownika - FU1
2. Wybranie opcji złożenia wniosku o wzięcie ślubu cywilnego.
3. System wyświetla formularze dotyczące osób chcących zawrzeć związek małżeński.
4. Użytkownik wypełnia informacje o sobie oraz przyszłym współmałżonku.
5. Użytkownik zaznacza, która z osób pochodzi spoza Polski.
6. System umożliwia dołączenie dokumentów z innego kraju.
7. System oznacza dokumenty jako obce.
8. Weryfikacja poprawności danych przez użytkownika.
9. System pyta, czy użytkownik chce dokonać opłaty za wniosek teraz.
10. Użytkownik dokonuje opłaty.
11. System informuje użytkownika o kolejnych krokach, które ten musi podjąć po złożeniu wniosku.
12. Wniosek zostaje złożony w urzędzie.

Scenariusz alternatywny - wymagana zgoda sądu na zawarcie małżeństwa:
1. Logowanie użytkownika - FU1
2. Wybranie opcji złożenia wniosku o wzięcie ślubu cywilnego.
3. System wyświetla formularze dotyczące osób chcących zawrzeć związek małżeński.
4. Użytkownik wypełnia informacje o sobie oraz przyszłym współmałżonku.
5. Użytkownik wysyła prośbę o dołączenie aktów stanu cywilnego swojego oraz przyszłego współmałżonka do wniosku o zawarcie małżeństwa.
6. System wykrywa, że potrzebna jest zgoda sądu na zawarcie małżeństwa.
7. System informuje o konieczności wybrania się do urzędu w celu wypełnienia niezbędnych formalności.

Scenariusz alternatywny - opłata dokonywana w urzędzie:
1. Logowanie użytkownika - FU1
2. Wybranie opcji złożenia wniosku o wzięcie ślubu cywilnego.
3. System wyświetla formularze dotyczące osób chcących zawrzeć związek małżeński.
4. Użytkownik wypełnia informacje o sobie oraz przyszłym współmałżonku.
5. Użytkownik wysyła prośbę o dołączenie aktów stanu cywilnego swojego oraz przyszłego współmałżonka do wniosku o zawarcie małżeństwa.
6. System dołącza akta do wniosku.
7. Weryfikacja poprawności danych przez użytkownika.
8. System pyta, czy użytkownik chce dokonać opłaty za wniosek teraz.
9. Użytkownik wybiera opcję zapłaty w urzędzie.
10. Wniosek jest oznaczany jako nieopłacony.
10. System informuje użytkownika o kolejnych krokach, które ten musi podjąć po złożeniu wniosku.
11. Wniosek zostaje złożony w urzędzie.

**FU9**: Rozpatrzenie wniosku o wzięcie ślubu cywilnego

1. Urzędnik przyjmuje narzeczonych i wyszukuje odpowiedni wniosek - FU3
2. System wyświetla wprowdzone poprzednio dane
3. Urzędnik weryfikuje poprawność danych
4. Urzędnik zatwierdza formularz
5. System pokazuje dostępne daty ślubu
6. Urzędnik wraz z narzeczonymi decyduje o dacie ślubu
7. Urzędnik wprowadza datę
8. System przydziela dostępnego urzędnika udzielającego ślubu

**FU10**: Generacja harmonogramu odprawianych ślubów cywilnych

Scenariusz główny:
1. Logowanie urzędnika - FU1
2. Urzędnik wybiera opcję generowania harmonogramu własnego.
3. Urzędnik wybiera zakres dat, który go interesuje.
4. Urzędnik zatwierdza wybór.
5. System generuje harmonogram ślubów do pliku pdf.

**FU11**: Rejestracja nowego małżeństwa
1. Urzędnik po udzieleniu ślubu wyszukuje odpowiedni wniosek - FU3
2. Wprowadza do systemu potwierdzenie zawartego ślubu
3. System rejestruje zmianę statusu osób

**FU12**: Złożenie wniosku o zmianę imienia/nazwiska

Scenariusz główny:
1. Logowanie użytkownika - FU1
2. Użytkownik wybiera opcję złożenia wniosku o zmianę imienia/nazwiska
3. Wybór kogo dotyczy wniosek (użytkownika, czy małoletniego potomka)
4. Wypełnienie informacji nt. miejsca sporządzenia aktu urodzenia
5. Jeśli dotyczy - wypełnienie informacji nt. miejsca sporządzenia aktu małżeństwa
6. Jeśli dotyczy - złożenie wniosku o przeniesienie zagranicznych dokumentów stanu cywilnego
7. Załączenie wymaganych dokumentów
8. Wypełnienie informacji dot. motywacji do zmiany imienia/nazwiska
9. Zatwierdzenie poprawności informacji przez użytkownika
10. Wysłanie wniosku

Scenariusz alternatywny - użytkownik niepełnoletni:
1. Logowanie użytkownika - FU1
2. Użytkownik wybiera opcję złożenia wniosku o zmianę imienia/nazwiska
3. System rozpoznaje, że użytkownik jest niepełnoletni
4. Wyświetlenie informacji o braku możliwości złożenia wniosku

**FU13** Rozpatrzenie wniosku o zmianę imienia/nazwiska
1. Przeglądanie katalogu z nieobsłużonymi wnioskami o zmianę imienia/nazwiska - FU2
2. System oznacza wniosek jako w trakcie obsługi
3. Sprawdzenie poprawności wniosku
4. Zatwierdzenie wniosku
5. Rozesłanie przez system informacji do wnioskodawców o pomyślnym zakończeniu rozpatrzenia wniosku
6. Rozesłanie przez system informacji do innych urzędów o zmianie danych osobowych wnioskodawcy
7. Uaktualnienie przez system aktu stanu cywilnego wnioskodawcy

### Projekty ekranów
graficzny szkic lub zrzut z ekranu komputera, ekranu/formularza służącego do wprowadzania danych lub wybierania opcji przez użytkownika w ramach danego przypadku użycia.


**Uwaga:** Dla każdego przypadku użycia na diagramie należy opracować jego specyfikację oraz projekt ekranu (jeśli z przypadkiem użycia wiąże się wprowadzanie danych, wybieranie opcji).

<!-- Mateusz Brzozowski -->

<div style="page-break-after: always;"></div>

## Logowanie - FU1

![](./ekrany/Wireframe%20-%206.png)

![](./ekrany/Wireframe%20-%207.png)

<div style="page-break-after: always;"></div>

## Przeglądanie katalogu z dostępnymi wnioskami - FU2

![](./ekrany/FU2.png)

<div style="page-break-after: always;"></div>

## Wyszukiwanie wniosku - FU3

![](./ekrany/FU3.png)

<div style="page-break-after: always;"></div>

## Zgłoszenie narodzin dziecka przez personel medyczny - FU4

![](./ekrany/Wireframe%20-%2010.png)

<div style="page-break-after: always;"></div>

## Zgłoszenie narodzin dziecka przez rodziców dziecka - FU5

![](./ekrany/Wireframe%20-%202.png)
![](./ekrany/Wireframe%20-%201.png)
![](./ekrany/Wireframe%20-%203.png)
![](./ekrany/Wireframe%20-%204.png)
![](./ekrany/Wireframe%20-%205.png)
![](./ekrany/Wireframe%20-%208.png)

<div style="page-break-after: always;"></div>

## Zatwierdzenie narodzin dziecka przez urzędnika - FU6

![](./ekrany/Wireframe%20-%209.png)


<div style="page-break-after: always;"></div>

## Rejestracja zgonu przez urzędnika - FU7

![](./ekrany/FU7-a.png)
![](./ekrany/FU7-b.png)

<div style="page-break-after: always;"></div>

## Złożenie wniosku o wzięcie ślubu cywilnego - FU8

![](./ekrany/FU8.png)

## Rozpatrzenie wniosku o wzięcie ślubu cywilnego - FU9

![](./ekrany/FU9.png)

<div style="page-break-after: always;"></div>

## Generowany harmonogram ślubów cywilnych - FU10

![](./ekrany/FU10.png)

<div style="page-break-after: always;"></div>

## Rejestracja nowego małżeństwa - FU11

![](./ekrany/FU11.png)

<div style="page-break-after: always;"></div>

## Złożenie wniosku o zmianę imienia/nazwiska - FU12

![](./ekrany/FU12.png)

<div style="page-break-after: always;"></div>

## Rozpatrzenie wniosku o zmianę imienia/nazwiska - FU13

![](./ekrany/FU13.png)

# Modelowanie pojęć systemu

## Cel
Rozdział dokumentu powinien opisywać specyfikację pojęć związanych z projektowanym systemem.

## Wyniki prac

### Diagram klas
diagram klas przedstawiający pojęcia dotyczące projektowanego systemu informatycznego, sporządzony zgodnie z notacją UML. Specyfikacje klas (pojęć) powinny obejmować specyfikacje atrybutów, dla których należy wyspecyfikować odpowiedni typ niezwiązany jednak z określoną platformą implementacji, np. LiczbaCałkowita, LiczbaRzeczywista, Data, Napis itp. Należy wyspecyfikować związki pomiędzy klasami: związek asocjacji (i ew. jej szczególne przypadki - agregację i kompozycję) wraz z licznością końców, oraz związek generalizacji/specjalizacji.


```mermaid
classDiagram
    class Osoba {
        Napis pesel

        Napis imię
        Napis drugieImię
        Napis kolejneImiona
        Napis nazwisko
        Napis nazwiskoRodowe

        Data dataUrodzenia
        Adres miejsceUrodzenia

        Napis obywatelstwo

        Adres zameldowanie
        Adres miejsceZamieszkania

        Napis wykształcenie
    }

    class Dziecko {
        Typ płeć


        LiczbaZmiennoPrzecinkowa czasTrwaniaCiąży

        LiczbaZmiennoPrzecinkowa ciężarCiałaPrzyUrodzeniu
        LiczbaZmiennoPrzecinkowa długośćCiałaPrzyUrodzeniu


        LiczbaZmiennoPrzecinkowa skalaApgar1min
        LiczbaZmiennoPrzecinkowa skalaApgar5min
        LiczbaZmiennoPrzecinkowa skalaApgar10min

        Osoba ojciec
        Osoba matka

        Adres miejsceSporządzeniaAktuUrodzenia
        Napis oznaczeniAktuUrodzenia
    }

    class Adres {
        Napis nazwaPlacówki
        Napis miejscowość
        Napis województwo
        Napis powiat
        Napis gmina

        Napis ulica
        Napis adresBudynku
        Napis adresMieszkania
    }

    class Wniosek {
        Napis typWniosku
        Adres urząd

        List~Osoba~ wnioskodawcy
        List~Osoba~ osobyZgłaszane

        List~Wydarzenie~ zaplanowaneWydarzenia

        Napis emailKontaktowy
        Napis telefonKontaktowy
    }

    class Wydarzenie {
        Napis typWydarzenia
        Adres adresWydarzenia
        Napis nazwa wydarzenia
        Data dataWydarzenia

        List~Osoba~ osobyWymagane
    }

    Osoba <|-- Dziecko

    Wniosek --o Osoba : Wnioskodawcy
    Wniosek --o Osoba : Osoby Zgłaszane

    Wniosek --o Adres : Urząd Stanu Cywilnego

    Osoba --o Adres : Miejsce Zamieszkania
    Osoba --o Adres : Miejsce Zameldowania

    Wniosek --o Wydarzenie : Zaplanowane Wydarzenia


    Wydarzenie --o Osoba : Osoby potrzebne na wydarzenie
    Wydarzenie --o Adres : Miejsce wydarzenia
```

### Specyfikacja klas
zwięzły opis znaczenia poszczególnych klas i ich atrybutów.

**Uwaga:** Nie podajemy operacji dla klas. Każda asocjacja musi być nazwana.

\
**Wniosek** \
Jest to podstawowa jednostka służąca do komunikacji pomiędy interesantem, a urzędem stanu cywilnego. Zawiera wszystkie niezbędne do identyfikacji konkretnego przypadku załatwianej sprawy informacje:
- typ wniosku,
- adres urzędu do którego zgłaszany jest wniosek (zawiera obiekt klasy *Adres*),
- dane wnioskodawców, dane osób zgłaszanych we wniosku, niebędących jednocześnie wnioskodawcami (np. nowonarodzone dziecko lub osoba zmarła) (zawiera obiekt klasy *Osoba*),
- datę wydarzenia uwzględnionego we wniosku (zawiera obiekt klasy *Wydarzenie*),
- dane kontaktowe do wnioskodawcy.

**Wydarzenie** \
Klasa obrazująca wydarzenie, które może zostać zaplanowane w ramach prośby złożonej we wniosku (np. zawarcie związku małżeńskiego). Klasa ta zawiera:
- typ planowanego wydarzenia,
- adres wydarzenia (zawiera obiekt klasy *Adres*),
- nazwę wydarzenia,
- datę wydarzenia,
- dane osób wymaganych do odbycia wydarzenia (angażuje osoby opisane przez klasę *Osoba*).

Wydarzenie jest też składową *Wniosku*.

**Osoba** \
Klasa ta zawiera w sobie wszystkie niezbędne z punktu widzenia urzędu stanu cywilnego informacje na temat konkretnej osoby. Są to:
- pesel,
- imię,
- kolejne imiona (jeśli posiada),
- nazwisko,
- nazwisko rodowe (jeśli posiada),
- datę urodzenia,
- miejsce urodzenia,
- obywatelstwo,
- adres zameldowania,
- miejsce zamieszkania,
- wykształcenie.

Klasa ta zawiera w sobie 3 obiekty klasy *Adres* - opisują one miejsce urodzenia, adres zameldowania oraz miejsce zamieszkania.

**Dziecko** \
Klasa pochodna od klasy *Osoba*. Zawiera te same elementy, co klasa nadrzędna, a dodatkowo również:
- płeć,
- czas trwania ciąży matki,
- ciężar ciała przy urodzeniu,
- długość ciała przy urodzeniu,
- wartości skali APGAR po 1 minucie, 5 minutach, 10 minutach,
- dane ojca dziecka (posiada rodzica opisywanego przez klasę *Osoba*),
- dane matki dziecka (posiada rodzica opisywanego przez klasę *Osoba*),
- miejsce sporządzenia aktu urodzenia (urodziło się pod danym *Adresem*),
- ozaczenie aktu urodzenia.

**Adres** \
Jest to klasa opisująca adres wykorzystywany w ramach *Wniosku*, pomagający określić dane osobowe *Osoby*, w tym *Dziecka*, a także określający lokalizację *Wydarzenia*. Posiada następujące atrybuty:
- nazwę placówki (jeśli wymagana),
- miejscowość,
- województwo,
- powiat,
- gminę,
- ulicę,
- adres (numer bądź ozanczenie) budynku,
- adres (numer bądź oznaczenie) mieszkania.
