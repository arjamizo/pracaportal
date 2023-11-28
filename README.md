Praca-portal
=

Praca-portal to oprogramowanie skierowane do agencji pośrednictwa pracy. Oprogramowanie jest realizowane za pomocą VueJs i integruje się z już istniejącym rozwiązaniem oferującym logikę działania za pomocą REST API.

Zakres funkcji w oprogramowaniu Praca-portal
==

W zakres oprogramowania wchodzi:
* rejestracja
* logowanie
* panel pracownika
  * zarządzanie danymi osobowymi
    * danymi urzędu skarbowego
    * danymi ZUS
    * wcześniejszym zatrudnieniem
    * zarządzanie plikami i dokumentami (CV, skany dowodu/paszportu)
  * przeglądanie ofert pracy
  * aplikowanie na oferty pracy
  * dodanie ogłoszenia o poszukiwaniu pracy
  * raportowanie godzin
* panel pracodawcy
  * dodanie oferty pracy
    * tymczasowej
    * stałej
  * przegląd aplikujących na stanowisko
  * powiadomienie pracowników o nagłej wiadomości
  * wypłacanie pensji
  * rozliczanie za pośrednictwem agencji
  * wybór formy prawnej zatrudnienia pracownika
* panel administracyjny (pracownik agencji pracy)

Opis techniczny działania systemu
==

<details>
  <summary>Autoryzacja</summary>
  <p>Autoryzacja odbywa się za pomocą tokenu JWT. Warto wspomnieć, że dla użytkowników z poszerzoną rolą tj. pracownik agencji, w tokenie JWT (w zaszyfrowanym i podpisanym przez serwer tokenie JWT) jest zaszyta informacja o tym, klientów o jakich identyfikatora może obsługiwać.</p>
</details>

(wkrótce więcej opisów technicznych)

Wersja demonstracyjna oprogramowania
==

Działające oprogramowanie można zobaczyć za pomocą dostarczonego narzędzia do wdrożeń (deploymentów) stron - najpewniej - statycznych - w opisie repozytorium. 


Organizacja wytwarzania oprogramowania
==

Link do tablicy kanban projektu znajduje się w issue #1. Nie umieszczamy tutaj linku, bo bez względu gdzie repozytorium zostanie zmirrorowane, to na administratorze nowego projektu będzie ciążyć obowiązek aktualizacji issue nr 1.
Z tego samego powodu 

Język komunikacji przy organizacji prac przy wytwarzaniu oprogramowania
==

Podczas prac posługujemy się językeim polskim, natomiast opisując zagadnienia wplatamy słowa angielskie, by - kiedy nadejdzie taki czas - osoby znające inne języki mogli również dołączyć.

Kontakt
==

Kontakt możliwy przez zakładkę kontakt w działającym systemie.

&copy; pracaportal 2023
