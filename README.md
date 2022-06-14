![logo_ironhack_blau 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Conceptes bàsics de Vue.js

## Introducció

En aquest laboratori, continuareu explorant els conceptes bàsics sobre com utilitzar Vue.js i establirà les bases per a projectes més grans i complicats.

Aquestes són les coses que haureu d'aconseguir durant aquest laboratori:

- Creeu una estructura bàsica de plantilla dins d'un projecte nou.
- Mostra el resultat d'una operació de JavaScript a l'HTML d'un component.
- Mostra un element només si una propietat concreta s'estableix en `true` .
- Mostra una llista d'elements que s'emmagatzemen dins d'un component.
- (Bonus) Canvia el color de fons d'un element en prémer un botó.

Anem a començar!

## Configuració

- Bifurca aquest repo
- Clona aquest repo
- Obriu el LAB i comenceu:

  ```bash
   $ cd lab-vue-basics-cat
   $ npm install
   $ npm start
  ```

## Submissió

- En finalitzar, executeu les ordres següents:

  ```bash
  $ git add .
  $ git commit -m "done"
  $ git push origin main # or master if you are working from a master
  ```

- Creeu una sol·licitud d'extracció perquè els vostres TA puguin comprovar el vostre treball.

<!-- ## Getting Started -->

## Instruccions

### Iteració 1 | Creeu una estructura bàsica de plantilla dins d'un projecte nou

Per a aquest laboratori, haureu de crear un nou projecte Vue en una carpeta nova. Podeu triar quines opcions voleu incloure, però recordeu quedar-vos amb Vue 2 de moment.

Un dels principals avantatges de Vue (o de qualsevol altre framework d'interfície) és la facilitat que és reutilitzar components a tota la vostra aplicació. Això és exactament el que practicarem ara mateix.

Heu de crear un component de `navbar` de navegació i un component de `footer` de pàgina, que incloureu a totes les pàgines interiors de l'aplicació. Consell: si els importeu al vostre component App.vue, totes les vostres pàgines interiors també les mostraran.

Ara mateix, no cal que us preocupeu per l'estil d'aquests components; només assegureu-vos que funcionin i que podeu avançar a la següent tasca.

### Iteració 2 | Mostra el resultat d'una operació Javascript a l'HTML d'un component

Ahir vau practicar mostrant una `string` dins de la plantilla d'un component Vue mitjançant la sintaxi del bigoti ( `{{}}` ). Avui hem vist que les cadenes no són les úniques coses que podeu inserir al vostre HTML amb aquesta tècnica.

Aquest repte té dues parts:

- Primer, només cal inserir una operació matemàtica dins del vostre HTML i veure què passa. Aquí n'hi ha prou amb una cosa tan simple com `2 + 2` .
- Aleshores, comença el veritable repte: has d'"imprimir" una `string` a la teva plantilla, amb un gir: aquesta cadena ha de ser retornada per una funció. Pista: [aquest article](https://lavalite.org/blog/created-and-mountedin-vuejs) pot donar una mica de llum sobre com podeu fer-ho.

### Iteració 3 | Mostra un element només si una propietat determinada s'estableix com a `true`

Un dels principals motius pels quals fem servir alguna cosa com Vue és perquè puguem simplificar les operacions habituals de JavaScript. Un dels principals avantatges d'aquest marc és que ens permet mostrar elements condicionalment d'una manera molt senzilla.

Practiquem això! El vostre repte aquí és crear dades booleanes dins d'un component Vue i enllaçar-les a un element HTML que només apareixerà a la vostra plantilla si la condició s'estableix en `true` .

Avui hem vist les propietats `v-if` i `v-show` a classe; però si estàs encallat, [la documentació oficial](https://v2.vuejs.org/v2/guide/conditional.html) pot ser molt útil aquí.

### Iteració 4 | Mostra una llista d'elements que s'emmagatzemen dins d'un component

Recordeu el difícil que semblava `for loops` amb JavaScript de vainilla? Vue fa molta feina quan els fem servir i ens pot permetre mostrar una llista d'elements a la pantalla d'una manera molt més fàcil.

En aquest exercici, practicareu com utilitzar la directiva `v-for` . El repte té els components següents:

- Heu de crear una llista de publicacions dins de les `data` d'un dels vostres components Vue. Aquestes publicacions han d'incloure les dades següents: títol, descripció i contingut; i en necessiteu almenys tres.
- Aleshores, heu de fer que les publicacions "apareguin" a la vostra `template` mitjançant la directiva `v-for` .

De nou, si us quedeu enganxat aquí, [sempre podeu consultar la documentació oficial](https://v2.vuejs.org/v2/guide/list.html) .

### Iteració 5 | Bonificació | Canvia el color de fons d'un element en prémer un botó

Preparats per a un repte més difícil? Vue ens permet fer coses força "màgiques" d'una manera simplificada. En aquest cas, aprendràs a canviar una propietat CSS de manera dinàmica mitjançant l'enllaç de dades.

No hem aprofundit molt en aquest tema; però aquí teniu alguns consells per indicar-vos la direcció correcta:

- Haureu de crear una classe o una propietat CSS i [lligar-la](https://v1.vuejs.org/guide/syntax.html) a una condició.
- Haureu de crear un mètode que canviï la classe o la propietat i activar-lo fent clic al botó. Ho vam practicar al laboratori d'ahir, així que no dubteu a consultar-lo si necessiteu ajuda.

Sona bé? Comencem!

<br/>

Feliç codificació! :heart: