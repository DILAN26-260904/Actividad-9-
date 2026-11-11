# Actividad-9-Visualizando el potencial de la Ciberseguridad
DILAN FELIPE LAGOS JIMENEZ


Sensores     │────▶│  Controlador│────▶│  Semáforo     │
│  (tráfico,    │     │  Principal   │     │  (LEDs R/A/V) │
│   cámaras)    │     │  (ESP32/PLC) │     └───────────────┘
└───────────────┘     └──────┬───────┘
│
┌────────────────────┼────────────────────┐
▼                    ▼                    ▼
┌──────────────┐    ┌──────────────┐    ┌───────────────┐
│ Comunicación │    │ Servidor/    │    │ Panel de      │
│ (WiFi/MQTT)  │    │ Plataforma   │    │ monitoreo     │
└──────────────┘    │ Central      │    └───────────────┘
└──────────────┘

┌──────────────────────────────────────────────────────┐
│         🚗 TRANSPORTE INTELIGENTE 🚦                  │
│  Conectando tecnología con movilidad segura           │
├──────────────┬──────────────────┬────────────────────┤
│   📡 PERCEPCIÓN    │   🔄 PROCESAMIENTO   │   🚙 ACCIÓN     │
│  Sensores y cámaras │   Análisis de datos │   Semáforos    │
│  capturan datos    │   e IA decide        │   dinámicos,   │
│  del tráfico       │   en tiempo real     │   rutas en app │
├──────────────────────────────────────────────────────┤
│  ⚡ Beneficios: 🛡️ Seguridad | ⏱️ Ahorro de tiempo     │
│                 🌿 Menos contaminación | 💰 Ahorro económico │
└──────────────────────────────────────────────────────┘

```
# 🍪 Ciberseguridad en una Planta de Producción de Galletas
(8 — Laboratorio de galletas]
## 📋 Proceso General


Recepción de materias primas → Almacenamiento → Mezclado → Moldeado → Horneado → Enfriamiento → Empaquetado → Distribución

# 🌾 Carpeta 03 — Campo Automatizado con Drones

## `03_Cultivo_Drones/README.md`

```
# 🌱 Agricultura Inteligente con Drones

**Fuente:** [AgroDatos Lab](https://github.com/dialejobv/Curso_Programacion_SENA/blob/main/)%20Actividad%208/AgroDatos%20Lab.html)

---

## 🚜 Funcionamiento del Sistema

```

┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│  Sensores    │───▶│  Drones      │───▶│  Plataforma │
│  del suelo   │    │  Multiespectral│   │  de Análisis │
│  (humedad,   │    │  + Cámaras   │    │  (IA + BD)  │
│   nutrientes)│    └──────┬───────┘    └─────┬──────┘
└──────────────┘           │                     │
│                  ▼                     ▼
│         ┌──────────────┐      ┌──────────────┐
└────────│ Sistema de   │─────▶│ Decisiones   │
│ Riego/Insumo │       │ Agrícolas    │
│ Automático   │       │  optimizadas │
└──────────────┘       └──────────────┘


# 🛡️ Carpeta 04 — Sistemas Embebidos, Cifrado y Drones de Rescate

## `04_Sistemas_Embebidos_Cifrado/README.md`

```
# 🔒 Ciberseguridad en Sistemas Embebidos y Cifrado

**Fuente:** [ESP-WROOM-32 — U_Militar](https://github.com/dialejobv/U_Militar/blob/main/14)%20Esp_Wroom_32/index.html)

---

## a) ¿Cómo la ciberseguridad afecta los sistemas embebidos?

Los **sistemas embebidos** son computadoras dedicadas dentro de dispositivos específicos — como el ESP32 — que controlan funciones en tiempo real. A diferencia de una computadora convencional, tienen **recursos limitados**: menos memoria, menor potencia de procesamiento y energía restringida.

### ⚠️ Principales vulnerabilidades:

| Problema | Explicación | Impacto |
|----------|-------------|---------|
| **Credenciales por defecto** | Muchos dispositivos salen de fábrica con contraseñas públicas → atacantes las conocen | Acceso total al sistema sin esfuerzo |
| **Firmware sin protección** | El código que ejecuta el dispositivo se puede leer o modificar libremente | Inyección de código malicioso; clonación del dispositivo |
| **Comunicaciones sin cifrar** | Datos enviados en texto plano por WiFi/Bluetooth | Intercepción y manipulación de comandos en tránsito |
| **Actualizaciones sin firma** | El dispositivo acepta cualquier actualización sin verificar su origen | Instalación remota de malware permanente |
| **Recursos limitados** | No pueden ejecutar antivirus ni cortafuegos completos | Detección tardía de intrusiones |

> Un dispositivo vulnerable conectado a la red puede servir como puerta de entrada para atacar toda la infraestructura a la que está conectado.

### ✅ ¿Cómo se ve la ciberseguridad en este campo?

| Estrategia | Qué hace en el ESP32 / sistemas embebidos |
|------------|-------------------------------------------|
| **Cifrado de memoria flash** | El firmware se almacena cifrado; el dispositivo lo descifra solo en el momento de ejecución. Si extraen el chip, no pueden leer el código. |
| **Arranque seguro (Secure Boot)** | Solo ejecuta firmware firmado por el fabricante. Si alguien intenta modificarlo, el dispositivo no arranca. |
| **Comunicaciones seguras** | Uso de TLS 1.2+ para conexiones por WiFi; MQTT sobre puerto 88
```

