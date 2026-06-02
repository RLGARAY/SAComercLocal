# Materials i Recursos

## Llistat de materials

### Equipaments

- Ordinadors de l'aula amb connexió a internet (un per alumne/a)
- Projector o pantalla per a les explicacions del docent

### Programari

- **Visual Studio Code** com a editor de codi principal
- **Node.js i npm**, necessaris per a executar l'entorn de desenvolupament de React (Vite)
- **Navegadors web moderns** (Chrome i/o Firefox) per a proves i depuració
- **Git** instal·lat localment per al control de versions
- **Compte en GitHub** (cada alumne/a haurà de crear la seua si no la té)
- **Trello** per a la gestió del projecte amb metodologia Scrum i tauler Kanban: [trello.com](https://trello.com)
- **React Router** per a la navegació entre vistes de l'aplicació: [reactrouter.com](https://reactrouter.com/)
- **Leaflet** per a la integració de mapes interactius (Sprint 5): [leafletjs.com](https://leafletjs.com/)

### Altres recursos

- Documentació oficial de MDN Web Docs: [developer.mozilla.org](https://developer.mozilla.org)
- Documentació oficial de React.js: [es.react.dev](https://es.react.dev/)
- Documentació oficial de React Router: [reactrouter.com](https://reactrouter.com/)
- Documentació de Leaflet: [leafletjs.com/reference.html](https://leafletjs.com/reference.html)
- Fitxer `comerçLocal.json` proporcionat pel docent com a conjunt de dades inicial, amb l'estructura completa: nom, telefon, ubicacio, horari, descripcio, email, url, categoria, subcategoria i imatge (array de URLs externes o paths locals)
- Tutorial interactiu de Git: [learngitbranching.js.org](https://learngitbranching.js.org)
- Guia de Trello i flux de treball Scrum disponible a `Alumnat/Materials/Guies/Indicacions_tauler.md`

> Les dades dels comerços es gestionaran mitjançant un fitxer JSON estàtic (`comerçLocal.json`) servit localment. Aquesta decisió és coherent amb l'àmbit del mòdul 0612 (entorn client) i permet treballar la comunicació asíncrona amb Fetch API sense dependre d'un backend extern, que correspon al mòdul 0613.

---

## Guies d'ús

- **VS Code:** guia d'inici ràpid i documentació oficial: [code.visualstudio.com/docs](https://code.visualstudio.com/docs)

- **React i Vite:** guia d'inici ràpid per a crear el projecte amb Vite (`npm create vite@latest`), l'estructura de carpetes recomanada i com alçar el servidor de desenvolupament. Referències: [react.dev/learn](https://react.dev/learn) i [vitejs.dev](https://vitejs.dev)

- **Git i GitHub:** donat el nivell mixt del grup, es dedicarà una sessió introductòria a l'inici del projecte. Per als qui necessiten reforç, es recomana el tutorial interactiu de [learngitbranching.js.org](https://learngitbranching.js.org)

- **Trello:** guia d'ús del tauler Kanban i flux de treball Scrum: [trello.com/guide](https://trello.com/guide)

- **Leaflet:** tutorial d'integració de mapes interactius amb OpenStreetMap: [youtube.com/watch?v=ogYl2BDTEKs](https://www.youtube.com/watch?v=ogYl2BDTEKs)

- **DevTools del navegador:** tutorial sobre l'ús de la consola i l'inspector d'elements per a depuració de JS i CSS: [youtube.com/watch?v=Yc9Ng774ulw](https://www.youtube.com/watch?v=Yc9Ng774ulw)

---

## Repositoris

- Es crearà un **repositori principal** del projecte.
- Cada grup treballarà en un **fork** del repositori principal, realitzant commits regulars que evidencien el progrés al llarg dels cinc sprints.
- S'establirà una convenció de nomenat de branques per sprint: `sprint1`, `sprint2`, `sprint3`, `sprint4`, `sprint5`.
- El repositori inclourà des de l'inici una estructura base amb les carpetes `/assets/img/` i el fitxer `comerçLocal.json` d'exemple, perquè l'alumnat puga centrar-se en el desenvolupament sense perdre temps en la configuració inicial.
- Es recomana seguir la convenció de **conventional commits** per als missatges de commit (p. ex., `feat:`, `fix:`, `docs:`, `style:`) per facilitar el seguiment del progrés.