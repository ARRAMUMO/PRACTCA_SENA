# 🚀 Mi Primer Proyecto con Git & GitHub

¡Bienvenido a mi aventura en el control de versiones! 🎉

## 📋 Descripción

Este es mi primer proyecto utilizando **Git** y **GitHub** para aprender sobre versionamiento de código. Aquí documento mi proceso de aprendizaje y los comandos más importantes que he descubierto.

## 🎯 Objetivos del Proyecto

- ✅ Aprender los comandos básicos de Git
- ✅ Crear mi primer repositorio en GitHub
- ✅ Practicar el flujo de trabajo con commits
- ✅ Entender las ramas (branches) y fusiones (merge)

## 🛠️ Comandos Básicos de Git

### 🔧 Configuración Inicial
```bash
# Configurar nombre de usuario
git config --global user.name "Tu Nombre"

# Configurar email
git config --global user.email "tu.email@ejemplo.com"

# Ver configuración actual
git config --list
```

### 📂 Inicialización y Clonado
```bash
# Inicializar un nuevo repositorio
git init

# Clonar un repositorio existente
git clone https://github.com/usuario/repositorio.git
```

### 📝 Trabajando con Cambios
```bash
# Ver el estado de los archivos
git status

# Añadir archivos al staging area
git add nombre-archivo.txt
git add .  # Añadir todos los archivos

# Hacer commit de los cambios
git commit -m "Descripción del cambio"

# Ver historial de commits
git log
git log --oneline  # Versión compacta
```

### 🌐 Trabajando con Repositorios Remotos
```bash
# Ver repositorios remotos
git remote -v

# Añadir repositorio remoto
git remote add origin https://github.com/usuario/repositorio.git

# Subir cambios al repositorio remoto
git push origin main

# Descargar cambios del repositorio remoto
git pull origin main
```

### 🌿 Trabajando con Ramas (Branches)
```bash
# Ver ramas existentes
git branch

# Crear nueva rama
git branch nueva-rama

# Cambiar a otra rama
git checkout nueva-rama
# O con el comando más moderno:
git switch nueva-rama

# Crear y cambiar a nueva rama en un solo comando
git checkout -b nueva-rama

# Fusionar rama en la rama actual
git merge nombre-rama

# Eliminar rama
git branch -d nombre-rama
```

## 📊 Estados de los Archivos en Git

```
🔴 Untracked → 🟡 Staged → 🟢 Committed → 🔵 Pushed
```

1. **🔴 Untracked**: Archivos nuevos que Git no está siguiendo
2. **🟡 Staged**: Archivos preparados para el próximo commit
3. **🟢 Committed**: Archivos guardados en el historial local
4. **🔵 Pushed**: Cambios enviados al repositorio remoto

## 🎨 Flujo de Trabajo Típico

```bash
# 1. Ver estado actual
git status

# 2. Añadir cambios
git add .

# 3. Hacer commit
git commit -m "✨ Añadir nueva funcionalidad"

# 4. Subir al repositorio remoto
git push origin main
```

## 💡 Consejos y Buenas Prácticas

- 📝 **Commits frecuentes**: Haz commits pequeños y frecuentes
- 💬 **Mensajes claros**: Usa mensajes descriptivos en tus commits
- 🌿 **Usa ramas**: Crea ramas para nuevas funcionalidades
- 🔄 **Pull regularmente**: Mantén tu código actualizado
- 🏷️ **Usa emojis**: Haz tus commits más visuales y organizados

## 📚 Emojis para Commits

- ✨ `:sparkles:` - Nueva funcionalidad
- 🐛 `:bug:` - Corrección de errores
- 📝 `:memo:` - Documentación
- 🎨 `:art:` - Mejoras de formato/estructura
- ⚡ `:zap:` - Mejoras de rendimiento
- 🔧 `:wrench:` - Archivos de configuración
- 🚀 `:rocket:` - Deploy/Release

## 🤝 Contribuir

Si quieres contribuir a este proyecto de aprendizaje:

1. Haz fork del repositorio
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`)
3. Haz commit de tus cambios (`git commit -m '✨ Añadir nueva funcionalidad'`)
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📞 Contacto

- 📧 Email: tu.email@ejemplo.com
- 💼 LinkedIn: [Tu Perfil](https://linkedin.com/in/tu-perfil)
- 🐙 GitHub: [@tu-usuario](https://github.com/tu-usuario)

---

⭐ ¡No olvides darle una estrella a este repo si te ayudó en tu aprendizaje!

**Happy Coding!** 👨‍💻👩‍💻
