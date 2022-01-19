[Aufnahme]
 Sensoren: 2 Empfänger
 Proben:   5 Zahnräder vom Typ 2057 Kettenrad (4 gute, 1 mit Fehler)

[Audiodateien]
 Wav:
   Samplerate: 1041,67 kHz
   Encoding:   int16
   Samples:    104674
   Länge:      100,4 ms
   Kanäle:     2 Empfänger

[Dateinamen]
 Z0[1-5]_Pos0[0-9]_AAAAA_NNNN/
     Z0[1-5]_Pos0[0-9]_AAAAA_NNNN_TTTTTTTTTT/
         Wav/
             Z0[1-5]_Pos0[0-9]_AAAAA_NNNN_TTTTTTTTTT_IIIII_14_(Ch1,Ch2).wav

 Z0[1-3]: Zahnrad ohne Fehler
 Z04:     Zahnrad bei NNNN=0000 ohne Fehler, bei NNNN=0001/0002 mit Fehler
 Z05:     Zahnrad mit Fehler

 Pos0[0-9]: Auflegeposition (beginnend gegenüber Verdickung, gegen Uhrzeigersinn im Abstand von 4 Zähnen)

 AAAAA: Anregungsfunktion:
    Crp1k_200k: Chrip von 1 kHz bis 200 kHz
    RC2_75k:    RC2 mit 75 kHz [ RCn(t,f,n) = 0.5 * (-1)^n * (1-cos(2*pi*f*t/n)) * cos(2*pi*f*t) ]

 NNNN: Messungs-ID

 TTTTTTTTTT: Zeitstempel

 IIIII: Aufnahme-ID

 Ch1,Ch2: Empfängerkanäle
