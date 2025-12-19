<div align="center">

# 🚀 ADSO_MASTERS
## Infraestructura Cloud Segura

[![License: GPL v2](https://img.shields.io/badge/License-GPL_v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![Course](https://img.shields.io/badge/Curso-2025--2026-green)]()
[![Status](https://img.shields.io/badge/Status-Active-success)]()
[![Institution](https://img.shields.io/badge/Instituto-CI.Estella-orange)]()

### 🎓 Administración de Sistemas Operativos

*Proyecto educativo de despliegue de infraestructura cloud segura*

---

</div>

## 📋 Tabla de Contenidos

- [🎯 Objetivo del Proyecto](#-objetivo-del-proyecto)
- [🔧 Tecnologías y Herramientas](#-tecnologías-y-herramientas)
- [📌 Reglas de Entrega](#-reglas-de-entrega)
- [📊 Rúbrica de Evaluación](#-rúbrica-de-evaluación)
- [📅 Calendario de Entregas](#-calendario-de-entregas)
- [🤝 Contribución](#-contribución)
- [📜 Licencia](#-licencia)

---

## 🎯 Objetivo del Proyecto

Desplegar una **infraestructura cloud segura** que demuestre dominio en:

<table>
<tr>
<td width="50%">

### Competencias Técnicas
- ✅ **Redes y segmentación**
- ✅ **Gestión de usuarios y permisos**
- ✅ **Seguridad y control de acceso**

</td>
<td width="50%">

### Competencias Profesionales
- ✅ **Automatización de servicios**
- ✅ **Documentación profesional**
- ✅ **Trabajo en equipo**

</td>
</tr>
</table>

---

## 🔧 Tecnologías y Herramientas

<div align="center">

| Categoría | Tecnologías |
|:---------:|:------------|
| ☁️ **Cloud** | Oracle Cloud Infrastructure (OCI) |
| 🐧 **SO** | Oracle Linux / Ubuntu Server |
| 🔐 **Seguridad** | SSH Keys, Firewall, VPN/Bastion Host |
| 📊 **Monitoring** | Grafana |
| ⚙️ **Automation** | n8n, Bash Scripts |
| 📝 **Versionado** | Git/GitHub |

</div>

---

## 📌 Reglas de Entrega

### 🔄 Push Diario Obligatorio

> **Repositorio:** `https://github.com/mikelapestegia/ADSO_MASTERS_Infraestructura_Cloud_Segura.git`

Cada día de trabajo debe incluir un commit con:

```markdown
📁 avance_dia_X.md (X = número de día)
├── 📝 Resumen de actividades realizadas
├── 📸 Capturas de pantalla o logs
├── ⚠️ Errores y problemas encontrados
└── 💡 Solicitudes de soporte (+0.5 puntos extra)
```

### 🎥 Defensa Final

<details>
<summary><b>Requisitos del Video (5-7 minutos)</b></summary>

- ✅ Participación de todos los miembros del equipo
- ✅ Demo en vivo de la infraestructura
- ✅ Explicación de decisiones técnicas
- ✅ Resumen de medidas de seguridad implementadas
- ✅ Lecciones aprendidas y desafíos superados

</details>

---

## 📊 Rúbrica de Evaluación

<div align="center">

### 💯 Puntuación Total: 100 puntos
**✅ Nota mínima para aprobar: 60 puntos**

</div>

### 🏗️ 1. Infraestructura y Red (20 pts)

| Nivel | Puntos | Criterios |
|:-----:|:------:|:----------|
| 🟢 **Excelente** | 20 | VPC personalizada, subredes bien configuradas, acceso seguro con VPN o Bastion Host |
| 🟡 **Bueno** | 15 | VPC propia con segmentación básica |
| 🟠 **Suficiente** | 10 | VPC por defecto, sin diseño personalizado |
| 🔴 **Insuficiente** | 0-5 | No hay conectividad o configuración insegura |

### 👥 2. Gestión de Usuarios y Permisos (20 pts)

| Nivel | Puntos | Criterios |
|:-----:|:------:|:----------|
| 🟢 **Excelente** | 20 | Múltiples usuarios/grupos, jerarquía clara, uso correcto de `chmod`/`chown` |
| 🟡 **Bueno** | 15 | Usuarios creados correctamente, permisos funcionales |
| 🟠 **Suficiente** | 10 | Todos admin o permisos inseguros (777) |
| 🔴 **Insuficiente** | 0-5 | Todo hecho como root ❌ |

### 🔐 3. Seguridad y Acceso (25 pts)

| Nivel | Puntos | Criterios |
|:-----:|:------:|:----------|
| 🟢 **Excelente** | 25 | Solo acceso por llave SSH, sin contraseña, firewall restringido |
| 🟡 **Bueno** | 18 | Llave SSH habilitada, pero permite contraseña |
| 🟠 **Suficiente** | 10 | Solo acceso por contraseña, firewall abierto |
| 🔴 **Insuficiente** | 0-5 | No se puede acceder o SSH falla |

### ⚙️ 4. Servicios y Automatización (25 pts)

| Nivel | Puntos | Criterios |
|:-----:|:------:|:----------|
| 🟢 **Excelente** | 25 | Grafana + n8n funcionando, integración con Git, persistencia al reiniciar |
| 🟡 **Bueno** | 18 | Un servicio funcional, Git configurado |
| 🟠 **Suficiente** | 10 | Solo Git o Apache básico sin Grafana/n8n |
| 🔴 **Insuficiente** | 0-5 | Servidor vacío o servicios caídos |

### 📝 5. Documentación y Defensa (10 pts)

| Nivel | Puntos | Criterios |
|:-----:|:------:|:----------|
| 🟢 **Excelente** | 10 | PDF claro, capturas paso a paso, demo fluida |
| 🟠 **Suficiente** | 5 | Documentación incompleta o demo con problemas |
| 🔴 **Insuficiente** | 0 | Sin entrega o sin defensa |

---

## 📅 Calendario de Entregas

| Fecha | Entrega | Descripción |
|:-----:|:--------|:------------|
| 📌 **Diario** | Push obligatorio | Archivo `avance_dia_X.md` con progreso |
| 📆 **Final** | Video de defensa | Presentación grupal de 5-7 minutos |
| 📁 **Final** | Documentación PDF | Documento completo del proyecto |

---

## 🤝 Contribución

Este proyecto es parte del programa de **Formación Profesional** en **CI.Estella**.

### 👥 Equipo

> Añade aquí los miembros de tu equipo

- **Miembro 1:** [Nombre] - Rol
- **Miembro 2:** [Nombre] - Rol
- **Miembro 3:** [Nombre] - Rol

### 📬 Contacto

- **Institución:** CI.Estella
- **Curso:** Administración de Sistemas Operativos
- **Período:** 2025-2026

---

## 📜 Licencia

Este proyecto está bajo la licencia [GPL-2.0](LICENSE).

---

<div align="center">

## 🧠 ¡Vamos ADSO_MASTERS!

### 💡 Consejo del Día

*"Si tu firewall permite 0.0.0.0/0 en el puerto 22...*  
*tu servidor tiene más agujeros que un Death Star tras el ataque de los rebeldes."* 🌌💥

---

**⭐ Si este proyecto te resulta útil, considera darle una estrella**

[![GitHub stars](https://img.shields.io/github/stars/mikelapestegia/ADSO_MASTERS_Infraestructura_Cloud_Segura?style=social)](https://github.com/mikelapestegia/ADSO_MASTERS_Infraestructura_Cloud_Segura/stargazers)

</div>
