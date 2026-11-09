# Currículum i apunts — Jaume Joan Pericàs Oliver

Lloc web estàtic que reuneix el **currículum** de Jaume Joan Pericàs Oliver, professor de formació professional de la família d'Informàtica i Comunicacions al CIFP Pau Casesnoves, i un **índex d'apunts** dels mòduls que imparteix.

Tot el lloc està escrit en **HTML5 semàntic pur**: sense CSS, sense JavaScript i sense cap dependència ni procés de compilació. Això és intencionat: els apunts formen part del mòdul de *Llenguatges de marques i sistemes de gestió d'informació* (LMSGI), i el mateix codi font serveix d'exemple d'estructura i bones pràctiques d'HTML.

---

## Taula de continguts

- [Característiques](#característiques)
- [Estructura del projecte](#estructura-del-projecte)
- [Continguts](#continguts)
- [Com visualitzar-lo](#com-visualitzar-lo)
- [Publicació amb GitHub Pages](#publicació-amb-github-pages)
- [Convencions de les pàgines](#convencions-de-les-pàgines)
- [Com afegir un apunt nou](#com-afegir-un-apunt-nou)
- [Com afegir un mòdul nou](#com-afegir-un-mòdul-nou)
- [Tasques pendents](#tasques-pendents)
- [Autoria i contacte](#autoria-i-contacte)

---

## Característiques

- **Només HTML5**: cap full d'estil ni script; el navegador aplica els estils per defecte.
- **Marcat semàntic**: `header`, `nav`, `main`, `article`, `section`, `figure`, `figcaption`, `footer`, taules amb `caption`, `thead` i `scope`.
- **Accessibilitat**: atribut `lang="ca"`, navegacions etiquetades amb `aria-label`, ruta de navegació (*breadcrumb*) amb `aria-current="page"` i textos alternatius a les imatges.
- **Metadades completes** a cada pàgina: `description`, `keywords`, `author`, `robots` i etiquetes Open Graph (`og:title`, `og:description`, `og:type`, `og:locale`).
- **Enllaços relatius**: el lloc funciona igual obert des del disc local que publicat en un servidor.
- **Favicon SVG** propi ([favicon.svg](favicon.svg)) amb el símbol `</>`.
- **Idioma**: tots els continguts estan en català.

## Estructura del projecte

```
currculum/
├── index.html                      # Currículum + índex de coneixements (pàgina d'inici)
├── favicon.svg                     # Icona del lloc
├── README.md
└── moduls/
    ├── llenguatge_marques/         # Llenguatges de marques i SGI (mòdul amb apunts)
    │   ├── index.html              # Índex del mòdul
    │   ├── ANALISI-CODI/           # Bloc 1: anàlisi i interpretació de codi (10 apunts)
    │   ├── HTML-BASIC/             # Bloc 2: HTML bàsic (12 apunts)
    │   └── HTML-AVANCAT/           # Bloc 3: HTML avançat (10 apunts)
    ├── programacio/index.html              # En preparació
    ├── bases_dades/index.html              # En preparació
    ├── sistemes_informatics/index.html     # En preparació
    └── entorns_desenvolupament/index.html  # En preparació
```

## Continguts

### Pàgina d'inici — [index.html](index.html)

Currículum amb les seccions: informació personal, resum professional, experiència laboral, educació i formació, habilitats tècniques, habilitats, idiomes i, al final, l'**índex de coneixements** que enllaça amb cada mòdul.

### Llenguatges de marques — [moduls/llenguatge_marques/](moduls/llenguatge_marques/index.html)

Únic mòdul amb apunts publicats de moment. S'organitza en tres blocs:

#### 1. Anàlisi i interpretació de fragments de codi (`ANALISI-CODI/`)

| Fitxer | Tema |
|---|---|
| [dades.html](moduls/llenguatge_marques/ANALISI-CODI/dades.html) | Les dades i les seves característiques |
| [emmagatzematge.html](moduls/llenguatge_marques/ANALISI-CODI/emmagatzematge.html) | L'emmagatzematge de dades |
| [formats_fitxer.html](moduls/llenguatge_marques/ANALISI-CODI/formats_fitxer.html) | Formats de fitxer |
| [llenguatges_marques.html](moduls/llenguatge_marques/ANALISI-CODI/llenguatges_marques.html) | Introducció als llenguatges de marques |
| [classificacio_marques.html](moduls/llenguatge_marques/ANALISI-CODI/classificacio_marques.html) | Classificació dels llenguatges de marques |
| [tasca_investigacio.html](moduls/llenguatge_marques/ANALISI-CODI/tasca_investigacio.html) | Tasca d'investigació |
| [sintaxi_html.html](moduls/llenguatge_marques/ANALISI-CODI/sintaxi_html.html) | Sintaxi d'HTML |
| [sintaxi_xml.html](moduls/llenguatge_marques/ANALISI-CODI/sintaxi_xml.html) | Sintaxi d'XML |
| [sintaxi_csv.html](moduls/llenguatge_marques/ANALISI-CODI/sintaxi_csv.html) | Sintaxi de CSV |
| [sintaxi_json.html](moduls/llenguatge_marques/ANALISI-CODI/sintaxi_json.html) | Sintaxi de JSON |

#### 2. HTML bàsic (`HTML-BASIC/`)

| Fitxer | Tema |
|---|---|
| [introduccio.html](moduls/llenguatge_marques/HTML-BASIC/introduccio.html) | Introducció a HTML |
| [estructura.html](moduls/llenguatge_marques/HTML-BASIC/estructura.html) | Estructura bàsica d'un document HTML |
| [etiquetes_basiques.html](moduls/llenguatge_marques/HTML-BASIC/etiquetes_basiques.html) | Etiquetes bàsiques |
| [elements_anidament.html](moduls/llenguatge_marques/HTML-BASIC/elements_anidament.html) | Elements HTML i anidament |
| [atributs.html](moduls/llenguatge_marques/HTML-BASIC/atributs.html) | Atributs HTML |
| [text_formatat.html](moduls/llenguatge_marques/HTML-BASIC/text_formatat.html) | Text formatat |
| [comentaris.html](moduls/llenguatge_marques/HTML-BASIC/comentaris.html) | Comentaris en HTML |
| [imatges.html](moduls/llenguatge_marques/HTML-BASIC/imatges.html) | Inserció d'imatges |
| [enllacos.html](moduls/llenguatge_marques/HTML-BASIC/enllacos.html) | Enllaços |
| [llistes.html](moduls/llenguatge_marques/HTML-BASIC/llistes.html) | Llistes |
| [taules.html](moduls/llenguatge_marques/HTML-BASIC/taules.html) | Taules |
| [eines.html](moduls/llenguatge_marques/HTML-BASIC/eines.html) | Eines inicials (Notepad++, Sublime Text) |

#### 3. HTML avançat (`HTML-AVANCAT/`)

| Fitxer | Tema |
|---|---|
| [html5.html](moduls/llenguatge_marques/HTML-AVANCAT/html5.html) | HTML5 i etiquetes semàntiques |
| [formularis.html](moduls/llenguatge_marques/HTML-AVANCAT/formularis.html) | Formularis |
| [validacio_formularis.html](moduls/llenguatge_marques/HTML-AVANCAT/validacio_formularis.html) | Validació de formularis |
| [tipus_entrada.html](moduls/llenguatge_marques/HTML-AVANCAT/tipus_entrada.html) | Tipus d'entrada especials |
| [multimedia.html](moduls/llenguatge_marques/HTML-AVANCAT/multimedia.html) | Multimèdia (img, video, audio) |
| [contenidors.html](moduls/llenguatge_marques/HTML-AVANCAT/contenidors.html) | Contenidors: div, span i center |
| [hr.html](moduls/llenguatge_marques/HTML-AVANCAT/hr.html) | Separador temàtic: hr |
| [template.html](moduls/llenguatge_marques/HTML-AVANCAT/template.html) | Plantilles: template |
| [iframe.html](moduls/llenguatge_marques/HTML-AVANCAT/iframe.html) | Contingut incrustat: iframe |
| [metadades.html](moduls/llenguatge_marques/HTML-AVANCAT/metadades.html) | Metadades |

### Altres mòduls (en preparació)

| Mòdul | Descripció |
|---|---|
| [Programació](moduls/programacio/index.html) | Fonaments de programació |
| [Bases de dades](moduls/bases_dades/index.html) | Disseny i gestió de bases de dades |
| [Sistemes informàtics](moduls/sistemes_informatics/index.html) | Maquinari, sistemes operatius i xarxes |
| [Entorns de desenvolupament](moduls/entorns_desenvolupament/index.html) | Eines i entorns per desenvolupar programari |

Aquestes pàgines ja tenen la capçalera, la navegació i el peu definitius, però de moment només mostren un avís de contingut en preparació.

## Com visualitzar-lo

No cal instal·lar res.

**Opció 1 — Obrir directament el fitxer**

Obre [index.html](index.html) amb qualsevol navegador (doble clic o arrossegant-lo a la finestra).

**Opció 2 — Servidor local** (recomanat si es vol simular un entorn real)

```bash
# Amb Python 3
python -m http.server 8000

# o amb Node.js
npx serve .
```

I després obre <http://localhost:8000>.

**Opció 3 — Visual Studio Code**

Instal·la l'extensió *Live Server*, fes clic dret sobre `index.html` i tria **Open with Live Server**.

## Publicació amb GitHub Pages

El repositori és a <https://github.com/JaumePericasOliver/currculum>. Per publicar-lo:

1. Ves a **Settings → Pages** del repositori.
2. A **Source**, tria **Deploy from a branch**.
3. Selecciona la branca `master` i la carpeta `/ (root)` i desa.
4. Al cap d'uns minuts el lloc estarà disponible a `https://jaumepericasoliver.github.io/currculum/`.

Com que tots els enllaços són relatius, no cal modificar cap ruta.

## Convencions de les pàgines

Totes les pàgines segueixen la mateixa plantilla, de manera que el lloc és coherent i fàcil d'ampliar.

### Noms de fitxers i carpetes

- Fitxers en minúscules, sense accents ni espais, amb `_` com a separador (`text_formatat.html`).
- Carpetes de mòdul en minúscules (`llenguatge_marques`); carpetes de bloc en majúscules amb guionet (`HTML-BASIC`).
- Cada mòdul té el seu propi `index.html`.

### Estructura de cada pàgina

```html
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Títol de l'apunt | Apunts de Jaume Joan Pericàs Oliver</title>
  <meta name="description" content="...">
  <meta name="keywords" content="...">
  <meta name="author" content="Jaume Joan Pericàs Oliver">
  <meta name="robots" content="index, follow">
  <meta property="og:title" content="Títol de l'apunt">
  <meta property="og:description" content="...">
  <meta property="og:type" content="article">   <!-- profile | website | article -->
  <meta property="og:locale" content="ca_ES">
  <link rel="icon" href="../../../favicon.svg" type="image/svg+xml">
</head>
<body>
  <header>
    <p><a href="../../../index.html">Apunts de Jaume Joan Pericàs Oliver</a></p>
    <nav aria-label="Navegació principal">  <!-- menú amb tots els mòduls --> </nav>
    <nav aria-label="Ruta de navegació">    <!-- breadcrumb: Inici › Mòdul › Apunt --> </nav>
  </header>

  <main>
    <article>
      <header>
        <h1>Títol de l'apunt</h1>
        <p>Bloc · Descripció breu.</p>
      </header>
      <section>
        <h2>Apartat</h2>
        ...
      </section>
    </article>
  </main>

  <footer>
    <p>&copy; 2026 Jaume Joan Pericàs Oliver. Contacte: <a href="mailto:...">...</a></p>
  </footer>
</body>
</html>
```

Detalls a tenir en compte:

- **Títol**: sempre amb el format `Tema | Apunts de Jaume Joan Pericàs Oliver`.
- **`og:type`**: `profile` per al currículum, `website` per als índexs de mòdul i `article` per als apunts.
- **Breadcrumb**: l'últim element porta `aria-current="page"`.
- **Rutes relatives** segons la profunditat: `index.html` (arrel), `../../` (índex de mòdul) o `../../../` (apunt dins d'un bloc).
- **Exemples de codi**: dins d'un `<figure>` amb `<figcaption>Codi d'exemple</figcaption>` i `<pre><code>`, escapant `<` i `>` com a `&lt;` i `&gt;`. Quan és útil, a continuació s'afegeix un segon `<figure>` amb `<figcaption>Resultat al navegador</figcaption>` que mostra l'HTML renderitzat.
- **Termes en anglès**: marcats amb `<i lang="en">`.

## Com afegir un apunt nou

1. Copia un apunt existent del mateix bloc (per exemple `HTML-BASIC/llistes.html`) amb un nom nou.
2. Actualitza `<title>`, `description`, `keywords`, `og:title` i `og:description`.
3. Canvia l'últim element del *breadcrumb* (text, `href` i `aria-current`).
4. Escriu el contingut dins de `<article>`, amb un `<h1>` i seccions `<section>` amb `<h2>`.
5. Afegeix l'enllaç a l'índex del mòdul ([moduls/llenguatge_marques/index.html](moduls/llenguatge_marques/index.html)), dins del bloc corresponent, amb el format `<li><a href="BLOC/fitxer.html">Títol</a>: descripció breu.</li>`.

## Com afegir un mòdul nou

1. Crea la carpeta `moduls/nom_modul/` amb un `index.html` copiat d'un mòdul existent.
2. Afegeix l'enllaç al **menú de navegació principal** de *totes* les pàgines del lloc (cal fer-ho a mà, ja que no hi ha plantilles compartides). Una cerca i substitució a tot el projecte és la manera més ràpida.
3. Afegeix el mòdul a l'**Índex de coneixements** d'[index.html](index.html).

## Tasques pendents

- [ ] Personalitzar el resum professional, l'experiència i la formació del currículum (marcats amb `<!-- TODO -->` a [index.html](index.html)).
- [ ] Corregir l'any d'inici a l'experiència laboral (`20015` → any correcte).
- [ ] Substituir la fotografia de prova (`picsum.photos`) per una imatge real allotjada al repositori.
- [ ] Redactar els apunts de Programació, Bases de dades, Sistemes informàtics i Entorns de desenvolupament.
- [ ] Ampliar Llenguatges de marques amb CSS, XML (DTD, XML Schema), XPath/XSLT i sistemes de gestió d'informació.
- [ ] Opcional: afegir un full d'estil comú quan el temari arribi a CSS.

## Autoria i contacte

**Jaume Joan Pericàs Oliver** — CIFP Pau Casesnoves
Correu: [poj@paucasesnovescifp.cat](mailto:poj@paucasesnovescifp.cat)

© 2026 Jaume Joan Pericàs Oliver. Material docent per a ús educatiu.
