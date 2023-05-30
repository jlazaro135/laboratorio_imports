# laboratorio imports

**[DEMO LINK - LABORATORIO IMPORTS](https://https://siete-y-media.netlify.app/)**

Es una continuación del laboratorio de condicionales (bootcamp JS - Lemoncode), en la que se ha modularizado todo el código en diferentes archivos:

- motor.ts
Contiene las reglas y lógica del juego

- model.ts
Contiene los datos del juego

- literals.ts
Contiene textos estáticos

- utils.ts
Contiene utilidades usadas en diferentes lugares


A la vista de que el archivo que encargado de manipular el DOM, he propuesto la siguiente segregación en cuanto a la parte de interfaz de usuario:
- ui:
    - buttons.ts
    Gestiona los botones

    - card.ts
    Gestiona todo lo relacionado con las cartas

    - dataGame.ts
    Gestiona el renderizado de los datos del juego

    - modal.ts
    Gestiona los diferentes modales

    - ui.ts
    Es un archivo más general que auna diferentes funcionalidades






