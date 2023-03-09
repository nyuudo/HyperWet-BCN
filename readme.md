# SPRINT 1

En aquesta pràctica hauràs de fer un Layout que ha de funcionar tant en escriptori, com mòbil i tauleta.

Tingues en compte les següents consideracions. Són errors habituals en els lliuraments:

- En general, mai li posem height a una capa, sinó que deixem que la capa s'adapti al seu contingut (si la capa no té contingut, li pots posar un height).
- La pàgina no hauria de tenir barra de scroll horitzontal (si et passa, hauràs d'esbrinar inspeccionant la pàgina quin bloc és més ample que la pantalla del navegador).
- Dins d'un div sol haver-hi altres divs. - Els divs tenen display:block per defecte. Això fa que es vagin col·locant de manera vertical. Per tant, sovint no és necessari especificar els següents estils per a un element per ser una cosa redundant:
  .element{ display:flex; flex-direction:column }
- En un div, per defecte l'ample és la totalitat de la capa que embolica, així que normalment no serà necessari especificar width:100%

## Exercici 1

A partir del wireframe que t'aportem en format .png, hauràs de fer la maquetació en format escriptori. És indiferent els colors escollits, però sí que és molt important que facis l'estructura de caixes que t'indiquem.

## Exercici 2

S'ha de començar a preparar l'adaptació a diferents dispositius, i per això has de tenir clar el concepte de Media Query. Fixa't que hi ha canvi de distribució i color d'alguns elements.

## Exercici 3

Com en el cas anterior, ara hauràs de fer l'adaptació a versió Mobile.
