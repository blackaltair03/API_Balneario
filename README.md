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
