# API

#### Anbindung

Um die API Schnittstellen von Okourse nutzen zu können, wird ein API-Key benötigt. Mehrere API-Keys können pro Person generiert werden. Wichtig ist, dass jeder API-Key an die Person gebunden ist, welche diesen erstellt hat und pro Organisation funktioniert. Der API-Key besitzt somit genauso viele Rechte in der Organisation, wie der Nutzer selbst auch. 
Generiert werden kann der API Key in den Einstellungen der Organisation für den du diesen erstellen willst.
Unter dem Entwicklerbereich und dem Menüpunkt API-Key ist diese Funktion zu finden. Nach der Generierung des API-Keys speichere diesen sicher ab.

#### Authentifizierung

Um einen Request an das Backend von Okourse durchzuführen, muss in dem Header des Requests das Secret des API-Keys mitgesendet werden. Der Header heißt "x-auth-token".
Damit wird der Request gegenüber Okourse authentifiziert.