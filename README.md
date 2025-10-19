# Testy-ZO - Privacy Policy Page

Jednoduchá stránka pro ochranu osobních údajů hostovaná na GitHub Pages.

## Obsah

- `index.html` - Hlavní stránka s politikou ochrany osobních údajů

## Nastavení GitHub Pages

1. Přejděte do nastavení vašeho GitHub repository
2. V sekci "Pages" vyberte zdroj "Deploy from a branch"
3. Vyberte branch "main" a složku "/ (root)"
4. Klikněte na "Save"
5. Vaše stránka bude dostupná na: `https://crocodiluscz.github.io/Testy-ZO/`

## Místní spuštění

Pro zobrazení stránky lokálně můžete použít:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (pokud máte nainstalovaný)
npx serve .
```

Poté otevřete `http://localhost:8000` v prohlížeči.

## Úpravy

Pro úpravy stránky:
1. Editujte soubor `index.html`
2. Commitněte změny: `git add . && git commit -m "Update privacy policy"`
3. Nahrajte na GitHub: `git push origin main`
4. GitHub Pages automaticky aktualizuje stránku
