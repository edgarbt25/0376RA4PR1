# 0376RA4PR1 — Exercicis de DOM

## Descripció
Pràctica d'exercicis per aprendre a manipular el DOM amb JavaScript.

## Fitxers
- `index.html` — estructura de la pàgina
- `estils.css` — estils visuals
- `script.js` — lògica JavaScript

## Exercicis

### 1. Canviar text
Seleccionem un element i canviem el seu contingut:
`document.getElementById("paragraf-hola").textContent = "Hola, DOM!";`

### 2. Canviar imatge
Modifiquem l'atribut `src` d'una imatge:
`document.getElementById("imatge-canviant").src = "https://nova-url.com/img.jpg";`

### 3. Llançar alerta
Afegim un event al botó:
`document.getElementById("boto-alerta").addEventListener("click", () => alert("Hola!"));`

### 4. Toggle de classe
Commuta la classe `actiu` sobre un element:
`document.getElementById("text-classe").classList.toggle("actiu");`

### 5. Afegir element a la llista
Creem un `<li>` nou i l'afegim a la llista:
`document.getElementById("llista-compra").appendChild(document.createElement("li"));`