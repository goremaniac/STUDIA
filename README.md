# STUDIA

Zadania różne:

Sortowanie metodą: bąbelkową, przez wstawianie, merge.
Wyznaczanie najczęściej występującego elementu.
Sprawdzanie czy liczba jest pierwsza
czy wyraz jest palindromem
Suma cyfr liczby
Silnia
Tabliczka mnożenia

Oblicz pole powierzchni koła. Dane wprowadź od użytkownika z klawiatury.

Podpowiedź:
dodaj na początku:
import java.io.*;
wczytywanie danych z klawiatury:
Scanner obiekt = new Scanner(System.in);

String zmienna=obiekt.nextLine;
int liczba=obiekt.nextInt;

BufferedReader odczyt = new BufferedReader(new InputStreamReader(System.in));

oraz obsługę wyjątku IOException
public static void main(String[] args) throws IOException

użyj metody parseDouble.
sposób użycia:
liczba= Double.parseDouble(odczyt.readLine());

2. Wyświetl wynik dzielenia dwóch liczb.

3. Napisz program, który sprawdza ile użytkownik ma lat, jeśli:
mniej niż 18 - wyś    wietla się komunikat “nie możesz głosować”
co najmniej 18, mniej niż 35 “możesz głosować, ale nie możesz zostać wybranym na prezydenta”
co najmniej 35 “możesz kandydować na prezydenta miasta”
4. Napisz program, który wczyta trzy liczby, następnie wyświetli je w kolejności od najmniejszej do największej
5. Napisz program, który sprawdzi czy z podanych trzech liczb oznaczających długości boków można utworzyć trójkąt.
6. Napisz program, który sprawdzi czy z podanych trzech liczb oznaczających długości boków można utworzyć trójkąt prostokątny.




Pętle - zadania od najprostszych.
Wyświetl liczby od 1 do 10
Wyświetl liczby od 5 do 10
Wyświetl liczby od 10 do 1
Wyświetl liczby od 1 do 100 podzielne bez reszty:
przez 3
przez 5
przez 3 i 5 jednocześnie
Wyświetl liczby w pętli z przedziału podanego przez użytkownika
Wyświetl tabliczkę mnożenia (w wierszach i kolumnach)
 Wyświetl kolejne elementy ciągu Fibonacciego.
Napisz program obliczający pierwiastki równania kwadratowego ax2+bx+c = 0

Losowanie:
Wylosuj liczbę z podanego zakresu i wyświetl ją (zakres min i max wpisuje użytkownik).
Napisz program,  który losuje liczbę. Użytkownik ma za zadanie odgadnąć liczbę wylosowaną przez komputer z określonego zakresu.  Program ma podpowiadać “za dużo”, “za mało” lub “odgadłeś za “+liczba_prób+”razem”.
Napisz program, który losuje 6 z 49 liczb (używając tablic).
Napisz program, który losuje 6 z 49 liczb (używając tablic), liczby nie mogą się powtarzać.
Napisz program, który losuje 6 z 49 liczb (używając kolekcji).
Napisz program, który pobiera od użytkownika 6 liczb z 49. Program ma wziąć pod  uwagę zestaw unikalnych sześciu liczb.  Następnie program dokonuje losowań do czasu gdy wylosuje wybrane przez użytkownika zestawienie liczb. Program podaje po ilu lata i ilu dniach użytkownik wylosowałby liczby (np. potrzeba x lat i x dni). Zakładamy że losowania odbywają się codziennie (jedno losowanie na jeden dzień).

Operacje na plikach - wczytywanie danych z pliku, zapis do plików.


Jak losować:
import java.util.Random;

public class Main {

   public static void main(String[] args) {
       int liczbaWylosowana;
       Random los = new Random();

       do {
           liczbaWylosowana=los.nextInt(50);
           System.out.print(liczbaWylosowana+" ");
       }
           while(liczbaWylosowana!=10);
   }
}



Wprowadzanie liczb typu int z klawiatury:

Scanner  zKlawiatury = new Scanner(System.in);
int zakresMin= zKlawiatury.nextInt();
System.out.print(zakresMin);


