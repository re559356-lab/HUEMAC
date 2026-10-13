# EL HUEMAC · Softstar v6.3

Sistema web de demostración para administrar ventas y servicios de EL HUEMAC.

## Abrir el proyecto
1. Descomprime el ZIP.
2. Abre la carpeta en Visual Studio Code.
3. Abre `index.html` con Live Server.

## Accesos iniciales para configuración
- Administrador: usuario `admin`, contraseña `1234`.
- Empleado de ejemplo: usuario `empleado`, contraseña `1234`.

Cambia estos datos en cuanto inicies sesión. No se muestran dentro de la pantalla de acceso.

## Cambios de esta versión
- Logo PNG de Softstar con la línea morada eliminada, colocado únicamente en la esquina superior izquierda de la pantalla de acceso. Al pulsarlo se muestran los créditos.
- El logo, el nombre Softstar y el nombre del proyecto son fijos; el administrador solo puede editar los nombres y roles de los participantes desde **Créditos**.
- Sección **Mi cuenta** para que administrador y empleados cambien usuario y contraseña.
- El administrador puede crear empleados con usuario y contraseña temporal, y cambiar su usuario o restablecer contraseña.
- La aplicación nunca muestra contraseñas guardadas. El administrador puede establecer una nueva, pero no consultar la anterior.
- Se conserva el resto de los módulos de la versión de anuncios: ventas, tickets, servicios, proveedores, gastos, anuncios y reportes.

## Aviso de seguridad importante
Esta versión sigue siendo una aplicación local de demostración: los datos se guardan en `localStorage` del navegador y las contraseñas no están protegidas por un servidor de autenticación. No la uses para información real ni la publiques en internet con estos accesos. Para producción, conecta las cuentas a Supabase Auth y configura políticas RLS; no es suficiente ocultar elementos de la interfaz.


## Corrección de acceso (v6.1)

Si el acceso de administrador no funciona en esta versión de demostración, selecciona **Administrador** y pulsa **“No puedo entrar · Restablecer acceso de prueba”**. Esto cambia solo la cuenta del administrador a usuario `admin` y contraseña `1234`; conserva las ventas, servicios, anuncios y demás datos guardados en este navegador. Cambia la contraseña después de entrar.

Esta recuperación es solo para desarrollo local: al ser una aplicación que guarda datos en el navegador, no debe publicarse en internet como sistema seguro hasta conectarla a un servidor de autenticación y aplicar permisos.


## Créditos de Softstar

El apartado de créditos incluye los nombres y roles revisados ortográficamente: Carlos Navarrete Tapia (Programador), Esmeralda Gudiño Cruz (Analista), Rachel Reséndiz Morán (Tester), Nathaly Andrea Santillán Gómez (Diseñadora) y Camila Serrano Álvarez (Líder). El administrador puede editarlos desde el apartado **Créditos**.


## Ajustes de la versión 6.3

- Se eliminó el logo del menú lateral para que no se repita en las páginas internas.
- Se retiró del apartado de créditos la opción de cargar o reemplazar el logo.
- El archivo PNG conserva su fondo transparente.
