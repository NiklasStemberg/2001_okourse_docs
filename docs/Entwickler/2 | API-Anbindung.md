# API

#### Anbindung

Um mit der API Schnittstelle von OKourse kommunizieren zu können benötigst du einen API-Key und das dazugehörige Secret. Die Informationen kannst du dir im API-Menü in den Organisationseinstellungen generieren. Du kannst dir beliebig viele API-Keys erstellen. Achte allerdings stets darauf, dass niemand anderes Zugriff zu deinem Secret bekommt, da derjenige sonst Informationen und Nutzer in deiner Organisation bearbeiten kann.

#### Authentifizierung

Sobald du dir einen API-Key erstellt hast, musst du diesen in den header deines request einfügen. Das genaue Feld heißt 'Authentication' und der Wert ist "Bearer [YOUR_API_KEY]". Damit authentifizierst du deinen Request gegenüber OKourse.