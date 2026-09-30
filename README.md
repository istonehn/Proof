# QR dinámico — Medigold

Este repositorio contiene un enlace estable para un QR impreso.

URL prevista del QR:

`https://istonehn.github.io/Proof/medigold/`

## Cambiar el destino del QR

Edita `medigold/config.js` y cambia:

`window.MEDIGOLD_TARGET = "";`

por, por ejemplo:

`window.MEDIGOLD_TARGET = "https://dominio-del-cliente.com";`

El QR impreso no cambia.

Mientras el destino esté vacío, la página muestra un mensaje neutro de "Sitio en preparación".
