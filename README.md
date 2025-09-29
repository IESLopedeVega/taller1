## Objetivos
- Clonar este repositorio.  
- Trabajar en **ramas de grupo**.  
- Cada integrante del grupo hace **cambios distintos en el mismo archivo**.  
- Subir los cambios y abrir un **Pull Request (PR)**.  
- Revisar, aprobar y hacer **merge**.  
- Resolver un conflicto si aparece.  

---

## Pasos

### 1. Clonar el repositorio
1. Abre **GitHub Desktop**.  
2. Ve a **File → Clone repository…**.  
3. Pega la URL de este repo.  
4. Elige una carpeta local y pulsa **Clone**.  

---

### 2. Crear rama de grupo
Dependiendo del grupo al que pertenezcas será:
- **Grupo A** → `feature/grupo-a`  
- **Grupo B** → `feature/grupo-b`  
- **Grupo C** → `feature/grupo-c`

  Usaremos la carpeta feature porque vamos a añadir contenido nuevo. Si fueran arreglos se utilizaría la carpeta "fix".
  Podríamos no utilizar esta carpeta, pero así queda más organizado.

En GitHub Desktop:  
1. Arriba, en **Current branch**, pulsa **New branch…**.  
2. Escribe el nombre de la rama de tu grupo.  
3. Pulsa **Create branch** y luego **Publish branch**.  

---

### 3. Trabajo colaborativo dentro del grupo
Cada grupo tiene su propio archivo:  
- Grupo A → `grupoA.md`  
- Grupo B → `grupoB.md`  
- Grupo C → `grupoC.md`  

**Cada integrante del grupo debe añadir su nombre al mismo archivo**:  
- Su nombre en una lista.  
- Un emoji que te represente.  

Importante: **no trabajéis todos en la misma máquina**, cada persona hace su commit en su rama de grupo.  

Pasos para cada persona:  
1. Abre el archivo de tu grupo.  
2. Añade tu línea.  
3. En GitHub Desktop:  
   - Revisa **Changes**.  
   - Escribe un mensaje en **Summary** (ej.: `feat: añade integrante María al grupo A`).  
   - Pulsa **Commit to feature/grupo-x**.  
   - Pulsa **Push origin**.  

---

### 4. Crear Pull Request (PR)
Cuando todos los miembros de un grupo hayan subido sus commits. 
El o la responsable del grupo debe:

1. En GitHub Desktop → botón **Create Pull Request**.
Todos los cambios del grupo deben aparecer en ese PR.
3. Se abre GitHub en el navegador:  
   - **Title**: `feat: añade integrantes grupo A`.  
   - **Description**: breve explicación.  
   - Asigna un **Reviewer** (otro grupo).  
4. El o la responsable del equipo pulsa **Create Pull Request**.  

---

### 5. Revisar y mergear
- El grupo revisor abre el PR en GitHub.  
- Comprueba que están los nombres de todos.  
- Deja un comentario y aprueba.  
- Haz clic en **Merge pull request → Confirm merge**.  
- Opcional: **Delete branch**.  

---

### 6. Resolver conflictos (si aparecen)
Si dos personas han editado exactamente la **misma línea** del archivo, GitHub marcará un **conflicto**:  
1. Abre el PR → GitHub mostrará un aviso de conflicto.  
2. Pulsa **Resolve conflicts**.  
3. Edita el archivo para quedarte con todas las aportaciones (eliminando las marcas `<<<<<<<`, `=======`, `>>>>>>>`).  
4. Guarda y confirma la resolución.  
5. Completa el **Merge**.  

---

### 7. Ver resultados
- Todos cambian a la rama `main`.  
- Pulsa **Fetch origin** y luego **Pull origin**.  
- Verás que el archivo de tu grupo contiene todas las aportaciones. 🎉  

---

## Checklist
- [ ] Cloné el repo.  
- [ ] Creé la rama de mi grupo.  
- [ ] Hice commit con mi aporte.  
- [ ] Subí la rama al remoto.  
- [ ] Creamos un PR con todos los cambios del grupo.  
- [ ] Revisamos y mergeé un PR.  
- [ ] Sincronizé "main" y vi el resultado final.  

---
