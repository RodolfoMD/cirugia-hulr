# SUMARIO COMPLETO DE LA SESIÓN — VIII Jornada Científica de Cirugía General

> Documento de contexto para retomar el trabajo en otra sesión / otro dispositivo.
> Última actualización: 25-nov-2026 (ver sección 16 para lo nuevo: pendón 80x120cm, 2 ponentes y 3 patrocinantes nuevos). Carpeta del proyecto: `C:\Users\Rodolfo\Documents\Flyer`
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
- 8:30 – 8:50 · Patología biliar aguda: ¿Qué hacer cuando no hay cirujano de guardia? · Dr. Francisco Salazar *(título corregido el 18-nov)*
- 8:55 – 9:15 · Manejo de la necrosis pancreática · Dr. Freddy Pereira
- 9:20 – 9:40 · Apendicitis aguda en el siglo XXI: actualización en diagnóstico, escalas de riesgo y manejo · Dr. Rafael González
- 9:40 – 10:00 · Sepsis en el paciente quirúrgico: de los criterios Sepsis-3 al manejo crítico en urgencias · Dra. Patricia Lucena
- 10:00 – 10:30 · **Receso** · Café y sesión de pósters

**Bloque 3 · Abordajes y escenarios de urgencia**
- 10:35 – 10:55 · Abordaje moderno en el área de flebología · Dr. Manuel Toquero
- 11:00 – 11:20 · Enterotomografía · Lic. Mariela Mejías
- 11:20 – 11:40 · Atención inicial del paciente quemado: desafíos terapéuticos de las primeras 24 horas · Dra. Yraida Peña
- 11:45 – 12:05 PM · Laparoscopia en el escenario de urgencia: indicaciones y límites · Dr. Eduardo Nunes
- 12:05 – 1:20 PM · **Receso** · Almuerzo

**Bloque 4 · Conferencia magistral, piso pélvico, urología y trauma** *(modificado hoy)*
- **1:30 – 1:55 PM · Conferencia Magistral · Dr. Francisco Zamora · (Virtual)** ← nueva, abre el bloque
- 1:55 – 2:15 PM · Geometría quirúrgica del piso pélvico: restauración funcional vs recurrencia · Dra. Judibeth Medina
- 2:15 – 2:40 PM · Urología dirigida al médico rural · Dr. José Carvajal *(el usuario confirmó el 18-nov que es **José**; su foto venía rotulada "Francisco Carvajal")*
- 2:40 – 3:15 PM · Trauma toracoabdominal penetrante vs cerrado: prioridades de tratamiento y oportunidad quirúrgica · Dr. Juan **Guzmán**
- 3:15 – 3:35 PM · **Código Quirúrgico: El Podcast de Cirugía** (conversatorio) · Dr. Díaz, Dr. Sotillo, Dra. Vásquez, Dr. Guzmán y Dra. Sara Zabala *(el 31-oct se dejó solo "Conversatorio"; después el usuario lo renombró a este título directamente en GitHub)*

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
- ~~Nombres sin tilde (Gonzalez, Mejias)~~ → **resuelto el 18-nov**: González y Mejías en landing, flyer del programa y Excel. Siguen como el usuario los escribió: Nunes, Judibeth, Yraida.
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
     4_Landing_Page\             index.html (= versión del repo), ponentes\ y patrocinantes\ (fotos/logos de la web),
                                 landing_para_subir_a_GitHub.zip (desactualizado), imágenes de pago/epónimo
     5_Invitacion_Trabajo_de_Grado\  Invitacion_General.png/.pdf, Personalizadas\ (36 invitaciones x PNG+PDF),
                                 Opciones_ubicacion_nombre\ (pruebas A/B/C del nombre)
     6_Ponentes\                 Flyer_General_Ponentes.png/.pdf, Individuales\ (14 flyers x PNG+PDF)
     7_Patrocinantes\            Flyer_General_Patrocinantes.png/.pdf, Individuales\ (7 flyers x PNG+PDF)
  2_EDITABLES\                   *_EDITABLE.pptx (3), Ponencia_datos_del_programa.xlsx, Enlaces_Canva_para_editar.txt,
                                 Invitacion_Trabajo_de_Grado\, Ponentes\, Patrocinantes\  (plantillas HTML + scripts, ver 11 a 13)
  Ponentes\  y  Patrocinantes\   (en la raíz) carpetas de ENTRADA donde el usuario deja fotos de ponentes / logos de patrocinantes
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

