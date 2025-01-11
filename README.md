# GooglePlaces

Zainstaluj:
npm install axios xlsx
axios: Do obsługi zapytań HTTP.
xlsx: Do tworzenia i zapisywania plików Excel.

Aby chronić klucz API, użyj pliku .env:

Zainstaluj bibliotekę dotenv:
bash: npm install dotenv
Stwórz plik .env:
bash:touch .env
W pliku .env dodaj swój klucz API, który dostaniesz z google cloud API:
API_KEY=TWOJ_KLUCZ_API

Utwórz plik skryptu:
bash:touch index.js
Struktura plików powinna wygladać tak:
google-places-app/
├── node_modules/
├── .env
├── .gitignore
├── index.js
├── package.json
├── package-lock.json
