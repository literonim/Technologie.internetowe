# Markdown - nauka !
###### by literonim


![](http://www.njs.com.np/a/GitHub_Logo_small.png) to strona która została uruchomiona w kwietniu 2008 roku przez Tom-a Preston-Werner-a, Chris-a Wanstrath-a oraz PJ Hyett-a. Sewris przeznaczony jest do rozwoju projektów programistycznych wykorzystujący system kontroli wersji Git. 10 kwietnia 2013 roku ![](http://www.njs.com.np/a/GitHub_Logo_small.png) ogłosił iż posiada 3.5 miliona zarejestrowanych użytkowinków i przechowuje ponad 6 milionów repozyntoriów.

####Niektóre z funkcji oferowane przez portal:

- Projekty mogą być publikowane na serwerach Github-a oraz przechowywane lokalnie
- Posiada interfejs graficzny
- Wyszukiwarka repozytoriów
- Możliwość klonowania repozytoriów
- Statystyki
- Przeglądanie historii
- Tworzenie gałęzi oraz zarządzanie nimi
- Klonowanie repozytoriów
- Sprawdzanie zmian w kodzie
- GitHub Wiki

##Pierwsze kroki

Pomoc:

```
$ git help <polecenie>
$ git <polecenie> --help
$ man git-<polecenie>
```

Konfiguracja własnej nazwy użytkownika:

`$ git config --global user.name "twoja_nazwa"`

Konfiguracja adresu e-mail:

`$ git config --global user.email twoja_nazwa@twoja_nazwa.twoja_nazwa`

Aby sprawdzić bieżącą listę ustawień należy użyć następującego polecenia:

`$ git config --list`

Klonowanie istniejącego repozytorium:

`$ git clone git://github.com/twoja_nazwa/twoja_nazwa.git`

Sprawdzanie stanu plików:

`$ git status`

Aby rozpocząć śledzenie nowego pliku użyj komendy:

`$ git add twoja_nazwa`

Zatwierdzanie zmian:

`$ git commit`

Podgląd historii rewizji:

`$ git log`

Pobieranie danych ze zdalnego projektu:

`$ git fetch [twoja_nazwa_zdalengo_repozytorium]`

Wypychanie zmian na zewnątrz:

`$ git push [twoja_nazwa_zdalnego_repo] [twoja_nazwa_gałęzi]`

Wygenerownie pary kluczy SSH:

```
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/schacon/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /twoja_nazwa/twoja_nazwa/twoja_nazwa/twoja_nazwa_rsa.
Your public key has been saved in /twoja_nazwa/twoja_nazwa/twoja_nazwa/twoja_nazwa_rsa.pub.
The key fingerprint is:
44:c6:3b:8f:c2:j8:66:33:bb:92:n8:87:3l:1l:8k:2n twoja_nazwa@twoja_nazwa.twoja_nazwa
```


----
To tyle odnośnie krótkiego wstępu, poniżej zamieszczam listę z przydatnymi adresami witryn internetowych:

[Nauka markdown-a](http://markdowntutorial.com/)

[Pro Git book](http://git-scm.com/book/pl/)

[Github Wikipedia](http://pl.wikipedia.org/wiki/GitHub)

[Podstawy Git-a i Github-a](http://designconcept.webdev20.pl/articles/podstawy-gita-i-githuba/)
