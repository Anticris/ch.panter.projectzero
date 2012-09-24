Java / Maven Kickstart Project
==============================

Installation
------------

You may fork this project using the github functionality and use it as a base
for your own project.

Usage
-----

    git clone https://github.com/Anticris/ch.panter.projectzero
    cd ch.panter.projectzero
    mvn install
    mvn eclipse:eclipse

    in eclipse IDE:
    ->import -> add project to workspace ->browse to folder ->finish
    If Maven is not configured yet, select add

Features
--------

* Java 1.6
* Maven
* Junit
* Mock Objects
* slf4j

Diskussion als Fallstudie
-------------------------

-Als Build-Tool wurde Apache Maven gewählt, welches uns im Unterricht vorgestellt wurde: Maven ist frei verfügbar, auf jedem Rechner zu installieren
 und hat ein grosses Repository verschiedenster bekannter Java-Bibliotheken.

-Durch die dependencies welche in Maven deklariert werden, ist sichergestellt das:
	-> Die gleiche Arbeitsumgebung (hier eclipse)
	-> Eine bestimmte Version dieser Arbeitsumgebung (hier Junot) als Mindestanforderung
	-> Alle externen (nicht Java-Runtime) Bibliotheken sowie deren Version
	-> Somit ist sichergestellt dass alle am Projekt Mitwirkenden dieses auch kompilleren können.
-Die 3rd Party Library sfl4j ist ein einfach zu gebrauchender Logger, welcher ermöglicht das z.B. Debug-Ausgaben nur während der Ausführung in der  IDE ausgegeben werden und nicht später im fertigen Programm, es sei denn ein Protokoll ist an bestimmten Stellen erwünscht.


