Aktualizacja 10 kwiecień 2018.
# ECMA-262 JavaScript - the Core.
Moje tłumaczenie (eng/pl) dokumentu utworzonego przez Dmitriego Shoshnikova. Opisane są tam wszystkie zagadnienia dotyczącze core JavaScript:
1) Obiekt.
2) Łańcuch prototypu (a prototype chain).
3) Konstruktor.
4) Stos kontekstów wykonania (Execution context stack).
5) Kontekst wykonania. (Execution context).
6) Variable object.
7) Activation object.
8) Łańcuch zasięgu. (Scope chain).
9) Domknięcia - closures.
10) Wskaźnik kontekstu "this".

Link do tłumaczenia:
http://eternes.pl/blog/ecma-262-javascript-the-core

# Lista aplikacji typu "proof of concept": 

 1) Mała aplikacja oparta o framework Angular(ver. 4) pobiera 
i aktualizuje listę użytkowników.
 
[Demo aplikacji](http://eternes.pl/demo/angular/)

[Repozytorium na github](https://github.com/RobertERS/angular-app)

Język programowania: ES6, TypeScript.

Użyte techniki, biblioteki i właściwości JavaScript:
- Fetch API (Body.json),
- RxJS.

Opis modułów:
- dataservice.ts - komponent odpowiedzialny za warstwę połaczenia z serwerem
- user.component.ts - komponent obsługujący akcje użytkownika.
- app.component.ts - główny komponent aplikacji.
 ------------------------------------------------------------------------

2) Prosta aplikacja pobiera dane zadanego użytkownika z dwóch adresów API i po pomyślnym odebraniu obiektów JSON, wyświetla dane dokumencie HTML.
 
[Demo aplikacji](http://eternes.pl/demo/promises/)

[Repozytorium na github](https://github.com/RobertERS/promises)

Użyte narzędzia i technologie:

 - ES6
 - XHR
 - Promise
 - Gulp
    
    Główne pliki to app.es6 oraz load-content.es6

------------------------------------------------------------------------

3) Skrypt tworzy jedną wspólną listę dla dwóch typów obiektów.
Efekt działania jest widoczny w konsoli i częściowo w dokumencie HTML (pola input i textarea).
Po wypełnieniu pola Subject i kliknięciu "Send" zmienia się wartość pól elementów html
oraz wartość message w powiązanym obiekcie.
 
[Demo aplikacji](http://eternes.pl/demo/observer/)

[Repozytorium na github](https://github.com/RobertERS/observer_pattern)

Język programowania: ES5

Wzorce projektowe:
- Module
- Revealing Module
- Interface
- Observer

Użyte techniki i właściwości JavaScript:
- Closure
- Prototype
- Context manipulation

Opis plików:
   - main.js - utworzenie obiektu MObserver.
   - observer.js - moduł MObserver oraz interfejs IObserver
   - dom.js - moduły tworzące uchwyty do elementów DOM 

------------------------------------------------------------------------