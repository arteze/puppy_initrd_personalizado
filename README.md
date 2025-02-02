# puppy_initrd_personalizado

Modificación del initrd del PuppyLinux. Todavía no funciona, es experimental.

- El objetivo es: __No usar enlaces simbólicos.__

Adaptación para teclado roto.

# Cambios

- https://github.com/arteze/puppy_initrd_personalizado/blob/main/bin/b
- https://github.com/arteze/puppy_initrd_personalizado/blob/main/bin/bn

Se cambia el abecedario en los ejecutables del busybox.

```sh
pqwertyuio
0123456789
```

# Original

- El original se llama LxPupSc64, esta es una modificación de su initrd.
- https://sourceforge.net/projects/lxpup/files/Other/LxPupSc64/

## Leeme del original traducido al español con Google Traductor:

LxPupSc64 es una compilación Woof-CE de 64 bits que utiliza componentes Slackware-Current con los últimos kernels de 64 bits con firmware en el fdrv.

LxPupSc64 ofrece Openbox como administrador de ventanas, LxPanel como administrador de paneles y PCManFM como administrador de archivos.

Light-48.0 es el navegador web liviano integrado (en adrv, por lo que se puede cambiar fácilmente por otros navegadores).

El iso incluye un directorio /opt/lxpup-xtras que tiene complementos útiles que se pueden cargar mediante el botón Opciones en el menú Cambiar apariencia.

Este cachorro experimental se ofrece para pruebas...

Algunas características clave a partir de noviembre de 2024:

- una compilación woof-ce de 64 bits que utiliza una combinación de componentes Slackware Current y 15.0 + componentes LXDE de Slackware-Ponce
- kernel 6.11.x-lxpup64
- el navegador web liviano integrado es Light-48.0 en adrv
- el firmware está en fdrv
- navegadores alternativos: Chromium, Firefox, Palemoon disponibles para descargar
- escritorio LXDE
- sin controladores adicionales que no sean del kernel (por ejemplo, no wl, ndiswrapper)
