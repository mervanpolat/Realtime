**Real-Time-Chat**

**Lernziele**
- Verwendung von HTML/CSS und JavaScript für das Frontend der App.
- Einsatz von Java, Spring Boot und WebSocket mit dem STOMP-Protokoll als Lösung für das Backend.

**Über**
Dies ist eine einfache Mehrbenutzer-Chat-Anwendung; sie unterstützt öffentliche Chats, bei denen alle Benutzer der App Nachrichten senden und sehen können, sowie private Chats zwischen zwei App-Benutzern.

Wenn Sie eine visuelle Darstellung davon sehen möchten, wie die App aussehen soll, schauen Sie bitte im Abschnitt **Beispiele** auf der folgenden Webseite nach: **Projekt-Endphase**.

Diese Anwendung läuft in Echtzeit; nachdem das Projekt gestoppt wurde, gehen alle Informationen verloren. Jeder neue Benutzer muss sich mit einem eindeutigen Benutzernamen anmelden und wird dann zur Haupt-Chat-Seite weitergeleitet. Jeder neue Benutzer beginnt mit dem öffentlichen Chat, in dem alle vorher gesendeten Nachrichten sichtbar sind. Andere Online-Benutzer werden als Liste auf der linken Seite der Seite angezeigt. Der Benutzer kann öffentliche Nachrichten senden, die für alle Benutzer sichtbar sind, oder private Nachrichten an beliebige verfügbare Online-Benutzer. Wenn eine private Nachricht gesendet wird und der Empfänger nicht im privaten Chatfenster des Senders geöffnet ist, erscheint ein neuer Nachrichten-Zähler, der die Anzahl der ungelesenen Nachrichten anzeigt, und der Name des neuesten Absenders wird an den Anfang der Online-Benutzerliste verschoben.

Sobald sich ein Benutzer abmeldet (indem er einfach das Fenster schließt), wird sein Benutzername wieder freigegeben und kann erneut verwendet werden. Die bereits gesendeten öffentlichen Nachrichten bleiben bestehen, jedoch besteht kein Zugriff mehr auf die privaten Nachrichten.

Das Projekt wurde mit Java 17 entwickelt.

**Anleitung zum Ausführen**
Laden Sie das Stammprojekt als Zip-Ordner herunter, entpacken Sie den Ordner und öffnen Sie ihn in IntelliJ IDEA (oder einer anderen IDE Ihrer Wahl). Führen Sie die Datei `src/main/java/chat/Application.java` aus.

Die Webseite kann über `localhost:8080` in Ihrem bevorzugten Browser aufgerufen werden. Um mehrere Benutzer zu simulieren, öffnen Sie mehrere Browserfenster mit `localhost:8080`.

---

**Diplomarbeit entwickelt von Mervan Polat und Sawsan Arab.**