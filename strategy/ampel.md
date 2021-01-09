<html>
  <head>
    <title>Ampelsystem</title>
    <meta charset="utf-8" />
    <meta http-equiv="expires" content="0">
  <style>
 /* FONTS */
 @import url("https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300,700");
</style>
  </head>
  <body> 
 <div style="display:flex;"><h2>Ampelsystem</h2> <div style="margin-left:2em;padding:3px 6px 0 6px;background-color:#888;color:#fff;font-weight:300;height:27px!important;"><a href="main" style="color:#fff;">Zurück</a></div><div style="margin-left:0.5em;padding:3px 6px 0 6px;background-color:#888;color:#fff;font-weight:300;height:27px!important;"><a href="https://github.com/pnwscm60/CovidStrategyCH/issues" style="color:#fff;">Mitarbeiten</a></div></div>
    <div class="twocol">
    <div class="ntext">
    Das Ampelsystem beinhaltet einfache und klar zu bestimmende Kriterien, die ab bestimmten Grenzwerten bzw. in bestimmten Kombinationen automatisch einen Wechsel der Alarmstufe auslösen. Mit dem Umschalten auf eine andere Stufe treten die entsprechenden Massnahmen innerhalb einer kurzen Frist von 36 Stunden in Kraft. Dies gilt für Verschärfungen und für Lockerungen.
    Die beiden zentralen Ziele – verhindern von Todesfällen und Folgeerkrankungen einerseits, das Offen halten der Schulen zumindest der unteren Stufen – sind nur zu erreichen, wenn die Fallzahlen so tief bleiben, dass ein effizientes Contact Tracing möglich ist. Die Ausbreitung in Schulen der unteren Stufen kann nur mit Mühe beherrscht werden, weil viele Kinder asymptomatisch bleiben. Entsprechend reagiert das System früh auf steigende Infektionsraten.</div>
      <div class="ntext">Im Kontext der teilweise sehr kleinen Schweizer Kantone und der dank kurzen Wegen starken Mobilität in der Schweiz, wäre zu überlegen, die Werte pro Region zu berechnen.
    Folgende Kriterien werden laufend bestimmt:
      <ul>
        <li><strong>7-Tage-Inzidenz/100000 Einwohner*innen</strong> Die 7-Tageinzidenz der neu nachgewiesenen Infektionen wird verwendet, weil dieser Werte weniger auf Ausreisser reagiert, als der Tageswert. Ausgehend von der Initiative für eine pan-Europäische Strategie, in der als Grenze 10 Fälle pro Tag/Million Einwohner*innen genannt wird, ergibt sich eine 7-Tages-Inzidenz/100000 Einwohner*innen von 7 [Priesemann et al 2020].</li>
        <li><strong>Re</strong> Ein Re > 1 bedeutet ein exponentielles Wachstum, Re < 1 eine Abnahme, Re = 1 eine gleichbleibende Infektionsrate. Zu beachten ist, dass die Bestimmung des Re methodenbedingt mit einer Verzögerung von rund 10 Tagen erfolgt. In kleinen Kantonen und bei tiefen Fallzahlen ist Re weniger aussagekräftig. Re kann nicht als «fixe» Schwelle verwendet werden, weil Re bei stabiler sehr niedriger Inzidenz zu 1 konvergieren wird. Re wird deshalb konsequenterweise einzig als Alarmwert verwendet: Steigt R > 1.2, führt dies, unabhängig von den anderen Kriterien, immer zur Anhebung der Stufe. Zur Entscheidung wird der Konfidenzbereich verwendet, d. h. dass bei Re 1.1 [0.95–1.21] dies als Wert >1.2 angesehen wird.</li>
         <li><strong>Aufklärungsrate des Contact Tracing</strong> Das Contact Tracing (und die nachfolgende Quarantäne/Isolation) ist die letzte Abwehrmöglichkeit, wenn das Virus es trotz der anderen Massnahmen schafft, Menschen zu infizieren. Wegen der Überdispersion muss das Tracing vor- und rückwärts erfolgen [Low 2020]. Nur so kann eine hohe Aufklärungsrate und damit Unterbrechung der Infektionsketten sichergestellt werden. Hier ist eine frühzeitige Steuerung wichtig, weil das Contact Tracing nicht beliebig skalierbar ist und bereits bei mässig hohen Fallzahlen überfordert wird.</li>
        <li><strong>Auslastung zertifizierte IPS-Betten</strong> Intensivpflegestationen (IPS) sind bei der Behandlung die letzte Abwehrlinie. Eine Überlastung führt unweigerlich zu steigenden Todesfallzahlen, auch unter nicht-Covid-19-Patient*innen. Das Kriterium ist insofern problematisch, als es gegenüber dem Anstieg der Infektionen ein um 2–3 Wochen verzögertes Signal ergibt. Entsprechend müssen hier grosszügige Sicherheitsgrenzen enthalten sein. Basis für die Angabe der zertifizierten Betten ist die entsprechende Publikation der SGI [SGI 2020].</li>
      </ul>
        <div class="ntext">Das Ampelsystem führt bei Überschreiten von Schwellen <em>automatisch</em> zum Wechsel von Massnahmen. Die Ampel schaltet eine Stufe höher, wenn die Schwelle <em>in mindestens 2 der 4 Kriterien überschritten</em> wird. Lockerungen bedingen, dass <em>alle</em> Schwellen unterschritten werden.</div>
