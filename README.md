# challenge_amigo_secreto
desarrollo de lógica de programación - ejercicio amigo secreto

Este proyecto es una aplicación we desarrollada para sortear el "Amigo Secreto".
El desarrollo hace parte del curso Lógica de Programación de Alura One y es una aplicación
que permite a los usuarios ingresar nombres de amigos, visualizarlos en una lista y
al momento de realizar el sorteo, seleccionar de forma aleatoria un nombre.
Una vez sorteado, el nombre se elimina de la lista para evitar repeticiones y se formatea
cada nombre para que solo la primera letra sea mayúscula, de forma que sin importar como ingrese
el usuario los nombres, el formato de salida sea homogéneo.

## Autor

Rita Ballesteros

## Lenguajes y Tecnologías Utilizadas

- ** HTML:** Estructura básica de la página.
- ** CSS:** Estilización y diseño responsivo
- ** JavaScript:** Lógica de programación para la validación de entradas, almacenamiento de nombres,
  sorteo aleatorio y manipulación del DOM

  ## Funcionalidades
  - **Agregar Amigos:**
    Permite ingresar nombres de amigos a través de un campo de texto.
    Se valida que el campo no esté vacío y se formatea el nombre para que la primera letra sea
    mayúscula y el resto minúscula, sin importar como lo escriba el usuario que ingresa los datos.

  - **Visualización de la lista:**
    Los nombres ingresados se muestran en una lista que se actualiza en tiempo real.

  - **Validación de Entrada:**
    Si el usuario intenta ingresar un nombre vacío, se muestra una alerta solicitando un nombre válido.

  - **Sorteo Aleatorio:**
    Se selecciona  aleatoriamente un nombre de la lista cuando se da click en el botón "Sortear Amigo".

  - **Eliminación de Amigo Sorteado:**
    Una vez sorteado, el nombre se elimina de la lista para evitar que se repita en futuros sorteos

  - **Alertas de Estado:**
    Si ya no quedan nombres en la lista para sortear, se muestra un alerta indicando que no hay
    más amigos disponibles.

  ## Instrucciones de Uso
  1. Abra el archivo "index.html" en su navegador
  2. Ingrese el nombre de un amigo en el campo de texto y pulse en **Añadir**.
  3. Agregue tantos nombre como necesite.
  4. Cuando esté listo para realizar el sorteo, haz clic en **Sortear Amigo**.
  5. El nombre sorteado se mostrará en la pantalla y se eliminará de la lista.
   
     
  

