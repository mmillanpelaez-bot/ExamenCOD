# Examen 1ª Evaluación (2ª Parte) - Control de Versiones

---
**Alumno**: Manuel Felipe Millan Pelaez
## Instrucciones
- Los commits de cada apartado deben tener el mensaje *"Apartado X - descripción del cambio realizado"*
- Entrega en la tarea de Moodle tu repositorio
- Solo se corrigen los commits que estén en el repositorio remoto

### Apartado 1
![CAPTURA 1.0](Screenshot from 2025-12-16 13-56-57.png "nombre y commit")
- Clona este repositorio.
- Modifica este Readme, poniendo tu nombre completo, realiza un `commit` con el mensaje *"Apartado 1"* y un `push`.

Pregunta 
- ¿Qué paso es fundamental cuando clonamos un repositorio ajeno para que podamos subir nuestros propios commits? Explícalo y utiliza capturas de pantalla.

El paso fundamental es **hacer un FORK del repositorio original antes de clonarlo**. Esto es necesario porque:

1. **Sin fork**: Si clonas directamente el repositorio ajeno (`https://github.com/damiancastelao/ExamenCOD`), no tendrás permisos de escritura. Cuando intentes hacer `git push`, recibirás un error de permisos denegados.

2. **Con fork**: Al hacer fork, creas una copia del repositorio en tu propia cuenta de GitHub donde SÍ tienes permisos completos de lectura y escritura.

**Paso 1: Hacer Fork en GitHub**
- Acceder al repositorio original: https://github.com/damiancastelao/ExamenCOD
- Hacer clic en el botón "Fork" ubicado en la parte superior derecha
- GitHub crea automáticamente una copia en tu cuenta

![CAPTURA 1.1](Screenshot from 2025-12-16 13-44-57.png "fork")

![CAPTURA 1.2](Screenshot from 2025-12-16 14-10-35.png "forkeado")

### Apartado 2

- Realiza una modificación en el código en la web de tu repositorio en GitHub
- Utiliza fetch para descargar los cambios realizados en tu repositorio.

Pregunta
- Explica los pasos para que el código modificado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.

### Apartado 3

- Realiza otro cambio desde la web de tu repositorio en GitHub.
- Utiliza pull para descargar los cambios realizados en tu repositorio.

Pregunta
- Explica los pasos dados para que el cambio realizado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.

