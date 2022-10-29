# 30 Days Of JavaScript

| # Day |                                                                       Topics                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| 01    |                                                             [Introduction](./readMe.md)                                                             |
| 02    |                                               [Data Types](./02_Day_Data_types/02_day_data_types.md)                                                |
| 03    |                             [Booleans, Operators, Date](./03_Day_Booleans_operators_date/03_booleans_operators_date.md)                             |
| 04    |                                            [Conditionals](./04_Day_Conditionals/04_day_conditionals.md)                                             |
| 05    |                                                     [Arrays](./05_Day_Arrays/05_day_arrays.md)                                                      |
| 06    |                                                       [Loops](./06_Day_Loops/06_day_loops.md)                                                       |
| 07    |                                                 [Functions](./07_Day_Functions/07_day_functions.md)                                                 |
| 08    |                                                    [Objects](./08_Day_Objects/08_day_objects.md)                                                    |
| 09    |                             [Higher Order Functions](./09_Day_Higher_order_functions/09_day_higher_order_functions.md)                              |
| 10    |                                           [Sets and Maps](./10_Day_Sets_and_Maps/10_day_Sets_and_Maps.md)                                           |
| 11    |                      [Destructuring and Spreading](./11_Day_Destructuring_and_spreading/11_day_destructuring_and_spreading.md)                      |
| 12    |                                  [Regular Expressions](./12_Day_Regular_expressions/12_day_regular_expressions.md)                                  |
| 13    |                             [Console Object Methods](./13_Day_Console_object_methods/13_day_console_object_methods.md)                              |
| 14    |                                         [Error Handling](./14_Day_Error_handling/14_day_error_handling.md)                                          |
| 15    |                                                    [Classes](./15_Day_Classes/15_day_classes.md)                                                    |
| 16    |                                                        [JSON](./16_Day_JSON/16_day_json.md)                                                         |
| 17    |                                            [Web Storages](./17_Day_Web_storages/17_day_web_storages.md)                                             |
| 18    |                                                  [Promises](./18_Day_Promises/18_day_promises.md)                                                   |
| 19    |                                                   [Closure](./19_Day_Closures/19_day_closures.md)                                                   |
| 20    |                                  [Writing Clean Code](./20_Day_Writing_clean_codes/20_day_writing_clean_codes.md)                                   |
| 21    |                                                          [DOM](./21_Day_DOM/21_day_dom.md)                                                          |
| 22    |                            [Manipulating DOM Object](./22_Day_Manipulating_DOM_object/22_day_manipulating_DOM_object.md)                            |
| 23    |                                        [Event Listeners](./23_Day_Event_listeners/23_day_event_listeners.md)                                        |
| 24    |                             [Mini Project: Solar System](./24_Day_Project_solar_system/24_day_project_solar_system.md)                              |
| 25    | [Mini Project: World Countries Data Visualization 1](./25_Day_World_countries_data_visualization_1/25_day_world_countries_data_visualization_1.md) |
| 26    | [Mini Project: World Countries Data Visualization 2](./26_Day_World_countries_data_visualization_2/26_day_world_countries_data_visualization_2.md) |
| 27    |                             [Mini Project: Portfolio](./27_Day_Mini_project_portfolio/27_day_mini_project_portfolio.md)                             |
| 28    |                          [Mini Project: Leaderboard](./28_Day_Mini_project_leaderboard/28_day_mini_project_leaderboard.md)                          |
| 29    |             [Mini Project: Animating characters](./29_Day_Mini_project_animating_characters/29_day_mini_project_animating_characters.md)             |
| 30    |                                     [Final Projects](./30_Day_Mini_project_final/30_day_mini_project_final.md)                                      |

🧡🧡🧡 HAPPY CODING 🧡🧡🧡

<div>
<small>Support the <strong>author</strong> to create more educational materials</small> <br />  
<a href = "https://www.paypal.me/asabeneh"><img src='./images/paypal_lg.png' alt='Paypal Logo' style="width:10%"/></a>
</div>

