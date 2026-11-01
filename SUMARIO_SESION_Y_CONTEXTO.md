# SUMARIO COMPLETO DE LA SESIÓN — VIII Jornada Científica de Cirugía General

> Documento de contexto para retomar el trabajo en otra sesión / otro dispositivo.
> Última actualización: 31-oct-2026. Carpeta del proyecto: `C:\Users\Rodolfo\Documents\Flyer`
> Idioma de trabajo con el usuario: **español (Venezuela)**. Trato: directo, sin rodeos.

---

## 1. Qué es el proyecto (datos del evento)

| Dato | Valor |
|---|---|
| Nombre | **VIII Jornada Científica de Cirugía General** (VIII = octava, en números romanos) |
| Lema | **Cirugía General a 360º: Actualización y emergencias** |
| Epónimo | **Dr. Hernán Malave** (en la landing y el programa se escribe **Malavé**; en los flyers de portada quedó "Malave") |
| Fecha / hora | **Viernes 27 de noviembre de 2026, 8:00 AM** (horarios de Venezuela, UTC−4) |
| Lugar | **Salón de Conferencias We Talks, Lechería** (estado Anzoátegui). Ojo: se dijo primero "Weeds", luego el usuario corrigió: es **"We Talks"** |
| Organizan | Postgrado de Cirugía General · Hospital Universitario Dr. Luis Razetti (HULR, Barcelona-Anzoátegui) · Universidad de Oriente (UDO) |
| Contacto (CORRECTO) | **+58 424-834.93.35** (el número inicial +58 412-088.09.80 estaba mal para contacto; ya corregido en todo) |
| Inscripción | Formulario de Google: https://forms.gle/x7qseUa7ZdxBJ8GG6 (datos, categoría y comprobante de pago) |
| Entradas | Estudiantes y médicos generales **$20**; Especialistas **$25** (en bolívares se paga en euros a tasa BCV: €20 / €25; ver landing) |
| **Landing pública** | **https://rodolfomd.github.io/cirugia-hulr/** (GitHub Pages, repo `RodolfoMD/cirugia-hulr`, rama `main`, archivo `index.html`). Antes estuvo en Netlify (`cirugia-hulr.netlify.app`), ya NO se usa |

Nota de datos: el Excel original (`Ponencia.xlsx`, hoja 2) decía "VII Jornada"; el usuario indicó que es **VIII** y así se usa en todo.

---

## 2. Cronología resumida de lo que se hizo

1. **Punto de partida:** imagen `Gemini_Generated_Image_...jpg` con 3 propuestas de flyer. El usuario eligió el **tercero (el de la derecha)**: fondo azul marino, banda superior azul, título blanco, franja dorada de fecha, sesiones, botón dorado, QR, banda inferior.
2. **Intento fallido 1:** teoría de color "complementario dividido" con color principal **#003B85** (matiz 213°, complemento 33°, divididos ≈ 3° `#E64137` y 63° `#E2E83A`). Al usuario no le gustó ("muy feo"). **Se descartó.** No volver a esa paleta.
3. **Se pidió fidelidad total al flyer original** → reconstrucción en HTML y luego en **PowerPoint editable** (pptxgenjs) con los colores originales. Se usó Arial Narrow.
4. **Flyer "tipo Canva", más minimalista** con título VIII, epónimo, logos, lugar, fecha, hueco para imagen. El usuario dijo que **no era igual al ejemplo** → se volvió a la distribución del flyer original (banda azul con logos, círculo con VIII, título 3 líneas, franja dorada, etc.).
5. **Logos:** se buscaron en las presentaciones de `Documents\Gene` y `Documents\HULR` (extrayendo `ppt/media`). Se limpió el fondo blanco y se amplió. **Error corregido:** el logo del postgrado hallado era de otra institución ("IVSS Dr. Domingo Guzmán Lander"); el usuario aportó el correcto: **`Logo Cirugia General.jpg`** (sello "Hospital Universitario Dr. Luis Razetti · Postgrado de Cirugía · Universidad de Oriente"). Logo del hospital: escudo H.U.L.R. (dice "1963–2007"; en otras diapositivas aparece "1963–2001" → el usuario no confirmó cuál es el correcto). Logo UDO: sello de 1200 px, transparente.
6. **Diseño final en Canva** (conector Canva MCP): se generó con `create-design` (A4 vertical) una versión con foto de quirófano generada por Canva, y se fue ajustando con `edit-design`: logos reales, epónimo, lugar "We Talks", se quitó el cuadro de los logos y el bloque "Organiza…", se añadió **"CIRUGÍA GENERAL A 360º / ACTUALIZACIÓN Y EMERGENCIAS"** (dorado y blanco), teléfono, y un **QR** en la esquina inferior derecha. El usuario dijo "el flyer está perfecto".
7. **Tres flyers finales** (todos en Canva, A4 vertical 794×1123 px):
   - **Flyer principal** (con contacto).
   - **Pantalla de entrada** (copia del principal sin el bloque de contacto; para pantalla vertical en la puerta; conserva el QR).
   - **Programa de la jornada** (mismo branding, con los 4 bloques y horarios desde el Excel).
