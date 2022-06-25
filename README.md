# PAC1
Repositori de la PAC1 del curs de Front End Web Developer de la UOC.

Descripció i enunciat
HTML + CSS
 
Porftoli personal.
 

Aquesta pràctica consisteix en crear una pàgina web amb un portfoli personal en HTML i CSS.La web ha de tenir 3 pàgines: una pàgina inicial, una pàgina amb un Currículum Vitae i una pàgina amb un formulari de contacte.
 

Tot i que l'entrega final serà una sola, la pràctica es dividirà en petites parts sobre les que anirem treballant cada setmana del primer mòdul.
 
Preparació del projecte
 
Crear un compte a Github o utilizar-ne un de propi si ja es té.
Crear un repositori per al projecte.
Sincronizar el respositori amb l'entorn de desenvolupament local (VS Code)
Tots els canvis que es vagin fent en local s'hauran d'anar pujant al repositori.

Part 1
Crear un Currículum Vitae amb HTML.

Exercici
 
Crear un fitxer cv.html utilitzant les etiquetes o tags HTML necessàris per aconseguir la següent estructura:
 

1. Un títol principal (<h1>) i un títol per cada secció (<h2>).

Es recomana utilitzar l'etiqueta h1 per al títol principal, i que a cada pàgina només n'hi hagi un d'aquest tipus. Tota la resta de títols es poden crear amb h2, h3, h4, h5 i h6, utilitzats de forma jeràrquica. Per exemple, els títols de secció podrien ser h2, i si a dins d'una secció cal un altre subtítol, podria ser h3, i així successivament.
 
Cada títol ha de tenir un identificador amb l'atribut ID, de manera que servirà de destí per quan es fagi clic des d'un enllaç. Per exempe, si volem que la secció idiomes tingui l'identificador "idiomes":
 
<h2 id="idiomes">Idiomes</h2>
 
És important que els identificados siguin únics (no estiguin repetits), idealment escrits en lletres minúscules, no poden començar per un número i no poden contenir caractres "extranys" (accénts, apostrofs, dièresis, ç, ñ...); és a dir, idealment només hauria de contenir lletres i si cal algún guió baix o mig ( _ o - ) 
 
 
 
2. Índex de continguts amb enllaços (etiqueta <a>) cap a les diferents seccions.
 
Un petit índex on es llistin les diferents seccions. Per exemple: dades personals, idiomes, estudis i laboral. Cada element de l'index ha de ser clicable, i al fer-hi clic ha de portar a la secció corresponent.

Per enllaçar un link a una secció, cal indicar a través de l'atribut href l'ID de l'objectiu precedit de # . Per exemple, si volem enllaçar un link amb el text "Idiomes" cap a la secció amb ID = "idiomes" ho podem fer de la següent forma:
 
<a href="#idiomes">Anar a la secció Idiomes</a>
 
 
3. Una secció amb títol “Dades personals” amb les dades personals bàsiques (aquesta informació no cal que sigui real): nom i cognoms, data i lloc de naixement i adreça de residència actual.
 
Es poden utilitzar els tags: <p>, <span>, <div> ...
 
4. Una secció amb títol “Idiomes” amb una taula amb els idiomes que es parlen, on s'indiqui l'idioma i el nivell. Similar a l'exemple següent:
 
Idioma	Nivell baix	Nivell mig	Nivell alt	Natiu
Català	 	 	 	x
Espanyol	 	 	 	x
Anglès	 	 	x	 
 

Es poden utilitzar els tags: <table>, <thead>, <th>, <tr>, <td>

 
5. Una secció amb títol “Estudis” amb un llistat dels estudis realitzats, el nom del centre i la data, amb el format: estudis en negreta, salt de línia i nom del centre. Per exemple:
 
