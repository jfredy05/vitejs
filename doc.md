## Características

1. **Pre-bundling**
    - Agrega compatibilidad, pues adapta módulos en CommonJs o UMS, al formato estándar de ECMAScript, los ES Modules.  
<br>

2. **Resolución de dependencias**
    - Usa un servidor estático para exponer los archivos vía URL.
    - Reemplaza tus imports vía NodeJS, por imports URL.
    - Sirve los archivos de forma inteligente y con caché, para optimizar tiempo y procesamiento.  
<br>

3. **Hot Module Replacement (HRM)**
    - Es hacer que ni bien se guarden los archivos en el editor automáticamente se reflejen los cambios sin necesidad recargar el navegador sin perder el estado de la aplicación
    - Permite una mejor experiencia de desarrollo al ser mucho más rápido que los convencionales.  
<br>

4. **Integración simple con TypeScript**
    - Desde el primer momento el proyecto de Vite tiene integración con TypeScript sin necesidad de alguna configuración adicional.
    - Es opcional la configuración de TypeScript.
    - Es totalmente utilizable con cualquier librería o framework.  
<br>

5. **Integración con frameworks**
    - Soporte perfecto con Vue.js.
    - Vite es desarrollado por el team de Vue.js por lo cual la integración es simple y completa.
    - Útil para usar JSX con Vue.js
    - Hace que sea extremadamente simple usar Vite con React.js.  
<br>

6. **Integración de archivos**
    - Resuelve la importación sin necesidad de loaders.
    - Es simple de usar con archivos multimedia, de estilos, de código o con los pre-procesadores más comunes, incluyendo TypeScript.  
<br>

7. **Build Optimization**
    - Permite tomar el control de la configuración.
        - Es opcional el archivo de configuración para vite
    - Optimiza la velocidad en desarrollo gracias a esbuild.
    - Optimiza el bundle de producción gracias a rollup.
        - Mediante el archivo de configuración de Vite se puede configurar el bundler de Rollup
    - Rollup al momento de optimizar hace la importación de dependencias de manera inteligente.
        - Realiza la tarea de forma inteligente de saber cuáles son los módulos que utilizará el proyecto y predecir hasta cierto punto cuáles son los módulos que van a seguir para importarlos de un inicio.  
<br>

8. **Soporte a Web Workers y Web Assembly**
    - Los web workers son una característica de JavaScript para crear procesos alternativos al proceso principal de donde se ejecuta nuestra página web y estos tienen una configuración que puede ser tediosa
        - Con Vite nos permite únicamente importar y utilizarlos.
    - Vite.js nos permite Web Assembly importando los archivo e invocándolo de una cierta manera para que se ejecute
        - Si requiere inyectar alguna dependencia te permite realizarlo
        - Vite te facilita el uso a diferencia de vanilla JS
