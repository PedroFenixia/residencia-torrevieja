# Campaña Meta Ads — Centro Mayores Mar Bella (Noruega)

> Documento interno de estrategia. Toda la publicidad se publica en **noruego (bokmål)**.
> Presupuesto total estimado: **600 €/mes** (15 € + 5 € diarios).

---

## 1. Configuración de página y cuentas

### Facebook Page

1. Crear página de Facebook:
   - **Nombre:** Centro Mayores Mar Bella
   - **Categoría principal:** "Nursing Home" (Residencia de ancianos)
   - **Categoría secundaria:** "Senior Living" (Vida para mayores)
   - **Nombre de usuario:** @centromayoresmarbella
   - **Foto de perfil:** Logo o fachada cercana (`fachadacerca-hd.jpg`)
   - **Foto de portada:** Amanecer con fachada (`amanecer-hd.jpg`)
   - **Bio:** "Luksus eldresenter ved Middelhavet i Torrevieja, Spania. 30+ års erfaring. Norske beboere velkommen. 🌊☀️"
   - **Datos de contacto:** Teléfono, email, web, dirección completa
   - **CTA button:** "Kontakt oss" → enlace a WhatsApp

### Instagram

1. Crear cuenta de Instagram:
   - **Usuario:** @centromayoresmarbella
   - **Nombre mostrado:** Mar Bella | Eldresenter Spania
   - **Bio:** "Luksus eldresenter ved havet 🌊 Torrevieja, Spania 🇪🇸 30+ år ✨ Norske beboere velkommen 🇳🇴 ⬇️ Bestill omvisning"
   - **Link en bio:** marbellacarehome.com/no.html
   - **Foto de perfil:** Misma que Facebook

### Meta Business Suite

