📦 AI Asystent – backend gotowy do Render.com

1. Wgraj ten folder do nowego repozytorium GitHub (plik package.json musi być na samej górze)
2. W Render.com kliknij:
   - New > Web Service
   - Wybierz to repozytorium
   - Ustaw:
     • Build Command: npm install
     • Start Command: npm start
     • Environment > Add Variable: OPENAI_API_KEY = twój_klucz_OpenAI

Port: 3000 (Render go wykryje sam)
Po wdrożeniu podmień link backendu w swoim frontendzie.

Powodzenia!
