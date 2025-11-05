# Ghid pentru Actualizarea Anunțurilor

## Cum să adaugi un anunț nou

1. Deschide fișierul `index.html` într-un editor de text
2. Caută secțiunea cu `id="announcements"` (în jurul liniei 337)
3. Găsește codul pentru un anunț existent care arată așa:

```html
<div class="col-lg-6 col-sm-12 sm-padding">
    <div class="blog-item box-shadow">
        <div class="blog-content" style="padding: 30px;">
            <span style="color: #ff6b35; font-weight: bold;">DATA AICI</span>
            <h3 style="margin-top: 15px; margin-bottom: 15px;">TITLUL ANUNȚULUI</h3>
            <p>Textul anunțului aici...</p>
        </div>
    </div>
</div>
```

4. Copiază acest cod și schimbă:
   - `DATA AICI` - pune data anunțului (ex: "5 Decembrie 2025")
   - `TITLUL ANUNȚULUI` - titlul anunțului tău
   - `Textul anunțului aici...` - conținutul anunțului

5. Salvează fișierul `index.html`

## Exemple de Anunțuri

### Anunț despre proiect nou:
```html
<div class="col-lg-6 col-sm-12 sm-padding">
    <div class="blog-item box-shadow">
        <div class="blog-content" style="padding: 30px;">
            <span style="color: #ff6b35; font-weight: bold;">10 Ianuarie 2026</span>
            <h3 style="margin-top: 15px; margin-bottom: 15px;">Proiect nou în București</h3>
            <p>Am început construcția unei case pasive moderne în zona de nord a Bucureștiului. Suprafață totală: 250mp.</p>
        </div>
    </div>
</div>
```

### Anunț despre certificare:
```html
<div class="col-lg-6 col-sm-12 sm-padding">
    <div class="blog-item box-shadow">
        <div class="blog-content" style="padding: 30px;">
            <span style="color: #ff6b35; font-weight: bold;">15 Februarie 2026</span>
            <h3 style="margin-top: 15px; margin-bottom: 15px;">Certificare PassivHaus</h3>
            <p>Suntem mândri să anunțăm că am obținut certificarea PassivHaus pentru ultimul nostru proiect din Cluj.</p>
        </div>
    </div>
</div>
```

## Locația Fișierelor Importante

- **Pagina principală**: `index.html`
- **Imagini**: `img/` folder
- **Stiluri CSS**: `css/` folder
- **JavaScript**: `js/` folder

## Modificări Rapide

### Schimbă informațiile de contact în footer:
Caută în `index.html` linia cu "Cluj-Napoca, România" și actualizează:
- Adresa
- Email: `contact@dmpassive.ro`
- Telefon: `+40 XXX XXX XXX`

### Actualizează textul din slider:
Caută în `index.html` secțiunile cu clasa `slider-content` și modifică textele în română.

## Observații
- Fă întotdeauna un backup înainte de a modifica fișiere
- Testează site-ul după modificări deschizând `index.html` într-un browser
- Pentru modificări majore, consideră să angajezi un web developer
