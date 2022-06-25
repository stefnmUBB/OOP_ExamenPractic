# OOP_ExamenPractic

## Cerința

<i>Creați o aplicație C++ cu interfața grafica utilizator pentru gestiunea melodiilor. Melodia are:
id:int (unic); titlu: string, artist: string, rank (int intre 0 si 10). Melodiile sunt salvate in fișier si
sunt încărcate la pornirea aplicației. Creați un fișier text care conține cel puțin 10 melodii.

Fereastra principala:

1. Prezinta intr-un tabel lista de melodii sortate după rank. Coloane: id, titlu, artist, rank
Melodiile rămân sortate tot timpul.
1. Folosiți QTableView si un model custom, tabelul sa prezinta fiecare atribut al melodiei
plus o coloana adiționala care afișează numărul de melodii care au același rank cu
melodia curenta. Tabelul se actualizează la orice modificare a listei de melodii
1. Interfața permite modificarea rank-ului. Daca se selectează o linie in tabel se încarcă
intr-un textfield titlu melodiei si pe un slider se setează rank-ul lui. Utilizatorul poate
modifica atât titlul cat si rank-ul si daca apasă pe butonul update melodia se actualizează
(actualizarea se reflecta si in fișier) 
1. Melodiile pot fi șterse selectând o melodie in tabel si apăsând butonul delete (melodia se
șterge si din fișier). Daca melodia selectata este ultima melodie a artistului atunci se
afișează un mesaj si melodia nu se șterge.
1. Fereastra in partea de jos are desenate 10 bare, înălțimea barelor este proporționala cu
numărul de melodii de anumit rank (prima bara corespunde la melodii cu rank 0, a doua
la melodii cu rank 1, etc.) Desenul se actualizează la orice modificare a listei de
melodii. </i>