8. **Landing page** responsive (HTML único con logos embebidos en base64): hero con cuenta regresiva, logos, "sobre la jornada", programa por pestañas, entradas, métodos de pago, lugar/contacto, WhatsApp, botón "añadir al calendario" (.ics), botón flotante en móvil.
9. **Hosting:** primero Netlify; luego el usuario migró a **GitHub Pages**. Los QR de los flyers se regeneraron para apuntar a la nueva URL.
10. **Sesión paralela (20-oct, hecha por el usuario, commits en GitHub):** añadió métodos de pago (Pago móvil, Binance, efectivo, QR), sección del epónimo, ajustó tarifas y programa, corrigió acentos/apellidos (Nunes, Malavé) y cambió "Palabras de apertura" a cargo del Comité Organizador. **La landing del repo es la fuente de verdad más reciente.**
11. **Correcciones de hoy (31-oct)** — ver sección 5.

---

## 3. Sistema de diseño (branding) — NO modificar

- **Colores (originales del flyer elegido):**
  - Azul marino de fondo `#0A2C56`; azul oscuro del círculo `#012245`; azul de bandas `#125CA5`
  - Dorado `#D39A29` / `#E8A817` / `#D6A53C`; azul claro de apoyo `#9DB8DA`; blanco `#FFFFFF`
- **Tipografías:** en Canva las que asigna el diseño (sans tipo Roboto / condensada para el VIII). En PowerPoint/HTML: Arial Narrow; la landing usa Barlow Condensed + Inter.
- **Distribución del flyer principal (Canva, px sobre 794×1123):**
  - Logos en franja superior: hospital (100,32,120×120), postgrado (318,32,158×120), UDO (558,32,120×120) y dos separadores finos.
  - "VIII" grande a la izquierda; título "Jornada Científica de Cirugía General" a la derecha.
  - Epónimo, fecha/hora (dorado), lugar, foto de quirófano en el centro-inferior con curvas azules/doradas, titular dorado "CIRUGÍA GENERAL A 360º", subtítulo blanco, línea dorada, "Contacto: …".
  - **QR** inferior derecho: 132×132 en (634, 960) en principal y entrada. En el **programa**: 76×76 en (682, 1040).
- **Regla del usuario:** *"solo modifica lo que te pido, sin alterar distribución ni nada más"*. Respetarla estrictamente.

---

## 4. Identificadores y llaves técnicas

**Canva (diseños)** — página única `PBPy3tSvtdL3wWTC`:
| Diseño | design_id | Enlace de edición |
|---|---|---|
| Flyer principal | `DAHYL_py22E` | https://canva.link/995qivuio5n0iq5 |
| Pantalla de entrada | `DAHYMKCHdqU` | https://www.canva.com/d/cn4HME_6a1tXNFp |
| Programa | `DAHYMGv0A14` | https://www.canva.com/d/TRpoEua2PH6DsQH |

