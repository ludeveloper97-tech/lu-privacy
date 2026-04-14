# Politica de Privacidad

Ultima actualizacion: 14 de abril de 2026

## 1. Identidad del responsable

Esta Politica de Privacidad describe como se accede, usa, almacena y comparte la informacion en relacion con la app `N3D Launcher` (paquete Android `com.ludev.threedlauncherm`) en su version para Google Play.

Responsable del tratamiento:

- Correo: [ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com)

Si publicas la app con otra entidad o correo, sustituye estos datos antes de subirla a Google Play.

## 2. Alcance

Esta politica cubre:

- los datos a los que la app accede en el dispositivo;
- los datos que la app almacena localmente;
- los datos que la app puede transmitir fuera del dispositivo;
- los permisos solicitados por la version actual para Google Play;
- la retencion y eliminacion de datos.

## 3. Resumen de privacidad

La version actual revisada para Google Play funciona principalmente como launcher y experiencia de personalizacion para Android. La mayor parte de la informacion que usa se procesa localmente en el dispositivo del usuario.

La build `play` revisada:

- no usa badges de notificaciones;
- no usa podometro ni monedas internas;
- no usa Nearby/Bluetooth/ubicacion para intercambio local;
- no usa Firebase ni backend propio;
- no usa acceso amplio al almacenamiento;
- ofrece una compra unica opcional gestionada por Google Play para desbloquear personalizacion avanzada.
- puede acceder a contactos si el usuario concede permiso al abrir `Friends List`.

La app no esta disenada para vender datos personales ni para usar datos personales con fines de publicidad.

## 4. Datos a los que la app accede o que trata localmente

### 4.1 Apps instaladas y metadatos basicos

La app puede leer informacion de apps lanzables instaladas para:

- mostrarlas en el launcher;
- permitir busqueda y apertura;
- organizarlas en carpetas;
- establecer accesos por defecto en modulos del launcher.

Los datos tratados localmente pueden incluir:

- nombre de la app;
- paquete Android;
- icono;
- version;
- fecha de instalacion.

### 4.2 Camara y contenido visual

Si el usuario concede permiso de camara, la app puede:

- usar la camara dentro del modulo correspondiente;
- capturar imagenes dentro de la app;
- permitir usar imagenes seleccionadas por el usuario en funciones de personalizacion.

En la version revisada para Google Play, la grabacion con audio esta desactivada y la app no solicita permiso de microfono.

### 4.3 Contactos

Si el usuario concede permiso de contactos al abrir `Friends List`, la app puede leer localmente contactos del dispositivo para:

- mostrar la lista de amigos dentro del launcher;
- buscar contactos por nombre;
- mostrar nombre, telefono y miniatura local cuando el sistema la proporciona;
- iniciar una llamada o abrir WhatsApp con el numero elegido por el usuario;
- permitir crear un contacto desde la propia pantalla de amigos.

Los contactos se procesan localmente en el dispositivo. La build actual no usa Firebase ni backend propio para subir contactos a un servidor.

La app muestra una explicacion previa antes de solicitar el permiso de contactos:

```text
N3D Launcher usa tus contactos solo para mostrar la lista de amigos y permitir llamadas o abrir WhatsApp desde esta pantalla. Los contactos no se suben a ningun servidor.
```

### 4.4 Archivos seleccionados por el usuario

La app puede acceder a archivos elegidos voluntariamente por el usuario mediante el selector del sistema para:

- importar imagenes o animaciones;
- configurar fondos personalizados;
- importar archivos compatibles para la biblioteca local.

La app no solicita `MANAGE_EXTERNAL_STORAGE` ni acceso amplio al almacenamiento.

### 4.5 Biblioteca local de archivos compatibles

La app puede permitir al usuario seleccionar archivos compatibles, como `.3ds`, `.cia` o `.3dz`, para mostrarlos en una biblioteca local dentro del launcher.

Cuando el usuario importa uno de esos archivos, la app puede procesar localmente:

- nombre del archivo;
- ruta del archivo seleccionada por el usuario;
- identificador interno del contenido cuando esta disponible;
- miniatura embebida del propio archivo.

La miniatura extraida se guarda localmente en almacenamiento interno de la app para volver a mostrarla dentro de la biblioteca.

### 4.6 Preferencias, fondos y contenido local

La app puede almacenar localmente informacion como:

- temas y gradientes;
- fondos personalizados;
- carpetas y configuracion del grid;
- notas dibujadas;
- logs de uso dentro de la app;
- estado de proteccion local de ciertos accesos.

### 4.7 Autenticacion local del dispositivo

