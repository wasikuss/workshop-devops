***
GIT
***

Wprowadzenie
============

Opis dostępnych darmowych klientów gita
---------------------------------------

Podstawy git
============
- konfiguracja nazwy użytkownika, adresu e-mail i parametr autocrlf
- rozróżnienie konfiguracji globalnej i lokalnej
- zakładanie lokalnego repozytorium oraz jego wewnętrzna struktura

    * repozytorium bare
    * repozytorium normalne

- podstawowe operacje
- sprawdzenie statusu kopii roboczej
- obsługa git staging area (aka git index)
- zapisywanie zmian w repozytorium (commit)
- przeglądanie historii zmian w repozytorium
- ignorowanie zbędnych plików
- obsługa git diff (podgląd zmian wprowadzanych przez commit/commity oraz w kopii roboczej i staging area)
- obsługa git reset

Git Internals
-------------
#. Anatomia
#. jak git przechowuje informacje o wersjach
#. jak są one ze sobą powiązane
#. jak przechowywane są informacje o branchach i tagach,
#. co to są „referencje”)

Pojęcia zaawansowane
====================
- schowek – stash
- shelve
- moduły zależne -  submodule
- odnajdowanie „winnych” – blame
- ostatnia deska ratunku – reflog
- wyszukiwanie miejsca regresji – bisect
- cofanie pojedynczego commitu
- „zaawansowane” opcje konfiguracji
- pielęgnacja repozytorium – fsck, gc
- git fat i inne przydatne pluginy
- git hooks

Zadania praktyczne
==================

Praca na commitach
------------------
- inicializacja oraz sprawdzenie statusu repozytorium
- dodawanie oraz commitowanie zmian
- ignorowanie plików oraz katalogów
- resetowanie stanu repozytorium
- obsługa branch'y
- co to jest master, HEAD, HEAD~1, HEAD^1
- tworzenie, usuwanie oraz przełączanie między branchami
- rozróżnienie branchy lokalnych, lokalnych-zdalnych oraz zdalnych
- tworzenie branchy „śledzących” (tracking branches)
- co to jest 'detached HEAD'
- operacje merge, rebase, cherry-pick
- rozwiązywanie konfliktów
- edycja commitów (edycja commit message, łączenie commitów)

Manipulacja branchami
---------------------
- przeprowadzenie operacji merge (fast-forward i non fast-forward), rebase, cherry pick + rozwiązywanie konfliktów
- tworzenie branchy
- praca ze zdalnym repozytorium
- operacje clone, push, fetch, pull
- czym różni się fetch od pull
- tworzenie oraz usuwanie zdalnych branchy

Zarządanie remote
-----------------
- tworzenie oraz usuwanie zdalnych branchy
- pushowanie zmian
- pobieranie zmian



