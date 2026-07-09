## 1. Roles y Responsabilidades

| **Rol** | **Nivel** | **Alcance** | **Escala a** |
|---|---|---|---|
| **Equipo de Porcicultura** | 1 — Revisión Inicial | Limpieza, verificación visual de LEDs, reinicio básico, registro de novedades | Mantenimiento o Asimetrix |
| **Equipo de Mantenimiento** | 2 — Diagnóstico Eléctrico y de Red | Revisión de alimentación eléctrica, UPS, breakers y router | Tecnología |
| **Equipo de Tecnología** | 3 — Diagnóstico de Red Avanzado | Resolución de conectividad cuando el router genera red pero no tiene internet | Asimetrix (si aplica) |

> **Regla general:** Cada nivel resuelve lo que le corresponde. Si no puede resolver, escala al siguiente nivel. Nunca saltar niveles.

## 2. Procedimiento Detallado

### 2.1 Revisión Inicial — Equipo de Porcicultura

**Cuándo:** En cada visita programada de revisión inicial.

| **Paso** | **Acción** | **Verificar** |
|---|---|---|
| 1 | Limpiar el lente de cada cámara | Sin polvo, residuos ni condensación |
| 2 | Limpiar el exterior de la cámara | Sin suciedad acumulada en carcasa |
| 3 | Verificar el estado de los LEDs | Observar color y comportamiento de cada LED |
| 4 | Registrar novedades | Anotar número de cámaras con anomalías |

---

### 2.2 Diagnóstico por Estado del LED — Equipo de Porcicultura

#### 2.2.1 Cámara no enciende (ningún LED activo)

| **Paso** | **Acción** |
|---|---|
| 1 | Confirmar que no haya un problema visible de conexión (cable suelto, desconectado, dañado) |
| 2 | Si la conexión física está bien, escalar al equipo de **Mantenimiento** |

> **⚠ Nota:** No intentar reparaciones eléctricas. Solo el equipo de Mantenimiento interviene en instalaciones eléctricas.

#### 2.2.2 LED rojo encendido

| **Paso** | **Acción** |
|---|---|
| 1 | Apagar la cámara desde el botón **ON** |
| 2 | Desconectar la cámara de la fuente de energía |
| 3 | Esperar **5 minutos** completos |
| 4 | Volver a conectar la cámara a la energía |
| 5 | Encender la cámara desde el botón **ON** |
| 6 | Esperar unos minutos y verificar si el LED vuelve a estado normal |

**Resultado:** ¿Se resolvió?

| **Sí** | **No** |
|---|---|
| Registrar como resuelto y continuar revisión | Reportar la novedad a **Asimetrix** para intervención especializada |

#### 2.2.3 Solo encendido el LED de ON (resto apagados)

**Posible causa:** La cámara presenta un bloqueo de software, generalmente ocasionado por una interrupción o descarga de energía.

| **Paso** | **Acción** |
|---|---|
| 1 | Apagar la cámara desde el botón **ON** |
| 2 | Desconectar la cámara de la fuente de energía |
| 3 | Esperar **5 minutos** completos |
| 4 | Volver a conectar la cámara a la energía |
| 5 | Encender la cámara desde el botón **ON** |

**Resultado:** ¿Se resolvió?

| **Sí** | **No** |
|---|---|
| Registrar como resuelto y continuar revisión | Reportar a **Asimetrix** para cambio de la cámara |

---

### 2.3 Verificaciones Eléctricas y de Red — Equipo de Mantenimiento

**Cuándo intervenir:**
- Una o varias cámaras no encienden (LED apagado).
- Todas las cámaras presentan LED rojo simultáneamente.

> Si solo una cámara tiene LED rojo, el Equipo de Porcicultura realiza el reinicio descrito en el paso 2.2.2 antes de escalar a Mantenimiento.

#### 2.3.1 Verificaciones eléctricas