**Assets subidos a Canva:** logo hospital `MAHYMOi9fXU` · logo postgrado `MAHYMFyuglA` · logo UDO `MAHYMHifPrQ` · QR actual (GitHub Pages) `MAHYj5M1pHc` · QR formulario (viejo) `MAHYMFI6TIA` · QR Netlify (viejo) `MAHYMdDZmAc`.

**Elementos clave (locator = `PBPy3tSvtdL3wWTC-<id>`):** teléfono del principal `LBpVFlHMkBBLjqvF` · epónimo `LB4g8j9qbLSBBbXK` · fecha `LBn5L0zcZbNHgDYf` · lugar `LBBvbsLN5GFwzBvc` · titular `LBq6Sh2zc6KVzwVP` · subtítulo `LBFkPT2Mhfjz7r00`. (Los ids de QR cambian cada vez que se reemplaza: leerlos con `read-design` antes de editar.)

**GitHub:** repo https://github.com/RodolfoMD/cirugia-hulr (redirige desde `rodolfomd`), commits con identidad `RodolfoMD <143008647+RodolfoMD@users.noreply.github.com>`. `git push` desde esta máquina **funciona** con las credenciales guardadas (el conector GitHub MCP falló; `gh` no está instalado).

---

## 5. Programa final (fuente: landing publicada + correcciones del 31-oct)

**Bloque 1 · Apertura e inauguración**
- 7:30 – 8:00 AM · Acreditación y entrega de material a los participantes · Protocolo
- 8:00 – 8:15 AM · Palabras de apertura · Comité Organizador
- 8:15 – 8:30 AM · Semblanza y homenaje institucional al Dr. Hernán Malavé · Comité Organizador *(se quitó "In Memoriam")*

**Bloque 2 · Urgencias abdominales y sepsis**
- 8:30 – 8:50 · Patología biliar aguda: qué hacer cuando no hay cirujano de guardia · Dr. Francisco Salazar
- 8:55 – 9:15 · Manejo de la necrosis pancreática · Dr. Freddy Pereira
- 9:20 – 9:40 · Apendicitis aguda en el siglo XXI: actualización en diagnóstico, escalas de riesgo y manejo · Dr. Rafael Gonzalez
- 9:40 – 10:00 · Sepsis en el paciente quirúrgico: de los criterios Sepsis-3 al manejo crítico en urgencias · Dra. Patricia Lucena
- 10:00 – 10:30 · **Receso** · Café y sesión de pósters

**Bloque 3 · Abordajes y escenarios de urgencia**
- 10:35 – 10:55 · Abordaje moderno en el área de flebología · Dr. Manuel Toquero
- 11:00 – 11:20 · Enterotomografía · Lic. Mariela Mejias
- 11:20 – 11:40 · Atención inicial del paciente quemado: desafíos terapéuticos de las primeras 24 horas · Dra. Yraida Peña
- 11:45 – 12:05 PM · Laparoscopia en el escenario de urgencia: indicaciones y límites · Dr. Eduardo Nunes
- 12:05 – 1:20 PM · **Receso** · Almuerzo

**Bloque 4 · Conferencia magistral, piso pélvico, urología y trauma** *(modificado hoy)*
- **1:30 – 1:55 PM · Conferencia Magistral · Dr. Francisco Zamora · (Virtual)** ← nueva, abre el bloque
- 1:55 – 2:15 PM · Geometría quirúrgica del piso pélvico: restauración funcional vs recurrencia · Dra. Judibeth Medina
- 2:15 – 2:40 PM · Urología dirigida al médico rural · Dr. José Carvajal
- 2:40 – 3:15 PM · Trauma toracoabdominal penetrante vs cerrado: prioridades de tratamiento y oportunidad quirúrgica · Dr. Juan **Guzmán**
- 3:15 – 3:35 PM · **Conversatorio** · Dres. Díaz, Sotillo, Vásquez, Guzmán y **Dra. Sara Zabala** *(se quitó el título "Podcast de cirujanos de la San José")*

