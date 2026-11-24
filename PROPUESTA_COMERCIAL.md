# PROPUESTA COMERCIAL & ARQUITECTURA TÉCNICA ESTRATÉGICA
**VORTEX LABS S.A.S. | NIT 901.8XX.XXX-X**  
*Laboratorio de Ingeniería Creativa, Analítica de Datos, Ciberseguridad e Inteligencia Artificial*

---

| **Documento:** | **VRTX-PROP-2026-LLANO-01** |
| :--- | :--- |
| **Cliente / Prospecto:** | Inversionista Inmobiliario & Candidato Concejo Medellín 2027 |
| **Lugar de Encuentro:** | La Alpujarra, Oficina 1311, Edificio Nuevo Alpujarra, Medellín |
| **Fecha de Presentación:** | 24 de Noviembre de 2026 · 2:00 PM |
| **Equipo Consultor:** | **Jesús Cossio** (CEO & Project Manager · Físico, Esp. Datos & IA)<br>**Nadia Hernández** (Estratega de Marketing Digital Multiplataforma)<br>**Jonathan Canarias** (Omnicol Solutions · Dirección de Operaciones & CRM) |
| **Artefacto Interactivo:** | `mapa-spaghetti-llanogrande-concejo-2027.html` (32 nodos · 54 conexiones) |

---

## 1. RESUMEN EJECUTIVO & CONTEXTO ESTRATÉGICO

El cliente es un profesional del derecho e inversionista de alto capital con cuatro desarrollos de parcelaciones en Colombia —destacando como **prioridad de negocio inmediata la parcelación junto al Aeropuerto Internacional José María Córdova (JMC) en Llanogrande**— además de activos inmobiliarios en Panamá, Dubái y Estados Unidos. En paralelo, proyecta su postulación oficial al **Concejo de Medellín 2027** (arranque en enero), apalancando y respaldando a dos o tres candidatos aliados bajo una bandera central: **Innovación Tecnológica Real aplicada a la Ciudadanía**.

### Diagnóstico de Dolores Actuales Detectados
1. **Cero Infraestructura Digital en Llanogrande:** Activos de altísima valorización comercial sin vitrina inmersiva ni canal directo de reserva, dependiendo de PDFs pesados y chats informales en WhatsApp.
2. **Fuga Crítica de Leads Internacionales:** Compradores de alto ticket en Dubái, Panamá o EE.UU. no reciben atención inmediata en su zona horaria ni scoring de capacidad crediticia.
3. **Operación Artesanal en Hojas de Excel:** Ruptura de comunicación entre las agencias de pauta, el equipo comercial y el call center. Nadie mide el ciclo de vida del cliente segundo a segundo.
4. **Desperdicio de Presupuesto en Política Tradicional:** Enfoque arcaico de invertir entre $20.000.000 y $100.000.000 COP en camisetas y gorras efímeras sin trazabilidad de votos, ignorando modelos estadísticos predictivos (metodología analítica moderna) y posicionamiento orgánico en motores de IA (ChatGPT, Perplexity, Google AI).
5. **Vulnerabilidad Jurídica y de Datos:** Inexistencia de consentimientos explícitos Ley 1581 (Habeas Data) para entrenar IA, sin bitácora inmutable de transacciones y sin resguardo inmutable contra ransomware (WORM).

---

## 2. EL ECOSISTEMA VIVO EN 8 CAPAS DE VORTEX LABS

Para erradicar la improvisación, **Vortex Labs S.A.S.** estructuró la solución como un ecosistema vivo interconectado (mapeado visualmente en el Mapa Mental Spaghetti adjunto):

