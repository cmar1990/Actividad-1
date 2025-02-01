# Instalaci贸n y Configuraci贸n de un Proyecto con Vite y React-TS

## Consultas en PowerShell

Se realizaron las siguientes consultas para verificar las versiones de Node.js, npm y npx:

```powershell
node --version
npm -v
npx --version
![Consulta ](Actividad-1/1.jpg)


Instalaci贸n de npm

Si es necesario actualizar npm, se muestra el siguiente aviso:

npm notice To update run: npm install -g npm@11.1.0

Creaci贸n del Proyecto con Vite y React-TS

En la carpeta donde se alojar谩 el proyecto, ejecutar el siguiente comando:

npm create vite@latest introduccion -- --template react-ts

Alternativamente, se puede usar npx:

npx create-vite introduccion --template react-ts

Al finalizar, seguir los siguientes pasos:

cd introduccion
npm install
npm run dev

Proyecto Levantado

Si la instalaci贸n y configuraci贸n fueron exitosas, se podr谩 acceder al proyecto en:

Local: http://localhost:5173/

Network: Usar --host para exponer el servidor


Para ver las opciones de ayuda, presionar h + Enter.



