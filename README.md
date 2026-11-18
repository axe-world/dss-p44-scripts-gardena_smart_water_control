Integration von Gardena Smart water control mit Gardena Gateway in DigitalStrom smarthome System via Plan44.

Die Steuerung erfolgt lokal im Netz, ohne Gardena Cloud.

Das Script stellt in DigitalStrom device actions zur Verfügung (5min, 10min, 20min, 30min Bewässerung starten, Bewässerung stoppen und sendet events zum Digitalstrom-server).
Steuerung via Gardena App wird als event an DigitalStrom gesendet und kann z.B. via SceneResponder verwendet werden.

Im implementation script müssen die eigene ID des Gardena Gateways (steht auf der Rückseite des Gateways) und das Gardena Passwort (die ersten 8 Zeichen der ID) und die IP des Gatways angepasst werden.
In der Gardena Gateway Oberfläche muss unter Advanced Settings die local API aktiviert werden.