```
[ CAPA 01: FRONTEND & EXPERIENCIA 3D / PWA / HUB CÍVICO ]
                          │  (Eventos / GeoJSON / Token)
                          ▼
[ CAPA 02: GATEWAY API, PYDANTIC/ZOD & ANTI DOBLE-VENTA ]
                          │  (Mensajería Atómica / SSE)
                          ▼
[ CAPA 03: BASE CENTRAL POSTGIS, MEDALLION & AUDIT HASH ] ◄──┐
                          │  (Datos Limpios / Vistas Gold)   │ (Blindaje
                          ▼                                  │  Transversal
[ CAPA 04: INTELIGENCIA ARTIFICIAL, SCORING ML & GEO/LLMO]   │  Capa 05:
                          │  (Leads A/B/C/D / Top-3 IA)      │  RLS, WAF,
                          ▼                                  │  Ley 1581,
[ CAPA 06: INTEGRACIONES: WOMPI/STRIPE, CRM & META CAPI ]    │  Backups WORM)
                          │  (Recaudo Confirmado / Lookalike)│
                          ▼                                  │
[ CAPA 07: CLOUD AUTO-SCALE, EDGE CDN & OBSERVABILIDAD ] ────┘
                          │  (Uptime 99.95% / MTTD < 60s)
                          ▼
[ CAPA 08: RETORNO DE INVERSIÓN (ROI), VOTOS & PATRIMONIO PROPIO ]
```

---

## 3. PAQUETES DE SERVICIO & ESTRUCTURA ECONÓMICA

La propuesta se compone de una **Fase de Implementación & Despliegue de Infraestructura** (pago único estructurado por hitos) y un **Acompañamiento Estratégico Recurrente Mensual** (tráfico, producción de contenidos y optimización de conversión).

### FASE 1: DESPLIEGUE TECNOLÓGICO & PLATAFORMA (Pago Único)

#### Opción A · Módulo Base Web 3D Inmersiva Llanogrande
*Enfoque prioritario: solucionar de inmediato la venta de la parcelación junto al Aeropuerto JMC.*
- Vitrina Web 3D progresiva (Next.js 15 + CesiumJS / Three.js).
- Integración de ortofotos y modelos de dron sobre poligonales catastrales GeoJSON.
- Selector interactivo de lotes (área, vista, precio, estado disponible/reservado).
- Formulario de captación ultra-rápido vinculado a WhatsApp Business.
- Hosting Edge global, dominio y certificado SSL de alta velocidad.
- **Inversión Módulo Base:** **$6.000.000 COP** + IVA

#### Opción B · Ecosistema Integral Dual (PropTech Llanogrande + Hub Concejo 2027) — *(Recomendada)*
*Plataforma completa enterprise para operar parcelaciones e impulsar la campaña política.*
- Todo lo incluido en la Opción A (Web 3D Llanogrande).
- **Hub Cívico Concejo de Medellín 2027** con micrositios dedicados para el titular y 2–3 candidatos aliados.
- **App Móvil PWA Offline-First con GPS** para asesores inmobiliarios en terreno y brigadas políticas en comunas (sincronización bidireccional automática al recuperar señal).
- **Motor WebSockets Anti Doble-Venta:** Bloqueo atómico de lotes en tiempo real para evitar conflictos entre compradores internacionales y locales.
- **Base de Datos Enterprise:** PostgreSQL 16 + PostGIS geoespacial + Lakehouse Medallion (Bronze/Silver/Gold).
- **Bot Conversacional RAG 24/7:** Atención automática en WhatsApp y Web entrenada con especificaciones de parcelaciones y propuestas de ciudad, con cláusula Zero-Training de privacidad.
- **Modelo de Scoring Predictivo ML:** Calificación de prospectos en categorías A/B/C/D para priorizar el esfuerzo de cierre del Call Center.
- **Arquitectura GEO / LLMO Pionera:** Marcado semántico Schema JSON-LD y `/llms.txt` para garantizar indexación y citación destacada en ChatGPT, Perplexity y Google AI en las búsquedas electorales y de parcelaciones.
- **Pasarela de Pagos Híbrida:** Integración de Wompi / PSE para recaudo local y Stripe para tarjetas internacionales en USD/AED con verificación estricta HMAC.
- **Suite de Dashboards por Rol:** Monitoreo ejecutivo en tiempo real para Gerencia, Ventas y Coordinación de Campaña (eliminando por completo las planillas manuales de Excel).
- **Inversión Ecosistema Integral:** **$15.000.000 COP** + IVA

---

### FASE 2: TRÁFICO, CONTENIDO AUDIOVISUAL & OPERACIONES (Fee Mensual Recurrente)

