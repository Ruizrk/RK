<p align="center"> 
<a href="https://github.com/GataNina-Li"><img src="http://readme-typing-svg.herokuapp.com?font=mono&size=17&duration=4000&color=F7B11B&center=falso&vCenter=falso&lines=GataBot-MD++%F0%9F%90%88;Gracias+por+visitar+este+repositorio.+%F0%9F%92%96" height="90px"></a> 
</p>
 
<p align="center">
<img src="https://i.imgur.com/kd8sus3.jpeg" alt="GataBot-MD" width="800"/>

### 🌟 (OPCIÓN 1) INSTALACIÓN AUTOMÁTICA 🫰
[![blog](https://img.shields.io/badge/Instalacion-Automatica-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/PESW8LXXlOI?feature=share)
> **Note** Comandos para instalar de forma automática en Termux  
```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget mpv && wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBot-MD/master/gata.sh | bash
```
### Edita lo siguiente si deseas usar este método de instalación en tú repositorio previamente hecho un fork
```js
// PERSONALIZAR INSTALACIÓN AUTOMÁTICA (En caso de una Bifurcación)
// Parámetros editables

// REFERENCIA
"wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBot-MD/master/gata.sh | bash"

// PARÁMETROS QUE PUEDE SER MODIFICADOS --> "[...]"
// Reemplace por su usuario de GitHub, y nombre del repositorio
"wget -O - https://raw.githubusercontent.com/[usuario]/[repositorio]/master/gata.sh | bash"
```
#### MODIFICAR ARCHIVO [`gata.sh`](https://github.com/GataNina-Li/GataBot-MD/blob/master/gata.sh)
```js
//LÍNEAS A MODIFICAR
205 --> "git clone https://github.com/[user]/[repositorio].git"
//Ejemplo: git clone https://github.com/GataNina-Li/GataBot-MD.git

209 --> "cd [repositorio]"
//Ejemplo: cd GataBot-MD

//Una vez hecho estos cambios ejecute los nuevos comandos en Termux
```
-----
### 🪄 (OPCIÓN 2) INSTALACIÓN MANUAL POR TERMUX - GITHUB 
> **Note** Comandos para instalar de forma manual
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install -y git nodejs ffmpeg imagemagick yarn
```
```bash
git clone https://github.com/GataNina-Li/GataBot-MD && cd GataBot-MD
```
```bash
yarn install && npm install
```
```bash
npm start
```
> **Warning** Si aparece (Y/I/N/O/D/Z) [default=N] ? use la letra "y" + "ENTER" para continuar con la instalación 
----
### 📁 (OPCIÓN 3) INSTALACIÓN POR TERMUX - ARCHIVOS
> **Note** Descargué y Descomprime
### [`GataBot-MD ~ Archivos`](https://github.com/GataNina-Li/GataBot-MD/archive/refs/heads/master.zip)
[![blog](https://img.shields.io/badge/Termux-GataBotMD-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://youtu.be/UcWlyQ8u5HE)
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install -y git nodejs ffmpeg imagemagick yarn
```
```bash
cd storage/downloads/GataBot-MD-master/GataBot-MD-master 
```
```bash
yarn install
```
```bash
npm install
```
```bash
npm start
```
* #### APLICACIÓN RECOMENDADA PARA [`DESCOMPRIMIR`](https://play.google.com/store/apps/details?id=com.rarlab.rar)
* #### APLICACIÓN RECOMENDADA PARA EDITAR [`NÚMERO DE OWNER`](https://play.google.com/store/apps/details?id=com.rhmsoft.code)
> **Note** Guardar los archivos en la ubicación: storage/downloads/GataBot-MD-master/GataBot-MD-master   
----
### 🚀 USAR GATABOT 24/7 EN TERMUX 
> Ejecutar estos comandos dentro de la carpeta GataBot-MD
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
``` 
#### ⬇️ Opciones Disponibles
> **Warning** Esto eliminará todo el historial que hayas establecido con PM2:
```bash 
pm2 delete index
``` 
> Si tienes cerrado Termux y quiere ver de nuevo la ejecución use:
```bash 
pm2 logs 
``` 
> Si desea detener la ejecución de Termux use:
```bash 
pm2 stop index
``` 
> Si desea iniciar de nuevo la ejecución de Termux use:
```bash 
pm2 start index
``` 
---- 
### 👉 ACTIVAR EN CASO DE DETENERSE EN TERMUX
> [!NOTE]
> Si despues que ya instalastes tu bot y termux te salta en blanco, se fue tu internet o reiniciaste tu celular, solo realizaras estos pasos:
```bash
cd && cd GataBot-MD && npm start
```
----
### ✳️ OBTENER OTRO CODIGO QR EN TERMUX
> **Warning** deten el bot, haz click en el símbolo (ctrl) [default=z] usar la letra "z" + "ENTER" hasta que salga algo verdes similar a: `GataBot-MD $`
> Escribe los siguientes comando uno x uno :
```bash 
cd && cd GataBot-MD && rm -rf GataBotSession && npm run qr
```
----
### ✳️ OBTENER NUEVO CÓDIGO DE 8 DÍGITOS 
```bash 
cd && cd GataBot-MD && rm -rf GataBotSession && npm run code
```
----
### 😼 ACTUALIZAR GATABOT
> **Note** Comandos para actualizar GataBot-MD de forma automática
```bash
grep -q 'bash\|wget' <(dpkg -l) || apt install -y bash wget && wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBot-MD/master/update.sh | bash 
```
#### Para que no pierda su progreso en GataBot, estos comandos realizarán un respaldo de su `database.json` y se agregará a la versión más reciente.
> **Warning** Estos comandos solo funcionan para TERMUX, REPLIT, LINUX                       
