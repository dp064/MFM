Variablenname,Variablenlabel (Frage),Wertetabelle,Variablentyp,Skalenniveau
V1Alter,Frage 1: Geben Sie ihr Alter an,offen,Numerisch,Ratio
V2Geschlecht,Frage 2: Mit welchem Geschlecht identifizieren Sie sich?,"1 = männlich 
2 = weiblich 
3 = divers",String,nominal
V3Wohnort,Frage 3: Wo wohnen Sie?,"1 = Dorf (3.000)
2 = Stadt (20.000)
3 = Großstadt (100.000)",String / Numerisch,ordinal
V4Wohnsituation,Frage 4: Wie sieht Ihre Wohnsituation aus?,"1 = allein 
2 = mit Familie 
3 = mit Partner
4 = WG",String,nominal
"V5SocialMedia
V5Print
V5Fernsehen
V5Radio
V5Podcast
V5Sonstiges","Frage 5: Welche Medien nutzen Sie als Informationsquelle?

Mehrfachantworten","1 = Ja
2 = Nein",String,nominal
"V6SocialMedia
V6Print
V6Fernsehen
V6Radio
V6Podcast
V6Sonstiges","Frage 6: Welche Medien nutzen Sie als Unterhaltungsquelle?

Mehrfachantworten","1 = Ja
2 = Nein",String,nominal
V7Podcastnutzung,Frage 7: Haben Sie schon einmal einen True-Crime-Podcast gehört?,"1 = Ja
2 = Nein",String,nominal
V8keinePodcastnutzung,"Frage 8: Aus welchen Gründen hören Sie keine True-Crime-Podcasts?

bei V7=2",offen,String,nominal
"V9spannend
V9informieren
V9praevention
V9Hosts
V9Sonstiges","Frage 9: Aus welchen Gründen hören Sie True-Crime-Podcasts?

Mehrfachantworten","1= ja 
2= nein",String,nominal
V10Regelmaessigkeit,Frage 10: Wie regelmäßig konsumieren Sie True-Crime-Podcasts?,"5 = täglich
4 = mehrmals die Woche
3= einmal die Woche
2 = einmal im Monat
1 = mindestens einmal im Jahr",Numerisch,ordinal
V11Format,Frage 11: Welche Formate bevorzugen Sie?,"1 = dokumentarisch (nüchtern z.B. Sprechen wir über Mord) 
2 = erzählend (emotional z.B. Mord am Mittwoch) 
3 = unterhaltend (humorvoll z.B. Mord auf Ex)",String,nominal
"V12AngstOpfer 
V12Mitgefuehl
V12Unwohlsein
V12Spannung
V12Erleichterung",Frage 12: Wie oft empfinden Sie beim Hören von True-Crime-Podcast folgende Gefühle?,"1 = nie 
2 = selten 
3 = manchmal 
4 = oft
5 = sehr oft",numerisch,intervall
"V13Kriminalitaetsrate 
V13Straftaten
V13Gewaltdelikte","Frage 13: Bitte geben Sie an, inwieweit die folgende Aussagen auf Sie zutreffen?","1 = überhaupt nicht zu 
2 = eher nicht zu 
3 = weder noch 
4 = eher zu 
5 = voll zu",numerisch,intervall
V14Sicherheit,Frage 14: Wie sicher fühlen Sie sich im Alltag?,"1 = sehr sicher 
2 = eher sicher 
3 = neutral 
4 = eher unsicher 
5 = sehr unsicher",numerisch,ordinal
V15Angst,"Frage 15: Haben Sie Angst, Opfer von Kriminalität zu werden?","5 = immer Angst
4 = häufig Angst
3 = manchmal Angst 
2 = selten Angst 
1 = nie Angst",String,ordinal
"V16Gewaltverbrechen
V16Belaestigung
V16SexualDelikte
V16Ueberfall
V16Terroranschlaege
V16Einbruch
V16EntfuehrungGeiselnahme","Frage 16: Vor welcher Art der Kriminalität fürchten Sie sich?

Mehrfachantworten","1 = gar nicht
2 = eher weniger
3 = manchmal
4 = stark 
5 = sehr stark",numerisch,intervall
V17Opfererfahrung,Frage 17: Wurde Sie schon einmal Opfer einer Kriminalität,"1 = ja 
2 = nein
3 = keine Angabe",String,nominal
V18OpfererfahrungKriminalitaet,"Frage 18: Wenn ja, von welcher?
bei bei V17=1","Gewaltverbrechen
Belaestigung
Sexual Delikte
Ueberfall
Terroranschlaege
Einbruch
Entfuehrung Geiselnahme",String,nominal
V19Veraenderung,"Frage 19: Wenn Sie ja angekreuzt haben, wie hat sich Ihr Empfinden von Angst vor Kriminalität verändert?
bei bei V17=1","1 = unsicherer
2 = keine Veränderung
3 = Ich weiß jetzt besser, wie ich mich schütze",String,nominal
