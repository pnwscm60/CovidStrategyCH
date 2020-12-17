<html>
  <head>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3.0.1/es5/tex-mml-chtml.js"></script>
    <title>Why to hold the r-value low</title>
    <meta charset="utf-8" />
    <meta http-equiv="expires" content="0">
  <style>
 /* FONTS */
 @import url("https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300,700");
</style>
  </head>
  <body>
    <div style="flex: 1;"><h2>R-Wert</h2> <a href="main">Zurück</a></div>
    <div class="twocol">
    <div class="ntext">
   Was sagt R<sub>e</sub> genau aus? Die Reproduktionszahl zeigt, um wie viel grösser (oder kleiner) die nächste Generation an Infizierten während einer Epidemie sein wird. Nehmen wir an, Person 0 sei infiziert und infiziere zwei andere Personen. Dies entspricht einem R<sub>e</sub> von 2. Diese Person ist also die 1. Generation, nennen wir sie g. Sie enthält g = 1 Person. Die zweite Generation umfasst g&#183;R<sub>0</sub> = 2 Personen. Da jede dieser beiden Personen wieder 2 andere infiziert, sind es in der dritten Generation g&#183;R<sub>e</sub>^2 = 4 Personen, usw. Wir werden also pro Infektionszyklus 1, 2, 4, 8, 16, ... neue Infektionsfälle haben. Mathematisch interessierten fällt sofort auf, dass es sich dabei um eine geometrische Reihe handelt. Solange R<sub>e</sub> 2 bleibt, steigt die Zahl der Infizierten <em>exponentiell</em> an. Die Fallzahl wird erst sinken, wenn die Anzahl der infizierten Personen so gross ist, dass es für eine infizierte Person schwieriger wird, noch nicht infizierte Personen «zu finden».
    </div>
    <div class="ntext">
      Liegt R<sub>e</sub> also über 1, steigt die Fallzahl laufend an, bis die Zunahme durch die grosse Zahl der bereits Infizierten gebremst wird. Liegt R<sub>e</sub> aber zwischen 0 und 1, konvergiert die Summe der täglichen Fallzahlen zur Summe 
      $$
      \frac{g}{1-R_e}
      $$
    </div>
      <div class="ntext">
        Bei einem einfachen eingipfeligen Verlauf können wir vermuten, dass R<sub>e</sub> unter 1 liegt, sobald die Spitze der Neuinfektionen überschritten wird. Nehmen wir ab diesem Zeitpunkt ein gleichbleibendes R<sub>e</sub> an, können wir die Gesamtsumme der Fälle abschätzen. In der Schweiz wurde der Gipfel der Neuinfektionen in der ersten Welle mit 13000 Fällen ungefähr am 26. März überschritten. Nehmen wir ab diesem Zeitpunkt ein R<sub>e</sub> von 0.7 an – dies erscheint aufgrund der Daten der <a href="#ref2" id="rref2">Swiss National Covid-19 Science Task Force</a> als vernünftig – konvergiert die Summe der Infektionsfälle zu 
        $$
        Bestätigte Infektionen = \frac{g}{1-r} = \frac{13000}{0.3} = 43000
        $$
        </div>
    <div class="ntext">
      Aus der Formel wird sofort klar, dass ein R<sub>e</sub> von 0.9 zu wesentlich mehr Fällen führen wird. Deshalb macht es Sinn, die Massnahmen so zu treffen, dass das R<sub>e</sub> möglichst rasch möglichst tief liegt – eine lange auf hohem Niveau verbleibende Fallzahl wird in der Konsequenz zu vielen Toten führen.
      Die Summe der zu erwartenden Todesfälle lässt sich nach demselben Prinzip abschätzen. 
      </div>
    </div>
      <div id="foot" style="font-size:0.9em;margin-top:1em;font-style:italic;">
        <div style="border-top:1px solid #000000;width:100px;clear:both;height:4px;line-height:4px;">&nbsp;</div>
        <div id="ref1"><a href="#rref1">^</a> As R is the name of a statistics software widely used today, we use the term of r-value instead of R.</div>
        <div id="ref2"><a href="#rref2">^</a> <a href="https://ncs-tf.ch/de/lagebericht" target="_blank">Situation report by the Swiss National Covid-19 Science Task Force</a></div>
    <div id="ref2"><a href="#rref2">^</a> <a href="https://www.worldometers.info/coronavirus/" target="_blank">Worldometer</a></div>
        <div id="ref3"><a href="#rref3">^</a>Ich bevorzuge den Begriff «Abstand halten» oder «physical distancing». Denn es geht m. E. nicht darum, keine Kontakte mehr zu pflegen, sondern um das Einhalten der physikalischen Distanz.</div>
    </div>