La app puede usar autenticacion del dispositivo, como biometria o bloqueo seguro, para proteger el acceso a determinadas apps o carpetas dentro del launcher.

La app no recibe ni almacena la huella biometrica del usuario; solo recibe del sistema Android el resultado de la autenticacion.

### 4.8 Compras integradas con Google Play

La version `play` puede ofrecer una compra unica opcional para desbloquear funciones premium de personalizacion.

Cuando el usuario inicia una compra, la transaccion se gestiona mediante Google Play Billing. La app puede recibir y tratar localmente informacion tecnica necesaria para desbloquear el contenido, como:

- identificador del producto comprado;
- estado de la compra o restauracion;
- identificador de la transaccion cuando lo facilita Google Play.

La app no procesa directamente datos de tarjeta ni credenciales de pago en sus propios servidores.

## 5. Datos que pueden transmitirse fuera del dispositivo

Segun la revision actual de la flavor `play`, la app no usa Firebase ni esta pensada para transmitir datos personales a un backend propio como parte de su flujo principal.

No obstante:

- la app puede abrir webs, correo u otras apps externas cuando el usuario asi lo elige;
- la compra premium opcional se tramita con Google Play;
- si en una version futura se reactivan funciones remotas, esta politica debera actualizarse antes de publicar esa build.

## 6. Finalidades del tratamiento

La app trata datos para:

- ofrecer una pantalla de inicio/launcher funcional;
- mostrar, organizar y abrir apps instaladas;
- permitir personalizacion visual del launcher;
- mostrar la lista de amigos desde los contactos locales si el usuario concede permiso;
- gestionar una biblioteca local de archivos compatibles seleccionados por el usuario;
- proteger accesos locales mediante autenticacion del dispositivo;
- guardar preferencias y contenido creado por el usuario;
- comprobar el estado de una compra premium opcional realizada mediante Google Play.

## 7. Base de legitimacion

Segun la funcion utilizada, el tratamiento puede basarse en:

- la ejecucion de la funcionalidad solicitada por el usuario;
- el consentimiento del usuario al activar permisos o funciones opcionales;
- la ejecucion de una compra opcional solicitada por el usuario a traves de Google Play;
- el interes legitimo del responsable para operar y mantener la app dentro de los limites legales aplicables;
- el cumplimiento de obligaciones legales, cuando proceda.

## 8. Con quien se comparten los datos

Segun la revision actual de la build `play`, la app no esta disenada para compartir datos personales con terceros desde un backend propio.

La app puede interactuar con terceros unicamente cuando el usuario asi lo solicita, por ejemplo:

- Google Play, para una compra integrada opcional;
- apps externas o enlaces externos abiertos por el usuario, por ejemplo telefono o WhatsApp cuando el usuario los abre desde `Friends List`.

## 9. Conservacion de datos

### 9.1 Datos locales

Los datos almacenados en el dispositivo se conservan normalmente hasta que:

- el usuario los borra desde la propia app;
- el usuario borra los datos de la app desde Android;
- el usuario desinstala la app.

### 9.2 Datos de compra

La app puede mantener estado local minimo para UX, pero en la flavor `play` el entitlement premium se vuelve a sincronizar con Google Play y no se considera valido solo por almacenamiento local.

## 10. Eliminacion de datos

El usuario puede:

- desinstalar la app;
- borrar los datos de la app desde Android;
- eliminar contenido local desde las funciones disponibles;
- solicitar informacion adicional contactando con [ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com).

## 11. Seguridad

La app aplica medidas tecnicas razonables acordes a la naturaleza del producto y del almacenamiento local que utiliza. No obstante, ninguna transmision o sistema de almacenamiento es completamente infalible.

## 12. Menores de edad

La app no esta dirigida especificamente a menores salvo que la ficha publicada y la configuracion final indiquen otra cosa. Si un padre, madre o tutor considera que un menor ha proporcionado datos en contra de lo esperado, puede contactar con el responsable para solicitar revision o eliminacion cuando sea posible.

## 13. Enlaces y servicios de terceros

La app puede abrir webs, redes sociales, correos o apps externas. Cuando el usuario usa esos enlaces o servicios, el tratamiento de datos pasa a regirse por las politicas del tercero correspondiente.

En caso de compra integrada, tambien aplican las condiciones y politicas de Google Play.

## 14. Cambios en esta politica

Esta Politica de Privacidad puede actualizarse para reflejar cambios legales, tecnicos o funcionales. La version vigente sera la publicada en la URL oficial asociada a la app y, cuando proceda, tambien dentro de la propia aplicacion.

## 15. Contacto

Para dudas sobre privacidad, acceso, rectificacion, eliminacion o uso de datos, puedes contactar en:

- Correo: [ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com)
