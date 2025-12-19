<div align="center">

# 📚 Guía Git para Estudiantes ADSO_MASTERS

**Cómo subir tu progreso diario al repositorio del proyecto**

---

</div>

## 🎯 Objetivo

Esta guía te enseñará paso a paso cómo usar Git y GitHub para documentar tu progreso diario en el proyecto de Infraestructura Cloud Segura. Es **simple, rápido y profesional**.

---

## 📋 Tabla de Contenidos

- [🛠️ Requisitos Previos](#️-requisitos-previos)
- [⚡ Método Rápido (Recomendado)](#-método-rápido-recomendado)
- [💻 Método Línea de Comandos](#-método-línea-de-comandos)
- [📝 Formato del Archivo Diario](#-formato-del-archivo-diario)
- [🆘 Problemas Comunes](#-problemas-comunes)
- [💡 Tips Profesionales](#-tips-profesionales)

---

## 🛠️ Requisitos Previos

### ✅ Necesitas tener:

1. **Cuenta de GitHub** → [Crear cuenta aquí](https://github.com/signup)
2. **Git instalado** en tu ordenador
3. **Acceso al repositorio** del proyecto

### 🔍 Verificar que Git está instalado

Abre tu terminal y ejecuta:

```bash
git --version
```

Si aparece algo como `git version 2.x.x`, ¡estás listo! ✅

Si no, instala Git:
- **Windows:** [git-scm.com/downloads](https://git-scm.com/downloads)
- **Linux:** `sudo apt install git` o `sudo dnf install git`
- **macOS:** `brew install git`

---

## ⚡ Método Rápido (Recomendado)

### Para principiantes o si quieres ir rápido

<div align="center">

### 🌐 **Opción 1: Subir desde GitHub.com (SIN comandos)**

</div>

1. **Ve al repositorio** en tu navegador
   ```
   https://github.com/TU-USUARIO/ADSO_MASTERS_Infraestructura_Cloud_Segura
   ```

2. **Haz clic en "Add file" → "Create new file"**

3. **Nombra tu archivo**
   ```
   avance_dia_1.md
   ```
   *(Cambia el número según el día)*

4. **Escribe tu contenido** usando la [plantilla](#-formato-del-archivo-diario)

5. **Scroll hasta abajo** y rellena:
   - **Commit message:** `📝 Avance día 1 - [Breve descripción]`
   - **Extended description:** Opcional - detalles adicionales

6. **Haz clic en "Commit changes"**

✅ **¡Listo!** Tu progreso está guardado

---

## 💻 Método Línea de Comandos

### Para quienes prefieren la terminal

<details>
<summary><b>🔽 Haz clic para expandir las instrucciones detalladas</b></summary>

### 📥 Paso 1: Clonar el repositorio (solo la primera vez)

```bash
# Navega a la carpeta donde quieres trabajar
cd ~/Documentos

# Clona el repositorio
git clone https://github.com/TU-USUARIO/ADSO_MASTERS_Infraestructura_Cloud_Segura.git

# Entra en la carpeta
cd ADSO_MASTERS_Infraestructura_Cloud_Segura
```

### 📝 Paso 2: Crear archivo de avance diario

```bash
# Crea el archivo (cambia X por el número de día)
nano avance_dia_1.md

# O usa tu editor favorito
code avance_dia_1.md
vim avance_dia_1.md
```

Copia la [plantilla de formato](#-formato-del-archivo-diario) y complétala con tu información.

### 📤 Paso 3: Subir cambios a GitHub

```bash
# 1. Añadir el archivo al staging
git add avance_dia_1.md

# 2. Hacer commit con mensaje descriptivo
git commit -m "📝 Avance día 1 - Configuración VPC y subredes"

# 3. Subir los cambios
git push origin main
```

### 🔄 Paso 4: Para días siguientes

```bash
# Antes de empezar cada día, actualiza tu repositorio local
git pull origin main

# Crea el nuevo archivo del día
nano avance_dia_2.md

# Repite el paso 3
git add avance_dia_2.md
git commit -m "📝 Avance día 2 - [Tu descripción]"
git push origin main
```

</details>

---

## 📝 Formato del Archivo Diario

### Plantilla: `avance_dia_X.md`

Copia y pega esta plantilla. **Reemplaza la información entre corchetes `[...]`**:

```markdown
# 📅 Avance Día [NÚMERO] - [FECHA]

**Estudiante:** [Tu Nombre]  
**Equipo:** [Nombre del equipo]  
**Fecha:** [DD/MM/YYYY]

---

## 🎯 Objetivos del Día

- [ ] [Objetivo 1]
- [ ] [Objetivo 2]
- [ ] [Objetivo 3]

---

## ✅ Tareas Completadas

### 1. [Nombre de la tarea]

**Descripción:**  
[Explica qué hiciste]

**Comandos ejecutados:**
```bash
# Ejemplo
sudo systemctl start apache2
```

**Resultado:**  
✅ [Éxito / Parcial / Pendiente]

**Evidencia:**  
![Captura de pantalla](ruta/a/imagen.png)

### 2. [Otra tarea]

[Repite el formato...]

---

## 📸 Capturas de Pantalla

> Incluye capturas de los pasos más importantes

![Descripción](url-o-ruta-imagen)

---

## ⚠️ Problemas Encontrados

### Problema 1: [Título del problema]

**Descripción:**  
[¿Qué pasó?]

**Error recibido:**
```
[Copia el mensaje de error aquí]
```

**Solución aplicada:**  
[¿Cómo lo resolviste? o "Pendiente de resolver"]

**Solicitud de ayuda:**  
- [ ] Necesito soporte del profesor
- [ ] Resuelto por mí mismo
- [ ] Resuelto con ayuda del equipo

---

## 📝 Notas Adicionales

[Cualquier observación, aprendizaje importante, o recordatorio para mañana]

---

## 🔗 Enlaces Útiles

- [Documentación consultada]
- [Tutoriales seguidos]

---

## ⏱️ Tiempo Dedicado

**Total:** [X horas]

**Distribución:**
- Configuración: [X horas]
- Investigación: [X horas]
- Resolución de problemas: [X horas]
- Documentación: [X horas]

---

<div align="center">

**📌 Próximos pasos para mañana:**

1. [Tarea pendiente 1]
2. [Tarea pendiente 2]
3. [Tarea pendiente 3]

---

*Documentado con 💙 por [Tu nombre]*

</div>
```

---

## 🆘 Problemas Comunes

<details>
<summary><b>❌ Error: "Permission denied (publickey)"</b></summary>

**Causa:** No tienes configurada una clave SSH.

**Solución:**

1. Genera una clave SSH:
```bash
ssh-keygen -t ed25519 -C "tu_email@ejemplo.com"
```

2. Copia la clave pública:
```bash
cat ~/.ssh/id_ed25519.pub
```

3. Agrégala en GitHub: **Settings → SSH and GPG keys → New SSH key**

O usa HTTPS en lugar de SSH cuando clones:
```bash
git clone https://github.com/usuario/repo.git
```

</details>

<details>
<summary><b>❌ Error: "Updates were rejected"</b></summary>

**Causa:** Tu repositorio local está desactualizado.

**Solución:**
```bash
git pull origin main
git push origin main
```

</details>

<details>
<summary><b>❌ "No tengo permisos para subir archivos"</b></summary>

**Causa:** No tienes acceso de escritura al repositorio.

**Solución:** Contacta al profesor para que te añada como colaborador.

</details>

<details>
<summary><b>🤔 "¿Cómo subo imágenes?"</b></summary>

**Opción 1:** Arrastra y suelta la imagen directamente en GitHub al editar

**Opción 2:** Guarda imágenes en una carpeta `imagenes/` en tu repo
```markdown
![Descripción](imagenes/captura_dia1.png)
```

</details>

---

## 💡 Tips Profesionales

### ✨ Buenas Prácticas

1. **Commits frecuentes** → Mejor muchos pequeños que uno grande
2. **Mensajes descriptivos** → `✅ Configurar firewall` mejor que `update`
3. **Documentar errores** → Son oportunidades de aprendizaje (+0.5 puntos!)
4. **Capturas claras** → Asegúrate de que se vea bien el contenido

### 🎨 Emojis para Commits

Haz tus commits más visuales:

- 📝 `:memo:` → Documentación
- ✨ `:sparkles:` → Nueva funcionalidad
- 🐛 `:bug:` → Corrección de bug
- 🔒 `:lock:` → Seguridad
- 🔥 `:fire:` → Eliminar código
- 🚀 `:rocket:` → Deployment
- ⚡ `:zap:` → Mejora de rendimiento
- 💄 `:lipstick:` → UI/estilo

**Ejemplo:**
```bash
git commit -m "🔒 Configurar SSH keys y desactivar password login"
```

### 📊 Checklist Diaria

Antes de finalizar cada día, verifica:

- [ ] Archivo `avance_dia_X.md` creado y completo
- [ ] Al menos 2 capturas de pantalla incluidas
- [ ] Problemas documentados (si los hubo)
- [ ] Cambios subidos con `git push`
- [ ] Mensaje de commit descriptivo
- [ ] Próximos pasos definidos para mañana

---

## 🎓 Recursos de Aprendizaje

### 📚 Git & GitHub

- [Git - La guía sencilla](https://rogerdudler.github.io/git-guide/index.es.html)
- [Learn Git Branching (interactivo)](https://learngitbranching.js.org/?locale=es_ES)
- [GitHub Docs en Español](https://docs.github.com/es)

### 🎥 Videos Recomendados

- [Git y GitHub desde cero](https://www.youtube.com/watch?v=3GymExBkKjE)
- [Markdown Tutorial](https://www.youtube.com/watch?v=oxaH9CFpeEE)

### 🔧 Herramientas Útiles

- [GitHub Desktop](https://desktop.github.com/) → Git con interfaz gráfica
- [Visual Studio Code](https://code.visualstudio.com/) → Editor con Git integrado
- [Markdown Preview](https://markdownlivepreview.com/) → Vista previa de Markdown

---

<div align="center">

## 🚀 ¡Estás listo para empezar!

### Recuerda: **El push diario es OBLIGATORIO**

Cada día sin push = día sin documentar = pérdida de puntos 😱

---

### 🆘 ¿Necesitas ayuda?

1. **Revisa esta guía** primero
2. **Consulta con tu equipo**
3. **Pregunta al profesor** (y documéntalo para +0.5 puntos)

---

### 💪 Consejos Finales

> *"El mejor momento para documentar es AHORA, mientras lo recuerdas."*

> *"Un commit al día mantiene el suspenso alejado."* 😄

---

**⭐ Recuerda:** La documentación profesional es una habilidad clave en el mundo IT

**¡Buena suerte, ADSO_MASTERS!** 🎯

</div>
