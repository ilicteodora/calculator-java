
Zbirni LOC za sve fajlove = 235

Ciklomatska slozenost za metode evaluateExpression i metodu Calculate iznosi 12. Sto znaci da je rizik umanjen.
Kognitivna slozenost za metodu evaluateExpression iznosi 9, a za Calculate iznosi 13. 

Neformalni pregled fajla
Ovaj fajl je implementacija jednostavnog kalkulatora koji moze da izvrsava osnovne matematicke operacije. Napisan je programskim jezikom Java.
Sastoji se od dva fajla, a to su Calculator.java i Start.java. Start.java klasa sadryi glavnu metodu, dok je Calculator.java klasa koja sadryi logiku za izvrsavanje matematickih operacija.

Staticka analiza koda
Fajl Calculator.java:
 - broj linije koda 18- potrebno je preimenovati metodu "ToString" kako ne bi doslo do do zamene sa metodom "toString" iz klase "java.lang.Object";
 - broj linije koda  24 - potrebno je preimenovati metodu "Run" kako bi odgovarala regularnom izrazu;
 - broj linije koda  70 - kako bi smanjili broj linija koda, umesto da promenljivoj "textResult" dodelimo rezultat pa je onda vratimo, mozemo to uraditi direktno;
 - broj linije koda  74 - potrebno je izvrsiti preimenovanje metode "Calculate" da odgovara regularnom izrazu;
 - broj linije koda  183 - return je suvisan i mozemo ga izbaciti.

Fajl Start.java
- broj linije koda 8 i 19- potrebno je zameniti "System.out" sa "logger";
- broj linije koda 6 - potrebno je preimenovati promenljivu "Expresssion" da odgovara regularnom izrazu.
