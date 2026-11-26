# Landing de Ferretería El Maestro

Página de una sola pantalla, pensada para celular y para cargar rápido con señal débil (sin librerías, logo de 35 KB).

## Qué tiene que completar antes de publicarla

1. **WhatsApp y teléfono**: al final de `index.html`, en el bloque `DATOS`, ponga el número (`whatsapp: "57300..."`) y cómo quiere que se vea (`telefonoVisible`). Con eso todos los botones de WhatsApp y Llamar quedan funcionando.
2. **Perfil de Google Business**: pegue el enlace en `DATOS.googleBusiness` y en `sameAs` del bloque `application/ld+json` (arriba). Los datos de ese bloque (dirección, teléfono, horario) deben ser iguales a los de su ficha en Google.
3. **Textos entre corchetes** `[ ... ]`: dirección, referencia ("diagonal al parque principal"), horario, años en el pueblo, marca adicional, enlaces de Facebook e Instagram.
4. **Fotos reales**: cambie los recuadros de la sección "Gente del pueblo" por fotos del local y del equipo (`<img src="fachada.webp" alt="...">`).
5. **Testimonios**: solo de clientes reales y con su permiso. Si no tiene, borre ese bloque.
6. **Servicios y marcas**: borre los que no preste o no maneje.

## Cómo publicarla gratis

Sirve cualquier hosting estático: GitHub Pages, Netlify o Cloudflare Pages. Suba la carpeta `landing/` completa (`index.html`, `logo.webp`, `icono.png`).
