# Práctica 1 - Creación de página web

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 1 - Sesión 2
En esta práctica se realizó una página web con Wordpress en la nube de Azure de Microsoft

----------------------------------------------------------

#### Requerimientos
- Cuenta de Azure con suscripción.

----------------------------------------------------------

#### Pasos a seguir

1. Ingresamos al portal de Azure (portal.azure.com). Una vez logueados con nuestra cuenta, vamos al buscador de la parte superior (*'Buscar recursos, servicios y documentos (G+/)'*) y buscamos 'Wordpress'.

![P1I1](https://github.com/AlbertoSF99/Practica-1/blob/main/Images/Sesi%C3%B3n%202%20-%20P1%2001.PNG)

2. Una vez seleccionada la opción de Wordpress, llenamos los espacios necesarios para su creación. **IMPORTANTE:** Lo mínimo que necesita un recurso para ser creado es una suscripción, un grupo de recursos, una región y un nombre. Prosiguiendo con esto, en el apartado de suscripción elegiremos ‘Azure para estudiantes’. Para grupo de recursos elegimos ‘Crear nuevo’ y damos un nombre alusivo a la práctica, como: “Sesion2-practica1”. En región, elegimos la que más nos convenga. Finalmente, en nombre, elegimos uno que sea apropiado. Una vez hecho y revisado todo esto, le damos en ‘Revisar y crear’ y en ‘Crear’.

![P1I2](https://github.com/AlbertoSF99/Practica-1/blob/main/Images/Sesi%C3%B3n%202%20-%20P1%2002.PNG)

3. Una vez creado, le damos en ‘Ir al recurso’. En el direccionamiento de la página, podremos ver la información del recurso, así como el link del sitio web que se ha creado, accedemos a la página por medio de ese link.

![P1I3](https://github.com/AlbertoSF99/Practica-1/blob/main/Images/Sesi%C3%B3n%202%20-%20P1%2003.PNG)

![P1I4](https://github.com/AlbertoSF99/Practica-1/blob/main/Images/Sesi%C3%B3n%202%20-%20P1%2004.PNG)

4. Dentro de la página, podremos configurar el sitio web de Wordpress que acabamos de crear. Para esto, rellenamos los campos que nos pidan. En la opción de ‘Visibilidad en los motores de búsqueda’ nos permitirá activar o desactivar la búsqueda del sitio web a través del buscador de Google. Una vez realizado el ingreso de datos (como cuenta, contraseña, nombre, etc.) podemos corroborar el sitio web de Wordpress nuevamente ingresando al link original que aparece en el recurso de Wordpress creado en Azure.

![P1I5](https://github.com/AlbertoSF99/Practica-1/blob/main/Images/Sesi%C3%B3n%202%20-%20P1%2005.PNG)

![P1I6](https://github.com/AlbertoSF99/Practica-1/blob/main/Images/Sesi%C3%B3n%202%20-%20P1%2006.PNG)

5. Ingresamos ahora con permisos de administrador a la página, por medio de la adhesión de *'/wp-admin'* en el URL del sitio web. Iniciamos sesión con nuestrar credenciales que usamos en el paso 4. Así pues, se puede modificar la página web a gusto personal, teniendo la debida experiencia y creatividad para ello.

![P1I7](https://github.com/AlbertoSF99/Practica-1/blob/main/Images/Sesi%C3%B3n%202%20-%20P1%2007.PNG)

![P1I8](https://github.com/AlbertoSF99/Practica-1/blob/main/Images/Sesi%C3%B3n%202%20-%20P1%2008.PNG)

***Información adicional:*** El plan de App Service usado para esta práctica es un complemento, mientras que los servicios usados son 2, el servicio de App Service y el servicio de Azure Database for MySQL. Todas las bases de datos son PaaS. El plan de App Service ubicada dentro del grupo de recursos creado, sirve para escalar vertical y/o horizontal, aunque, evidentemente, hacer esto cobra saldo. Es importante una vez que ya no se use los recursos usados en esta práctica, apagarlos o eliminarlos, para que no gasten saldo, ya que esta página de wordpress hace uso de Azure Database for MySQL, el cual consume bastante saldo. Se pueden agregar recursos de diferentes regiones en un mismo grupo de recursos sin problemas.
