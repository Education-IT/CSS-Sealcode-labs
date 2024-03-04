# SealCode.org

## Progessive Enhancement:

- Fajnie jest od razu podać szerokość i wysokość zdjęcia, bo w czasie jego ładowania - przeglądarka już zarezerwuje mniejce na niego

## TOPOGRAFIA:

- Ukłąd topogrficzny: Rozmiar tekstu (linijka tekstu powinna mieć średnio 66 znaków - nie więcej niż 70! Łatwość czytania)
- Paragrafy powinny być odzielone
- Musi być "oddech" pomiędzy krawędziami tekstu a krawędziami ekranu

## FONTY:

- https://systemfontstack.com
- Możemy w CSS ustalić kolejke fontów które chcemy aby przeglądarka wybierze pierwszy dostępny. Używanie wgranych w przeglądarke fontów - przyspiesza działanie naszej strony!
- Możemy to zobaczyć w DevTools w zakłądce Computed
- Szeryfowe: Te z ozdobnikami sans-serif

## Dostępność (ally):

- jeżeli strona będzie dobra dla osób niewidomych, to będzie również dobre dla botów chodzącymi po stronie i dla pozycjonowania
  -> alt-text dla obrazków : Opis obrazka w postaci tekstu, co się na nim znajduje
  -> semantyczny HTML | nagłówki, linki jako tag 'a' a nie jako JS.
  -> https://frontlive.pl/blog/dostepnosc-semantyczny-html
  -> https://www.whocanuse.com/

## Layout Shift

- Wtedy gdy w wyniku załadowania zdjęcia zmieni się nam układ strony.
- Dobrze jest pobrać informacje o zdjęciu (ile ma px) i dodać to jako atrybut width i height i w CSS zmienić jego wielkość/szerokość.

## shape-outside

- dzięki niemu można osiągnąć efekt "przytulenia" tekstu -> fajnie to w narzędziach developerskich można w FireFox zrobić.

## Nawigowanie do nagłówków:
to co jest napisane po "#" -> nie jest wysyłany do serwera | to tylko jest na użycie przeglądarki. # domyślnie skupia się na elemencie o danym id
