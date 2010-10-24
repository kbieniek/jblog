---
layout: post
title: Laboratorium2
---

# Laboratorium 2

W katalogu *c* utwórz plik *program.c* zawierający co najmniej 10
linii kodu napisanego w języku C.

    mkdir c
    cd c
    touch program.c


1\. Wyświetl na ekran 2 pierwsze wiersze pliku *program.c*. (*head*)

    head -2 program.c


2\. Wyświetl na ekran 4 ostatnie wiersze pliku *program.c*. (*head*, *tail*)

    tail -4 program.c
lub
    tac program.c |head -4|tac


3\. Wyświetl na ekran całą zawartość pliku *program.c*.

    cat program.c


5\. Plikowi *program.c* nadaj następujące uprawnienia: właściciel – czytanie,
pisanie, grupa – czytanie, pozostali użytkownicy: brak uprawnień. (*chmod*)

    chmod 640


6\. Będąc w katalogu *temp* przenieś katalog *wazne-sprawy* do
katalogu *praca*.

    mv dom/wazne-sprawy praca/


7\. Zarchiwizuj cały katalog *temp*. (*zip* i *tar*)

    tar -rf temp.tar temp
    gzip temp.tar
lub
    zip -r temp.zip temp


8\. Usuń katalog *temp*.

    rm -rf temp


9\. Odtwórz z archiwum katalog *temp*. (*unzip* i *tar*)

    tar -xzf temp.tar.gz

    unzip temp.zip 


[Powrót do bloga](http://sigma.inf.ug.edu.pl/~kbieniek/blog)