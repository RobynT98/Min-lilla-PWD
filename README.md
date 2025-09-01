# Min lilla PWA (GitHub Pages-demo)

En superenkel PWA som visar hur man gör en webapp som kan installeras på mobilen och funkar offline.  
Den här versionen är gjord för att köras direkt på **GitHub Pages**.

## 🚀 Kom igång

1. Skapa ett nytt repo på GitHub (t.ex. `Min-lilla-PWD`).
2. Lägg in filerna:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icons/` (med `icon-192.png` och `icon-512.png`)

3. Gå till **Settings → Pages** i ditt repo.
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
   - Klicka på **Save**

4. Efter några minuter får du en länk som ser ut ungefär så här: https://robynT98.github.io/Min-lilla-PWD/

5. Öppna länken i Chrome/Edge/Android. Du får upp en installationsknapp på sidan.  
Alternativt: använd webbläsarens meny (**⋮**) → *Add to Home screen*.

## 🛠 Testa lokalt (valfritt)

Kör en enkel server (krävs för att service worker ska fungera):

```bash
# Python 3
python -m http.server 8080
