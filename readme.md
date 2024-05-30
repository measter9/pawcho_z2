# Zadanie 2

Łańcuch CI po podstawowej konfiguracji i zalogowaniu na dockerhub buduje obraz i przesyła go na prywatne repozytorium.

W następnym kroku sprawdzane jest czy w obrazie na prywatnym repo nie znaleziono cves high i critical.

Ostatni krok wykonuje się jedynie gdy poprzedni zakończył się sukcesem w nim ponownie budujemy obraz i przesyłamy go na publiczne repozytorium.