Para garantizar que la infraestructura técnica facture y sume simpatizantes día a día:

| Rubro | Alcance Operativo | Rango Mensual |
| :--- | :--- | :--- |
| **Estrategia & Pauta Multiplataforma** | Gestión y escalamiento de campañas en Meta Ads (Facebook/Instagram con Meta CAPI server-side), Google Search, YouTube y pauta geo-segmentada por comunas. | $2.500.000 – $3.500.000 COP / mes |
| **Producción Audiovisual (Filmmaker)** | Rodaje profesional mensual de video en parcelación (drones 4K, tomas in situ) y cápsulas de contenido político/estratégico de alto valor psicológico. | $1.500.000 – $2.500.000 COP / mes |
| **Soporte SRE, DevOps & Hosting Cloud** | Mantenimiento 24/7, parches de seguridad, optimización de consultas SQL, backups WORM inmutables diarios y monitoreo FinOps de tokens de IA. | $800.000 – $1.200.000 COP / mes |
| **PAQUETE INTEGRADO RECURRENTE (Tráfico + Audiovisual + Soporte)** | **Gestión total mes a mes de adquisición y tecnología sin fricción.** | **$4.500.000 COP / mes** |

*Nota: El presupuesto de pauta publicitaria pagado directamente a Meta/Google es asignado de forma independiente por el cliente según su ritmo de inversión.*

---

## 4. ESQUEMA TRIBUTARIO, LEGAL & MODELO DE PARTICIPACIÓN

1. **Formalización Empresarial por Vortex Labs S.A.S.:**
   - El contrato de prestación de servicios se suscribe directamente con **Vortex Labs S.A.S.**, emitiendo facturación electrónica formal con cumplimiento de la normatividad DIAN.
   - Vortex Labs es agente responsable de IVA y retenciones en la fuente aplicables (según la naturaleza del servicio y retención ICA en Medellín), blindando jurídicamente los egresos del cliente y su contabilidad para reportes ante el Consejo Nacional Electoral (CNE).
2. **Modelo de Reparto & Compensación por Porcentaje:**
   - La compensación entre las partes ejecutoras (Jesús Cossio / Vortex Labs, Nadia Hernández / Marketing Multiplataforma, y Jonathan Canarias / Omnicol Solutions) se liquidará bajo un **porcentaje pactado sobre el valor neto ejecutado**, garantizando que todo el equipo opere alineado al éxito y cierre del cliente.

---

## 5. CRONOGRAMA DE EJECUCIÓN (LISTO PARA ENERO 2027)

```
SEMANA 1 (Dic 01 - 07): Levantamiento técnico, ortofotos de dron Llanogrande, setup cloud y diseño UI/UX.
SEMANA 2 (Dic 08 - 14): Montaje Web 3D, configuración PostgreSQL/PostGIS y despliegue del Hub Cívico Concejo 2027.
SEMANA 3 (Dic 15 - 21): Entrenamiento de Bot RAG WhatsApp, integración Wompi/Stripe y pruebas de carga anti doble-venta.
SEMANA 4 (Dic 22 - 30): Configuración de Meta CAPI, marcado semántico GEO/LLMO, dashboards y QA integral en sala.
SEMANA 5 (Ene 02 - 08): LANZAMIENTO OFICIAL ENERO: Inicio de pauta digital y despliegue territorial con aliados.
```

---

## 6. COMPROMISOS & SIGUIENTE PASO

1. **Reunión de Sala (24 Nov, 2:00 PM - Alpujarra):**
   - Demostración en vivo en pantalla del **Mapa Mental Spaghetti Interactivo** (`mapa-spaghetti-llanogrande-concejo-2027.html`).
   - Simulación en tiempo real del impacto de recortar piezas críticas (demostración de efecto dominó ante descarte).
   - Indagación del presupuesto inicial disponible del cliente para ajustar la orden de compra inmediata (pisar con anticipo del 50%).
2. **Firma de Contrato & Kick-off:** Emisión inmediata de pólizas y acta de inicio en la primera semana de diciembre.