### Correcciones pedidas el 31-oct y cómo se resolvieron
1. **Acento en Guzmán** → aplicado en flyer de programa y landing (todas las apariciones).
2. **Conversatorio** → solo "Conversatorio"; se añadió a la Dra. Sara Zabala.
3. **Conferencia Magistral (Francisco Zamora)** primero en el último bloque, después del almuerzo.
4. **"In Memoriam"** → ya no aparece en ningún sitio.
5. **Verificación de horas (continuidad):** al quitarse participantes del último bloque, los horarios habían quedado compactados (terminaban 3:10 PM). Al insertar la Magistral (25 min, igual que su espacio original en el Excel) **se recorrieron los siguientes sin huecos conservando las duraciones originales** (20, 25, 35, 20 min): el programa ahora termina **3:35 PM**. Se comprobó automáticamente sobre la página publicada: 18 filas, sin solapes ni huecos mayores de 10 min (los huecos de 5 min entre charlas del mismo bloque son cambios de ponente).
6. **Subida a GitHub (push)** → commit `ae23339` en `main`; la web pública ya muestra los cambios.

### Pendientes / cosas a confirmar con el usuario
- Si "Francisco Zamora · Virtual" debe seguir marcado como virtual (venía del Excel).
- El pilar de la landing dice **"14 ponentes y conversatorio final"**; tras sumar a Zamora y a la Dra. Zabala quizá cambie el conteo (no se tocó).
- El archivo `.ics` ("añadir al calendario") termina a las **4:00 PM**; el programa ahora termina 3:35 PM.
- No hay "Palabras de cierre" (estaban en el primer Excel, 3:40–4:00); no se agregaron.
- Logo del hospital: ¿"1963–2007" o "1963–2001"?
- Nombres tal como están en la landing/Excel (Gonzalez, Mejias, Nunes, Judibeth, Yraida); no se "corrigieron" por cuenta propia.
- En la sección de pagos de la landing el **teléfono de Pago Móvil (04120880980)** es distinto del de contacto; confirmar que sea el de la cuenta de pago.
- Los datos de pago (cédula, Binance, etc.) viven solo en la landing; **no se copian en este documento**.

---

## 6. Carpeta del proyecto (organización actual)

```
Flyer\
  1_PRODUCTOS_FINALES\
     1_Flyer_Principal\          Flyer_Principal.png / .pdf
     2_Pantalla_de_Entrada\      Pantalla_de_Entrada.png / .pdf
     3_Programa_de_la_Jornada\   Programa_de_la_Jornada.png / .pdf
     4_Landing_Page\             index.html (= versión del repo), landing_para_subir_a_GitHub.zip,
                                 imágenes de pago/epónimo del trabajo paralelo
  2_EDITABLES\                   *_EDITABLE.pptx (3), Ponencia_datos_del_programa.xlsx, Enlaces_Canva_para_editar.txt
  3_LOGOS_Y_QR\                  logos limpios (png), Logo_Postgrado_ORIGINAL.jpg, QR_Landing_rodolfomd.github.io-cirugia-hulr.png
  _archivo\                      versiones anteriores y trabajo (no se borró nada)
     pruebas_y_trabajo\gh\repo   clon local del repositorio de GitHub
  SUMARIO_SESION_Y_CONTEXTO.md   este documento
```
Exportes de Canva: PNG 2480×3507 ("pro"), PDF A4, PPTX. Los `.pptx` salen de Canva (no se revisaron abriéndolos en PowerPoint).

---

## 7. QR (cómo se hacen y se comprueban)

- URL actual de los QR: **https://rodolfomd.github.io/cirugia-hulr/**
- Generación: Python `qrcode` (versión 3, corrección M, borde 3 módulos, color `#0A2C56` sobre blanco, esquinas redondeadas). Subir a Canva con `create-upload-url` + `curl -X POST --data-binary` (Content-Type `application/octet-stream`) → devuelve `mediaId`.
- **Siempre** reemplazar el QR con `delete_element` + `insert_fill` (no con `resize_element`).
- **Siempre verificar** escaneando el PNG **y el PDF** exportados con OpenCV (`cv2.QRCodeDetector`) y comprobar que se vea completo.

