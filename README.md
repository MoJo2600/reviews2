Erfolgreiche Reviews 2
======================
Beispielprojekt für den Artikel "Erfolgreiche Reviews 2" aus windows developer 12.2013

Enthalten sind:

* HelloWorld.sln - Ein Beispielprojekt
* HelloWorld.build - NAnt Buildfile für das Projekt
* verify.xml - Jenkins Konfiguration für einen verify Job

Hinweise zu Jenkins
-------------------

Die Konfiguration für den Verify Job kann mit folgendem Befehl importiert werden:

java -jar "C:\Program Files\Jenkins\war\WEB-INF\Jenkins-cli.jar
" -s http://localhost:8080 create-job verify < verify.xml


