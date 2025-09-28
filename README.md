# 🚀 Reglas “suaves” para Pull Requests

### ✅ Normas básicas
- 👀 **No merges propios**  
  No debes hacer *merge* de tus propios Pull Requests.  
  Al menos otra persona debe revisar y aprobar tu PR antes de integrarlo (**regla de los 4 ojos**).  

- ⚙️ **Workflows obligatorios**  
  Antes de hacer *merge*, asegúrate de que todos los *workflows* de integración continua (CI) hayan finalizado correctamente.  
  ❌ No integres un PR si los *workflows* han fallado.  

---

### 🛠️ Responsabilidad sobre los Workflows
- Si un *workflow* de CI falla y la causa **no son tus cambios**, sino un problema del propio workflow:  
  - 🔧 Intenta solucionarlo por tu cuenta.  
  - 📩 Si no es posible, contacta con una de las personas responsables a través de **Telegram**.  

---

### 📂 Workflows actuales
- 🐧 **C/C++ CI (ccpp-linux.yml)** → Responsable: *Pendiente de asignar*  
- 🪟 **C/C++ CI Win64 Compile (ccpp-win64.yml)** → Responsable: *Pendiente de asignar*  

---

⚠️ **Recuerda:** la calidad del código no solo depende de lo que aportes, sino también de mantener los *workflows* y procesos de CI funcionando correctamente.