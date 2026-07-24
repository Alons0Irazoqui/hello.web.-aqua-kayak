# Brief de Proyecto — Aqua Kayak Xochimilco (Landing Page)

Este documento es el informe/brief de negocio, branding y requisitos visuales para el desarrollo de la landing page de **Aqua Kayak Xochimilco**. El sitio se construirá sobre la plantilla base HTML ya entregada, siguiendo el prompt inicial de adaptación que también recibiste. Este README **no define la estructura de secciones de la página**: esa estructura ya está dada por la plantilla base y debe respetarse tal cual.

Toda la información de negocio de este documento fue extraída directamente de las imágenes y capturas provistas en la carpeta `imagenes/`.

---

## 1. Información del Negocio

- **Nombre:** Aqua Kayak Xochimilco
- **Giro:** Tours guiados en kayak por los canales y chinampas de Xochimilco, CDMX.
- **Teléfono de contacto:** 55 4491 5299

### Horarios de tours
| Salida | Horario |
|---|---|
| Amanecer | 4:50 am |
| Medio día | 11:00 am – 2:00 pm |
| Atardecer | 4:00 pm |

- Servicio los 7 días de la semana.
- Atención a clientes (pedidos/reservas) las 24 horas del día.

### La experiencia
- Recorrido totalmente guiado, con guías expertos dedicados al kayak.
- Embarcaciones recreativas equipadas con chaleco salvavidas, pensadas para evitar caídas.
- El tour se adentra en la zona ecológica de Xochimilco, pasando por ajolotarios y animalarios donde se conservan especies, además de fauna típica del canal (ranas, patos, peces, lagartijas).
- En el recorrido se puede pasar por puntos de interés como la Isla de las Muñecas.
- Pet friendly: se puede asistir con mascota.
- Ideal para pareja, amigos o familia.
- Toda reserva requiere un anticipo para apartar material y guía.

### Paquetes y precios
| Paquete | Precio |
|---|---|
| Tour en kayak | $300 MXN por persona |
| Tour en kayak + desayuno | $450 MXN por persona |

**El desayuno incluye:**
- Café y pan dulce (bagel, croissant)
- Chilaquiles (pollo o huevo, crema, queso, pan blanco)
- Bebidas: agua natural, agua de sabor, algún tipo de soda

---

## 2. Branding (extraído del logo e imágenes)

### Paleta de colores
Colores tomados visualmente del logo (`imagenes/logo.jpeg`). Son una referencia aproximada: ajusta los tonos exactos con un selector de color una vez que tengas el logo sin fondo.

| Color | HEX aprox. | Uso en el logo |
|---|---|---|
| Azul marino / Navy | `#0B2545` | Anillo del emblema, tipografía "AQUA KAYAK", silueta del kayak |
| Azul cielo | `#5BB8E0` | Degradado del cielo |
| Verde-azulado / Teal | `#1F6F60` | Agua del canal |
| Dorado / Atardecer | `#F2C24C` | Sol y acentos cálidos |
| Blanco | `#FFFFFF` | Texto "XOCHIMILCO" y contrastes |

### Tipografía sugerida
- **Títulos:** sans-serif bold/condensada, en línea con el trazo del logo (ej. Montserrat, Poppins Bold, Archivo Black).
- **Cuerpo de texto:** sans-serif limpia y legible (ej. Inter, Poppins Regular, Work Sans).

### Identidad visual
Aventura acuática al aire libre con un toque ecológico y cultural (chinampas y tradición xochimilca), comunicada con un lenguaje visual premium y actual: tonos de amanecer/atardecer con neblina sobre el canal, agua en tonos azul-teal, y acentos dorados de sol.

---

## 3. Estilo Visual Obligatorio

El sitio debe manejar:
- Estilo **premium, enterprise y corporativo de marca**.
- Nivel **big tech**: elegante y a la vez minimalista.

---

## 4. Efectos y Animaciones Requeridos

- Efectos visuales y **animaciones de scroll**.
- **Pantalla de carga (preloader)** con spinner + logo del negocio.
- **Animaciones en el título del hero**: efecto máquina de escribir, cambio de color en las letras u otros efectos tipográficos.

---

## 5. Instrucciones sobre Assets

- El logo se encuentra en `imagenes/logo.jpeg` y **viene con fondo**: debes removerle el fondo antes de usarlo (exportarlo como PNG transparente).
- Al remover el fondo, recorta también la marca de agua **"Dola AI"** ubicada en la esquina inferior derecha del logo original; no debe quedar visible en el sitio.
- El resto de las imágenes de la carpeta `imagenes/` son fotografías reales de los tours (kayaks, canales, amaneceres con neblina, Isla de las Muñecas, zona de desayuno). Úsalas como material gráfico del sitio, optimizando/comprimiendo cada imagen para uso web antes de integrarlas.

---

## 6. Nota para el Desarrollador

Puedes iterar sobre el proyecto con Claude dándole instrucciones las veces que sea necesario hasta lograr el resultado deseado. Úsalo para ajustar branding, efectos, textos o cualquier detalle hasta que el sitio final cumpla con lo especificado en este brief.

---

## Checklist

- [ ] Remover el fondo del logo (`imagenes/logo.jpeg`) y recortar la marca de agua "Dola AI"; exportar como PNG transparente.
- [ ] Aplicar la paleta de colores definida en la sección 2 en todo el sitio.
- [ ] Aplicar las tipografías sugeridas (títulos y cuerpo de texto).
- [ ] Adaptar la plantilla base al negocio siguiendo el prompt inicial ya entregado, respetando su estructura de secciones.
- [ ] Cargar la información del negocio (nombre, teléfono, horarios, paquetes, precios, desayuno) en los espacios correspondientes de la plantilla.
- [ ] Implementar el preloader con spinner + logo.
- [ ] Implementar animaciones de scroll en el sitio.
- [ ] Implementar la animación del título del hero (máquina de escribir / cambio de color / efecto tipográfico).
- [ ] Verificar que el resultado final tenga un acabado premium, enterprise y minimalista tipo big tech.
- [ ] Optimizar y comprimir las imágenes de `imagenes/` antes de subirlas al sitio.
- [ ] Iterar con Claude las veces que sea necesario hasta lograr el resultado deseado.