Batxillerat tecnològic
Institut Joan Brudieu.
Enginyeria Informàtica de Gestió
Universitat Rovira i Virgili (URV).
Màster en Multimèdia
Escoles Universitàries Gimbernat i Tomàs Cerdà (EUG).
Es poden utilitzar els tags: <ul>, <li>,<br>, <div>, <p>, <strong>, <i>

6. Una secció amb títol “Laboral” amb un llistat de les feines realitzades, la localitat, la data i una breu descripció de les tasques realitzades, amb el format: posició o nom de la feina en negreta i, entre parèntesis, la localitat en cursiva i el període temporal. Un salt de línia i escriure una breu descripció de les tasques realitzades. Per exemple:
 
Suport IT a grup CREVER (Tarragona, 2009 - 2011)
Tasques de suport IT al grup d'investigació CREVER de la URV. Suport als usuaris, desenvolupament, instal·lació i manteniment de software, gestió del servidor intern i desenvolupament de pàgines web.
Desenvolupament backend a G.Software (Reus, 2011-2013)
Desenvolupament de software tipus ERP enfocat a negocis d'hosteleria utilitzant un framework propi.
 
A tenir en compte
 
En aquesta part només cal entregar el document HTML sense estils. Més endavant, durant el bloc de CSS tornarem a modificar aquesta part per donar-li estils (posició dels elements, colors, tipografia, etc
 
Tot i que l'entrega final del Mòdul serà la part evaluable, es recomana crear un repositori a Github per tal d'anar pujant les parts. D'aquesta manera serà molt fàcil compartir el codi amb els companys o professors i poder anar fent un seguiment detallat del procés.

 
Objectius
 
En aquesta part es treballarà l'estructura principal d'un document HTML i es tindrà un primer contacte amb Github.
 
Es treballaran les etiquetes HTML més habituals, com poden ser: div, section, h1, h2, ul, li, a, p, table, thead, tr, td…
 
 
Recursos recomanats
 
Consultar els videos d'introducció a Github, inicialització d'un projecte amb VS Code, els exemples de codi del repositori Github del curs i els document HTML5 i CSS3 (part HTML) i Introducció al frontend.
 

Repositori de Github amb exemples i codi comentat
https://github.com/Aleix-Marti/curs-frontend/blob/main/HTML

Web All The Tags amb una recopilació molt visual de totes les etiquetes HTML
https://allthetags.com

W3schools: Introducció i referència HTML
https://www.w3schools.com/tags/default.asp
https://www.w3schools.com/html/default.asp

MDN: Introducció i referència HTML
https://developer.mozilla.org/es/docs/Web/HTML
https://developer.mozilla.org/es/docs/Learn/HTML


Part 2
Crear pàgina d'inici, pàgina de contacte i carpeta de recursos

Exercici

Crear una pàgina d'inici tipus home page (index.html) i una pàgina amb un formulari de contacte (contacte.html) i una carpeta per desar imatges.

Cada pàgina, respectivament, haurà de contenir els elements HTML necessaris per ajustar-se al disseny proposat. Cal tenir en compte que en aquest punt encara no s'ha vist temari de CSS, que és la part necessària per a posicionar els elements i donar-los estils. Per tant, del que tracta aquesta activitat principalment, és de fer un anàlisi del disseny proposat i identificat i utilitzar aquelles etiquetes HTML que es considerin necessàries per ajustar-se al disseny.

Per exemple, a la capçalera del disseny apareixen una imatge full width amb un text. Treballant només amb HTML sense CSS, no hi ha manera d'aconseguir que el resultat final s'assembli al disseny proposat, però si que s'ha de construïr una estructura amb els elements identificats, com poden ser un contenedor (section, article, div…), una imatge (img) i un text (h2, h3, p, span…). El resultat d'aquesta part podria ser quelcom similar a:

 
<section>
    <img src=”...”>
    <h2>La web de Homer Simpson</h2>
</section>
 

També caldrà crear una carpeta on desar els assets o imatges i recursos addicionals. Amb l'objectiu de tenir els fitxers ben estructurats, sol ser una bona pràctica agrupar i ordenar els diferents fitxers i recursos utilitzats en una carpeta típicament anomenda assets o algun nom similar fàcilment identificable. Cal tenir en compte assignar rutes relatives quan s'utilitzi l'etiqueta img, això vol dir que quan es cridi una imatge des d'un fitxer HTML, s'ha d'indicar la ubicació de la imatge a partir de la ubicació del fitxer des d'on es crida. Per exemple:

Si tenim la carpeta assets al mateix nivell que el nostre fitxer HTML, a dins una subcarpeta img i una imatge desada a dins d'aquesta carpeta:

index.html
  assets
    img 
      imatge.jpg
 

Si volem mostrar una imatge des del nostre fitxer index.html, podrem utilitzar l'etiqueta img i indicar-li la ruta corresponent.
 
<img src=”assets/img/imatge.jpg”>
 
En canvi, si tenim la imatge al mateix nivell que el nostre fitxer HTML:
 
index.html
imatge.jpg
 
Per mostrar una imatge des del nostre fitxer index.html haurem de cridar la ruta:
 
<img src=”imatge.jpg”>
 
En que es vulgui utilitzar una imatge en format svg, es pot fer de 2 maneres. Utilitzar l'etiqueta <img> i posar-li la ruta com si fós un altre format més:

<img src=”assets/twitter.svg”>

O directament obrir el fitxer svg amb l'editor VS Code i copiar tot el codi, com si fós una etiqueta més de HTML.

<svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Book</title><path d="M256 160c16-63.16 76.43-95.41 208-96a15.94 15.94 0 0116 16v288a16 16 0 01-16 16c-128 0-177.45 25.81-208 64-30.37-38-80-64-208-64-9.88 0-16-8.05-16-17.93V80a15.94 15.94 0 0116-16c131.57.59 192 32.84 208 96zM256 160v288" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/></svg>
 
 

La pàgina de contacte ha de contenir un formulari (es pot obviar la funcionalitatd d'enviament) amb el següents elements:

Un camp per introduïr el nom
Un camp per introduïr una adreça de correu electrònic
Un camp que permeti escriure un text de diverses línies
Un camp tipus checkbox per a que l'usuari accepti el tractament de les seves dades
Un botó per enviar el formulari (opcionalment est pot treballar l'enviament d'un correu a través del formulari, però d'entrata no cal que s'enviï res)

Tots els camps excepte el botó d'enviament han d'anar acompanyats de la seva corresponent etiqueta de text per informar de la finalitat del camp. Per exemple

<label for=”campCP”>Escriu el teu codi postal</label>
<input id=”campCP” type=”number”>
 

A tenir en compte
 

En aquesta part només cal entregar el document HTML sense estils. Més endavant, durant el bloc de CSS tornarem a modificar aquesta part per donar-li estils (posició dels elements, colors, tipografia, etc)
 
Tot i que l'entrega final del Mòdul serà la part evaluable, es recomana utilitzar el repositori de Github per tal d'anar pujant els canvis i les noves parts. D'aquesta manera serà molt fàcil compartir el codi amb els companys o professors i poder anar fent un seguiment detallat del procés.
 
Podeu trobar el disseny proposat en aquesta carpeta de Drive. Més avall, a continguts i recursos tornareu a trobar el link. 

Veureu que al disseny hi ha la proposat amb estils CSS i sense, i que son MOLT diferents. De fet, en aquest punt en que encara no hem començat amb CSS el resultat final hauria ser quelcom similar al disseny sense CSS. És normal. Però he adjuntat el disseny final amb estils per tenir-lo com a referència i poder veure com pot arribar a canviar el resultat un cop s'hi afegeixen estils.

De cara a l'entrega, en aquesta part si que us demanarem que ens envieu un correu a mi i al Luis amb un enllaç al vostre repositori de Github per tal de poder anar fent una mica de seguiment.

Al diseny del formulari, a l'apartat del checkbox hi ha un enllaç cap a la política de privacitat. No cal que porti a cap lloc ni que fagi res. Si algú es vol animar i crear un popup que mostri el text legal (encara que sigui inventat), deixo aquí un exemple.

https://www.w3schools.com/howto/howto_css_modals.asp

 

Objectius
 

En aquesta part es treballarà l'estructura d'un formulari HTML, s'indentificaran els elements HTML representats en un disseny i es treballarà l'estructura de fitxers d'una pàgina web.
 
Es treballaran les etiquetes HTML més habituals, com poden ser: div, section, article, h1, h2, h3, a, p, form, input, button…
 

Recursos recomanats
 

Consultar w3schools, la web all the tags, els exemples de codi del repositori Github del curs i el doocument HTML5 i CSS3 (part CSS)

Proposta de disseny
https://drive.google.com/drive/folders/1hgcqORxgX8zuc6a727vI22QDyKDne84M?usp=sharing

Video “Semánticamente hablando, de Roberto Tuñón”
https://www.youtube.com/watch?v=kt0Jc6g1nw4&ab_channel=WordPressTarragona

Una mica més avall trobareu el zip recursos-part2 amb SVG i icones per si les voleu utilitzar.
 
 
Part 3
Crear barra de menú transversal, un document CSS i donar estils a la pàgina de Currículum Vitae i contacte

Introducció

En aquesta part es començarà a treballar amb CSS. Cada pàgina HTML ha de tenir enllaçat un document CSS (típicament se li diu style.css) on s'hi escriuran totes les propietats i valors CSS per tal de donar-li els estils visuals necessaris per a que el resultat final s'ajusti al disseny proposat.

El CSS serveix per donar estils als elements HTML. És molt comú que en una web hi hagi elements repetits i és aquí on entra en joc CSS. Si a tots els elements que tenen el mateix estil se'ls hi assigna la mateixa classe CSS, només caldrà definir els estils una vegada al document style.css, i l'estil es replicarà per tots els elements que comparteixin la mateixa classe. Per exemple, si volem que tots els títols tinguin la mateixa mida i color, podem crear una classe titol i assignar-la a tots els títols.

style.css
.titol {
  font-size: 2rem;
  color: red;
}
 

index.html
<h2 class=”titol”>Els nostre serveis</h2>
…
<h2 class=”titol”>El nostre equip</h2>
 

Exercici
 

Crear un fitxer style.css i enllaçarlo a la pàgina cv.html
A document cv.html, identificar tots els elements que comparteixen el mateix estil, i assignar-los el mateix nom de classe.
Al document style.css, escriure les propietats i valors corresponents per tal d'ajustar el resultat final al disseny proposat (maquetació)
Crear la capçalera de la web amb la barra de menú i els enllaços cap a les altres pàgines.
Enllaçar el fitxer style.css a la pàgina contacte.html i maquetar la pàgina de contacte seguint el mateix procés.

 

A tenir en compte
 

En una web amb moltes pàgines, el document CSS pot arribar a ser molt gran, per tant és important tenir el codi ben estructurat i amb comentaris, per saber a quina part correspon cada grup de propietats.

D'igual manera és important utilitzar noms de classe descriptives. Per exemple, si tenim un formulari, és millor utilitzar noms de classe com “contacte” o “formulari” que no pas noms genèrics “element” o “part”.

En aquest punt no cal saber les mesures ni colors exactes del disseny, només cal arribar a tenir un resultat aproximat al disseny proposat. Més endavant es treballarà en base a Figma per tal d'ajustar el disseny exactament a la proposta.

La capçalera de la web és un element que es repetirà a totes les pàgines (index, contacte i cv). En aquest tipus d'elements, per evitar repetir feina, és recomanable crear-lo i donar-li estils primer en una pàgina i, quan l'estructura HTML ja estigui acabada (etiquetes i classes), llavors replicar-lo per la resta de pàgines. D'altra manera si, per exemple, canviem una classe del menú a cv, també l'haurem de canviar a index i contacte. Per evitar aquesta feina duplicada es recomana acabar-lo primer en una pàgina i després replicar-lo.

Treballant amb frameworks es pot evitar aquesta tasca de duplicar elements, ja que estan pensats per optimitzar el flux de treball, però en aquest punt encara hem fer aquesta feina per cada pàgina.

 

Objectius
 

Enllaçar un document css a una pàgina HTML, identificar els elements amb estils repetits i assignar-los classes per optimitzar el procés de maquetació (ajustar el codi a un disseny final). Començar a treballar amb els estils bàsics de CSS: unitats, padding, margin, color, font, posicionament.

 

Recursos recomanats
 

Consultar documentació adjunta de CSS, exemples de codi del repositori Github del curs.

Zip recursos-cv (el trobareu més avall, a l'apartat de recursos). Hi ha una imatge amb una proposta de disseny per CV i algunes icones.
 
W3schools: Introducció i referències de CSS
https://www.w3schools.com/css/default.asp
https://www.w3schools.com/cssref/default.asp
 
MDN: Introducció i referpencies de CSS
https://developer.mozilla.org/es/docs/Web/CSS
https://developer.mozilla.org/es/docs/Learn/CSS
 

Part 4
Maquetació de la pàgina principal

Introducció

En aquesta part es començarà a treballar amb Figma. Figma és una eina de disseny i prototipat, que permet als programadors consultar en detall totes les parts del disseny i inclús veure'n algunes de les propietats de CSS. D'aquesta manera es poden ajustar mides, espaiats, tipografies, colors… amb l'objectiu d'aconseguir una maquetació plenament fidel al disseny proposat.

Més endavant es treballarà en Figma per tal de crear un wireframe o esbós inicial d'un disseny. En aquest punt només s'utilitzarà per consultar el disseny proposat i mirar d'ajustar la maquetació per tal d'obtenir un resultat final el més similar possible al disseny proposat.

 

Exercici
 

Maquetar la pagina d'inici (index.html) per tal d'aconseguir un resultat el més similar possible al disseny proposat.
Enllaçar el fitxer style.css a index.html
Escriure el codi CSS necessari per obtenir un resultat el més similar possible al disseny proposat.

 

A tenir en compte
 

És força comú que al plantejament inicial del fitxer index.html se li hagin d'aplicar modificacions. No només afegir classes CSS, sinó inclús canviar l'estructura d'alguns elements.

Per exemple, per utlitzar Flexbox, cal tenir un element que actuï com a contenidor. D'una proposta inicial on s'ha identificat una secció destacada amb una imatge i un text es pot tenir quelcom així:

<img src=”imatge.jgp”>
<p>lorem ipsum dolor sit amet...</p>
 

Però si volem tractar aquest conjut d'elements amb propietats Flexbox, caldrà posar-los a dins d'un altre element que actuï de contenidor. Per exemple:

<div class=”destacat”>
  <img src=”imatge.jgp”>
  <p>lorem ipsum dolor sit amet...</p>
</div>

D'aquesta manera ja podrem “atacar” aquesta secció desde la nostra classe CSS amb les propietats de Flexbox:

.destacat {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}
 

Figma permet veure els atributs o propietats CSS dels elements del disseny. És molt útil sobretot per ajustar tamanys de lletra, espaiats, colors i descarregar recursos (icones i imatges).
 

Objectius
 

Ajustar els elements HTML per tal de poder treballar amb CSS de forma òptima. 

Familiaritzar-se amb Figma per poder consultar les propietats més útils per poder maquetar la web de forma que s'ajusti al disseny proposat.

 

Recursos recomanats
 

Consultar documentació adjunta de CSS, exemples de codi del repositori Github del curs i document amb exemples de Flexbox.
Veure els vídeos Figma-consultar-disseny i Base Flexbox (més avall, a l'apartat Recursos Generals).
 
Disseny proposat
https://www.figma.com/file/093xOOr3uJr9ClxYrepqMD/Untitled

Vídeos ús de variables amb CSS.
https://wordpress.tv/2018/11/11/aleix-marti-variables-nativas-css-front-end-con-superpoderes

Joc per aprendre Flexbox
https://flexboxfroggy.com/#ca

Joc per aprendre Flexbox
http://www.flexboxdefense.com

W3schools: Flexbox
https://www.w3schools.com/css/css3_flexbox.asp

 
Part 5
Maquetació responsive de la pàgina web

 

Introducció
 

Grid CSS no és una tècnica específica per aplicar responsive, però ben combinat amb media queries pot ser útil ja que, igual que Flexbox, treballa de forma molt fluïda i s'adapta força bé al canvis de mida de la pantalla, gairebé de forma automàtica.

De totes maneres, hi ha alguns elements que és complicat que s'adaptin automàticament, tot i utilitzar Flexbox o Grid. En aquests casos serà necessari fer ús de les media queries.

Hi ha dos formes de plantejar la maquetació responsive: de petit a gran (mobile first) o de gran a petit. És cert que quan es té certa experiència és més fàcil adoptar la primera forma, però d'entrada sembla més complicat. Es pot utilitzar la forma que sigui més còmoda per cadascú, només cal tenir en compte a escriure bé les media queries i entendre els seus objectius.

Per exemple, agafant la mida de tall de 768px, es vol que el color d'un text sigui blau per dispositius mòbils i tauleta vertical, i de color vermell per tota la resta de pantalles més grans. Es pot plantejar de 2 maneres. El resultat serà el mateix, però cal posar la propietat inicial fora de la media query, i la propietat amb el canvi a dins.

Mobile first: min-width ( o a partir de la mida indicada )

.text {
  color: blue;
}

@media only screen and (min-width: 768px) {
  .text {
    color: red;
  }
}
 

Desktop first: max-width ( o fins a la mida indicada )

.text {
  color: red;
}

@media only screen and (max-width: 768px) {
  .text {
    color: blue;
  }
}
 

Exercici
 

Escriure el codi CSS necessari i modificar HTML si cal, per aconseguir que la pàgina web (inici, contacte i cv) es vegi bé en les 3 mides.
Maquetar la capçalera de la web i el peu (header i footer) i replicar-ho a les 3 pàgines

 

A tenir en compte
 

Si es treballa amb media queries, aplicar els talls per les mides següents:

600px (mòbil)
768px (tauleta vertical)
992px (tauleta horitzontal)
1200px (escriptori)
 

Objectius
 

Familiaritzar-se amb les media queries i Grid CSS per aconseguir que la web s'adapti a les 3 mides estandaritzades de dispositius: mobile, tablet i desktop (mòbil, tauleta i escriptori).
 

Recursos recomanats
 

Consultar exemples de codi del repositori Github del curs. Document sobre Responsive Web Design.
 
W3schools: RWD
https://www.w3schools.com/css/css_rwd_intro.asp

W3schools: apartat Typical Device Breakpoints
https://www.w3schools.com/css/css_rwd_mediaqueries.asp

Documentació de Google Chrome Developer Tools.
https://developer.chrome.com/docs/devtools/device-mode/

La web CSS Grid Garden per familiaritzar-se amb Grid jugant.
https://cssgridgarden.com/#ca

Article CSS Grid: A guide to getting started.
https://blog.logrocket.com/css-grid-getting-started/

Web Learn CSS Grid.
https://learncssgrid.com/

Col·lecció de Codepen amb exemples de Grid
https://codepen.io/collection/XRgWPe/

Exemple de Codepen amb una tarjeta responsive amb media queries i Grid CSS
https://codepen.io/Aleix/pen/BazMJYp

Vídeo de trucs de CSS avançat.
https://www.youtube.com/watch?v=D1-hKNZgFBA&t=218s&ab_channel=WordPressTarragona
