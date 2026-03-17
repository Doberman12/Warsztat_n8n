# Warsztat_n8n

## **DISCORD** - https://discord.gg/wBrp6kHn

## Instrukcja Docker


### 1. Pobieramy pliki: `docker-compose.yaml` i `workflow.json` lub klonujemy repozytorium

### 2. Odpalamy Docker Desktop

### 3. Odpalamy wiersz poleceń

### 4. W wierszu poleceń przechodzimy do folderu z plikiem `docker-compose.yaml` (komenda `cd`)

### 5. Wpisujemy komende `docker compose up -d`

### 6. W Docker Desktop w zakladce Containers powinien pojawić się utworzony kontener

### 7. Klikamy RUN (lub symbol trójkąta) 

### 8. Pojawia się napis 

`Editor is now accessible via:
http://localhost:XXXX'

---

## Instrukcja N8N


### 1. Wchodzimy w link z Dockera

### 2. Wyszukujemy pierwszy `node` - *Trigger manualy*

### 3. Dodajemy kolejny `node` - *HTTP Request* 

### 4. Klinamy *HTTP Request* - przechodzimy do ustawień `node`

### 5. Ustawiamy `Method` na `GET`

### 6. Wpisujemy *URL* - `https://api.nbp.pl/api/exchangerates/tables/A/`

### 7. Zamykamy `node`

### 8. Kolejne `node` będą pokazywane przez prowadzącego