---

## 11. Invitación "Presentación de Trabajo de Grado" (sesión del 10–17 nov)

**Evento aparte de la jornada:** martes **17-nov-2026, 9:00 AM**, Hospital Universitario Dr. Luis Razetti, **piso 5, Sala de Conferencias de Ginecología y Obstetricia**. Presentación del trabajo de grado como requisito para el título de **CIRUJANO GENERAL**. (El usuario dijo "logo del audio" = logo de la UDO.)

- **Diseño final = "modelo B":** logos arriba (hospital · postgrado · UDO) + línea dorada; **nombre del invitado grande y centrado** (Playfair Display cursiva); debajo, sobre una **foto de quirófano translúcida**, "Nos complace invitarle a nuestra" / **PRESENTACIÓN DE TRABAJO DE GRADO** (blanco + dorado) / "Requisito para la obtención del título de CIRUJANO GENERAL"; abajo fecha, hora, lugar. Tipografía Montserrat. Mismo branding/colores de los flyers.
- **Plantilla y scripts:** `2_EDITABLES\Invitacion_Trabajo_de_Grado\` → `invitacion.html` (parámetros `?n=Nombre` y `&o=B|A|C|G`; sin nombre usa la versión general `G`), `generar_invitaciones.py [lista.txt]` (genera PNG 2382×3369 + PDF A4 en `1_PRODUCTOS_FINALES\5_Invitacion_Trabajo_de_Grado`), `nombres_adjuntos.txt` (**36 nombres**, uno por línea con su Dr./Dra./Lcda./Sr.). Respaldos de iteraciones: `_invitacion_v1…v3*.html`.
- **Salida:** `Invitacion_General.png/.pdf` y `Personalizadas\Invitacion_<Tratamiento>_<Nombre>.png/.pdf` (36×2). Una versión con la palabra "Adjuntos" se descartó (en `_archivo\invitaciones_descartadas`).
- **Para agregar a alguien:** añadir su línea a `nombres_adjuntos.txt` y generar solo ese (crear un txt temporal con esa línea y pasarlo al script).
- **Supuestos sin confirmar:** tratamientos puestos por el modelo cuando el usuario no los dio: *Dr. Yoel Hernández*, *Dra. María Mariño*, *Dr. Rafael Toirac*. Escritos tal cual: "Mariajose Chaguan", "Sr. Humberto Rodriguez" (sin tilde). Faltan en la invitación el **nombre del residente que presenta** y el **título del trabajo** (nunca se dieron).
- **Intento de subir el sumario a "Obsidian Vortex":** bóveda local `C:\Users\Rodolfo\Documents\Obsidian\Vortex`, remoto `https://github.com/rodolfomoreno95/obsidian-vortex.git` → GitHub respondió *Repository not found* con las credenciales guardadas (cuenta `RodolfoMD`). **No se subió nada.** Falta iniciar sesión con la cuenta `rodolfomoreno95` o confirmar la URL.

## 12. Ponentes: fotos, sección web y flyers (18-nov, ampliado 25-nov)

