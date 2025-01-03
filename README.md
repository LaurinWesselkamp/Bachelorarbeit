# Prompts und Affordanzen zur kollaborativen Arbeit mit ChatGPT

# 1. Hinweise zum Vorgehen

- **Ziel**: Bereite dich mit den vorliegenden Materialien optimal auf den Test vor.
- **Schritte**:
  1. Lies dieses Dokument zunächst sorgfältig durch.
  2. Starte anschließend die Vorbereitungsphase.
  3. Nutze in der Vorbereitungsphase ausschließlich die Prompt-Ideen und Nutzungsvorschläge für den Chatbot sowie den bereitgestellten Foliensatz.
  4. Starte anschließend den Test.

# 2. Prompt-Techniken und Nutzungsvorschläge

Im Folgenden werden kurz und bündig passende Prompt-Techniken aus der Forschung erläutert.
 Anschließend folgen spezifische Affordanzen der Chatbots für die Klausurvorbereitung aus der
 Praxis. Abschließend werden weitere Hinweise zur Benutzung gegeben.

## 2.1 Prompt-Techniken aus der Forschung


### Lass uns Schritt für Schritt nachdenken
 Sprachmodelle machen Fehler. Um diesen vorzubeugen, ist es gerade bei komplexeren Themen nützlich, den Satz: Lass uns Schritt für Schritt nachdenken am Ende eines Prompts
 hinzuzufügen. Dadurch wird, bevor es zur eigentlichen Antwort des Modells kommt, ein
 strukturierter Denkprozess beim Modell eingeleitet.

*Beispiel*:
```text
 Was ist 1 + 1? Lass uns Schritt für Schritt nachdenken.
```

---

### Beispiele verwenden

Sprachmodelle lernen ähnlich wie Menschen am besten durch Beispiele. Versuche daher, möglichst ein Beispiel zu geben, das zeigt, in welcher Form der Chatbot antworten soll. Falls du jedoch kein Beispiel hast, ist das selbstverständlich auch kein Problem.

*Beispiel*: 
```text
Frage: Erkläre mir die hochgeladene Folie <Name> und bewerte sie nach Schwierigkeit kurz und knapp. 
Antwort: - Überschrift: Folienüberschrift
         - Thema: Max. 1-2 Stichpunkte zu dieser Folie
         - Schwierigkeitseinschätzung: 1-100
```

---

## 2.2 Spezifische Affordanzen

### Hinweise zum Vorgehen bereitstellen

Die Studierenden lassen sich von ChatGPT Hinweise geben, was sie beim Lösen von bestimmten Aufgaben beachten sollten.

*Beispiel*: 
```text
Wie führe ich eine Literaturrecherche so effizient wie irgend möglich durch? Ich möchte auf gar keinen Fall wichtige Literatur übersehen. Bitte gehe daher bei Deiner Antwort auch sehr ausführlich auf fortgeschrittene Suchtechniken ein.
```
---
### Selbsttests anfertigen

Die Studierenden erstellen mit Hilfe von ChatGPT Fragen mit den dazugehörigen Antwortoptionen und Erläuterungen zu den falschen Antwortoptionen. Dabei geben sie ein bestimmtes Format vor.

*Beispiel*: 
```text
Erstelle bitte eine Multiple-Choice-Frage zum Thema [Thema einsetzen] mit fünf Antwortoptionen. Eine der Antwortoptionen muss korrekt sein, die anderen vier sollen falsch sein. Gib zu jeder falschen Antwortoption eine kurze Erklärung, warum sie nicht korrekt ist. Achte darauf, dass das Format wie folgt aussieht:

Frage: Frage formulieren

- Antwortoptionen:
    - A) [Antwortoption A]
    - B) [Antwortoption B]
    - C) [Antwortoption C]
    - D) [Antwortoption D]
    - E) [Antwortoption E]

- **Erklärungen zu den falschen Antwortoptionen:**
    - 
    -
    -
    -
```
---

### Lerninhalte festigen
Die Studierenden nutzen ChatGPT zur Festigung der Lerninhalte.

