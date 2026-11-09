# B&P Studio · Barbería y peluquería

Template de reservas para servicios de barbería y peluquería, con selección de servicio y profesional, perfil, confirmaciones y pago simulado.

## Tecnología y alcance

HTML, CSS y JavaScript nativo. Usa Tailwind CSS vía CDN. No requiere un proceso de compilación para previsualizar las páginas. Se necesita conexión a Internet para cargar los recursos externos referenciados por los HTML, como estilos, fuentes e imágenes.

La autenticación y las reservas son demostrativas y utilizan almacenamiento del navegador. No hay backend ni conexión a una agenda compartida. Los pagos y las confirmaciones son simulados; no se procesan transacciones reales.

## Ejecución local

Desde esta carpeta, con Node.js y npm instalados:

```powershell
npx --yes http-server . -p 8080 -c-1
```

Abre [la vista previa local](http://localhost:8080/) y comienza en `index.html`. Mantén el mismo origen y puerto al recorrer las páginas para conservar los datos del navegador.

## Acceso de demostración

| Correo | Contraseña |
|---|---|
| `juan@test.com` | `123456` |
| `maria@test.com` | `123456` |

Abre la pantalla de inicio de sesión e ingresa con una cuenta de la tabla. Los cambios de perfil y las reservas se guardan solamente en ese navegador y origen.

## Páginas incluidas (17)

| Archivo | Título de la página |
|---|---|
| `confirmacion.html` | Confirmación · B&P Studio |
| `contacto.html` | Contacto · B&P Studio |
| `detalle-reserva.html` | Detalle de Reserva · B&P Studio |
| `galeria.html` | Galería · B&P Studio |
| `horarios.html` | Horarios · B&P Studio |
| `index.html` | B&P Studio · Barbería & Peluquería en Santiago |
| `inicio-sesion.html` | Iniciar Sesión · B&P Studio |
| `pago-confirmado.html` | Pago Confirmado · B&P Studio |
| `pago.html` | Pago de Reserva · B&P Studio |
| `perfil.html` | Mi Perfil · B&P Studio |
| `precios.html` | Precios y Membresías · B&P Studio |
| `privacidad.html` | Políticas de Privacidad · B&P Studio |
| `recuperar-password.html` | Recuperar Contraseña · B&P Studio |
| `registro.html` | Registro · B&P Studio |
| `reserva.html` | Reservar Cita · B&P Studio |
| `servicios.html` | Servicios · B&P Studio |
| `terminos.html` | Términos y Condiciones · B&P Studio |

## Personalización

- Textos, imágenes, enlaces y datos de contacto: revisa los HTML y `main.js`.
- Colores, espaciados y ajustes responsivos: `css/styles.css`.
- Catálogos, datos de ejemplo y lógica del template: `main.js`. Algunos textos y resúmenes también están definidos en scripts dentro de los HTML.

Los importes visibles usan pesos chilenos (CLP) y los contactos son ejemplos para Chile. Sustituye precios, dirección, teléfono, correo e información del negocio antes de usarlos como datos comerciales.

## Comprobación visual

Recorre las páginas en móvil, tablet y escritorio. Comprueba que el menú, los formularios, las tarjetas y los precios permanezcan legibles; las tablas extensas pueden utilizar desplazamiento horizontal dentro de su contenedor.