- **Entrada:** carpeta `Ponentes\` (15 fotos al 25-nov). Ponentes y orden del programa: Salazar, Pereira, R. González, Patricia Lucena, Toquero, Lcda. Mariela Mejías, **Dra. Zulmi Pineda** (cirujana plástica; **reemplaza a la Dra. Yraida Peña** con la misma ponencia, 11:20), E. Nunes, **Zamora (magistral, virtual; tema: "De la cirugía abierta a la cirugía sin huella: el presente y futuro del abordaje quirúrgico")**, Judibeth Medina, **José Carvajal**, J. Guzmán, J. Díaz, **Dr. Ali Sotillo** y **Dra. Estefany Vásquez** (estos tres últimos, solo en el conversatorio, 3:15 PM, mismo tema "Código Quirúrgico: El Podcast de Cirugía"). **El 23-nov el usuario retiró a la Dra. Sara Zabala** de todo (web, programa, flyers, identificadores); su foto y la de Yraida Peña se movieron a `_archivo\retirados_23nov\` (no se borraron). La lista de la invitación de trabajo de grado (evento del 17-nov, ya pasado) sí conserva a la Dra. Zabala como adjunta.
- **25-nov:** se agregaron fotos de Ali Sotillo y Estefany Vásquez (ambas circulares, igual tratamiento que Mejías: `rellenar_circulo` en `recortar_ponentes.py`, set `CIRCULARES`). Coordenadas de rostro: ali-sotillo (.53,.32,.18), estefany-vasquez (.51,.32,.17; cy subido a .32 para evitar la costura visible del relleno circular cerca del borde superior de la foto original). Se agregaron a `flyer_ponentes.html` (`SP`) con rol "Conversatorio" a las 3:15 PM. El flyer general pasó de 13 a 15 ponentes (layout 5-5-5, automático por los cortes fijos `slice(0,5)/slice(5,10)/slice(10)`). Flyers individuales: `Ponente_Ali_Sotillo` y `Ponente_Estefany_Vásquez`. Landing: tarjetas agregadas en `index.html` tras José Díaz, e imágenes 640×800 copiadas a `repo\ponentes\` y a `4_Landing_Page\ponentes\`.
- **Recorte uniforme:** `2_EDITABLES\Ponentes\recortar_ponentes.py` → `recortes\<slug>.jpg` de **1000×1250 (4:5)**, centrado en el rostro (coordenadas manuales por foto; OpenCV 5 no trae Haar), leve ajuste azul. Casos especiales: foto circular de Mejías (se rellenan las esquinas), rótulo de Instagram de Yraida Peña (se recorta por arriba), Carvajal (cofia cortada en la foto original). Fotos de baja resolución: Pereira, Salazar, Guzmán.
- **Landing:** sección `id="ponentes"` entre Programa y Entradas (tarjetas 4:5 con hora, nombre y tema; Zamora con borde dorado y etiqueta "Magistral · Virtual"; 4/3/2 columnas según ancho). Imágenes en el repo: `ponentes\<slug>.jpg` (640×800). Enlaces nuevos en el menú: **Ponentes** y **Patrocinantes**; el menú pasa a hamburguesa por debajo de **1100 px** y los enlaces no se parten (`white-space:nowrap`).
- **Flyers:** `2_EDITABLES\Ponentes\flyer_ponentes.html` + `generar_flyers_ponentes.py [slug]` → `1_PRODUCTOS_FINALES\6_Ponentes\`: **flyer general** (14 fotos en filas 5-5-4, QR) y **14 individuales** (foto grande con marco dorado, "DR./DRA./LCDA." dorado y nombre blanco del mismo tamaño, título completo de la ponencia, hora propia, lugar, QR). Zamora = "Conferencista magistral" + etiqueta Virtual; Díaz y Zabala = "Conversatorio".
- **Centrado verificado midiendo píxeles:** desvío máximo 1,8 px sobre 794 (la primera versión tenía el marco corrido 7 px, y lugar/pie corridos por reservar espacio al QR).

## 13. Patrocinantes (18-nov, ampliado 25-nov)

- **Actualización 23-nov: ya son 14 patrocinantes.** Se sumaron Arco Iris Laboratorio, Kalua Meds (fondo negro, modo full), Kaoe (logo circular; se rellenan de blanco las esquinas grises con `circle_white`), Talleres F1, Teje tu Logo, Tiares y Vitaozono. El flyer general con 14 reparte las tarjetas en 4 filas (4-4-3-3, tarjetas de 136 px); la fórmula de tamaño es: 1 fila 250, 2 filas 220, 3 filas 176, 4 filas 136.
- **Actualización 25-nov: ya son 17 patrocinantes.** Se sumaron Crearte (logo png con alpha, `trim_alpha`, pad), IQMED Suministros (idem) y Dra. María Fernanda Mariño (logo-firma jpg fondo blanco, `trim_white`, pad). **Bug encontrado y corregido:** con 17 patrocinantes el grid necesitaba 5 filas y se desbordaba sobre el texto de fecha/lugar (el código solo contemplaba hasta 4 filas). Fix en `flyer_patrocinantes.html`: `per = n<=9?3:(n<=16?4:5)` (antes `n<=9?3:4`), así con >16 patrocinantes usa 5 columnas y se mantiene en 4 filas (136 px) en vez de generar una 5ª fila. Si se agregan más patrocinantes en el futuro, revisar que las filas resultantes de `Math.ceil(n/per)` sigan cabiendo en el `g-grid` (650 px de alto).
- **Entrada:** carpeta `Patrocinantes\` (raíz del proyecto). Al 21-nov había **7 patrocinantes**: Fundación Creando mi Vida, Dra. María Elizabeth Brito (Medicina y Cirugía, logo "MEB"), JJAS Gorros, Megalabs, Punto Rosa Dream Shop, Servicio de Urología Dr. Yoel Hernández (Complejo Hospitalario Universitario Dr. Luis Razetti) y Tecno Asfaltos de Oriente. (Esto confirma que el Dr. Yoel Hernández es urólogo del Razetti.)
- **Preparación de logos:** `2_EDITABLES\Patrocinantes\preparar_logos.py` → `logos\<slug>.(jpg|png)`. Cada logo se recorta según su tipo: modo **pad** (logo sobre tarjeta blanca, se recorta el blanco sobrante) o **full** (la imagen llena toda la tarjeta; usado en Brito y Punto Rosa por tener fondo propio). Para uno nuevo, añadir su entrada en el diccionario `LOGOS` del script.
- **Flyers:** `2_EDITABLES\Patrocinantes\flyer_patrocinantes.html` (lista `SPON = [slug, nombre, extensión, modo]` dentro del archivo) + `generar_flyers_patrocinantes.py [slug] [--general]` → `1_PRODUCTOS_FINALES\7_Patrocinantes\` (**7 individuales PNG+PDF y el flyer general**). A pedido del usuario los flyers **no llevan el nombre escrito ni "Gracias por acompañar…"**: solo "PATROCINANTE" (individual) o "NUESTROS PATROCINANTES" (general), logos en tarjetas, fecha/lugar y QR. El general reparte las tarjetas automáticamente en filas equilibradas (7 → 3-2-2, tarjetas de 176 px; el tamaño se ajusta según el número).
- **Landing:** sección `id="patrocinantes"` con las 7 tarjetas (logo + nombre debajo y frase "Gracias a quienes hacen posible esta jornada"; imágenes en el repo `patrocinantes\<slug>.(jpg|png)`; las de modo full llevan la clase `.spn.full`). Aquí **sí** se conserva el nombre bajo el logo.
- **Para agregar un patrocinante:** dejar el logo en `Patrocinantes\` → añadirlo a `LOGOS` en `preparar_logos.py` y correrlo → añadir `["slug","Nombre","ext","pad|full"]` a `SPON` → correr `generar_flyers_patrocinantes.py --general` → copiar el logo a `repo\patrocinantes\` (≤800 px) y añadir su `<article class="spn [full] rv">` en `index.html` → push. Se copia también `index.html` y `patrocinantes\` a `1_PRODUCTOS_FINALES\4_Landing_Page`.
- **Pendiente:** el archivo de Tecno Asfaltos es un **afiche de baja resolución (438×620)**, no un logo suelto; se ve pequeño/borroso. Pedir el logo original.

## 14. Estado de GitHub y pendientes (18-nov)

- Commits de la sesión en `main`: `f65e518` (sección Ponentes), `c2c0970` (José Carvajal, tildes, Patrocinantes, menú), `76ea074` (título de Salazar), `44fedfb` (sumario 18-nov), `5632f8f` (6 patrocinantes nuevos), más el de esta actualización del sumario. Un `git push` llegó a tardar más de 2 min por el *credential manager*; si se cuelga, revisar si hay una ventana de inicio de sesión de GitHub abierta.
- **Programa:** flyer de Canva (`DAHYMGv0A14`), Excel y landing quedaron sincronizados el 18-nov (título de Salazar con ¿?, González, Mejías, José Carvajal). Versiones anteriores en `_archivo\versiones_anteriores\programa` y `\excel`.
- **Pendiente de confirmar con el usuario:** tratamientos supuestos (Yoel, María Mariño, Rafael Toirac); "Rodriguez"/"Mariajose"; datos del residente y título del trabajo de grado (invitación); si la tarjeta web del patrocinante debe perder también el nombre/la frase de gracias; credenciales para Obsidian Vortex; mejores fotos de Pereira/Salazar/Guzmán; los puntos de la sección 5 que seguían abiertos (Zamora virtual, conteo "14 ponentes", fin del `.ics`, logo 1963–2007).
- **Trampas nuevas:** `<img height=…>` rompe `aspect-ratio` (usar `height:auto`); el `letter-spacing` deja espacio al final y descentra (compensar con `padding-left`); `text-wrap:balance` evita palabras sueltas; en Python con `re.sub` los `\u` del reemplazo fallan (usar `str.replace`); `python -I` aísla el entorno (OpenCV 5.0 no trae `CascadeClassifier`); los heredocs con comillas/backticks fallan en Git Bash → crear los archivos con la herramienta de escritura; `/tmp` de Git Bash no es el mismo que ve Python en Windows.

## 15. Identificadores / gafetes (22–23 nov)

- **Medida:** **8 cm de ancho × 11 cm de alto**, vertical (el usuario dijo "11 por 8"; se interpretó vertical para colgar del cuello. Confirmar si quería horizontal). Diseño en 378×519 px reducido a 303×416 px (80×110 mm a 96 dpi).
- **Categorías:** **Participante** (franja azul), **Comité Organizador** (blanca), **Protocolo** (azul claro): solo el rol en una franja fina al centro, **sin tabla de nombre**; **Ponente** (franja dorada): **personalizado** con el nombre impreso en una tarjeta clara (Dr./Dra./Lcda. en dorado arriba, nombre en una sola línea con ajuste automático). Franja del rol centrada entre el texto de arriba y la fecha (huecos medidos 48/49 px); margen superior mayor para la perforación (ranura punteada de guía).
- **Plantilla y scripts:** `2_EDITABLES\Identificadores\` → `identificador.html` (parámetros `?c=participante|comite|protocolo|ponente`, `&n=Nombre` o varios con `|`, `&sheet=1` hoja A4, `&tab=1` pliego tabloide), `ponentes.txt` (13 nombres), `generar_identificadores.py` (`--solo-roles`, `--solo-ponentes`, `--lista otros.txt`, `--tabloide`).
- **Salidas** (`1_PRODUCTOS_FINALES\8_Identificadores\`): `Individuales\` (3 roles, PNG+PDF), `Ponentes_personalizados\` (13), `Hojas_A4_para_imprimir\` (4 por hoja con marcas de corte; ponentes en hojas de 4 distintos) y **`Tabloide_32x47cm\`**: pliegos de **32×47 cm con 16 identificadores (4×4) pegados sin espacio y líneas punteadas de corte** (usa 32×44 cm; quedan 1,5 cm arriba y abajo; horizontalmente ocupa los 32 cm completos, hace falta impresión sin márgenes). Un PDF por categoría y `Tabloide_TODOS.pdf` (4 páginas). El pliego de ponentes lleva los 13 y 3 casillas vacías.
- **Trampas:** Chrome headless no baja de ~500 px de ancho (se captura grande y se recorta); `print-to-pdf` respeta `@page size`; el PDF de una tarjeta de 80×110 mm necesita `html,body` 1 px más chicos para no generar 2ª página.

## 16. Pendón de la Pantalla de Entrada y ampliación de ponentes/patrocinantes (25-nov)

- **Pendón 80×120 cm:** a partir del diseño Canva de la Pantalla de Entrada (`DAHYMKCHdqU`) se usó `resize-design` (tipo `custom`) para crear una versión en formato pendón vertical. **Importante:** Canva exporta el PDF asumiendo **96 px/pulgada** sin importar el DPI "pensado" al pedir el tamaño custom — pedir el tamaño en píxeles a 100 dpi (3150×4724) da un PDF de ~83×125 cm, no 80×120. Para que el PDF imprima al tamaño físico exacto hay que calcular los píxeles a **96 dpi**: 80 cm × 96/2.54 ≈ **3024 px**, 120 cm × 96/2.54 ≈ **4536 px** (conserva la razón 2:3). Con esas dimensiones el PDF exportado dio 80.01×120.015 cm (prácticamente exacto). El `resize-design` también tiene un límite de área máxima (un pedido a 150 dpi, área ~33M px², fue rechazado con "above the maximum allowed area"; a 100 dpi, área ~14,9M px² sí lo aceptó, y el de 96 dpi final, ~13,7M px², también).
  - Diseño final: `DAHb8dUyN90` (edit: https://www.canva.com/d/t_KJaAy-PrS-LM6). El reflow automático de Canva quedó bien sin necesidad de ajustes manuales (la razón de aspecto pasó de 1:1.414 "A4" a 1:1.5, un cambio moderado). Se verificó el QR con OpenCV en el PNG y en el PDF (renderizado con pymupdf a 150 dpi) — ambos decodifican correctamente a la landing.
  - **Salida:** `1_PRODUCTOS_FINALES\2_Pantalla_de_Entrada\Banner_80x120cm\Pantalla_de_Entrada_Banner_80x120cm.png` (3024×4536 px) y `.pdf` (80×120 cm exactos).
  - Nota: `resize-design` devolvió `"uses_remaining":0` en el segundo intento (posible límite de prueba/cuota de la cuenta Canva para esta operación) — si en el futuro falla con un error de cuota, puede ser necesario upgrade o esperar a que se restablezca.
- **Ponentes y patrocinantes nuevos:** ver secciones 12 y 13 (Dr. Ali Sotillo, Dra. Estefany Vásquez; Crearte, IQMED Suministros, Dra. María Fernanda Mariño). Flujo seguido: `recortar_ponentes.py` / `preparar_logos.py` → `generar_flyers_ponentes.py` / `generar_flyers_patrocinantes.py --general` → copiar imágenes 640×800 (ponentes) o ≤800 px (patrocinantes) a `repo\ponentes\` / `repo\patrocinantes\` → añadir tarjetas en `index.html` → copiar `index.html` y ambas carpetas de imágenes a `4_Landing_Page\` → regenerar `landing_para_subir_a_GitHub.zip` → commit + push.
- **Commit de hoy:** `6888e61` en `main` ("Agregar 2 ponentes... y 3 patrocinantes... a la landing"), verificado en vivo en https://rodolfomd.github.io/cirugia-hulr/.
- **Pendiente / no tocado hoy:** el pilar de la landing sigue diciendo "14 ponentes y conversatorio final" (ya desactualizado antes de hoy, ver sección 5; ahora son 15 ponentes + el conversatorio ya incluye 3 personas con flyer propio). El usuario no pidió corregir ese conteo.
