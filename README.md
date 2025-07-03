# 📌 API_Balneario - Guía Completa para Colaboradores 🚀

Bienvenido al repositorio **API_Balneario**  
Este proyecto es una **API REST** construida con **Laravel 10**.

---

## ⚙️ Ramas Oficiales

| Rama     | Descripción                                                     |
|----------|-----------------------------------------------------------------|
| `main`   | Contiene el **código estable en producción**. **No desarrolles directo aquí.** |
| `develop`| Rama base para **desarrollo e integración** de nuevas funcionalidades. |

**👉 Regla clave:**  
- Todo trabajo nuevo **parte de `develop`** usando ramas `feature/*` para funcionalidades.  
- Para bugs urgentes en producción, se usan ramas `hotfix/*` desde `main`.

---

## 🌿 Convenciones para Nombres de Ramas

- **Nuevas funcionalidades:**  
  `feature/nombre-descriptivo`  
  _Ejemplos:_ `feature/registro-usuarios`, `feature/login-api`

- **Correcciones urgentes:**  
  `hotfix/nombre-descriptivo`  
  _Ejemplos:_ `hotfix/fix-login-error`

---

## ✅ Flujo Básico para Colaborar

### 1️⃣ Clonar el proyecto

```bash
git clone https://github.com/TU-USUARIO/API_Balneario.git
cd API_Balneario

```
---
## 🌿 Gestión de Ramas
```bash
# Cambiar a develop
git checkout develop

# Crear nueva rama feature
git checkout -b feature/nombre-funcionalidad
git push -u origin feature/nombre-funcionalidad

# Crear rama hotfix (desde main)
git checkout main
git checkout -b hotfix/nombre-fix
```
---
##🔄 Flujo de Trabajo
# Subir cambios
```bash
git add .
git commit -m "Mensaje descriptivo"
git push origin nombre-rama

# Sincronizar rama
git fetch origin
git rebase origin/develop
🆘 Solución de Problemas
bash
# Resolver conflictos en rebase
git add .
git rebase --continue

# Cancelar rebase
git rebase --abort

# Resetear cambios
git reset --hard COMMIT_ID

# Eliminar ramas
git branch -d nombre-rama
git push origin --delete nombre-rama
```
---
##🔄 Actualizar ramas
```bash
# Para features
git checkout develop
git pull origin develop
git checkout feature/nombre-rama
git merge develop

# Para hotfixes
git checkout main
git pull origin main
git checkout hotfix/nombre-fix
git merge main
```
