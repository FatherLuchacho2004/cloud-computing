# Storingsmelder

1. Clone de repository.

Kies een map waar je de repository wil zetten en open hierin een command prompt.

``` bash
git clone https://github.com/FatherLuchacho2004/cloud-computing.git
cd cloud-computing
```

2. Maak .env aan.

``` bash
cp .env.example .env
```
Ga in .env en verander \<wachtwoord> naar jouw wachtwoord voor de database.

3. Start de app.

``` bash
docker compose up -d --build
```

4. Bekijk de app.

Ga in je browser en typ "localhost:8000" in de zoekbalk.

5. Opruimen.

``` bash
docker compose down
```
