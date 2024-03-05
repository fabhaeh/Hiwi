<!--
author:   "Fabian Hähre"

user.email:    "fabianhaehre@gmail.com"

version:  0.0.1

language: en

comment:   !Beispiel! Erster Test des Online Kurses zur digitale Kompetenz der DHBW Mosbach
-->

# Digitale Kompetenz **- Selbstlernkurs**




Willkommen zum Selbstlernkurs "**Digitale Kompetenzen**" der [Dualen Hochschule Baden-Württemberg (DHBW) Mosbach](https://www.mosbach.dhbw.de). Dieser Kurs wurde entwickelt, um deine digitalen Fähigkeiten zu verbessern und dich dabei zu unterstützen, die Anforderungen der digitalen Welt besser zu verstehen und zu meistern.

Vorangestellt ist ein _Frageboge_ , welcher dir helfen kann deine bisherigen Fähigkeiten einzuschätzen und so deinen Startpunkt richtig zu wählen.

![images](https://events.mosbach.dhbw.de/media/cache/meta_opengraph/logo.png)





## Fragebogen **- Selbsteinschätzung**


Bitte wähle die Option aus, die am besten zu deiner digitalen Kompetenz passt:



- [ ] Keine Kenntnisse (0) 
- [ ] Grundlegende Kenntnisse (1) 
- [ ] Fortgeschrittene Kenntnisse (2) 
- [ ] Experte (3)



<script>
function calculatePoints() {
    var checkboxes = document.querySelectorAll('input[type="checkbox"]');
    var totalPoints = 0;
    
    checkboxes.forEach(function(checkbox) {
        if (checkbox.checked) {
            totalPoints += parseInt(checkbox.nextSibling.textContent.match([0]));
        }
    });
    
    document.getElementById('totalPoints').textContent = "Gesamtpunktzahl: " + totalPoints;
}
</script>
<div id="totalPoints">Gesamtpunktzahl: 0</div>

<button onclick=calculatePoints()>Punkte berechnen</button>






![images](https://events.mosbach.dhbw.de/media/cache/meta_opengraph/logo.png)










## IT-Kompetenzen


 

### Grundlagen Computertechnologie


_in Bearbeitung_




### Grundlagen Informatik

Informatik, auch als Computerwissenschaft bekannt, ist ein breites und faszinierendes Feld, das sich mit der Verarbeitung von Informationen durch Computer beschäftigt und eine wesentliche Grundlage für die Entwicklung _digitaler Kompetenz_ bildet.

Es umfasst sowohl theoretische als auch praktische Aspekte und spielt eine immer wichtigere Rolle in unserer modernen Welt.

Im Folgenden schauen wir uns die **Grundlagen der Informatik** an und wollen so einen Einstieg finden.


![images](https://events.mosbach.dhbw.de/media/cache/meta_opengraph/logo.png)




#### Programmieren und Programmiersprache




       {{1}}

Um zu die **Arbeitsweise eines Computers** zu verstehen schauen wir uns das Neumann Prinzip an:
!?[video](https://youtu.be/dKKSKModUHk)

{{2}}
Ein Computer führt sogenannte **Maschinenprogramme** aus. Wir wollen uns ansehen, wie solche Maschinenprogramme aussehen:

!?[video](https://youtu.be/v16_4FCqO_I)

{{3}}

Im Gegensatz zu einem CXomputer programmieren wir in sogenannten **höheren Programmiersprachen**:

!?[video](https://youtu.be/JsNOFm2Swnw)



![images](https://events.mosbach.dhbw.de/media/cache/meta_opengraph/logo.png)
##### Algorithmen und Ablaufdiagramme

{{1}}

Ein Algorithmus ist im Grunde genommen wie ein präziser Plan oder eine Anleitung, die wir verwenden, um bestimmte Probleme zu lösen oder Aufgaben zu erledigen. 

Stell dir vor, du bist ein Student, der eine Hausaufgabe bearbeitet. Du könntest einen Algorithmus verwenden, um systematisch durch die Schritte zu gehen, die erforderlich sind, um das Problem zu verstehen, relevante Informationen zu sammeln, Lösungsansätze zu entwickeln und schließlich die Aufgabe erfolgreich zu lösen.

Es ist im Grunde wie ein gut durchdachter Plan, der dich von Anfang bis Ende führt, um das gewünschte Ergebnis zu erreichen.

Ein **Algorithmus** ist ein **schrittweises**, **präzises**, **endliches** Verfahren zur **Lösung eines Problems**, um aus gegebenen Größen, den Inputs, gesuchte Größen, die Outputs, zu ermitteln.


!?[video](https://youtu.be/4wcwqOtReMA)



{{2}}

Zur Darstellung von Algorithmen verwendet man häufg sogenannte  **"Ablaufdiagramme"**.

Neben dem Fakt, dass diese wesentlich _leichter_, sogar ohne Programmiererfahrung, _zu verstehen_ sind, lassen sich so auch sehr komplizierte Algorithmen _übersichtlich darstellen und verdeutlichen_. 

Um einen Eindruck zu bekommen, wie wichtig Ablaufdiagramme sein können, ist der ["Freundschaftsalgorithmus"](https://youtu.be/7dz-7T9HYic?feature=shared) ein gutes Beispiel.


!?[video](https://youtu.be/b1K1dPk_qYo)


Sehr vorteilhaft für das Verstehen des Algorithmus können **Zusicherungen** sein. Diese sind Bedingungen, die an bestimmten Stellen im Algorithmus gelten müssen. Da solche Bedingungen dann auch bei der Programmierung wichtig und hilfreich sind, wollen wir diese im Folgenden besprechen. 



!?[video](https://youtu.be/MhchBNMNWeo) 


Es gibt verschiedene Arten von Ablaufdiagrammen, die je nach ihrem Anwendungszweck und der Zielgruppe, für die sie erstellt werden, variieren können. Hier sind einige der gängigsten Arten von Ablaufdiagrammen(Grafiken müssten noch neu gemaacht werden):

1. Flussdiagramme: 
![images](https://static.kanbantool.com/kanban-guide/de/einfaches-beispiel-eines-flussdiagramms.png)


2. UML-Diagramme:
![images](https://lh3.googleusercontent.com/proxy/F4oH2owBQQ42j0rCl86uKMY6rVufjonKAJJZ1_9LDQ4kCeP17-paGyD2BvUXTGvLoZJo4dIWhMS8LI14L13X_RUQPZ-fXCTByq4xFJhqr7AUVrk)


3. Sequenzdiagramme:
![images](https://www.ionos.de/digitalguide/fileadmin/DigitalGuide/Screenshots_2018/DE-Sequenzdiagramm-Lebenslinien5.png)







**Frage**

Nenne eins der üblichsten **Ablaufdiagramme**:
    [[Flussdiagramm]]
       


![images](https://events.mosbach.dhbw.de/media/cache/meta_opengraph/logo.png)
##### Einführung ins Programmieren mit Java



**Programmieraufgabe: Persönliche Begrüßung**



Schreibe ein Java-Programm, das den Benutzer nach seinem Namen fragt und dann eine personalisierte Begrüßung ausgibt.

```java
import java.util.Scanner;

public class GreetingProgram {
    public static void main(String[] args) {
        // Scanner-Objekt zur Eingabeerfassung erstellen
        Scanner scanner = new Scanner(System.in);
        
        // Benutzer nach seinem Namen fragen
        System.out.print("Geben Sie Ihren Namen ein: ");
        String name = scanner.nextLine();
        
        // Begrüßungsnachricht ausgeben
        System.out.println("Hallo, " + name + "! Willkommen zum Liascript-Kurs.");
        
        // Scanner schließen, um Ressourcen freizugeben
        scanner.close();
    }
}
```

Was macht dieser Code?

[[ ]] ... eine Zahlenreihe sortieren.
[[ ]] ... autonom ein Auto fahren.
[[X]] ... den Benutzer nach seinem Namen fragen.
[[X]] ... eine personalisierte Begrüßung ausgeben.



Schreibe eine Java-Methode namens `addition`, die zwei ganze Zahlen als Parameter annimmt und ihre Summe zurückgibt.



```java
public class Main {
    // Schreibe deine Methode hier
    // Gib die Summe der beiden Zahlen zurück
}
```


<button id="checkButton">Lösung überprüfen</button>

<!-- JavaScript-Code -->
<script>
document.getElementById("checkButton").addEventListener("click", function() {
    // Hier den Code einfügen, der die Lösung der Lernenden überprüft
    // Dies könnte das Ausführen der Tests oder das Vergleichen der Lösung mit erwarteten Ergebnissen beinhalten
    // Gib Feedback basierend auf den Testergebnissen aus
});
</script>


## Digitale Identität












## Medienkompetenz



## Digitales Zusammenleben
## Analyse- und Reflektionskompetetnz 

