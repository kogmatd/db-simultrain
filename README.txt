[Aufnahme]
 Sensoren: 1 Sender und 2 Empfänger
 Proben:   5 Zahnräder vom Typ 2057 Kettenrad (4 gute, 1 mit Fehler)

[Audiodateien]
 TDMS-Größe: 1260196 Byte
 Wav:
   Samplerate: 1041,67 kHz
   Encoding:   int16
   Samples:    104674
   Länge:      100,4 ms
   Kanäle:     1 Sender, 2 Empfänger

[Dateinamen]
 S00_AAAAA_NNNN/
     S00_AAAAA_NNNN_TTTTTTTTTT/
         S00_AAAAA_NNNN_TTTTTTTTTT_IIIII.tdms
         S00_AAAAA_NNNN_TTTTTTTTTT_IIIII.tdms_index
         Wav/
             S00_AAAAA_NNNN_TTTTTTTTTT_IIIII_14_(Ch1,Ch2,Wav3).wav

 Z0[1-5]_Pos0[0-9]{_Repo[1-5}_AAAAA_NNNN/
     Z0[1-5]_Pos0[0-9]{_Repo[1-5}_AAAAA_NNNN_TTTTTTTTTT/
         Z0[1-5]_Pos0[0-9]{_Repo[1-5}_AAAAA_NNNN_TTTTTTTTTT_IIIII.tdms
         Z0[1-5]_Pos0[0-9]{_Repo[1-5}_AAAAA_NNNN_TTTTTTTTTT_IIIII.tdms_index
         Wav/
             Z0[1-5]_Pos0[0-9]{_Repo[1-5}_AAAAA_NNNN_TTTTTTTTTT_IIIII_14_(Ch1,Ch2,Wav3).wav

 S00:     Scheibe als Vergleichsmessung
 Z0[1-3]: Zahnrad ohne Fehler
 Z04:     Zahnrad bei NNNN=0000 ohne Fehler, bei NNNN=0001/0002 mit Fehler
 Z05:     Zahnrad mit Fehler

 Pos0[0-9]: Auflegeposition (beginnend gegenüber Verdickung, gegen Uhrzeigersinn im Abstand von 4 Zähnen)

 AAAAA: Anregungsfunktion:
    Crp1k_200k: Chrip von 1 kHz bis 200 kHz
    RC2_75k:    Rc2 mit 75 kHz
    Sinc150k:   Sinc mit 150 kHz
 
 Repo[1-5]: Wiederholung der Messung

 NNNN: Messungs-ID

 TTTTTTTTTT: Zeitstempel

 IIIII: Aufnahme-ID

 Ch1,Ch2: Empfängerkanäle
 Wav3:    Sendesignal

 tdms-Dateien: Originaldateien, Konvertierung nach wav mit: common/doc/Tools/TDMStoDat.exe


[Beschreibung und Dokumentation]
 - common/doc/Doku/Log_Zahnrad2013.docx
 - Aufnahmen.xlsx
 - common/doc

