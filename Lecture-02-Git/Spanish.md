### Clase 2: Tema "Git"

📁 **Git**:
- Almacena historial del proyecto.

🔑 **Autenticación SSH**:
- Dos claves:
  1) Local (privada, una por PC).
  2) Pública remota (del repositorio remoto).

🔄 **Fetch vs Pull**:
- **Fetch**: Obtiene historial del proyecto (todas las ramas).
- **Pull**: Obtiene cambios de código (dentro de ramas).

📍 **HEAD**:
- Apunta dónde estás en el historial de git.
- Ejemplo: Podría apuntar a 3 commits antes del último.

🛠️ **Tres Etapas**:
1) **Directorio de trabajo**: Cambios locales.
2) **Área de preparación**: Archivos modificados para futuros commits.
3) **Historial de commits**: Cambios registrados.

🔧 **Comandos**:
- `branch`: Muestra todas las ramas (y la actual).
- `checkout`: Se mueve a hash de commit o rama.
- `revert`: Crea nuevo commit revirtiendo el último.
- `rebase`: Cambia historial de git, mueve commits entre ramas.
- `reset`: "Resetea dónde apunta HEAD".
  - `hard`: Afecta todas las etapas.
  - `mixed`: Afecta etapas 1 y 2.
  - `soft`: Afecta etapa 1.
- `amend`: Cambia nombre de commit o añade archivos al último commit.
- `cherry pick`: Toma commit arbitrario de una rama y lo mueve a otra.

🔍 **Consejos**:
1) Al conectar local con remoto, evitar añadir archivos al principio.
2) Siempre saber quién más está trabajando en la rama de la funcionalidad para colaborar efectivamente.
