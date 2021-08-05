# Was ist PFP?
PFP ist der codename für eine dezentrale Krypto-Tauschbörse mit PayPal-Integration.
# Was kann PFP?
PFP soll einen einfachen Einstieg in die Krypto-Welt ermöglichen.
# Welche Währungen werden unterstützt?
PFP basiert auf den Smart Contracts der Signum.network Blockchain und unterstützt neben dessen Coin "Signa" alle verfügbaren Fiat-Währungen die PayPal auch unterstützt. Diese sind unter folgendem Link zu finden: https://developer.paypal.com/docs/api/reference/currency-codes/
# Welche Vorraussetzungen braucht man?
Da PFP auf dem .NET-Framework in der Version 4.6.1 basiert, ist ein Betriebssystem welches dieses ünterstützt ebenfalls Vorraussetzung.
# Wie installiert man PFP?
In der Entwicklungsphase wird eine PFP.EXE-Datei unter https://github.com/EvolverDE/Signum/blob/master/PFP/PFP/bin/Debug/PFP.exe zur Verfügung gestellt, die an einen beliebigen Ort auf einer Festplatte verschoben und dort genutzt werden kann.
# Welche Einstellungen müssen vorgenommen werden?
Die Einstellungen werden mit Standard-Werten neben der PFP.EXE-Datei automatisch in einer Settings.ini-Datei erstellt. Neben dem Programm können auch dort direkt Änderungen vorgenommen werden.
# Was bedeuten die anderen Dateien, die neben der PFP.EXE erstellt werden?
Neben der Settings.ini werden noch weitere Dateien wie z.b. "cache.dat" und "cache2.dat" sowie mögliche .LOG-Dateien erstellt. Die cache.dat enthält informationen aller auf der Signum.network blockchain befindlichen Smart Contracts. Die chache2.dat enthält Zahlungsinformationen der eigenen Aufträge.

# Hier ist eine kleine Funktionsübersicht
- sichere Verbindung zu öffentlichen signa-nodes aufbauen dank integrierter EC-KCDSA und Curve19255 Lösungen
- eine TCP API für externe Applikationen zur verfügung stellen
- mit dem integriertem auf TCP basiertem DEXNET das Signa-Netzwerk um offchain-Lösungen erweitern um das Handels-Erlebnis zu verbessern