1. Ir a [business.facebook.com](https://business.facebook.com)
2. Crear cuenta de Meta Business (si no existe)
3. Agregar la página de Facebook recién creada
4. Conectar la cuenta de Instagram
5. Agregar método de pago (tarjeta de crédito/débito)
6. Verificar dominio `marbellacarehome.com` en Configuración del negocio → Seguridad de marca → Dominios
7. Instalar el píxel de Meta en la web (para retargeting futuro)

---

## 2. Estructura de campañas

### CAMPAÑA 1: Generación de Leads

| Parámetro | Valor |
|-----------|-------|
| **Nombre** | `NO_Leads_Eldresenter_2024` |
| **Objetivo** | Leads (Generación de contactos potenciales) |
| **Presupuesto** | 15 €/día (≈ 450 €/mes) |
| **Duración** | Continua, optimizar semanalmente |
| **Optimización** | Maximizar número de leads |

#### Conjunto de anuncios A: Hijos (40-65 años)

- **Nombre:** `NO_Leads_Hijos_40-65`
- **Ubicación:** Noruega (todo el país)
- **Edad:** 40-65 años
- **Género:** Todos
- **Idioma:** Noruego
- **Intereses (combinar con OR):**
  - España, Costa Blanca, Torrevieja, Alicante
  - Pensjon (pensión), pensjonsalder
  - Eldreomsorg (cuidado de mayores), sykehjem (residencia)
  - "Moving abroad", "Retirement abroad"
  - Norsk i Spania, nordmenn i utlandet
- **Exclusiones:** Personas que ya han enviado el formulario
- **Ubicaciones (placements):** Facebook Feed, Instagram Feed, Instagram Stories
- **Presupuesto:** 10 €/día

#### Conjunto de anuncios B: Mayores (65+)

- **Nombre:** `NO_Leads_Eldre_65+`
- **Ubicación:** Noruega (todo el país)
- **Edad:** 65+
- **Género:** Todos
- **Idioma:** Noruego
- **Intereses:**
  - España, sol, Middelhavet (Mediterráneo)
  - Pensjonisttilværelse (vida de jubilado)
  - Torrevieja, Costa Blanca, Alicante
  - Reise (viajes), overvintre i Spania (invernar en España)
- **Ubicaciones:** Facebook Feed (prioritario para este grupo)
- **Presupuesto:** 5 €/día

#### Formulario de leads (Instant Form)

- **Tipo:** Más volumen (More Volume)
- **Idioma del formulario:** Noruego
- **Imagen de cabecera:** `amanecer-hd.jpg`
- **Título:** "Oppdag luksuslivet ved Middelhavet"
- **Descripción:** "Fyll ut skjemaet, og vi sender deg en komplett brosjyre med priser, tjenester og bilder. Helt uforpliktende."

**Campos del formulario:**

| Campo | Tipo | Requerido |
|-------|------|-----------|
| Fullt navn | Texto (prellenado) | Sí |
| Telefonnummer | Teléfono (prellenado) | Sí |
| E-post | Email (prellenado) | Sí |
| Hvem søker du plass for? | Dropdown | Sí |

**Opciones del dropdown:**
1. Min mor eller far (Mi madre o padre)
2. Min ektefelle/partner (Mi cónyuge/pareja)
3. Meg selv (Yo mismo)
4. Annet (Otro)

**Pantalla de agradecimiento:**
- **Título:** "Takk for din interesse!"
- **Descripción:** "Vi sender deg vår brosjyre innen kort tid. Ønsker du å snakke med oss med en gang? Ring +34 677 919 951."
- **Botón CTA:** "Besøk nettsiden vår" → `marbellacarehome.com/no.html`
- **Acción automática:** Enviar `folleto-noruego.html` al email del lead via integración con CRM/email (ver sección de automatización)

---

### CAMPAÑA 2: Retargeting / Brand Awareness

| Parámetro | Valor |
|-----------|-------|
| **Nombre** | `NO_Retargeting_Awareness_2024` |
| **Objetivo** | Tráfico (Traffic) |
| **Presupuesto** | 5 €/día (≈ 150 €/mes) |
| **Duración** | Lanzar 1 semana después de Campaña 1 |

#### Audiencia personalizada

- Personas que interactuaron con la página de Facebook (últimos 90 días)
- Personas que interactuaron con el perfil de Instagram (últimos 90 días)
- Personas que abrieron el formulario de leads pero NO lo enviaron
- Visitantes de la web (si hay píxel instalado)
- **Excluir:** Personas que ya enviaron el formulario (ya son leads)

#### Creatividad

- **Formato:** Carrusel de fotos (5 imágenes)
  1. `amanecer-hd.jpg` — "Våkn opp til dette hver dag"
  2. `fachadacerca-hd.jpg` — "Nylig totalrenovert"
  3. `cala-hd.jpg` — "Stranden er din nabo"
  4. `fachadagrande-hd.jpg` — "45 plasser, 22 ansatte"
  5. `amanecerlejos-hd.jpg` — "Fra 3 200 €/mnd, alt inkludert"
- **CTA:** "Les mer" → marbellacarehome.com/no.html

---

## 3. Creatividades publicitarias (4 anuncios)

### Anuncio 1 — Emocional: "Tu madre/padre merece lo mejor"

**Imagen:** `amanecer-hd.jpg`

| Elemento | Texto (en noruego) |
|----------|---------------------|
| **Primary text** | Din mor eller far fortjener det aller beste. 💛 Etter et langt liv med hardt arbeid, fortjener de å nyte sine gylne år med sol, hav og førsteklasses omsorg. Centro Mayores Mar Bella er et eksklusivt eldresenter direkte ved Middelhavet i Torrevieja, Spania — med norske beboere, 24-timers medisinsk tilsyn og nylig totalrenoverte fasiliteter. 🌊 Fyll ut skjemaet, og motta vår komplette brosjyre. Helt uforpliktende. |
| **Headline** | Luksus eldresenter ved Middelhavet |
| **Description** | Fra 3 200 €/mnd · Alt inkludert · 30+ års erfaring |
| **CTA button** | Registrer deg (Sign Up) |

---

### Anuncio 2 — Práctico: precios y comparativa

**Imagen:** `fachadagrande-hd.jpg`

| Elemento | Texto (en noruego) |
|----------|---------------------|
| **Primary text** | Visste du at et luksus eldresenter i Spania koster en brøkdel av hva du betaler i Norge? 🇳🇴➡️🇪🇸 Centro Mayores Mar Bella tilbyr alt inkludert fra kun 3 200 €/mnd: ✅ Privat rom med bad ✅ Full pensjon — alle måltider ✅ Legetilsyn 24/7 ✅ Aktiviteter og underholdning ✅ Renhold og vaskeri. Sammenlign med 40 000+ kr/mnd for et sykehjem i Norge. Direkte ved stranden i Torrevieja, med 320 soldager i året. |
| **Headline** | Alt inkludert fra 3 200 €/mnd |
| **Description** | Privat rom · Full pensjon · 24/7 legetilsyn · Ved stranden |
| **CTA button** | Få tilbud (Get Quote) |

---

### Anuncio 3 — Social proof: "Noruegos ya nos eligieron"

**Imagen:** `fachadacerca-hd.jpg`

| Elemento | Texto (en noruego) |
|----------|---------------------|
| **Primary text** | Norske familier har allerede valgt Mar Bella. 🇳🇴🌞 Med 40% internasjonale beboere og norsktalende i vårt fellesskap, vil din kjære føle seg hjemme fra første dag. «Da mamma flyttet til Mar Bella, fikk hun tilbake livsgnisten. Personalet behandler henne som familie.» — Kari, Oslo. Vi ligger direkte ved Middelhavet i Torrevieja — bare 2,5 timer med fly fra Norge. Nylig totalrenovert, med 22 dedikerte ansatte for 45 beboere. Bestill en uforpliktende omvisning i dag. |
| **Headline** | Norske beboere har allerede valgt oss |
| **Description** | 40% internasjonale beboere · 30+ års erfaring · Ved havet |
| **CTA button** | Registrer deg (Sign Up) |

---

### Anuncio 4 — Lifestyle: sol, playa, Mediterráneo

**Imagen:** `cala-hd.jpg`

| Elemento | Texto (en noruego) |
|----------|---------------------|
| **Primary text** | 320 soldager i året. Middelhavet rett utenfor vinduet. Frisk sjøluft hver morgen. 🌊☀️ Forestill deg et liv der vinteren aldri kommer — der dagene fylles med sol, gode måltider ved havet, hyggelige aktiviteter og omsorg i verdensklasse. Centro Mayores Mar Bella er det eneste luksuseldresenteret direkte ved stranden i Torrevieja, Costa Blanca. Nylig totalrenovert. 25 min fra Alicante flyplass. Direktefly fra Oslo og Bergen — kun 2,5 timer. Fra 3 200 €/mnd, alt inkludert. |
| **Headline** | Et liv i sol ved Middelhavet |
| **Description** | 320 soldager · Direkte ved stranden · Direktefly fra Norge |
| **CTA button** | Les mer (Learn More) |

---

## 4. Calendario de contenido

### Semana 1-2: Construcción orgánica de la página

> Objetivo: crear una base de contenido antes de lanzar anuncios pagados. Publicar 4-5 posts orgánicos.

| Día | Tipo | Contenido |
|-----|------|-----------|
| Día 1 | Foto | Post de presentación: fachada + texto de bienvenida |
| Día 3 | Foto | Amanecer desde la terraza |
| Día 5 | Carrusel | Recorrido por las instalaciones (3-5 fotos) |
| Día 7 | Foto | Plato de comida mediterránea |
| Día 9 | Foto | Vista de la cala/costa cercana |
| Día 11 | Vídeo/Reel | Tour corto de la residencia (si disponible) |
| Día 13 | Foto | Personal con beboere (con permiso) |

### Semana 3: Lanzamiento Campaña 1

- Activar Campaña 1 (Generación de Leads)
- Continuar con 2-3 posts orgánicos semanales
- Monitorizar el coste por lead (CPL) diariamente los primeros 3 días
- Ajustar audiencias si el CPL > 15 €

### Semana 4: Lanzamiento Campaña 2

- Activar Campaña 2 (Retargeting)
- La audiencia personalizada ya tendrá datos de la semana anterior
- Publicar 2-3 posts orgánicos más

### Mantenimiento mensual

- **3 posts orgánicos por semana** (ver documento `contenido-redes-noruego.md`)
- **Revisar rendimiento** de ads cada lunes
- **Rotación de creatividades** cada 2-3 semanas (evitar fatiga publicitaria)
- **A/B testing:** probar variaciones de texto e imágenes
- **Responder comentarios** y mensajes directos en menos de 4 horas

---

## 5. Automatización de leads

### Opción A: Integración con Zapier (recomendada para empezar)

1. Zapier trigger: "New Lead from Facebook Lead Ads"
2. Action 1: Enviar email automático con el folleto (`folleto-noruego.html`) como enlace o PDF adjunto
3. Action 2: Agregar contacto a hoja de Google Sheets para seguimiento
4. Action 3 (opcional): Enviar WhatsApp automático via Twilio

### Opción B: CRM (para cuando haya volumen)

- Integrar con HubSpot Free o similar
- Pipeline: Lead → Contactado → Visita programada → Ingreso

### Seguimiento manual recomendado

- **Dentro de 2 horas:** Llamar al lead (o WhatsApp si no contesta)
- **Día 1:** Enviar folleto por email si no se envió automáticamente
- **Día 3:** Segundo contacto si no hubo respuesta
- **Día 7:** Tercer y último intento
- **Registrar todo** en la hoja de seguimiento

---

## 6. KPIs y resumen de presupuesto

### Presupuesto mensual

| Concepto | Importe |
|----------|---------|
| Campaña 1 (Leads) | 450 €/mes |
| Campaña 2 (Retargeting) | 150 €/mes |
| **Total ads** | **600 €/mes** |
| Herramientas (Zapier, etc.) | 0-20 €/mes |
| **Total estimado** | **600-620 €/mes** |

### KPIs objetivo

| Métrica | Objetivo | Notas |
|---------|----------|-------|
| **CPL (Coste por lead)** | < 12 € | Media del sector senior care: 8-15 € |
| **Leads/mes** | 35-50 | Con 450 € y CPL de 10 € |
| **CTR (Click-through rate)** | > 1.5% | Buen indicador de relevancia |
| **Tasa de conversión lead → visita** | 10-15% | 4-7 visitas/mes |
| **Tasa de conversión visita → ingreso** | 30-40% | 1-3 ingresos/mes |
| **Coste por ingreso** | 200-600 € | Muy rentable considerando el LTV |

### ROI estimado

- **Ingreso mensual por beboer:** 3.200 €+
- **LTV promedio (estancia media 2 años):** ~77.000 €
- **Inversión para conseguir 1 ingreso:** ~200-600 €
- **ROI:** > 12.000%

---

## 7. Notas importantes

1. **Normativa:** Los anuncios sobre residencias de mayores pueden requerir revisión adicional por Meta. Evitar afirmaciones médicas específicas o promesas de resultados de salud.
2. **Idioma:** TODOS los anuncios y formularios en noruego. La página puede tener contenido en español también, pero el enfoque noruego debe ser claro.
3. **Imágenes:** Usar fotos reales de la residencia. Meta penaliza imágenes de stock y prefiere contenido auténtico.
4. **Pixel de Meta:** Instalar ANTES de lanzar campañas para poder hacer retargeting de visitantes web.
5. **Política de privacidad:** Asegurar que el formulario de leads cumple con GDPR (los leads son ciudadanos de la UE/EEE). Incluir enlace a política de privacidad.
6. **Frecuencia:** Vigilar que la frecuencia no supere 3-4 impresiones por persona por semana para evitar fatiga.
