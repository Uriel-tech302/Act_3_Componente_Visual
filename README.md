# Componente Visual JS

**Autor:** Uriel Espinoza de la Rosa  
**Carrera:** Ingeniería en Sistemas Computacionales, ITO   

## ¿Qué problema resuelve?

En el desarrollo de interfaces modernas, es necesario informar al usuario sobre el estado de sus acciones por este motivo crearemos los componente  que resuelve este problema proporcionando notificaciones flotantes (Toasts) que son estéticamente agradables, no bloquean la pantalla, se ocultan automáticamente tras un tiempo definido y **son altamente reutilizables**, permitiendo generar múltiples alertas simultáneas en pantalla inyectando dinámicamente HTML desde JavaScript.

## Instalación

Solo necesitas incluir la hoja de estilos en el `<head>` y el script de la lógica antes del cierre del `</body>`:

```html
<!-- En el <head> -->
<link rel="stylesheet" href="css/componente.css">

<!-- Antes de cerrar </body> -->
<script src="js/componente.js"></script>
```
## Uso y Ejemplos de Código
El componente es 100% dinámico y no requiere agregar contenedores en el HTML manualmente.

1. Notificación de Éxito
Al confirmar una acción, se invoca con el parámetro 'success'.

```html
// Mostrará una tarjeta verde durante 4 segundos (4000ms)
mostrarToast('¡Artículo agregado al carrito con éxito!', 'success', 4000);
```
2. Notificación de Error
Al ocurrir una falla en el sistema, se utiliza el parámetro 'error'. Al omitir el tiempo, utiliza el valor por defecto de 3000ms.

```html
// Mostrará una tarjeta roja
mostrarToast('Error de sistema: No hay stock disponible.', 'error');
```

3. Notificación de Información
Ideal para avisos neutrales.
```html
// Mostrará una tarjeta azul
mostrarToast('Tienes nuevos mensajes en tu bandeja.', 'info');
```

## Capturas de Pantalla
1. Notificación de Éxito
<img width="1730" height="987" alt="1" src="https://github.com/user-attachments/assets/7f920f71-e7e0-4d2e-85a7-e4e7d8ece3f5" />
2. Notificación de Error
<img width="1920" height="1090" alt="Parte_7" src="https://github.com/user-attachments/assets/571de31a-2a41-406d-a316-01c63ef80959" />
3. Notificación de Información
<img width="1576" height="896" alt="3" src="https://github.com/user-attachments/assets/19f6c12e-4e43-4b9e-9d47-f94a09640868" />




## Video Demostrativo
En el siguiente video de 60 segundos explico el problema de diseño que resuelve el componente:
https://drive.google.com/file/d/1uoD076z1AJaofMmZNxrI57rpiDMOXrfG/view?usp=sharing
