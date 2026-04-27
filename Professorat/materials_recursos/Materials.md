# Materials i Recursos

## Llistat de materials

### Equipaments

- Ordinadors de l'aula amb connexió a internet (un per alumne/a)
- Projector o pantalla per a les explicacions del docent

### Programari

- **Visual Studio Code** com a editor de codi principal
- **Node.js i npm**, necessaris per a executar l'entorn de desenvolupament de React (Create React App o Vite)
- **Navegadors web moderns** (Chrome i/o Firefox) per a proves i depuració
- **Git** instal·lat localment per al control de versions
- **Compte en GitHub** (cada alumne/a haurà de crear la seua si no la té)

### Altres recursos

- Documentació oficial de MDN Web Docs: [developer.mozilla.org](https://developer.mozilla.org)
- Documentació oficial de React.js: [es.react.dev](https://es.react.dev/)
- Fitxer `comerços.json` proporcionat pel docent com a conjunt de dades inicial, amb la següent estructura per comerç: nom, descripció, horari, telèfon de contacte, categoria i ruta a imatge
- Carpeta `/assets/img/` dins del repositori amb les imatges de cada comerç en format `.jpg` o `.webp`, evitant així dependències externes i garantint el funcionament offline

> Les dades dels comerços es gestionaran mitjançant un fitxer JSON estàtic servit localment. Aquesta decisió és coherent amb l'àmbit del mòdul 0612 (entorn client) i permet treballar la comunicació asíncrona amb Fetch API sense dependre d'un backend extern, que correspon al mòdul 0613. Les imatges s'allotgen en el propi repositori per a mantindre tota l'aplicació autocontinguda.

---

## Guies d'ús

- **VS Code:** es proporcionarà a l'alumnat un document d'inici ràpid amb la instal·lació, les extensions recomanades (`Live Server`, `Prettier`, `ES7+ React/Redux/React-Native snippets`) i les dreceres de teclat més útils.

- **React i Vite:** es proporcionarà una guia d'inici ràpid per a crear el projecte amb Vite (`npm create vite@latest`), l'estructura de carpetes recomanada i com alçar el servidor de desenvolupament. Referència oficial: [react.dev/learn](https://react.dev/learn)

- **Git i GitHub:** donat el nivell mixt del grup, es dedicarà una sessió introductòria a l'inici del projecte. Per als qui necessiten reforç, es recomana el tutorial interactiu de [learngitbranching.js.org](https://learngitbranching.js.org)

- **DevTools del navegador:** s'explicarà en classe l'ús de la consola i l'inspector d'elements per a depuració de JS i CSS juntament amb l'extensió React Developer Tools.

---

## Repositoris

- Es crearà un **repositori principal** del projecte.
- Cada grup treballarà en un **fork** del repositori principal, realitzant commits regulars que evidencien el progrés al llarg dels tres sprints.
- S'establirà una convenció de nomenat de branques per sprint: `sprint1`, `sprint2`, `sprint3`.
- El repositori inclourà des de l'inici una estructura base amb les carpetes `/assets/img/` i el fitxer `comerços.json` d'exemple, perquè l'alumnat puga centrar-se en el desenvolupament sense perdre temps en la configuració inicial.