<div class="ntext">Die Positivitätsrate (Anzahl positiver Tests/alle durchgeführten Tests) ist nicht als Kriterium aufgenommen, da deren Interpretation grundsätzlich problematisch und mit der Einführung der Antigenschnelltests noch schwieriger geworden ist.</div>
    </div>
 <h3>Grüne Zonen</h3>
        <div class="ntext">Findet in einer Region während 14 Tagen keine lokale Übertragung statt, werden also nur Personen positiv getestet und bei Einreise isoliert, die von aussen in die Zone einreisen, kann eine Region als «grüne Zone» deklariert werden, was zu einer Aufhebung der Restriktionen aus den Modulen 2 und 3 führt. Bedingung ist, dass keine Nachbarzone höher als Stufe 1 klassiert ist. Die Umsetzung im Sinne der «green zones» von endcoronavirus.org ist in der Schweiz nicht möglich, keine Reisebeschränkungen zwischen Schweizer Kantonen möglich sind. Die Regioneneinteilung ist zu definieren. Wegen der hohen Mobilität insbesondere im Mittelland erscheint es sinnvoll, wenige grosse Regionen zu schaffen (zB West, Süd, Zentral, Nord, Ost).</div>
  </div>
  <div class="ntable" style="display:flex;width:100%;margin-top:1em;">
    <div class="tbl0 st0">
      Kriterien
    </div>
    <div class="tbl5 st1">
      Stufe 1
    </div>
    <div class="tbl5 st2">
      Stufe 2
    </div>
    <div class="tbl5 st3">
      Stufe 3
    </div>
    <div class="tbl5 st4">
      Stufe 4
    </div>
    </div>
  <div class="ntbl" style="display:flex;width:100%;min-width:400px;">
    <div class="tbl0 st0">
      7d-Inzidenz/100k
    </div>
    <div class="tbl5 s1">
      < 7
    </div>
     <div class="tbl5 s2">
      7–13
    </div>
     <div class="tbl5 s3">
      14–20
    </div>
     <div class="tbl5 s4">
     > 20
    </div>
  </div>
  <div class="ntbl" style="display:flex;width:100%;min-width:400px;">
    <div class="tbl0 st0">
      Aufklärung CT
    </div>
    <div class="tbl5 s1">
      > 90 %
    </div>
     <div class="tbl5 s2">
      80–90 %
    </div>
     <div class="tbl5 s3">
      70–80 %
    </div>
     <div class="tbl5 s4">
     < 70 %
    </div>
  </div>
  <div class="ntbl" style="display:flex;width:100%;min-width:400px;">
    <div class="tbl0 st0">
      Auslastung IPS zert.
    </div>
    <div class="tbl5 s1">
      < 50 %
    </div>
     <div class="tbl5 s2">
      50–60 %
    </div>
     <div class="tbl5 s3">
      60–70 %
    </div>
     <div class="tbl5 s4">
     > 70 %
    </div>
  </div>
  <div class="ntbl" style="display:block;margin-top:1em;width:100%;min-width:400px;">
    <div class="tbl0 st0">
      Re
    </div>
    <div class="tbl1 s5">
     Stufenreduktion nur, wenn Re < 1 | wenn Re > 1.2 &#8680; 1 Stufe höher
    </div>
    <div class="tbl1 s5" style="clear:both;">
     Grüne Zonen: Während 14 Tagen keine lokale Übertragung/keine angrenzende Region mit Stufe >1
    </div>
    </div> 
<div id="foot" style="font-size:0.9em;margin-top:1em;font-style:italic;">
  <h3>Literatur</h3>
  <div id="ref1">Low N. Contact tracing for COVID-19. WHO/GOARN Global Consultation on Contact Tracing for COVID-19. https://ispmbern.github.io/covid-19/Forward_backward_WHO_201007.pdf, abgerufen 18.12.2020</div>
<div id="ref2">Priesemann V et al. Calling for pan-European commitment for rapid and sustained reduction in SARS-CoV-2 infections. The Lancet, 2020, DOI:https://doi.org/10.1016/S0140-6736(20)32625-8, abgerufen 18.12.2020</div>
  <div id="ref3">Schweizerische Gesellschaft für Intensivmedizin SGI, Zertifizierungskommission. https://www.sgi-ssmi.ch/de/zertifizierte-is.html (abgerufen 18.12.2020)</div>
    </div>
