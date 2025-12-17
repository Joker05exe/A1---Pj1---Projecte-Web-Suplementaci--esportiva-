# Projecte Web Fitness - Suplementació Esportiva

Aquest document detalla com s'han assolit tots els requeriments del projecte.

## 1. Contextualització
- **Temàtica**: Botiga de Suplementació Esportiva.
- **Justificació**: Web orientada a atletes que busquen millorar el seu rendiment amb productes de qualitat.
- **Idioma**: Català.

## 2. Continguts Mínims

| Requeriment | Fitxer | Implementació |
|-------------|--------|---------------|
| **Menú principal** | Tots (`header`) | Menú de navegació amb enllaços a Inici, Productes, Sobre Nosaltres, Contacte. |
| **2 Imatges** | `index.html`, `about.html` | Imatge de fons al Hero (`index.html`) i imatge de l'equip (`about.html`). |
| **1 Vídeo** | `index.html` | Vídeo incrustat de YouTube sobre com triar suplements. |
| **Taula (colspan/rowspan)** | `services.html` | Taula nutricional comparativa utilitzant `rowspan` per al títol i `colspan` per a les categories. |
| **Llistes (subllistes)** | `services.html`, `about.html` | Llistes niades de categories de productes i valors de l'empresa. |
| **Enllaços externs** | `contact.html` | Enllaços a Examine.com i l'OMS. |
| **Formulari** | `contact.html` | Formulari de contacte amb camps de nom, email, missatge i checkbox GDPR. |
| **Estructura HTML5** | Tots | Ús correcte de `<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<article>`. |

## 3. Prototipat
- Els wireframes mentals s'han traduït directament a l'estructura HTML final, seguint un disseny net i modern.

## 4. Implementació i Codi
- **Validació**: Codi HTML5 i CSS3 estàndard.
- **Comentaris**: S'han afegit comentaris en català al codi font explicant les parts clau.

## 5. Metadades i SEO
- **Metadades**: Incloses al `<head>` de `index.html` (description, keywords, author).
- **Semàntica**: Ús d'etiquetes semàntiques HTML5.
- **Schema.org**: Implementat JSON-LD de tipus `Store` a `index.html`.

## 6. LOPD i RGPD
- **Política de Privadesa**: Pàgina `privacy.html` creada.
- **Consentiment**: Checkbox obligatori al formulari de contacte (`contact.html`).
- **Galetes**: Bàner informatiu de galetes al peu de pàgina (`index.html`).

## 7. Estils i Responsive
- **Full d'estils**: `css/styles.css` vinculat a totes les pàgines.
- **Selectors**: Ús de selectors d'etiqueta, classe (`.btn`), ID (`#hero`) i universal (`*`).
- **Responsive**: Disseny adaptatiu amb Flexbox, Grid i `@media queries` per a mòbils.

## 8. Allotjament
- El projecte està preparat per pujar-se a qualsevol hosting estàtic (GitHub Pages, Netlify, etc.) pujant la carpeta `web fitness`.
