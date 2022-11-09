# Übersicht über Markdown 
## In diesem File beschäftigen wir uns mit der Syntax von Markdown und was das Ziel von Markdown ist.
## Theorie:
### Was ist der Sinn hinter Markdown und warum wurde es erschaffen?

Die Erfinder definieren Markdown als [vereinfachte Auszeichnungssprache](https://de.wikipedia.org/wiki/Vereinfachte_Auszeichnungssprache) welche das Dokument in seiner Ausgangsform für den Benutzer leicht lesbar machen soll ohne es zu konvertieren. Als [Auszeichnungselemente](https://de.wikipedia.org/wiki/Auszeichnungselement) wurde deshalb Auszeichnungsarten verwendet welche an [Plain Text](https://de.wikipedia.org/wiki/Plain_text) oder E-Mails errinern. Mit Hilfe eines Markdown-Konverters werden diese Schlussendlich in [W3C](https://de.wikipedia.org/wiki/W3C) konforme [XHTML](https://de.wikipedia.org/wiki/Extensible_Hypertext_Markup_Language) Files umgewandelt.  
  
### Verbreitung
Genutzt wird Markdown oder eine Markdown-ähnliche Syntax vorwiegend auf Entwicklerplattformen mit eher technikaffinem Publikum wie GitHub, Stack Overflow oder der Blogging-Plattform Ghost. Markdown wird häufig bei Readme-Dateien verwendet. Es kommt auch in populären webbasierten Tools wie der Projektmanagementsoftware Trello oder dem Instant-Messaging-Dienst Slack zum Einsatz. Die meisten größeren [Content-Management-Systeme](https://de.wikipedia.org/wiki/Content-Management-System), Wikis und Foren lassen sich durch Plug-ins um Markdown-Unterstützung erweitern. Es gibt Plugins für [WordPress](https://de.wikipedia.org/wiki/WordPress), [Joomla](https://de.wikipedia.org/wiki/Joomla) oder [MediaWiki](https://de.wikipedia.org/wiki/MediaWiki). Auch [Flat-File-Content-Management-Systeme](https://de.wikipedia.org/wiki/Flat-File-Content-Management-System) wie Kirby setzen fast durchweg auf Markdown als Auszeichnungssprache. Viele statische Webseiten-Generatoren (static site generators, wie Jekyll, Hugo oder Hexo) nutzen Markdown als Auszeichnungssprache für den Inhalt. Markdown wird auch in anderer Software genutzt, z. B. im Software-Dokumentationswerkzeug [Doxygen](https://de.wikipedia.org/wiki/Doxygen). Es gibt viele Editoren für Markdown, die meist auch sofort ein HTML-Preview erzeugen – in einem zweiten Screen oder gleich im gerade editierten Text.   

  
## Praxis:
## Die Syntax von Markdown   

  
### Überschriften und deren Unterüberschriften
In Markdown gibt es unterschiedliche Arten von Überschriften die sich in ihrer Größe unterscheiden. Diese Überschriften werden alle mit eine # Symbol am Anfang des Textes definiert. 
#### Beispiele hierfür sind:

* Die Überschrift der Größe Level 1 die mit "# Beispiel Text" definiert wird. Diese sieht wie folgt aus:
# Überschrift Level 1

* Die Überschrift der Größe Level 2 wird mit "## Beispiel Text" definiert und sieht so aus:
## Überschrift Level 2

* Die Überschrift der Größe Level 3 wird mit "### Beispiel Text" definiert und sieht so aus:
### Überschrift Level 3

* Die Überschrift der Größe Level 4 wird mit "#### Beispiel Text" definiert und sieht so aus:
#### Überschrift Level 4

* Die Überschrift der Größe Level 5 wird mit "##### Beispiel Text" definiert und sieht so aus:
##### Überschrift Level 5

* Die Überschrift der Größe Level 6 wird mit "###### Beispiel Text" definiert und sieht so aus:
###### Überschrift Level 6    

  
### Trennstriche
Man kann auch Trennstriche in Markdown einfügen.
- - - 
Dies funktioniert durch drei Bindestriche "- - -" in diesem Format.  

### hervorgehoben/betonte Wörter
In Markdown gibt es verschiedene Möglichkeiten Wörter hervorzuheben.

__Zum Beispiel kann mann es mit zwei Unterstrichen vor und nach dem Satz machen.__
**Aber auch mit zwei Sternen vor und nach dem Satz funktioniert es.**

Allerdings kann man seine Wörter auch schief schreiben.

_Dies funktioniert mit einem Unterstrich vor und nach dem Satz._ 
*Und wie bei dem vorherigem natürlich auch wieder mit Sternen*

Man kann auch beides kombinieren und einen Fetten und kursiven Text machen.

***Dies funktioniert mit drei Sternen am Satzanfang und ende.***
___Oder drei Unterstrichen am Anfang und Ende eines Satzes___

### Aufzählungen in unterschiedlichen Ebenen
Hier gibt mehrere Aufzählungszeichen.

Das erste hierbei wären Punkte.

* Hierbei einfach
* einen Stern vor
* den Satz machen!
  * Mit einrückungen
  * gibt es sogar
  * Unterpunkte.

Und wenn man es nummeriert haben will .

1. Dann geht es
2. mit der Zahl 
3. und einem Punkt 
4. vor dem Satz.
5. (1. oder 2. und so weiter) 

### Links mit Textangabe
Wenn man eine Link einfügen will und diesem einen Text anfügen will macht man es wie folgt.

"[Text] (Link)"

[Hier kommt man zum Beispiel zu Google.](https://www.google.at/) 

### Quellcode Angabe
Wenn man ein Code Ausschnitt in das Dokument einfügen will geht das in dem man drei einzelne Anführungszeichen vor und nach dem Text einfügt.

```
Dies funktioniert nicht nur mit Code sondern auch mit Text!
```

### Tabellen
Tabellen erstellt man mit sogenannten Pipes(|) vor und nach dem Text. Um Überschriften abzutrennen von Text benutzt man Bindestriche zwischen den Pipes. Mit Doppelpunkte vor oder nach den Bindestrichen kann man ihn nach links oder rechts zentrieren. Wenn man keine Doppelpunkte benutzt zentriert sich der Text.
|Text|Text|
|:----|----:|
|Hallo Test|Hier Test|
|ist|ein|
|Text|!|

### Bilder
Auch Bilder können eingefügt werden. Dies funktioniert mit "![Alternativ-Text] (Pfad zum Bild)". So sieht das aus wenn es angewendet wird.
![Bild nicht gefunden.](Grosser_Panda.JPG "Panda")

### Blockzitate
Blockzitate werden mit ein Dach ">" Symbol gekennzeichnet. Wenn man mehrere aneinander Reiht wird es eingerückt.

>Hallo
>>Dies
>>>Ist
>>>>eingerückt.

### Fußnoten
So sieht eine Fußnote aus. Wie dies aussieht findet man heraus wenn man draufklickt.

Beschreibung einer Fußnote[^1]
[^1]: Eine Fußnote wird mit [^BeispielText] deklariert und mit [^BeispielText] : Text deklariert

### Task Listen
Task Listen werden in das File eingefügt in dem man vor dem Wort ein Minus und dann "[ ]" oder "[x]" setzt. Dies sieht wie folgt aus.

- [ ] Test
- [x] Test
- [ ] Test
- [ ] Test
- [x] Test
- [x] Test
- [x] Test

### durchgestrichene Absätze
Bei Durchgestrichenen Absätzen handelt es sich um durchgestrichenen Text. Das funktioniert mit zwei Wellen vor und nach dem Wort.

~~Dies ist ein Test~~

### deaktivierte Urls
Man kann Urls deaktivieren indem man sie unter zwei Graviszeichen setzt. Im folgenden Beispiel kann man sehen wied die funktioniert.

`https://www.google.at/`

# Quellen
* [Wikipedia](https://de.wikipedia.org/wiki/Markdown)
* [Markdown Syntax](https://markdown-syntax.de/Syntax/Horizontale-Linien/)
* [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
* [Textformatierung mit Markdown](http://intranet.psych.uni-potsdam.de/moodle/help.php?file=markdown.html#:~:text=Aufz%C3%A4hlungspunkte,Das%20Leerzeichen%20ist%20wichtig.)
* [Ionos](https://www.ionos.at/digitalguide/websites/web-entwicklung/markdown/#:~:text=%3A%2F%2Fexample.com)-,Tabellen,die%20entsprechenden%20Zellen%20mit%20Bindestrichen.)
* [Github Blog](https://github.blog/2014-04-28-task-lists-in-all-markdown-documents/)
