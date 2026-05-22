## Introducció

Per organitzar el nostre projecte utilitzarem la metodologia **Scrum**, i el tauler **Kanban** serà la nostra eina principal per visualitzar el treball de l'equip en tot moment. L'objectiu és que qualsevol membre de l'equip puga saber, d'un cop d'ull, en quin punt es troba cada tasca.

L'eina que utilitzarem serà **[Trello](https://trello.com)**, que és gratuïta, visual i molt adequada per al treball en equip.

---

## Estructura del Tauler

El tauler ha de tenir **5 columnes fixes** per on aniran passant totes les tasques:

| Columna | Descripció |
|---|---|
| 🗒️ **Backlog / Pendents** | Totes les tasques del sprint que encara no s'han començat. |
| 🔍 **Especificar** | La tasca s'està analitzant: qui la fa, com es farà, quins recursos cal, quins criteris ha de complir. |
| 💻 **Programar** | La tasca està en desenvolupament actiu. |
| 🧪 **Testing** | La tasca s'ha implementat i s'està comprovant que funciona correctament. |
| ✅ **Terminada** | La tasca ha superat les proves i ha estat revisada per l'equip. |

> Una tasca no pot saltar columnes. Ha de passar per totes en ordre.

---

## Com funciona el flux de treball

```
Backlog / Pendents  →  Especificar  →  Programar  →  Testing  →  Terminada
```

1. Al **inici de cada Sprint**, totes les tasques entren a la columna **Backlog / Pendents**.
2. Quan un membre de l'equip agafa una tasca, la mou a **Especificar** i hi posa el seu nom.
3. Un cop clara la implementació, passa a **Programar**.
4. En acabar el desenvolupament, passa a **Testing** perquè un altre company la revise.
5. Si tot és correcte, es mou a **Terminada**. Si no, torna a **Programar** amb un comentari explicant el problema.

---

## Com crear una targeta al tauler

Cada tasca ha de tenir **com a mínim una targeta** a Trello. Si una tasca és gran o complexa, es pot i es recomana **dividir-la en diverses targetes** més petites per facilitar el seguiment i el repartiment del treball.

Cada targeta ha d'incloure:

- **Títol** clar i concís
- **Sprint** al qual pertany
- **Responsable/s** (qui la fa)
- **Descripció** breu de què cal fer i com es considerarà completada *(criteri d'acceptació)*
- **Etiqueta de color** per identificar el Sprint o el tipus de tasca

---

## Tasques guiades vs. treball autònom

La majoria de les tasques d'aquest projecte s'aniran treballant i resolent durant les **activitats i sessions de classe** al llarg del curs. El professorat acompanyarà el procés, proporcionarà recursos i guiarà el desenvolupament de les funcionalitats principals.

No obstant això, hi ha algunes tasques que **no formen part del temari treballat a classe** i que, per tant, seran de **treball autònom de l'equip**. Exemples d'aquest tipus de tasques són el **wireframe** (disseny de prototips visuals de la web) entre d'altres. En aquests casos, l'equip haurà d'organitzar-se de manera independent, buscar informació i prendre les seues pròpies decisions de disseny i estratègia.

---

## Tasques per Sprint

A continuació trobareu les tasques de cada Sprint ja preparades per afegir al tauler. Totes comencen a **Backlog / Pendents** el primer dia del Sprint.

---

### Sprint 1 — Planificació i disseny *(2 setmanes)*

- [ ] Crear el tauler Trello i configurar les columnes
- [ ] Assignar rols a l'equip
- [ ] Analitzar la competència (webs de comerços similars) 
- [ ] Esquema de l'estructura inicial de la web 
- [ ] Wireframe: Home, Comerç, Navegació, etc. 
- [ ] Instal·lació d'eines (Node, VS Code, extensions...)
- [ ] Crear repositori Git i estructura de branques
- [ ] Crear projecte base amb React
- [ ] Prova d'execució del projecte base

---

### Sprint 2 — Estructura i maquetació *(3 setmanes)*

- [ ] Definir estructura de carpetes del projecte
- [ ] Maquetar en HTML: Home, Comerç i altres pàgines
- [ ] Implementar sistema de rutes (React Router)
- [ ] Vincular les vistes entre si
- [ ] Buscar i avaluar components React reutilitzables

---

### Sprint 3 — Lògica JavaScript *(7 setmanes)*

- [ ] Definir l'estructura de dades dels comerços
- [ ] Crear catàleg de mostra (dades estàtiques inicials)
- [ ] Definir variables d'estat amb React (useState, useEffect...)
- [ ] Convertir components HTML estàtics a components React
- [ ] Implementar la lògica: funcions, subcamps, utilitats
- [ ] Llistat de comerços a la pàgina Home
- [ ] Renderitzat de la fitxa individual de cada comerç
- [ ] Implementar el cercador de comerços
- [ ] Implementar filtres per categoria
- [ ] Classificació i ordenació del catàleg
- [ ] Aplicar patrons de disseny al codi
- [ ] Depuració i cerca d'errors

---

### Sprint 4 — Interactivitat i DOM *(6 setmanes)*

- [ ] Classificar les interaccions de la web
- [ ] Capturar esdeveniments del DOM
- [ ] Associar accions als esdeveniments
- [ ] Interactuar amb objectes predefinits del navegador
- [ ] Crear formularis web (contacte, registre, etc.)
- [ ] Validació de camps dels formularis
- [ ] Implementar expressions regulars per a la validació
- [ ] Afegir feedback visual de validació
- [ ] Missatge d'èxit en enviar formulari
- [ ] Menú de navegació responsive
- [ ] Persistència de dades (localStorage)

---

### Sprint 5 — Comunicació asíncrona *(4 setmanes)*

- [ ] Preparar el fitxer JSON amb les dades dels comerços
- [ ] Implementar petició asíncrona completa (fetch / axios)
- [ ] Implementar peticions específiques (per id, per categoria...)
- [ ] Renderitzat dinàmic de les dades rebudes
- [ ] Gestionar l'estat de càrrega (loading spinner, skeleton...)
- [ ] Gestió d'errors de xarxa
- [ ] Integrar i sincronitzar llibreries externes (per exemple, mapa)
- [ ] Depuració del codi complet
- [ ] Revisió de comentaris i qualitat del codi
- [ ] Preparar la presentació i documentació final

---

## Normes del tauler

1. **Actualitzar diari.** El tauler ha de reflectir la realitat en tot moment, no al final del sprint.
2. **Límit de tasques en curs (WIP).** No es poden tenir més de **2 tasques per persona** a la columna *Programar* simultàniament.
3. **Ningú tanca la seua pròpia tasca.** La columna *Testing* ha de ser revisada per un company diferent al que ha programat.
4. **Bloqueig visible.** Si una targeta no pot avançar per algun motiu extern, s'etiqueta com a 🚧 **Bloquejada** i s'indica el motiu.
5. **Retrospectiva.** Al final de cada Sprint, reviseu el tauler junts: quantes tasques han quedat sense acabar? Per què? Apreneu-ne per al següent Sprint.

---
