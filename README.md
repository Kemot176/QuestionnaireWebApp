# QuestionnaireWebApp

http://studentevent.pl/

# Cel projektu:

Celem  zadania  projektowego  było  wykonanie  systemu  webowego  umożliwiającego przeprowadzanie badań ankietowych online w sposób anonimowy. 


# Film prezentacyjny:

[Film prezentacyjny](https://www.youtube.com/watch?v=kQL19cP0gNQ&feature=youtu.be)


# Dokumentacja:

[Dokumentacja](https://snodom.github.io/QuestionnaireWebApp/html/)

# Repozytorium:

[Część front-end](https://github.com/Kemot176/projektinz) <br>
[Część back-end](https://github.com/snodom/questionnaire-app)


# Założenia projektowe:

Głownym założeniem projektowym było stworzenie web serwisu do przeprowadzenia anonimowych badań ankietowych online z możliwośćią podglądu przez użytkownika osobistych odpowiedzi. Aby spełnić załozenia niezbędnym było opracowanie koncepcji działania web serisu. Następnym krokiem było zaprojektowenie bazy danych oraz implementacja wykoncypowanych rozwiązań.

# Opis dzialania systemu:

Anonimowość: <br> <br> Administrator tworzy dla użytkownika token niepowiązany z kodem dostępu. Dzięki niemu użytkownik ma możliwość wygenerowania unikalnego kodu dostępu. 

Sprawdzanie odpowiedzi przez użytkownika: <br> <br> Po przesłaniu odpowiedzi przez użytkownika zostaje stworzony szyfr, wygenerowany na podstawie kodu autoryzacji, odpowiedzi oraz ciągu zaburzającego. Szyfr powstaje każdorazowo przy pobieraniu odpowiedzi z bazy danych. Dzięki zastosowaniu takiej funkcjonalości użytkownik ma możliwość sprawdzenia czy nikt nie ingerował w jego odpowiedzi. 


Funkcjonalności przewidziane dla administratora: <br>

- tworzenie ankiet <br>
- generowanie wybranej ilości kodów dostępu dla ankiet <br>
- generowanie wybranej ilości tokenów dla systemu generującego kody <br>
- podgląd odpowiedzi anonimowych użytkowników <br>
- możliwość sprawdzenia czy osoba, która otrzymała odpowiedni token przystąpiła do wypelniania ankiety  <br>

Funkcjonalności przewidziane dla użytkownika: <br>

- możliwość generowania unikalnego kodu dostępu na podstawie tokenu 
- możliwość udzielania odpowiedzi dla ankiety związanej z wygenerowanym kodem 
- możliwość sprawedzenia własnych odpowiedzi 





