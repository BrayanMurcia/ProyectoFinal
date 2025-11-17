# 🚀 ProyectoFinal – Git y GitHub

**👤 Autor:** Brayan Yesid Murcia Torres  
**📅 Fecha:** 16/11/2025  

---

## 📌 Descripción General

Este proyecto corresponde a la práctica del flujo de trabajo con **Git y GitHub**, aplicando:

- Creación de ramas  
- Commits organizados  
- Pull Requests  
- Fusiones (*merge*)  
- Revisión del historial mediante `git log`

El trabajo inició en la rama `main` y posteriormente en una rama secundaria para simular un flujo de desarrollo real, integrando los cambios mediante Pull Request.

---

## 🧩 Lista de Comandos Utilizados

```bash
git init
git clone <url>

git status
git add .
git commit -m "mensaje del commit"
git push

git checkout -b ramaSecundaria
git checkout main
git checkout ramaSecundaria

git push origin ramaSecundaria

git pull

git log
git log --oneline
