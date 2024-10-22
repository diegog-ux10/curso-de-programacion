# Tarea: Configuración inicial de Git y GitHub

## Objetivos
- Instalar Git en tu computadora
- Crear una cuenta de GitHub
- Aprender comandos básicos de Git
- Trabajar con ramas (branches)
- Publicar cambios en GitHub

## Requisitos previos
- Una computadora con Windows, Mac o Linux
- Conexión a internet
- Correo electrónico

## Paso 1: Instalar Git

### Para Windows:
1. Ve a https://git-scm.com/download/win
2. Descarga el instalador de Git para Windows
3. Ejecuta el archivo descargado
4. Acepta todas las opciones predeterminadas durante la instalación
5. Para verificar la instalación:
   - Abre el "Command Prompt" (CMD) o "PowerShell"
   - Escribe: `git --version`
   - Deberías ver el número de versión de Git

### Para Mac:
1. Abre la Terminal
2. Si ya tienes Homebrew instalado, escribe: `brew install git`
3. Si no tienes Homebrew:
   - Ve a https://git-scm.com/download/mac
   - Descarga e instala Git
4. Verifica la instalación con: `git --version`

### Para Linux:
1. Abre la Terminal
2. Para Ubuntu/Debian: `sudo apt-get install git`
3. Para Fedora: `sudo dnf install git`
4. Verifica la instalación con: `git --version`

## Paso 2: Crear una cuenta de GitHub
1. Ve a https://github.com
2. Haz clic en "Sign up"
3. Ingresa:
   - Tu correo electrónico
   - Crea una contraseña
   - Elige un nombre de usuario
4. Verifica tu correo electrónico
5. Completa la configuración inicial de tu cuenta

## Paso 3: Configurar Git en tu computadora
1. Abre la Terminal (Mac/Linux) o CMD/PowerShell (Windows)
2. Configura tu nombre:
   ```bash
   git config --global user.name "Tu Nombre"
   ```
3. Configura tu correo (usa el mismo que usaste en GitHub):
   ```bash
   git config --global user.email "tu@email.com"
   ```

## Paso 4: Clonar el repositorio del profesor
1. El profesor te proporcionará una URL del repositorio
2. Abre la Terminal o CMD
3. Navega a la carpeta donde quieres guardar el proyecto:
   ```bash
   cd Documents
   ```
4. Clona el repositorio:
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   ```
5. Entra a la carpeta del proyecto:
   ```bash
   cd [NOMBRE_DEL_REPOSITORIO]
   ```

## Paso 5: Crear tu rama personal
1. Asegúrate de estar en la rama principal:
   ```bash
   git checkout main
   ```
2. Crea tu nueva rama con tu nombre:
   ```bash
   git checkout -b nombre-apellido
   ```
   Ejemplo: `git checkout -b juan-perez`

## Paso 6: Realizar cambios y publicarlos
1. Realiza los cambios necesarios en los archivos
2. Verifica el estado de tus cambios:
   ```bash
   git status
   ```
3. Añade tus cambios:
   ```bash
   git add .
   ```
4. Guarda tus cambios con un mensaje:
   ```bash
   git commit -m "Agregando mi nombre al proyecto"
   ```
5. Publica tu rama en GitHub:
   ```bash
   git push origin nombre-apellido
   ```

## Problemas comunes y soluciones

### Si Git no reconoce el comando:
- Windows: Reinicia el CMD o PowerShell
- Mac/Linux: Asegúrate de que Git está instalado con `git --version`

### Si no puedes hacer push:
1. Asegúrate de estar conectado a internet
2. Verifica que hayas hecho commit de tus cambios
3. Confirma que tienes los permisos necesarios en el repositorio

### Si aparece error de autenticación:
1. Es posible que necesites generar un token de acceso personal en GitHub
2. Ve a GitHub → Settings → Developer settings → Personal access tokens
3. Genera un nuevo token y úsalo como contraseña cuando Git lo solicite

## ¿Necesitas ayuda?
- Consulta con tu profesor
- Revisa la documentación oficial de Git: https://git-scm.com/doc
- Visita la ayuda de GitHub: https://docs.github.com