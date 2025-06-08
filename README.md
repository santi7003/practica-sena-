# 🚀 Mi Primer Proyecto con Git & GitHub

¡Bienvenido a mi aventura en el mundo del control de versiones! 🎉

## 📝 Descripción

Este es mi primer proyecto utilizando **Git** y **GitHub** para aprender los fundamentos del versionamiento de código. Aquí documentaré mi progreso y los comandos más importantes que he aprendido durante este emocionante viaje. 🌟

## 🎯 Objetivos del Proyecto

- ✅ Aprender los comandos básicos de Git
- ✅ Crear mi primer repositorio en GitHub
- ✅ Entender el flujo de trabajo con Git
- ✅ Practicar commits, push y pull
- ✅ Documentar mi aprendizaje

## 🛠️ Comandos Git Básicos

### 🏁 Configuración Inicial
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

# Ver estado del repositorio
git status
```

### 💾 Staging y Commits
```bash
# Agregar archivos al staging area
git add archivo.txt          # Agregar un archivo específico
git add .                    # Agregar todos los archivos
git add *.js                 # Agregar archivos por extensión

# Hacer commit de los cambios
git commit -m "Mensaje descriptivo del commit"

# Agregar y hacer commit en un solo paso
git commit -am "Mensaje del commit"
```

### 🌐 Trabajo con Repositorios Remotos
```bash
# Conectar repositorio local con remoto
git remote add origin https://github.com/usuario/repositorio.git

# Ver repositorios remotos
git remote -v

# Subir cambios al repositorio remoto
git push origin main

# Bajar cambios del repositorio remoto
git pull origin main
```

### 📋 Historial y Logs
```bash
# Ver historial de commits
git log

# Ver historial de commits en una línea
git log --oneline

# Ver diferencias entre archivos
git diff

# Ver diferencias en staging area
git diff --staged
```

### 🌿 Trabajo con Ramas (Branches)
```bash
# Ver ramas existentes
git branch

# Crear nueva rama
git branch nombre-rama

# Cambiar a otra rama
git checkout nombre-rama

# Crear y cambiar a nueva rama
git checkout -b nueva-rama

# Fusionar rama con main
git checkout main
git merge nombre-rama
```

## 📚 Recursos Útiles

- 📖 [Documentación oficial de Git](https://git-scm.com/doc)
- 🎓 [GitHub Learning Lab](https://lab.github.com/)
- 🔧 [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
- 📊 [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## 🏆 Mi Progreso

- [x] ✨ Configuración inicial de Git
- [x] 🎯 Primer commit realizado
- [x] 🚀 Repositorio subido a GitHub
- [x] 📝 README.md creado
- [ ] 🌿 Práctica con branches
- [ ] 🔄 Primer pull request
- [ ] 👥 Colaboración en proyecto

## 🤝 Contribuciones

Este es un proyecto de aprendizaje personal, pero si tienes sugerencias o consejos para mejorar, ¡serán muy bienvenidos! 💡

## 📞 Contacto

Si quieres conectar conmigo o compartir tu experiencia aprendiendo Git:

- 💌 Email: tu.email@ejemplo.com
- 🐙 GitHub: [@tuusuario](https://github.com/tuusuario)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para más detalles.

---

⭐ **¡No olvides darle una estrella a este repo si te ayudó en tu aprendizaje!** ⭐

*Creado con ❤️ mientras aprendo Git y GitHub*