---

## 8. Lecciones técnicas (trampas conocidas)

**Canva (herramientas MCP):**
- `format_text.font_size` solo acepta **enteros**.
- `resize_element` sobre una imagen ya colocada deja el recorte interno → el QR salía cortado (pasó en el programa). Usar borrar + insertar.
- Cada edición exige abrir transacción (`read-design` con `open_transaction`), editar (`keep_open`) y **commit**. Los ids de elementos nuevos se leen de la respuesta.
- `add_text` no permite formato: se añade y luego se formatea con `format_text`.
- La respuesta de `edit-design` es enorme; usarla solo para verificar la miniatura.
- Exportar con `export-design` (png `width:2480`, pdf `size:a4`, pptx) y descargar con `curl` (URL firmada y temporal).
- El plugin `plugin:canva:canva` pide autorización aparte; el conector usado fue el MCP `a3f34ba9…`. Canva **no** acepta logos en `create-design` (hay que subir assets y usar `insert_fill`).

**Entorno (Windows 11, Git Bash / PowerShell):**
- Sin LibreOffice ni `pdftoppm`. Para previsualizar PPTX se usó PowerPoint por COM (`Slides(1).Export`). PDFs se renderizan con `pymupdf`.
- Chrome headless (`C:\Program Files\Google\Chrome\Application\chrome.exe`) tiene **ancho mínimo ~500 px**: para probar móvil se usó un `<iframe>` de 390 px.
- Los textos con acentos pasados por stdin a Python en Windows se corrompen: usar secuencias `\u00e1` o archivos UTF-8.
- Paquetes instalados: `qrcode`, `opencv-python-headless`, `pymupdf`, `openpyxl`, `scipy`, `pillow`; en `_archivo\pruebas_y_trabajo\pptx_build`: `pptxgenjs`, `sharp`, `react-icons`.
- `git` funciona; `gh` no está.

**Datos:** el Excel `Ponencia.xlsx` (Hoja2) tenía temas "falta" y erratas ("Geomaetria", "Postcad"); la landing del repo ya los tiene corregidos por el usuario.

---

## 9. Preferencias y reglas del usuario (importante)

1. **Cambiar solo lo pedido.** Si dice "no alteres nada más", no mover posiciones, tamaños ni estilos.
2. **Verificar antes de dar por hecho** (QR escaneado, horas continuas, texto sin errores) y reportar con honestidad lo que no se pudo comprobar.
3. **Mantener el estilo/branding** del flyer original; resultado "profesional, minimalista, llamativo".
4. **Todo editable** y **productos finales ordenados** y fáciles de encontrar; no borrar versiones antiguas (van a `_archivo`).
5. "Hacer el pull" = **subir (push) los cambios a GitHub** para que se actualice la web.
6. Prefiere explicaciones concisas, en español, con lo que tiene que decidir o revisar al final.

---

## 10. Cómo retomar rápido (recetas)

- **Cambiar texto de un flyer:** `read-design` (abrir transacción) → `edit-design` con `replace_text`/`find_and_replace_text` → commit → exportar PNG/PDF/PPTX → descargar a `1_PRODUCTOS_FINALES` y `2_EDITABLES`.
- **Cambiar el QR:** generar PNG → subir → borrar el elemento QR viejo e insertar el nuevo en el mismo (left, top, tamaño) → exportar → escanear PNG y PDF.
- **Actualizar la web:** editar `_archivo\pruebas_y_trabajo\gh\repo\index.html` (o clonar de nuevo el repo) → `git add/commit/push origin main` → esperar ~1 min y comprobar con `curl` en https://rodolfomd.github.io/cirugia-hulr/ → copiar el `index.html` a `1_PRODUCTOS_FINALES\4_Landing_Page` y regenerar el zip.
- **Cambiar el teléfono de contacto:** flyer principal (elemento `LBpVFlHMkBBLjqvF`), y en la landing 3 sitios (texto, `tel:+584248349335`, `wa.me/584248349335`). El flyer de entrada y el programa no muestran teléfono.
