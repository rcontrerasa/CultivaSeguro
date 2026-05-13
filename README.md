<div align="center">

# 🌱 CultivaSeguro

### *Escudo tecnológico contra los extremos climáticos para la Agricultura Familiar Campesina*

> **"Democratizar la asesoría experta para proteger el sustento de quienes cultivan nuestros alimentos."**

[![Torneo](https://img.shields.io/badge/Torneo-Innova%20Sostenible%202026-7CB342?style=for-the-badge&logo=leaflet&logoColor=white)](https://www.duoc.cl/innovasostenible-2026/)
[![Línea de acción](https://img.shields.io/badge/Línea%20de%20Acción-Bienestar%20%26%20Comunidades%20Resilientes-2E7D32?style=for-the-badge)](https://www.duoc.cl/innovasostenible-2026/)
[![Estado](https://img.shields.io/badge/Estado-Ideación%20%2F%20Prototipo-FFC107?style=for-the-badge)](#)
[![Institución](https://img.shields.io/badge/Duoc%20UC-Ingeniería%20en%20Conectividad%20y%20Redes-1565C0?style=for-the-badge)](https://www.duoc.cl)

</div>

---

## 📑 Tabla de Contenidos

- [📖 Sobre el Proyecto](#-sobre-el-proyecto)
- [🌍 El Problema](#-el-problema)
- [💡 La Solución](#-la-solución)
- [⚙️ Cómo Funciona](#️-cómo-funciona)
- [🏗️ Arquitectura Técnica](#️-arquitectura-técnica)
- [🚀 Diferencial e Innovación](#-diferencial-e-innovación)
- [🌱 Impacto en Sostenibilidad](#-impacto-en-sostenibilidad)
- [🏆 Alineación con el Torneo Innova Sostenible 2026](#-alineación-con-el-torneo-innova-sostenible-2026)
- [👥 Equipo y Motivación](#-equipo-y-motivación)
- [🗺️ Roadmap del Torneo](#️-roadmap-del-torneo)
- [📚 Fuentes que Respaldan el Proyecto](#-fuentes-que-respaldan-el-proyecto)
- [📄 Licencia y Aviso](#-licencia-y-aviso)

---

## 📖 Sobre el Proyecto

**CultivaSeguro** es una solución tecnológica integral diseñada para mitigar las severas pérdidas económicas que sufren los pequeños agricultores frente a los embates extremos del cambio climático, como **heladas atípicas**, **estrés hídrico agudo** y **olas de calor**.

El sistema despliega una red de **nodos físicos de bajo costo dentro de los invernaderos**, que combinan sensores microclimáticos, conectividad celular de banda estrecha (NB-IoT/5G), energía solar autónoma e inteligencia artificial **open-source operada localmente**, para enviar alertas preventivas y accionables en lenguaje natural —vía WhatsApp— al agricultor justo antes de que ocurra una catástrofe.

> 🎯 **Propósito**: Migrar el paradigma de la **indemnización post-desastre** (modelo actual del Estado vía seguro PACSA) hacia la **mitigación activa pre-evento**.

---

## 🌍 El Problema

La matriz silvoagropecuaria chilena enfrenta un punto de inflexión estructural. La **Agricultura Familiar Campesina (AFC)** —que agrupa más de **128.560 explotaciones a nivel nacional**— es el segmento más vulnerable y, paradójicamente, el menos atendido por la oferta AgTech tradicional.

### 📊 Cifras que dimensionan la urgencia

| 🌡️ Indicador | 📈 Magnitud | 🔗 Fuente |
|---|---|---|
| Pérdidas proyectadas del sector silvoagropecuario al 2050 | **> US$ 1.000 millones** | Plan Sectorial de Adaptación al Cambio Climático — MMA / ODEPA (2024) |
| Heladas julio 2024 (Coquimbo → Biobío) | **2.000 pequeños agricultores afectados / US$ 200 millones en pérdidas** | INIA Intihuasi vía Diario Frutícola |
| Inundaciones invierno 2023 (zona centro-sur) | **6.338 productores AFC dañados / US$ 900 millones** | INDAP / Colliers |
| Reducción de productividad por eventos climáticos | **Hasta 9% / $3,9 millones CLP por hectárea/año** | *Pérdidas y Desperdicios de Alimentos en Chile* — U. de Chile / ODEPA (2023) |
| Diferencia térmica nocturna interior/exterior del invernadero plástico | **Sólo +1 °C** | INIA La Platina (Chacón, 2024) |
| Aceleración del calentamiento (últimos 33 años) | **+0,21 °C/década** | Reporte Anual del Clima en Chile 2024 — DMC |

> ⚠️ **Hallazgo crítico (INIA La Platina, 2024):** El invernadero plástico del pequeño agricultor **no lo protege de la helada radiativa nocturna**. Esto justifica empíricamente la necesidad de una **alerta temprana in-situ**, no macroclimática.

### 🧨 La falla lógica del modelo actual

El Estado subsidia hasta el **95% de la prima del seguro agrícola (PACSA)**, pero ese mecanismo es **estructuralmente reactivo**: compensa el capital perdido, pero no previene la destrucción de la cosecha ni resguarda la cadena comercial del pequeño productor.

```diff
- Modelo actual: Pérdida → Catastro → Indemnización (semanas/meses)
+ CultivaSeguro: Sensor → IA → Alerta accionable (minutos)
```

---

## 💡 La Solución

CultivaSeguro instala dentro del invernadero pequeños **nodos sensores autónomos** que monitorean en tiempo real las variables críticas del microclima, y disparan una alerta preventiva **personalizada al cultivo** sólo cuando una variable se acerca al umbral de riesgo.

### 🧩 Componentes clave

<table>
<tr>
<td width="50%" valign="top">

**🔌 Nodo Físico (Hardware en invernadero)**
- 📡 Microcontrolador con NB-IoT / 5G nativo
- 🌡️ Sensor de temperatura y humedad
- 🔆 Sensor de iluminancia (lux reales)
- 🧭 Sensor de presión barométrica
- ☀️ Panel solar + batería = autonomía energética total
- 🛠️ Diseño optimizado para **fabricación digital**

</td>
<td width="50%" valign="top">

**☁️ Plataforma Central (Servidor + IA)**
- 🤖 Motor de IA **open-source local** (Llama 3.1 / Qwen)
- 🖥️ Dashboard web diurno, limpio y legible bajo el sol
- ⚙️ Configuración por tipo de hortaliza (umbrales personalizados)
- 📲 Notificaciones vía **WhatsApp Business API**
- 🔒 Privacidad por diseño (Ley 21.719)

</td>
</tr>
</table>

---

## ⚙️ Cómo Funciona

```mermaid
flowchart LR
    A[🌱 Invernadero<br/>Nodo Sensor] -->|Telemetría local| B{¿Variable<br/>en umbral<br/>de riesgo?}
    B -- No --> A
    B -- Sí --> C[📡 NB-IoT / 5G<br/>Petición crítica]
    C --> D[🖥️ Servidor Central<br/>IA Open-Source Local]
    D --> E[🤖 Análisis contextual<br/>por cultivo]
    E --> F[📲 Alerta WhatsApp<br/>Instrucciones accionables]
    F --> G[👨‍🌾 Agricultor<br/>actúa a tiempo]
```

### 🔄 Lógica Event-Driven (la disrupción arquitectónica)

> En lugar de transmitir telemetría continua —lo que disparía costos de datos y batería— el nodo **evalúa los datos localmente** y **sólo despierta la red cuando detecta un riesgo real**.

| Modelo tradicional IoT | 🆚 | CultivaSeguro (Event-Driven) |
|---|---|---|
| Telemetría continua → Cloud | | Evaluación on-device + envío sólo en evento |
| Plan de datos alto / batería corta | | Plan IoT mínimo / batería >10 años (NB-IoT PSM) |
| API pagada por solicitud | | IA open-source local (OPEX ≈ 0) |
| Dashboard complejo | | Mensaje WhatsApp en lenguaje natural |

---

## 🏗️ Arquitectura Técnica

### 🔧 Stack Tecnológico

| Capa | Tecnología | Justificación técnica |
|---|---|---|
| **Hardware** | Microcontrolador + módulo NB-IoT (ej. Quectel BC66 / SIMCom SIM7000G) | Costo unitario US$ 5–10, *link budget* de ~164 dB (penetra invernaderos densos) |
| **Sensores** | Temperatura, humedad, presión, iluminancia | Resolución microclimática *in situ* |
| **Conectividad** | NB-IoT (Entel/Wisely, Banda 28 – 700 MHz) | Primera red comercial NB-IoT en Chile (2023), cobertura Arica→Punta Arenas |
| **Energía** | Panel solar + almacenamiento Li-ion | Autonomía indefinida bajo PSM/eDRX |
| **Backend IA** | LLM open-source (Llama 3.1 8B / Qwen 2.5) sobre SBC con NPU (RK3588) | 3,72–11,5 t/s con consumo < 15W. **Elimina dependencia de APIs pagas** |
| **Notificación** | WhatsApp Business API (plantillas categoría *Utility*) | Canal masivo, sin instalar app, opt-in según Ley 21.719 |
| **Frontend** | Dashboard web responsive con diseño diurno | Legibilidad bajo luz solar directa |

### 📐 Diagrama de despliegue

```
┌─────────────────────────────────────────────────────────────────┐
│                    🌾 PREDIO DEL AGRICULTOR                      │
│                                                                  │
│   ┌──────────────────┐        ┌──────────────────┐              │
│   │  Invernadero #1  │        │  Invernadero #2  │              │
│   │  [☀️ Nodo IoT]   │        │  [☀️ Nodo IoT]   │              │
│   └────────┬─────────┘        └────────┬─────────┘              │
│            │                            │                        │
└────────────┼────────────────────────────┼────────────────────────┘
             │   📡 NB-IoT (sólo eventos) │
             ▼                            ▼
       ┌─────────────────────────────────────────┐
       │   ☁️ Servidor Central CultivaSeguro     │
       │  ┌───────────────────────────────────┐  │
       │  │  🤖 Motor IA local (open-source)  │  │
       │  │  🧠 Contexto agronómico cultivo   │  │
       │  │  📝 Generación de recomendación   │  │
       │  └───────────────────────────────────┘  │
       └───────────────────┬─────────────────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ 📲 WhatsApp API │
                  └────────┬────────┘
                           │
                           ▼
                  👨‍🌾  Agricultor recibe alerta
                       en lenguaje natural
```

---

## 🚀 Diferencial e Innovación

### 🆚 Benchmark competitivo

| Atributo | **CultivaSeguro** | Red Agromet (INIA) | CropX / Wiseconn | Davis Instruments |
|---|---|---|---|---|
| **Segmento** | AFC (pequeño agricultor) | Público general | Agroindustria | Académico/Corporativo |
| **Costo usuario** | 🟢 Ultra-bajo (subsidiable INDAP) | 🟢 Gratuito | 🔴 > US$ 500/nodo | 🟡 US$ 450–800 |
| **Resolución** | 🟢 Microclimática *in situ* | 🔴 Macro (comunal) | 🟢 Microclimática | 🟢 Microclimática |
| **Notificación** | 🟢 Push WhatsApp proactivo | 🔴 Web pasiva | 🟡 App/email | 🔴 Consola local |
| **Carga cognitiva** | 🟢 Muy baja (conversacional) | 🟡 Media | 🔴 Alta (dashboards) | 🔴 Media-Alta |
| **IA** | 🟢 Open-source en *edge* | 🔴 No | 🟡 Cloud predictiva | 🔴 No |

### 🌊 Océano azul detectado

> Nicho de **"monitoreo microclimático de ultra-bajo costo con interfaz conversacional"** para AFC. El sistema oficial **Agromet/heladas.minagri.gob.cl** opera a escala regional y **no compite, sino complementa** la capa fina *last-mile* que ofrece CultivaSeguro.

### 🔥 Tres palancas disruptivas

1. **NB-IoT comercial en Chile** (Entel/Wisely, 2023) → conectividad rural viable y barata.
2. **LLM open-source ejecutables en SBC** (Raspberry Pi 5 / RK3588 NPU) → IA sin APIs pagas.
3. **WhatsApp Business API** → eliminación de la barrera de adopción de apps en usuarios >50 años.

---

## 🌱 Impacto en Sostenibilidad

### 💧 Eje hídrico
- Cada kilogramo de tomate perdido implica el desperdicio de **~200 L de agua virtual** (Water Footprint Network).
- Una hectárea de tomate de invernadero protegida = **~20 millones de litros/ha** salvados por cosecha.

### 🌍 Eje climático
- Factor FAO: **2,5 kg CO₂eq por cada kg de alimento perdido** (incluye producción, transporte y descomposición).
- 100 ha protegidas a escala piloto regional ≈ **25.000 toneladas de CO₂eq evitadas**.
- Las Pérdidas y Desperdicios de Alimentos (PDA) representan **8–10% de las emisiones globales de GEI** (ONU/PNUMA 2024).

### 👨‍🌾 Eje social
- Protección del sustento económico de la AFC (sector más vulnerable).
- Democratización del acceso a asesoría experta.
- Reducción de la brecha digital rural.

### 🇨🇱 Alineación país
- ✅ **Plan Sectorial de Adaptación al Cambio Climático Silvoagropecuario 2024–2028** (MMA / ODEPA).
- ✅ **Estrategia Nacional de Residuos Orgánicos Chile 2040** (MMA).
- ✅ **ODS 2** (Hambre Cero), **ODS 6** (Agua Limpia), **ODS 12** (Producción Responsable), **ODS 13** (Acción por el Clima).

---

## 🏆 Alineación con el Torneo Innova Sostenible 2026

> *"¿Cómo podemos crear soluciones que ayuden a las personas y comunidades a enfrentar mejor los efectos del cambio climático y cuidar su entorno?"*

### 🎯 Línea de acción seleccionada

> **🌾 f) Bienestar, salud y comunidades más resilientes**
>
> *"Explorar alternativas que permitan fortalecer el bienestar de comunidades en cuanto a educación, salud, etc. promoviendo prácticas que incentiven e impulsen el desarrollo sostenible en diversos territorios..."*
>
> **Ámbitos cubiertos por CultivaSeguro:** Comunidades rurales · Alimentación y Agricultura sostenible · Impacto territorial · Educación ambiental y climática.

### 📋 Cumplimiento de los criterios de evaluación

| Criterio (Etapa 1: Activación) | Ponderación | Cómo lo cumple CultivaSeguro |
|---|---|---|
| **Problema alineado al desafío** | 20% | Pérdidas climáticas cuantificadas con fuentes oficiales (MMA, ODEPA, DMC, INIA, INDAP). |
| **Coherencia idea/proyecto** | 30% | Solución integrada (hardware + IA + WhatsApp) con cadena causal explícita. |
| **Potencial de la solución** | 30% | Benchmark competitivo, ventaja en océano azul AFC, tres palancas disruptivas verificadas. |
| **Formulación de la propuesta** | 5% | Documento estructurado, respaldado por más de 40 fuentes formales. |
| **Equipo** | 15% | Ingeniería en Conectividad y Redes — vinculación directa con NB-IoT, Python y sensores. |

### 🏅 Premio Especial HUB Providencia (Fabricación Digital)

CultivaSeguro califica como candidato natural a la **Mención Honrosa HUB Providencia**: el nodo físico está diseñado con enfoque de **prototipado experimental** (impresión 3D, corte láser, optimización de PCB) y **iteración con fabricación digital** —exactamente el perfil que el premio busca reconocer.

---

## 👥 Equipo y Motivación

> *"La tecnología y las telecomunicaciones tienen que servir para proteger a quienes más lo necesitan."*

Como estudiantes de **Ingeniería en Conectividad y Redes** de Duoc UC, contamos con las competencias específicas que este proyecto requiere para no quedarse en el papel:

### 🛠️ Capacidades técnicas internas

- ✅ Experiencia armando **redes de datos y proyectos de monitoreo**.
- ✅ **Programación en Python** para captura de datos de sensores ambientales.
- ✅ Transmisión en tiempo real a infraestructura *cloud*.
- ✅ Optimización de protocolos para conectividad de bajo consumo.

### 💚 Lo que nos mueve

Convertir el conocimiento técnico en una **herramienta real que ataque un problema país**: la desprotección del pequeño agricultor frente al cambio climático. Estamos convencidos de que la mejor tecnología **no tiene por qué ser cara ni complicada** —tiene que llegar a las manos correctas, en el momento correcto, con el mensaje correcto.

---

## 🗺️ Roadmap del Torneo

```
2026
├── 🟢 08 ABR – 06 MAY ─ Postulación (Activación) ◄── ETAPA ACTUAL
├── ⚪ 11 MAY – 20 MAY ─ Formación específica
├── ⚪ 02 JUN – 03 JUL ─ Aceleración
├── ⚪ 04 JUL – 19 JUL ─ Demo Day Final
└── ⚪    20 AGO       ─ Premiación
```

### 🎯 Roadmap post-torneo (visión de escalamiento)

| Año | Fondo objetivo | Monto | Hito |
|---|---|---|---|
| **2026** | Corfo Semilla Inicia | hasta $15–17M CLP | Validación técnica + MVP |
| **2027** | FIA Interés Privado | hasta $120M CLP | Piloto 30–50 invernaderos |
| **2027–2028** | Corfo Expande / INDAP IFP-PRI | hasta $25M CLP | Primeras ventas + subsidio compra |
| **2028+** | BID Lab / GSMA Innovation Fund | Internacional | Escalamiento LATAM |

---

## 📚 Fuentes que Respaldan el Proyecto

### 🇨🇱 Marco institucional chileno

- **MMA / ODEPA** — *Plan Sectorial de Adaptación al Cambio Climático del Sector Silvoagropecuario 2024–2028*. [expedientes.mma.gob.cl](https://expedientes.mma.gob.cl)
- **DMC** — *Reporte Anual de la Evolución del Clima en Chile 2024*. [climatologia.meteochile.gob.cl](https://climatologia.meteochile.gob.cl/publicaciones/reporteEvolucionClima/reporteEvolucionClima2024.pdf)
- **INIA La Platina** — Chacón, G. (2024) *Hortalizas versus heladas*. [inia.cl](https://www.inia.cl/2024/06/25/hortalizas-versus-heladas/)
- **U. de Chile / ODEPA** (2023) — *Pérdidas y desperdicios de alimentos en Chile*.
- **ODEPA** — *VIII Censo Agropecuario y Forestal*. [odepa.gob.cl](https://www.odepa.gob.cl)
- **INDAP** — Programas PRA, PRI e IFP. [indap.gob.cl](https://www.indap.gob.cl)
- **MMA** — *Estrategia Nacional de Residuos Orgánicos Chile 2040 (ENRO)*.

### 📡 Habilitadores tecnológicos

- **Entel / Wisely** — *NB-IoT en Chile: cómo la red de Entel habilita el IoT masivo*. [marketing.wisely.cl](https://marketing.wisely.cl/blog/nbiot-chile-red-entel-iot-masivo)
- **SUBTEL** — Homologación de equipos terminales. [subtel.gob.cl](https://www.subtel.gob.cl)
- **arXiv / IEEE Xplore** — Benchmarks de inferencia LLM en SBC (RK3588 NPU, Raspberry Pi 5, Llama 3.1/Qwen). [arxiv.org/html/2511.07425v1](https://arxiv.org/html/2511.07425v1)
- **Meta** — WhatsApp Business Platform API (plantillas categoría *Utility*).

### 🌎 Sostenibilidad y referencia internacional

- **FAO** (2013) — *Food Wastage Footprint: Impacts on Natural Resources*.
- **ONU / PNUMA** (2024) — *Food Waste Index Report*.
- **Water Footprint Network** — Aldaya & Hoekstra, *The Water Footprint of Food*. [waterfootprint.org](https://waterfootprint.org)
- **HuellaChile** (MMA) — [huellachile.cl](https://huellachile.cl)
- **IPCC** — Paneles climáticos vigentes.

### ⚖️ Marco regulatorio

- **Ley 21.719** — Protección de datos personales (Chile, vigencia diciembre 2026). [bcn.cl](https://www.bcn.cl/leychile/navegar?idNorma=1209272)
- **Ley 18.168** — Ley General de Telecomunicaciones.

### 📑 Documentación interna del proyecto

> Disponible en el directorio raíz del repositorio:
> - 📄 `Investigación_para_Propuesta_CultivaSeguro.md` — informe de respaldo principal.
> - 📄 `Investigación_complementaria___Proyecto_CultivaSeguro.md` — datos sectoriales adicionales.
> - 📄 `Materiales_para_fortalecer_tu_propuesta.txt` — síntesis ejecutiva.
> - 📄 `Bases_Torneo_Innova_Sostenible_2026.pdf` — bases oficiales del torneo.

---

## 📄 Licencia y Aviso

Este proyecto se desarrolla en el marco del **Torneo Innova Sostenible 2026 — Duoc UC**, con el apoyo de **Banco Santander** y la colaboración del **HUB Providencia**. El presente repositorio constituye documentación de la etapa de **ideación / activación**.

> Toda referencia a fuentes terceras es de carácter académico y de respaldo. Los datos cuantitativos están citados según sus fuentes originales; cualquier extrapolación (e.g., estimaciones de litros de agua o toneladas de CO₂ evitadas) está marcada como estimación metodológica con la fórmula utilizada.

---

<div align="center">

### 🌱 *"Creando hoy las ideas del mañana"* 🌱

**CultivaSeguro · 2026 · Duoc UC**

[![Innova Sostenible](https://img.shields.io/badge/🏆-Innova%20Sostenible%202026-7CB342?style=for-the-badge)](https://www.duoc.cl/innovasostenible-2026/)

</div>
