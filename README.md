# ToDoAppSturms

[lila todo app]

**1. Projekt erstellt:**

- Ich habe ein neues React-Projekt erstellt.

**2. Komponenten erstellt:**
Ich habe mehrere React-Komponenten erstellt, darunter:

- TodoWrapper: Eine Komponente, die die gesamte Todo-Liste verwaltet.
- TodoForm: Eine Formular-Komponente zum Hinzufügen neuer Todos.
- Todo: Eine Komponente, die eine einzelne Todo darstellt.

**3. Todo-Liste verwaltet:**

- Ich habe den Zustand der Todo-Liste in der TodoWrapper-Komponente mit Hilfe von useState verwaltet.
- Ich habe eine Funktion addTodo erstellt, um neue Todos zur Liste hinzuzufügen.

**4. Formular zum Hinzufügen von Todos:**

- Ich habe ein Eingabefeld und einen Button in der TodoForm-Komponente erstellt.
  Das Eingabefeld erlaubt es Benutzern, neue Todos einzugeben.
  Wenn der Benutzer den Button drückt, wird die eingegebene Todo zum Zustand der Todo-Liste hinzugefügt.

**5. Einzelne Todos gerendert:**
-Ich habe eine Schleife über die Todo-Liste in der TodoWrapper-Komponente implementiert, um jede einzelne Todo-Komponente zu rendern.
Jede Todo-Komponente zeigt den Inhalt einer einzelnen Todo sowie Symbole für Bearbeiten und Löschen an.

**6. Funktionalität zum Löschen von Todos:**

- Ich habe eine Funktion implementiert, um Todos aus der Liste zu entfernen, wenn der Benutzer auf das entsprechende Symbol klickt.

**7. Funktionalität zum Bearbeiten von Todos:**
-Ich möchte noch eine Bearbeitungsfunktion implementieren, die es dem Benutzer ermöglicht, den Text einer Todo zu bearbeiten.

**8. Visualisierung der Todo-Liste:**

Ich habe meine Todo-Liste mit CSS gestaltet, um ein ansprechendes Erscheinungsbild zu erzielen.

**9. Fehlerbehandlung:**

- Ich habe begonnen, Fehler zu behandeln, wie z.B. den Fehler "TypeError: task is undefined", indem ich eine Überprüfung in der Todo.js-Komponente implementiert habe, um sicherzustellen, dass task definiert ist, bevor ich darauf zugreife.


## Mittwoch, 15. Mai 2024:

# Welche Tickets wurden heute bearbeitet?/Was wurde gemacht?
- {REACT: Backend-Integration mit Axios
#15}
  -> `axios` installieren und verwenden, um API-Aufrufe an das Backend zu machen
- {REACT: API-Aufrufe für CRUD-Operationen integrieren
#16}
  -> Anpassung der `TodoWrapper.js`, um API-Aufrufe für die CRUD-Operationen hinzufügen, ohne den Import von uuid und dessen Verwendung zu entfernen.

### Zusammenfassung der App-Komponenten:

- `TodoList.js`: Diese Komponente verwaltet die ToDos und verwendet die API, um ToDo-Elemente zu laden, hinzuzufügen, zu aktualisieren und zu löschen.
- `TodoForm.js`: Formular zum Hinzufügen neuer ToDos.
- `EditTodoForm.js`: Formular zum Bearbeiten bestehender ToDos.
- `Todo.js`: Komponente zum Anzeigen eines einzelnen ToDo-Elements mit Optionen zum Bearbeiten und Löschen.
- `App.js`: Die Hauptkomponente der App, die TodoList rendert.
- `index.js`: Der Einstiegspunkt der React-App.