| **Paso** | **Acción** | **Resultado esperado** |
|---|---|---|
| 1 | Revisar la alimentación eléctrica de las cámaras | Alimentación presente y estable |
| 2 | Validar el estado de la UPS | UPS encendida y funcionando correctamente |
| 3 | Verificar si el breaker está disparado | Breaker en posición ON |

> Si el breaker está disparado, restablecerlo y verificar que no se vuelva a disparar. Si se repite, reportar al responsable de infraestructura de la granja.

#### 2.3.2 Revisión del router Asimetrix

| **Paso** | **Acción** |
|---|---|
| 1 | Verificar que el router esté encendido |

**¿El router enciende?**

| **NO** | **SÍ** |
|---|---|
| Verificar la alimentación eléctrica del router | Continuar al paso siguiente |
| Verificar si el equipo presenta daño físico visible | |

**Si el router enciende:**

| **Paso** | **Acción** |
|---|---|
| 2 | Confirmar que esté generando la red **Asimetrix ioA** |
| 3 | Verificar si aparece el estado **"Conectado, sin internet"** |
| 4 | Reiniciar el router |

**¿Después del reinicio el router tiene internet?**

| **Sí** | **No** |
|---|---|
| Registrar como resuelto | Escalar al equipo de **Tecnología** |

---

### 2.4 Diagnóstico de Conectividad Avanzado — Equipo de Tecnología

**Cuándo intervenir:**
- El router genera la red **Asimetrix ioA**, pero permanece en estado **"Conectado, sin internet"** después del reinicio.
- Se recibe el reporte del equipo de Mantenimiento con esta condición.

> **Restricción:** El equipo de Tecnología interviene únicamente cuando el caso le es escalado por Mantenimiento. No recibir reportes directos del personal de porcicultura para este nivel.

---

## 3. Reglas de Escalamiento

| **Situación** | **Origen** | **Escalar a** | **Medio de reporte** |
|---|---|---|---|
| Cámara no enciende tras revisión física de conexión | Porcicultura | Mantenimiento | Formato de reporte o mensajería interna |
| LED rojo persiste tras reinicio | Porcicultura | Asimetrix | Formato de reporte o mensajería interna |
| Solo LED ON encendido, persiste tras reinicio | Porcicultura | Asimetrix | Formato de reporte o mensajería interna |
| Todas las cámaras con LED rojo | Porcicultura | Mantenimiento | Formato de reporte o mensajería interna |
| Router con red pero sin internet tras reinicio | Mantenimiento | Tecnología | Formato de reporte o mensajería interna |

---

## 4. Registro de la Visita

Completar este checklist al finalizar cada revisión inicial. El registro debe ser conservado como evidencia documental.

| **#** | **Actividad realizada** | **Sí** | **No** | **N/A** | **Observaciones** |
|---|---|---|---|---|---|
| 1 | Se realizó la limpieza de los lentes | ☐ | ☐ | ☐ | |
| 2 | Se revisó el estado de todas las cámaras | ☐ | ☐ | ☐ | |
| 3 | Se realizaron los reinicios necesarios | ☐ | ☐ | ☐ | |
| 4 | Se revisó el router (cuando aplicó) | ☐ | ☐ | ☐ | |
| 5 | Se reportaron las novedades al área correspondiente | ☐ | ☐ | ☐ | |
| 6 | Todas las cámaras quedaron operando correctamente o se dejó registrado el pendiente | ☐ | ☐ | ☐ | |

| **Campo** | **Detalle** |
|---|---|
| **Fecha de inspección** | |
| **Nombre del responsable** | |
| **Granja inspeccionada** | |
| **Total de cámaras revisadas** | |
| **Cámaras con novedad** | |
| **Estado final** | ☐ Todas operativas ☐ Pendiente de intervención |

---

## 5. Información de Contacto

| **Área** | **Contacto** |
|---|---|
| Equipo de Mantenimiento | [Completar] |
| Equipo de Tecnología | [Completar] |
| Asimetrix — Soporte técnico | [Completar] |

---

*Documento elaborado bajo estándares de documentación técnica interna. Cualquier modificación al procedimiento debe ser aprobada por el responsable del área de Tecnología.*
