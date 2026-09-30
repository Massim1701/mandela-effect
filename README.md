# Mandela Effekt – Voting-Präsentation

## Setup

- **Audience:** `index.html`
- **Admin:** `admin.html`
- **Hosting:** GitHub Pages (Branch: `main`, Root: `/`)

## Admin-Tokens

| Admin | Token |
|-------|-------|
| Admin 1 | `mdlNews` |
| Admin 2 | `mdlMike` |
| Admin 3 | `mdlMassimo` |

## Bilder austauschen

Supabase Dashboard → Tabelle `image_pairs` → `image_left_url` / `image_right_url` anpassen.

## Ablauf

1. Admin öffnet `admin.html` → einloggen
2. Publikum öffnet `index.html` (anonym, Browser-Session)
3. Admin klickt **Voting starten** → Publikum sieht Bilder, klickt eines an
4. Admin klickt **Auswertung zeigen** → Ergebnis erscheint auf allen Geräten
5. Admin klickt **Nächstes Beispiel** → weiter mit Paar 2–20
6. Nach Paar 20 → **Gesamtauswertung**

## Supabase

- Project ID: `mgvjyyzurobcffulqyia`
- URL: `https://mgvjyyzurobcffulqyia.supabase.co`
