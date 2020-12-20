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
 <div style="display:flex;"><h2>Ampelsystem</h2> <div style="margin-left:2em;padding:3px 6px 0 6px;background-color:#888;color:#fff;font-weight:300;height:27px!important;"><a href="main" style="color:#fff;">Zurück</a></div></div>
    <div class="twocol">
    <div class="ntext">
    Das Ampelsystem beinhaltet einfache und klar zu bestimmende Kriterien, die ab bestimmten Grenzwerten bzw. in bestimmten Kombinationen automatisch einen Wechsel der Alarmstufe auslösen. Mit dem Umschalten auf eine andere Stufe treten die entsprechenden Massnahmen innerhalb einer kurzen Frist von 36 Stunden in Kraft. Dies gilt für Verschärfungen und für Lockerungen.
    Die beiden zentralen Ziele – verhindern von Todesfällen und Folgeerkrankungen einerseits, das Offen halten der Schulen zumindest der unteren Stufen – sind nur zu erreichen, wenn die Fallzahlen so tief bleiben, dass ein effizientes Contact Tracing möglich ist. Die Ausbreitung in Schulen der unteren Stufen kann nur mit Mühe beherrscht werden, weil viele Kinder asymptomatisch bleiben. Entsprechend reagiert das System früh auf steigende Infektionsraten.</div>
      <div class="ntext">Im Kontext der teilweise sehr kleinen Schweizer Kantone und der dank kurzen Wegen starken Mobilität in der Schweiz, wäre zu überlegen, die Werte pro Region zu berechnen.
    Folgende Kriterien werden laufend bestimmt:
      <ul>
        <li><strong>Re</strong> Ein Re > 1 bedeutet ein exponentielles Wachstum, Re < 1 eine Abnahme, Re = 1 eine gleichbleibende Infektionsrate. Zu beachten ist, dass die Bestimmung des Re methodenbedingt mit einer Verzögerung von rund 10 Tagen erfolgt. In kleinen Kantonen und bei tiefen Fallzahlen ist Re weniger aussagekräftig. Zur Entscheidung wird der Konfidenzbereich verwendet, d. h. dass bei Re 0.97 [0.85–1.09] dies als Wert >1 angesehen wird.</li>
        <li><strong>7-Tage-Inzidenz/100000 Einwohner*innen</strong> Die 7-Tageinzidenz der neu nachgewiesenen Infektionen wird verwendet, weil dieser Werte weniger auf Ausreisser reagiert, als der Tageswert. Ausgehend von der Initiative für eine pan-Europäische Strategie, in der als Grenze 10 Fälle pro Tag/Million Einwohner*innen genannt wird, ergibt sich eine 7-Tages-Inzidenz/100000 Einwohner*innen von 7.[Priesemann et al 2020]</li>
         <li><strong>Aufklärungsrate des Contact Tracing</strong> Das Contact Tracing (und die nachfolgende Quarantäne/Isolation) ist die letzte Abwehrmöglichkeit, wenn das Virus es trotz der anderen Massnahmen schafft, Menschen zu infizieren. Wegen der Überdispersion muss das Tracing vor- und rückwärts erfolgen [Low 2020]. Nur so kann eine hohe Aufklärungsrate und damit Unterbrechung der Infektionsketten sichergestellt werden.</li>
        <li><strong>Auslastung zertifizierte IPS-Betten</strong></li>
      </ul>
Die Positivitätsrate (Anzahl positiver Tests/alle durchgeführten Tests) ist nicht als Kriterium aufgenommen, da deren Interpretation grundsätzlich problematisch und mit der Einführung der Antigenschnelltests noch schwieriger geworden ist.
    </div>
  </div>
  <div class="ntable" style="display:flex;width:100%;min-width:400px;">
    <div class="tbl5 st0">
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
    <div class="tbl5 s0">
      Re
    </div>
    <div class="tbl5 s1">
     < 0.7
    </div>
     <div class="tbl5 s2">
      0.7–0.89
    </div>
     <div class="tbl5 s3">
      0.9–1.09
    </div>
     <div class="tbl5 s4">
      > 1.1
    </div>
  </div>
  <div class="ntbl" style="display:flex;width:100%;min-width:400px;">
    <div class="tbl5 s0">
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
    <div class="tbl5 s0">
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
    <div class="tbl5 s0">
      Auslastung IPS zert.
    </div>
    <div class="tbl5 s1">
      < 60 %
    </div>
     <div class="tbl5 s2">
      60–70 %
    </div>
     <div class="tbl5 s3">
      70–80 %
    </div>
     <div class="tbl5 s4">
     > 80 %
    </div>
  </div>
<div id="foot" style="font-size:0.9em;margin-top:1em;font-style:italic;">
  <h3>Literatur</h3>
  <div id="ref1">Low N. Contact tracing for COVID-19</div>
<div id="ref2">Priesemann V et al. <em>Calling for pan-European commitment for rapid and sustained reduction in SARS-CoV-2 infections</em>. The Lancet, 2020, DOI:https://doi.org/10.1016/S0140-6736(20)32625-8</div>
    </div>
