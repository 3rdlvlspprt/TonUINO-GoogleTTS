# TonUINO-GoogleTTS

Ein Powershell-Skript zur automatischen Generierung von Text-to-Speech-Mediendateien.


# Ersteller:
Ein Herzliches Dank geht an https://github.com/ceear der den Skript ursprünglich geschrieben hat.


# Hinweis:
Dieser Powershell-Skript ist ausschließlich für Windows Benutzer geeignet.
Empfohlen wird Windows 10.


# Vorwort:
Für Google TTS wird ein entsprechender API-Key benötigt.
Dieser Skript kommt mit einem API-Key und es wird kein eigener benötigt.

Wer dennoch seinen eigenen API-Key verwenden möchte, der kann dies unter Zeile 2 ersetzen.
Hier eine Anleitung wie ein API-Key erstellt wird:
https://discourse.voss.earth/t/professionelle-stimme-gesucht/19/35

Die Sprechgeschwindigkeit kann unter Zeile 3 eingestellt werden.
Der Bereich liegt zwischen 0.25 bis 4.00. Der Standard liegt bei 1.00.

Die Stimmhöhe kann unter Zeile 4 eingestellt werden.
Der Bereich liegt zwischen -20.00 bis 20.00. Der Standard liegt bei 0.

Das Skript erwartet die Datei "soundfiles.txt" als Eingabedatei für die zu erzeugenden Texte. 
Diese liegt bei und kann nach belieben umgeändert oder ersetzt werden.

Der Inhalt der "soundfiles.txt" als Beispiel: 
0300_new_tag.mp3|Oh, eine neue Karte!

0301_select_folder.mp3|Verwende die Lautstärketasten um einen Ordner für die Karte auszuwählen.
usw.

Hier könnt ihr die verschiedenen Stimmen Probehören und eure Powershell-Datei am Ende auswählen:
https://cloud.google.com/text-to-speech/


# Anleitung:
1. Entsprechende Änderungen in der soundfiles.txt machen. (Optional)
2. Start-*.ps1 starten. (*Je nachdem welche Stimme ihr auswählt.)
3. Mit "Ja" bestätigen.
4. Warten bis alles fertig ist.
5. Mit Enter am Ende bestätigen.
6. Die erstellten Dateien findet ihr unter "C:\TonUINO-TTS\GoogleTTS".
