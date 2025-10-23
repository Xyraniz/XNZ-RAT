# XNZ-RAT v3.0

**Control y Monitorización**
Ejecución remota de comandos, administración de archivos, captura de pantalla en tiempo real, acceso a cámara web, monitorización de procesos y servicios del sistema.

**Persistencia Avanzada**
Infección de MBR para supervivencia post-formateo, técnicas fileless sin archivos en disco, persistencia mediante WMI y eventos del sistema, múltiples métodos tradicionales de persistencia.

**Recolección de Datos Especializada**
Extracción de tokens de Discord con información completa, credenciales de navegadores, carteras de criptomonedas (8+ formatos), detección de frases semilla, información financiera y datos sensibles.

**Mecanismos de Evasión y Sigilo**
Motor polimórfico en tiempo de ejecución, sistema anti-sandbox con 9 técnicas de detección, protección anti-monitoring, process hollowing, capacidades rootkit, comunicación mediante Discord y DNS tunneling.

**Propagación Automatizada**
Infección automática de dispositivos USB, propagación en redes locales, múltiples vectores de activación, despliegue silencioso.

**Sistema de Protección**
Auto-protección contra terminación, restauración de procesos críticos, detección de herramientas de análisis, múltiples métodos de UAC bypass.

**Gestión y Mantenimiento**
Actualizaciones remotas automáticas, configuración dinámica, mecanismos de auto-reparación, cifrado AES-256 con clave dedicada.

**Panel Web Integrado**
Dashboard en tiempo real con estadísticas, gestión visual de víctimas, interfaz web responsive, sistema de comandos remotos via navegador.

---

## 🔒 SEGURIDAD AVANZADA

**Detección Anti-Sandbox (9 Técnicas)**
- Monitorea procesos de virtualización (VMware, VirtualBox)
- Detecta archivos y drivers de máquinas virtuales
- Verifica claves de registro específicas de entornos VM
- Analiza dirección MAC para prefijos de virtualización
- Revisa hardware insuficiente (poca RAM, CPU, disco)
- Controla tiempo de ejecución del sistema operativo
- Verifica uso de memoria del proceso
- Detecta resoluciones de pantalla bajas
- Mide aceleración de tiempo en el sistema

**Motor Polimórfico Automático**
- Cambia su propio código mientras se ejecuta
- Renombra variables y funciones internas
- Ofusca textos importantes del programa
- Genera código falso para confundir análisis
- Usa información única del sistema para mutaciones

**Comunicación Encubierta Multi-Canal**
- Discord como canal principal de comandos
- DNS Tunneling como respaldo (datos ocultos en consultas DNS)
- Panel web con APIs REST para gestión visual
- Comunicación cifrada end-to-end

**Protección Anti-Análisis Activa**
- Termina automáticamente Task Manager, CMD, PowerShell
- Detecta y cierra herramientas de debugging (OllyDbg, IDA)
- Elimina procesos de monitoreo (Process Hacker, Wireshark)
- Se inyecta en procesos legítimos del sistema para ocultarse

**Persistencia Multi-Nivel**
- Nivel 1: Métodos tradicionales (registro, tareas programadas)
- Nivel 2: Técnicas fileless (sin archivos en disco)
- Nivel 3: Infección MBR (sobrevive a formateos)
- Nivel 4: WMI Events (ejecución por eventos del sistema)

**Auto-Defensa y Recuperación**
- Auto-protección contra terminación
- Restaura procesos críticos si se cierran
- Múltiples métodos de UAC bypass automático
- Protocolo de auto-destrucción limpia ante detección

---

**Puntos Claves Esenciales:**

- **Persistencia Extrema**: Sobrevive a formateos mediante infección del MBR y técnicas sin archivos
- **Robo Especializado**: Extrae criptomonedas, contraseñas y datos financieros de forma dirigida
- **Evasión Avanzada**: Motor polimórfico y 9 técnicas anti-detección para evitar análisis
- **Comunicación Encubierta**: Usa Discord como canal principal con DNS tunneling de respaldo
- **Propagación Autónoma**: Se expande automáticamente por USB y redes locales
- **Control Total**: Acceso completo remoto incluyendo cámara y pantalla en tiempo real
- **Auto-protección**: Mecanismos contra eliminación y detección de herramientas de seguridad
- **Actualizaciones Remotas**: Sistema de mantenimiento y mejora continua automática
- **Gestión Centralizada**: Panel web integrado para control visual de múltiples objetivos