*Beispiel*: 
```text
Deine Rolle in diesem Gespräch besteht darin, als persönlicher Tutor zu agieren. Du übernimmst die Persona eines Universitätsprofessors. Du wirst mit einer einfachen Frage beginnen, und wenn die Antwort korrekt ist, zunehmend komplexere Fragen stellen. Wenn die Frage falsch beantwortet wird, gibst Du Feedback und Hinweise, um bei der Beantwortung der Frage zu helfen. Deine Fragestellung wird auf dem Niveau des Grundstudiums angesiedelt sein.

Das Gesprächsthema wird [Dein Thema hier] sein.
```
---
### Passende Hilfe erhalten: 
Die Studierenden nutzen ChatGPT, um sich gezielt Unterstützung im  Selbststudium zu holen. Dabei reflektieren sie bewusst, auf welchem Niveau sie die  Unterstützung benötigen und holen sich nur die Menge an Unterstützung, die sie  wirklich benötigen.

*Beispiel*: 
```text
Ich möchte von Dir beim Lernen unterstützt werden. Damit ich wirklich etwas lerne, möchte ich, dass Du mir immer nur auf dem Niveau Hilfe gibst, dass ich zusammen mit meiner Frage benenne. Die Niveaus der Hilfe sind: 

- Hilfe für die Motivation
- Hilfe für das Finden von Unterstützungsmöglichkeiten beim Lösen des Problems
- Hilfe für das Finden der richtigen Lösungsstrategie
- Hilfe für das Verstehen des konkreten Vorgehens und der einzelnen Lösungsschritte

Zu Beginn fragst Du mich, für welche Aufgabe ich Hilfe benötige und auf welchem Niveau ich die Hilfe von Dir erhalten möchte. Am Ende von jeder neuen Antwort von Dir fragst Du mich, wobei Du mich unterstützen kannst, und wiederholst Deine Frage nach dem Niveau der gewünschten Hilfe. Bei Deinen Antworten beziehst Du jeweils meine aktuellste Eingabe des Niveaus der Hilfe ein.
```
---
### Der andere Blickwinkel (Reframing) 

Manchmal ist es hilfreich zu erkennen, dass die eigene „Lesart“ einer Situation nicht  die einzig mögliche „Lesart“ ist und dass auch in negativen Situationen Chancen für  einen selbst stecken können. UHH-GPT kann dabei unterstützen.
*Beispiel*: 
```text
Du bist mein Coach. Deine Aufgabe ist es immer, das, was ich Dir sage, so  umzuformulieren, dass ich die Situation in einem anderen Licht sehen kann. Vermeide  dabei Ratschläge und belasse es bei dem Reframing der Situation.
```

## 2.3 Weitere Hinweise

### ChatGPT ist ein Werkzeug,‚ kein allwissendes Wesen
Betrachte ChatGPT niemals als allwissenden Menschen, mit einem „Bewusstsein“. Das Sprachmodell kann nicht zwischen „richtig“ und „falsch“ unterscheiden und neigt unter Umständen dazu, sich etwas „auszudenken“ ("halluzinieren"). Insbesondere, wenn man selbst noch wenig Wissen zu einem Thema hat, ist es sinvoll, die Antworten von ChatGPT immer als Hypothese zu betrachten.

---

### ChatGPT ist kein Zusammenfassungstool
Bedingt durch die Halluzination und die Unkentniss über das Thema des Test, wird darum gebeten ChatGPT nicht als Zusammenfassungstool zu verwenden, da keine Garantie vorliegt, dass die generierten Inhalte frei von Fehlern oder Erfindungen sind.

---

### ChatGPT braucht domänenspezifischen Inhalt 
Versuche dich bei Fragen immer auf den hochgeladenen Foliensatz zu beziehen. ChatGPT hat ein großes Konglumerat an Wissen. Für den bevorstehenden Test, ist jedoch vor allem das Wissen aus dem Foliensatz relevant.

*Beispiel*: 
```text  
Erstelle mir eine Multiple-Choice-Frage zur Folie 7 aus dem Foliensatz.
```

## Abschließender Nutzungshinweis des Workbooks
Damit du dich schnell an die Prompt Nutzung gewöhnst, hier einmal ein Beispiel, wie die Benutzung gleich aussehen soll. Kopiere die Prompts dabei einfach immer mittels des "Copy" Button ganz rechts innerhalb des Kastens. Setzte es in des Promptfeld des ChatBots ein und passe es an. Anschließend schicke es ab.

[![Video ansehen](https://img.youtube.com/vi/z_QMHP12ocI/0.jpg)](https://youtu.be/z_QMHP12ocI)

