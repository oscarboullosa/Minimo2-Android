Si vamos al fragmento de la derecha de todo (settings) vemos un menú desplegable (Spinner) donde están todos los idiomas que se pueden elegir.
Cuando seleccionemos un idioma le podremos dar al botón "Aplicar cambios". Dándole a este botón hacemos varias cosas:
- Con SharedReferences guardamos el valor de idioma para que si cerramos la aplicación se conserve el idioma.
- Actualizamos el idioma del usuario con updateLanguage
- Volvemos a la pantalla de SplashScreen con todos los cambios de idioma efectuados.
Arriba de todo a la izquierda hay un pequeño texto donde se puede ver el idioma que estamos usando.

Los cambios de idioma se han hecho utilizando SetLocale y el editor de traducciones (con el que gestionamos los diversos strings.xml).
