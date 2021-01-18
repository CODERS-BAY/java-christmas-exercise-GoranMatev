# Das ist eine Wiederholung der objektorientierten Konzepte.

Bitte versuche als Übung alles in Markdown zu beantworten. Hier ist ein [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

1. Was ist das Ziel der Objektorientierung?
 * Von der realen Welt ein Modell abzubilden.
2. Gibt es OOP nur in Java?
 * Nein auch andere Programmiersprachen wie C# usw. nutzen OOP.
3. Was ist der Unterschied zwischen Objekt und Klasse?
 * Eine Klasse ist die Schablone für ein Objekt. Das Objekt besitzt dann die Attribute und Methoden von der Klasse.
4. Wie erzeuge ich eine neue Instanz? (Welches Schlüsselwort gibt es dafür)
 *  Mit dem Schlüsselwort "new". 
5. Was bedeutet das Schlüsselwort `static` und wo kann es überall verwendet werden?
 * Wenn eine Variable auf static gesetzt wir bedeutet das in allen Objekten diese Variable gleich ist.
6. Wozu dient die Vererbung?
 * Um aus bestehenden Klassen neue zu erzeugen wobei zwischen alter und neuer Klasse dauerhafte Beziehung besteht.
7. Kann in Java von mehreren Klassen geerbt werden? Wenn ja wie?
 * Nein es kann nur von einer Klasse geerbt werden.
8. Welche Vererbungshierarchien kennst du? (Ein Bild reicht aus)
  * Die Subklassen erben von der Superklasse
9. Was beudeted Casten und wie ist die Syntax in Java dafür?
  * Bedeutet Typenumwandlung.  Von int auf long durch einfaches Zuweisen. 
    ```java
    int wert = 10; 
    long wert2 = 500; 
    wert2 = wert;
    ```
10. Was ist der Unterschied zwischen explizieten und implizieten Typecasting?
 * Beim impliziten benötigt man keinen cast-Operator da von klein auf Groß (int auf long)
 * Beim expliziten also von Groß auf Klein benötigt man einen cast-Operator 
   ```java
   int wert = 10; 
   float wert2 = 12.5f; 
   wert = (int) wert2;
   ```
11. Erkläre die folgenden Schlüsselwörter: `super`, `this`
 *  Mit dem Schlüsselwort `super` ruft man den Konstruktor der Superklasse auf.
 * Das Schlüsselwort `this` ist ein Zeiger auf das aktuelle Objekt oder eine Referenz in einer normalen Methode.
12. Für was dient der `instanceof` Operator. Gib ein sinnvolles Beispiel.
 *  Um zu testen ob ein Objekt einer bestimmten Klasse zugehört.
    ```java
    class Animals {
        public Animals() {}
    }
    
    class Dog extends Animals {
        public Dog() {
            super();    
        }   
    }
    
    public class Main {
        public static void main(String[] args) {
           Dog bello = new DOg();
           return bello instanceof Aninals;
       }
    }
    ```
 ---
 Eclipse bietet auch Markdown unterstützung inklusive Preview. Für die Verwendung muss kein Plugin installiert werden.