<div align="center">
  <h1> 30 Days Of JavaScript: Introduction</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

<sub>Author:
<a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
<small> January, 2020</small>
</sub>

<div>

🇬🇧 [English](./readMe.md)
🇪🇸 [Spanish](./Spanish/readme.md)
🇮🇹 [Italian](./Italian/readMe.md)
🇷🇺 [Russian](./RU/README.md)
🇹🇷 [Turkish](./Turkish/readMe.md)
🇦🇿 [Azerbaijan](./Azerbaijani/readMe.md)
🇰🇷 [Korean](./Korea/README.md)
🇻🇳 [Vietnamese](./Vietnamese/README.md)
🇵🇱 [Polish](./Polish/readMe.md)


</div>

</div>
</div>

[Day 2 >>](./02_Day_Data_types/02_day_data_types.md)

![Thirty Days Of JavaScript](./images/day_1_1.png)

- [30 Days Of JavaScript](#30-days-of-javascript)
- [📔 Day 1](#-day-1)
	- [Introduction](#introduction)
	- [Requirements](#requirements)
	- [Setup](#setup)
		- [Install Node.js](#install-nodejs)
		- [Browser](#browser)
			- [Installing Google Chrome](#installing-google-chrome)
			- [Opening Google Chrome Console](#opening-google-chrome-console)
			- [Writing Code on Browser Console](#writing-code-on-browser-console)
				- [Console.log](#consolelog)
				- [Console.log with Multiple Arguments](#consolelog-with-multiple-arguments)
				- [Comments](#comments)
				- [Syntax](#syntax)
			- [Arithmetics](#arithmetics)
		- [Code Editor](#code-editor)
			- [Installing Visual Studio Code](#installing-visual-studio-code)
			- [How to Use Visual Studio Code](#how-to-use-visual-studio-code)
	- [Adding JavaScript to a Web Page](#adding-javascript-to-a-web-page)
		- [Inline Script](#inline-script)
		- [Internal Script](#internal-script)
		- [External Script](#external-script)
		- [Multiple External Scripts](#multiple-external-scripts)
	- [Introduction to Data types](#introduction-to-data-types)
		- [Numbers](#numbers)
		- [Strings](#strings)
		- [Booleans](#booleans)
		- [Undefined](#undefined)
		- [Null](#null)
	- [Checking Data Types](#checking-data-types)
	- [Comments Again](#comments-again)
	- [Variables](#variables)
- [💻 Day 1: Exercises](#-day-1-exercises)

# 📔 Day 1
## Einleitung

**Glückwunsch**, dass Sie sich entschieden haben, an der 30 Tage JavaScript-Programmierung Challenge teilzunehmen. In diesem Wettbewerb lernen Sie alles, was Sie brauchen, um ein JavaScript-Programmierer zu werden, und generell das ganze Konzept der Programmierung. Am Ende der Challenge erhalten Sie ein 30DaysOfJavaScript-Programming-Challenge-Zertifikat. Falls Sie Hilfe benötigen oder anderen helfen möchten, können Sie der [Telegrammgruppe] (https://t.me/ThirtyDaysOfJavaScript) beitreten.

**Die 30DaysOfJavaScript**-Herausforderung ist ein Leitfaden für Anfänger und fortgeschrittene JavaScript-Entwickler. Willkommen bei JavaScript. JavaScript ist die Sprache des Webs. Mir macht es Spaß, JavaScript zu verwenden und zu lehren, und ich hoffe, Sie werden es auch tun.

In dieser JavaScript-Herausforderung lernen Sie Schritt für Schritt JavaScript, die beliebteste Programmiersprache in der Geschichte der Menschheit.
JavaScript wird verwendet **_um Websites interaktiv zu gestalten, um mobile Anwendungen, Desktop-Anwendungen und Spiele zu entwickeln_**. Heutzutage kann JavaScript auch für **_maschinelles Lernen_** und **_AI_** verwendet werden.
**_JavaScript (JS)_** hat in den letzten Jahren an Popularität gewonnen und ist seit sechs Jahren in Folge die führende
Programmiersprache und ist die am häufigsten verwendete Programmiersprache auf
Github.

## Anforderungen

Für die Teilnahme an dieser Challenge sind keine Vorkenntnisse im Programmieren erforderlich. Du brauchst nur:

1. Motivation
2. Einen Computer
3. Internet
4. Ein Browser
5. Ein Code-Editor

## Einrichtung

Ich glaube, Sie haben die Motivation und den starken Wunsch, ein Entwickler zu sein, einen Computer und Internet. Wenn du das hast, dann hast du alles, um loszulegen.

### Node.js installieren

Sie brauchen Node.js vielleicht nicht sofort, aber vielleicht für später. Installieren Sie [node.js](https://nodejs.org/en/).

![Node herunterladen](images/download_node.png)

Nach dem Herunterladen doppelklicken und installieren

![Node installieren](images/install_node.png)

Wir können überprüfen, ob node auf unserem lokalen Rechner installiert ist, indem wir unser Geräteterminal oder die Eingabeaufforderung öffnen.


```sh
asabeneh $ node -v
v12.14.0
```

Als ich dieses Tutorial erstellt habe, habe ich die Node-Version 12.14.0 verwendet, aber jetzt ist die empfohlene Version von Node.js für den Download die Version 14.17.6, wenn Sie dieses Material verwenden, haben Sie vielleicht eine höhere Node.js-Version.

### Browser

Es gibt viele Browser auf dem Markt. Ich empfehle jedoch dringend Google Chrome.

#### Installieren von Google Chrome

Installieren Sie [Google Chrome] (https://www.google.com/chrome/), falls Sie noch keinen Browser haben. Wir können kleinen JavaScript-Code auf der Browserkonsole schreiben, aber wir verwenden die Browserkonsole nicht zur Entwicklung von Anwendungen.

![Google Chrome](images/google_chrome.png)

#### Google Chrome-Konsole öffnen

Sie können die Google Chrome-Konsole öffnen, indem Sie entweder auf die drei Punkte in der oberen rechten Ecke des Browsers klicken, _Weitere Tools -> Entwicklertools_ wählen oder eine Tastenkombination verwenden. Ich bevorzuge die Verwendung von Tastenkombinationen.

Chrome öffnen](images/opening_developer_tool.png)

So öffnen Sie die Chrome-Konsole mit einem Tastaturkürzel.

```sh
Mac
Command+Option+J

Windows/Linux:
Ctl+Shift+J
```

![Opening console](images/opening_chrome_console_shortcut.png)

After you open the Google Chrome console, try to explore the marked buttons. We will spend most of the time on the Console. The Console is the place where your JavaScript code goes. The Google Console V8 engine changes your JavaScript code to machine code.
Let us write a JavaScript code on the Google Chrome console:

![write code on console](./images/js_code_on_chrome_console.png)

#### Writing Code on Browser Console

We can write any JavaScript code on the Google console or any browser console. However, for this challenge, we only focus on Google Chrome console. Open the console using:

```sh
Mac
Command+Option+I

Windows:
Ctl+Shift+I
```

##### Console.log

Um unseren ersten JavaScript-Code zu schreiben, haben wir eine integrierte Funktion **console.log()** verwendet. Wir haben ein Argument als Eingabedaten übergeben, und die Funktion zeigt die Ausgabe an. Wir haben `'Hello, World'` als Eingabedaten oder Argument in der Funktion console.log() übergeben.

```js
console.log('Hallo, Welt!')
```

##### Console.log mit mehreren Argumenten

Die Funktion **`console.log()`** kann mehrere durch Kommas getrennte Parameter annehmen. Die Syntax sieht wie folgt aus:**`konsole.log(param1, param2, param3)`**

![console log multiple arguments](./images/console_log_multipl_arguments.png)

```js
console.log('Hallo', 'Welt', '!')
console.log('HAPPY', 'NEW', 'YEAR', 2020)
console.log('Willkommen', 'bis', 30, 'Tage', 'Von', 'JavaScript')
```

Wie Sie aus dem obigen Codeschnipsel ersehen können, kann _`console.log()`_ mehrere Argumente annehmen.

Herzlichen Glückwunsch! Sie haben Ihren ersten JavaScript-Code mit _`console.log()`_ geschrieben.

##### Kommentare

Wir können Kommentare zu unserem Code hinzufügen. Kommentare sind sehr wichtig, um den Code besser lesbar zu machen und um Anmerkungen in unserem Code zu hinterlassen. JavaScript führt den Kommentarteil unseres Codes nicht aus. In JavaScript ist jede Textzeile, die mit // beginnt, ein Kommentar, und alles, was wie dieses `//` eingeschlossen ist, ist ebenfalls ein Kommentar.

**Beispiel: Einzeiliger Kommentar**

``js
// Dies ist der erste Kommentar  
// Dies ist der zweite Kommentar  
// Ich bin ein einzeiliger Kommentar
```

**Beispiel: Mehrzeiliger Kommentar**

```js
/*
Dies ist ein mehrzeiliger Kommentar  
 Mehrzeilige Kommentare können mehrere Zeilen umfassen  
 JavaScript ist die Sprache des Webs  
 */
```

##### Syntax

Programmiersprachen sind den menschlichen Sprachen ähnlich. Englisch und viele andere Sprachen verwenden Wörter, Phrasen, Sätze, zusammengesetzte Sätze und andere mehr, um eine sinnvolle Nachricht zu vermitteln. Die englische Bedeutung von Syntax ist _die Anordnung von Wörtern und Phrasen, um wohlgeformte Sätze in einer Sprache zu bilden_. Die technische Definition von Syntax ist die Struktur von Anweisungen in einer Computersprache. Programmiersprachen haben eine Syntax. JavaScript ist eine Programmiersprache, und wie andere Programmiersprachen hat sie ihre eigene Syntax. Wenn wir keine Syntax schreiben, die JavaScript versteht, wird es verschiedene Arten von Fehlern auslösen. Wir werden später verschiedene Arten von JavaScript-Fehlern untersuchen. Sehen wir uns zunächst einmal die Syntaxfehler an.

![Fehler](images/raising_syntax_error.png)

Ich habe absichtlich einen Fehler gemacht. Daraufhin meldet die Konsole Syntaxfehler. Eigentlich ist die Syntax sehr informativ. Sie informiert darüber, welche Art von Fehler gemacht wurde. Wenn wir den Leitfaden zur Fehlerrückmeldung lesen, können wir die Syntax korrigieren und das Problem beheben. Der Prozess der Identifizierung und Beseitigung von Fehlern in einem Programm wird Debugging genannt. Lassen Sie uns die Fehler beheben:

```js
console.log('Hallo, Welt!')
console.log('Hallo, Welt!')
```

Bis jetzt haben wir gesehen, wie man Text mit _`console.log()`_ ausgibt. Wenn wir einen Text oder eine Zeichenkette mit _`console.log()`_ ausgeben, muss der Text innerhalb von einfachen Anführungszeichen, doppelten Anführungszeichen oder einem Backtick stehen.
**Beispiel:**

```js
console.log('Hallo, Welt!')
console.log("Hallo, Welt!")
console.log(`Hallo, Welt!`)
```

#### Arithmetik

Lassen Sie uns nun das Schreiben von JavaScript-Codes mit _`console.log()`_ auf der Google Chrome-Konsole für Zahlendatentypen weiter üben.
Zusätzlich zum Text können wir mit JavaScript auch mathematische Berechnungen durchführen. Lassen Sie uns die folgenden einfachen Berechnungen durchführen.
Es ist möglich, JavaScript-Code auf der Google Chrome-Konsole direkt ohne die Funktion **_`console.log()`_** zu schreiben. Sie ist jedoch in dieser Einführung enthalten, weil der Großteil dieser Herausforderung in einem Texteditor stattfinden würde, wo die Verwendung der Funktion obligatorisch wäre. Sie können direkt mit Anweisungen auf der Konsole herumspielen.

![Arithmetik](images/arithmetic.png)

```js
console.log(2 + 3) // Addition
console.log(3 - 2) // Subtraktion
console.log(2 * 3) // Multiplikation
console.log(3 / 2) // Division
console.log(3 % 2) // Modulus - Ermitteln des Rests
console.log(3 ** 2) // Potenzierung 3 ** 2 == 3 * 3
```

### Code-Editor

Wir können unsere Codes auf der Browserkonsole schreiben, aber für größere Projekte wird das nicht reichen. In einer realen Arbeitsumgebung verwenden Entwickler verschiedene Code-Editoren, um ihre Codes zu schreiben. In dieser 30-Tage-JavaScript-Herausforderung werden wir Visual Studio Code verwenden.

#### Installieren von Visual Studio Code

Visual Studio Code ist ein sehr beliebter Open-Source-Texteditor. Ich empfehle [Visual Studio Code](https://code.visualstudio.com/) herunterzuladen, aber wenn Sie andere Editoren bevorzugen, können Sie gerne mit dem arbeiten, was Sie haben.

![Vscode](images/vscode.png)

Wenn Sie Visual Studio Code installiert haben, können Sie es jetzt benutzen.

#### Wie man Visual Studio Code verwendet

Öffnen Sie Visual Studio Code durch einen Doppelklick auf das Symbol. Wenn Sie es öffnen, erhalten Sie diese Art von Schnittstelle. Versuchen Sie, mit den beschrifteten Symbolen zu interagieren.

![Vscode ui](./images/vscode_ui.png)

![Vscode Projekt hinzufügen](./images/adding_project_to_vscode.png)

![Vscode Projekt öffnen](./images/opening_project_on_vscode.png)

![Skriptdatei](images/scripts_on_vscode.png)

![Live-Server installieren](images/vsc_live_server.png)

![laufendes Skript](./images/running_script.png)

![Codierung läuft](./images/launched_on_new_tab.png)

## Hinzufügen von JavaScript zu einer Webseite

JavaScript kann auf drei verschiedene Arten zu einer Webseite hinzugefügt werden:

- **_Inline-Skript_**
- **_Internes Skript_**
- **_Externes Skript_**
- **Mehrere externe Skripte_**

Die folgenden Abschnitte zeigen verschiedene Möglichkeiten, JavaScript-Code zu Ihrer Webseite hinzuzufügen.

### Inline-Skript

Erstellen Sie einen Projektordner auf Ihrem Desktop oder an einem beliebigen Ort, nennen Sie ihn 30DaysOfJS und erstellen Sie eine **_`index.html`_** Datei im Projektordner. Fügen Sie dann den folgenden Code ein und öffnen Sie ihn in einem Browser, zum Beispiel [Chrome](https://www.google.com/chrome/).

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfScript:Inline Script</title>
  </head>
  <body>
    <button onclick="alert('Welcome to 30DaysOfJavaScript!')">Click Me</button>
  </body>
</html>
```

Jetzt haben Sie gerade Ihr erstes Inline-Skript geschrieben. Mit der eingebauten Funktion _`alert()`_ können wir eine Pop-up-Warnmeldung erstellen.

### Internes Skript

Das interne Skript kann im _`head`_ oder im _`body`_ geschrieben werden, aber es ist vorzuziehen, es im Body des HTML-Dokuments unterzubringen.
Zuerst schreiben wir es in den Kopfteil der Seite.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfScript:Internal Script</title>
    <script>
      console.log('Welcome to 30DaysOfJavaScript')
    </script>
  </head>
  <body></body>
</html>
```

In den meisten Fällen schreiben wir ein internes Skript auf diese Weise. Den JavaScript-Code in den Body-Abschnitt zu schreiben, ist die bevorzugte Option. Öffnen Sie die Browserkonsole, um die Ausgabe von "console.log()" zu sehen.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfScript:Internal Script</title>
  </head>
  <body>
    <button onclick="alert('Welcome to 30DaysOfJavaScript!');">Click Me</button>
    <script>
      console.log('Welcome to 30DaysOfJavaScript')
    </script>
  </body>
</html>
```

Öffnen Sie die Konsole des Browsers, um die Ausgabe von `console.log()` zu sehen.

![js code from vscode](./images/js_code_vscode.png)

### Externes Skript

Ähnlich wie das interne Skript kann der Link zum externen Skript in der Kopfzeile oder im Textkörper platziert werden, wobei es vorzuziehen ist, ihn in den Textkörper zu setzen.
Zunächst sollten wir eine externe JavaScript-Datei mit der Erweiterung .js erstellen. Alle Dateien, die mit der Endung .js enden, sind JavaScript-Dateien. Erstellen Sie eine Datei mit dem Namen introduction.js in Ihrem Projektverzeichnis, schreiben Sie den folgenden Code und verlinken Sie diese .js-Datei am Ende des Textkörpers.

```js
console.log('Welcome to 30DaysOfJavaScript')
```

Externe Skripte im _head_:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfJavaScript:External script</title>
    <script src="introduction.js"></script>
  </head>
  <body></body>
</html>
```

Externe Skripte im _body_:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfJavaScript:External script</title>
  </head>
  <body>
    <!-- Der externe JavaScript-Link kann in der Kopfzeile oder im Textkörper stehen --> 
    <!-- Vor dem schließenden Tag des Körpers ist der empfohlene Platz für das externe JavaScript-Skript -->
    <script src="introduction.js"></script>
  </body>
</html>
```

Öffnen Sie die Browserkonsole, um die Ausgabe von `console.log()` zu sehen.

### Mehrere externe Skripte

Wir können auch mehrere externe JavaScript-Dateien mit einer Webseite verknüpfen.
Erstellen Sie eine Datei `helloworld.js` im Ordner 30DaysOfJS und schreiben Sie den folgenden Code.

```js
console.log('Hello, World!')
```

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Multiple External Scripts</title>
  </head>
  <body>
    <script src="./helloworld.js"></script>
    <script src="./introduction.js"></script>
  </body>
</html>
```

_Ihre Datei main.js sollte unter allen anderen Skripten stehen. Es ist sehr wichtig, sich dies zu merken.

![Multiple Script](./images/multiple_script.png)

## Einführung in Datentypen

In JavaScript und auch in anderen Programmiersprachen gibt es verschiedene Arten von Datentypen. Die folgenden sind die primitiven JavaScript-Datentypen: _String, Number, Boolean, undefined, Null_, und _Symbol_.

### Zahlen

- Ganze Zahlen: Ganzzahlige (negative, null und positive) Zahlen
  Beispiel:
  ... -3, -2, -1, 0, 1, 2, 3 ...
- Fließkommazahlen: Dezimalzahl
  Beispiel:
  ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...

### Zeichenketten

Eine Sammlung von einem oder mehreren Zeichen zwischen zwei einfachen Anführungszeichen, doppelten Anführungszeichen oder Backticks.

**Beispiel:**

```js
'a'
'Asabeneh'
"Asabeneh"
'Finland'
'JavaScript is a beautiful programming language'
'I love teaching'
'I hope you are enjoying the first day'
`We can also create a string using a backtick`
'A string could be just as small as one character or as big as many pages'
'Any data type under a single quote, double quote or backtick is a string'
```

### Boolesche Werte

Ein boolescher Wert ist entweder Wahr oder Falsch. Jeder Vergleich ergibt einen booleschen Wert, der entweder wahr oder falsch ist.

Ein boolescher Datentyp ist entweder ein wahrer oder ein falscher Wert.

**Beispiel:**

```js
true // wenn das Licht an ist, ist der Wert true
false // wenn das Licht aus ist, ist der Wert false
```

### Undefiniert

Wenn wir in JavaScript einer Variablen keinen Wert zuweisen, ist der Wert undefiniert. Wenn eine Funktion nichts zurückgibt, ist der Wert außerdem undefiniert.

```js
let vorname
console.log(vorname) // undefiniert, da noch kein Wert zugewiesen ist
```

### Null

Null in JavaScript means an empty value.

```js
let emptyValue = null
```

## Überprüfen von Datentypen

Um den Datentyp einer bestimmten Variablen zu überprüfen, verwenden wir den Operator **typeof**. Siehe das folgende Beispiel.

```js
console.log(typeof 'Asabeneh') // string
console.log(typeof 5) // number
console.log(typeof true) // boolean
console.log(typeof null) // object type
console.log(typeof undefined) // undefined
```

## Wieder Kommentare

Denken Sie daran, dass die Kommentierung in JavaScript ähnlich wie in anderen Programmiersprachen ist. Kommentare sind wichtig, um Ihren Code besser lesbar zu machen.
Es gibt zwei Arten des Kommentierens:

- _Einzeilige Kommentierung_
- _Multiline commenting_

```js
// Kommentierung des Codes selbst mit einem einzelnen Kommentar
// let vorname = 'Asabeneh'; einzeiliger Kommentar
// let nachname = 'Yetayeh'; einzeiliger Kommentar
```

Mehrzeilige Kommentierung:

```js
/*
  let location = 'Helsinki';
  let age = 100;
  let isMarried = true;
  Dies ist ein mehrzeiliger Kommentar
*/
```

## Variablen

Variablen sind _Behälter_ für Daten. Variablen werden verwendet, um Daten an einem Speicherplatz zu _speichern_. Wenn eine Variable deklariert wird, wird ein Speicherplatz reserviert. Wenn einer Variablen ein Wert (Daten) zugewiesen wird, wird der Speicherplatz mit diesen Daten gefüllt. Um eine Variable zu deklarieren, verwenden wir die Schlüsselwörter _var_, _let_ oder _const_.

Für eine Variable, die sich zu einem anderen Zeitpunkt ändert, verwenden wir _let_. Wenn sich die Daten überhaupt nicht ändern, verwenden wir _const_. Zum Beispiel ändern sich PI, der Name des Landes und die Schwerkraft nicht, und wir können _const_ verwenden. Wir werden var in dieser Aufgabe nicht verwenden und ich empfehle Ihnen auch nicht, es zu verwenden. Es ist eine fehleranfällige Art, Variablen zu deklarieren, und hat viele Lecks. Wir werden mehr über var, let und const im Detail in anderen Abschnitten (scope) sprechen. Für den Moment ist die obige Erklärung ausreichend.

Ein gültiger JavaScript-Variablenname muss die folgenden Regeln befolgen:

- Ein JavaScript-Variablenname darf nicht mit einer Zahl beginnen.
- Ein JavaScript-Variablenname darf keine Sonderzeichen außer Dollarzeichen und Unterstrich enthalten.
- Ein JavaScript-Variablenname folgt einer camelCase-Konvention.
- Ein JavaScript-Variablenname sollte keine Leerzeichen zwischen den Wörtern enthalten.

Im Folgenden finden Sie Beispiele für gültige JavaScript-Variablen.

```js
firstName
lastName
country
city
capitalCity
age
isMarried

first_name
last_name
is_married
capital_city

num1
num_1
_num_1
$num1
year2020
year_2020
```

Die erste und zweite Variable in der Liste entspricht der camelCase-Konvention für die Deklaration in JavaScript. In diesem Material werden wir CamelCase-Variablen (CamelWithOneHump) verwenden. Wir verwenden CamelCase(CamelWithTwoHump), um Klassen zu deklarieren, wir werden über Klassen und Objekte in einem anderen Abschnitt diskutieren.

Beispiel für ungültige Variablen:

```js
  first-name
  1_num
  num_#_1
```

Lassen Sie uns Variablen mit verschiedenen Datentypen deklarieren. Um eine Variable zu deklarieren, müssen wir das Schlüsselwort _let_ oder _const_ vor dem Variablennamen verwenden. Nach dem Variablennamen schreiben wir ein Gleichheitszeichen (Zuweisungsoperator) und einen Wert (zugewiesene Daten).

```js
// Syntax
let nameOfVariable = value
```

Der NameOfVriable ist der Name, der verschiedene Daten des Wertes speichert. Siehe unten für detaillierte Beispiele.

**Beispiele für deklarierte Variablen**

```js
// Deklaration verschiedener Variablen mit unterschiedlichen Datentypen
let firstName = 'Asabeneh' // Vorname einer Person
let lastName = 'Yetayeh' // Nachname einer Person
let country = 'Finnland' // Land
let city = 'Helsinki' // Hauptstadt
let age = 100 // Alter in Jahren
let isMarried = true

console.log(firstName, lastName, country, city, age, isMarried)
```

```sh
Asabeneh Yetayeh Finland Helsinki 100 true
```

```js
// Declaring variables with number values
let age = 100 // age in years
const gravity = 9.81 // earth gravity  in m/s2
const boilingPoint = 100 // water boiling point, temperature in °C
const PI = 3.14 // geometrical constant
console.log(gravity, boilingPoint, PI)
```

```sh
9.81 100 3.14
```

```js
// Variablen können auch in einer Zeile durch Komma getrennt deklariert werden, ich empfehle jedoch eine separate Zeile, um den Code besser lesbar zu machen
let name = 'Asabeneh', job = 'teacher', live = 'Finland'
console.log(name, job, live)
```

```sh
Asabeneh teacher Finland
```

Wenn Sie die Datei _index.html_ im Ordner 01-Day aufrufen, sollten Sie Folgendes erhalten:

![Day one](./images/day_1.png)

🌕 Du bist großartig! Du hast soeben Tag 1 der Herausforderung bestanden und bist auf dem Weg zur Größe. Mach jetzt ein paar Übungen für dein Gehirn und deine Muskeln.

# 💻 Tag 1: Übungen

1. Schreiben Sie einen einzeiligen Kommentar, der besagt, _Kommentare können Code lesbar machen_.
2. Schreiben Sie einen weiteren einzeiligen Kommentar, der besagt, _Willkommen bei 30DaysOfJavaScript_
3. Schreibe einen mehrzeiligen Kommentar, der besagt, _Kommentare können den Code lesbar, einfach wiederverwendbar_
   _und informativ_

4. Erstellen Sie eine variable.js-Datei und deklarieren Sie Variablen und weisen Sie die Datentypen string, boolean, undefined und null zu.
5. Erstellen Sie die Datei datatypes.js und verwenden Sie den JavaScript-Operator **_typeof_**, um verschiedene Datentypen zu überprüfen. Prüfen Sie den Datentyp jeder Variablen
6. Deklaration von vier Variablen ohne Zuweisung von Werten
7. Deklarieren Sie vier Variablen mit zugewiesenen Werten
8. Deklarieren Sie Variablen, um Ihren Vornamen, Nachnamen, Familienstand, Land und Alter in mehreren Zeilen zu speichern
9. Deklarieren Sie Variablen zum Speichern Ihres Vornamens, Nachnamens, Familienstandes, Landes und Alters in einer einzigen Zeile
10. Deklarieren Sie zwei Variablen _myAge_ und _yourAge_ und weisen Sie ihnen Anfangswerte zu und protokollieren Sie sie in der Browserkonsole.

```sh
I am 25 years old.
You are 30 years old.
```

🎉 CONGRATULATIONS ! 🎉

[Day 2 >>](./02_Day_Data_types/02_day_data_types.md)
