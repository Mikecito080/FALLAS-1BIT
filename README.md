# Fallas de almacén · 1Bit

Reporte interactivo. `index.html` es la página y `fallas.json` guarda los datos (fallas, comentarios y estado de gestión).

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (ej. `fallas-1bit`).
2. Sube `index.html` y `fallas.json` a la raíz (Add file → Upload files).
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. En 1–2 minutos queda en `https://TU-USUARIO.github.io/fallas-1bit/`. Ese es el enlace para tu jefe (modo lectura).

## Crear el token para poder guardar (solo tú)
1. GitHub → tu foto → Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token.
2. Repository access: *Only select repositories* → elige el repo de fallas.
3. Permissions → Repository permissions → **Contents: Read and write**.
4. Pon una expiración (ej. 90 días) y copia el token.
5. Abre la página → botón **Soy editor** → pega usuario, repo, rama y token → Guardar.
   El token queda solo en tu navegador, nunca en el repo.

## Uso diario
- Importa el Excel de 1Bit (solo agrega las líneas nuevas) o usa **+ Nueva falla**.
- Escribe comentarios y cambia la gestión.
- Pulsa **Guardar en GitHub**. Tu jefe ve los cambios en 1–2 minutos.
- **Exportar JSON** descarga una copia de respaldo.
