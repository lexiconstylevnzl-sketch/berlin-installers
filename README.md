# BERLIN Negocios

Instaladores oficiales de BERLIN para Windows y Mac. Este repositorio público distribuye binarios; no contiene datos de clientes ni el código privado de la plataforma.

**[Descargar la versión más reciente](https://github.com/lexiconstylevnzl-sketch/berlin-installers/releases/latest)** · **[Conocer BERLIN](https://berlin-oficial-events.vercel.app/sistema)** · **[Mi negocio](https://berlin-oficial-events.vercel.app/negocio)**

## Instalar

- Windows 10/11 x64: descarga `BERLIN-Setup-Windows-x64.exe` y sigue el asistente.
- Mac Apple Silicon: descarga `BERLIN-Mac-AppleSilicon.dmg` y copia BERLIN a Aplicaciones.
- Mac Intel: descarga `BERLIN-Mac-Intel.dmg` y copia BERLIN a Aplicaciones.

No necesitas instalar Python. Las versiones iniciales no tienen firma comercial de Microsoft ni notarización de Apple; las políticas de tu organización pueden exigir esos certificados. Las versiones de Mac se compilaron y probaron en macOS 14 ARM y macOS 15 Intel. El archivo `SHA256SUMS.txt` permite comprobar la integridad de las descargas.

## Activar

1. Registra tu cuenta web y solicita tu negocio en **Mi negocio**.
2. Acuerda la suscripción con BERLIN y recibe tu llave mensual por un medio privado.
3. Abre la aplicación, introduce la llave y crea tu administrador local. Las instalaciones nuevas no tienen una contraseña predeterminada.
4. Usa **Mesas y pedidos online** para abrir tu panel e iniciar sesión con la cuenta propietaria del negocio.

Cada negocio administra sus espacios con QR, carta, pedidos a barra y cocina, reservas por horario, eventos y entradas. Estas funciones usan internet y el panel web; no instalan un servidor LAN local. Las herramientas locales anteriores conservan su base SQLite independiente.

La suscripción y los pagos se concilian manualmente con BERLIN. No se realizan cargos recurrentes automáticos. La renovación reemplaza la llave y añade un mes de calendario. No publiques tu llave ni la incluyas en los QR de las mesas.

## Datos y actualizaciones

Los instaladores no incluyen bases, contraseñas, llaves ni credenciales de clientes. Tus datos locales se guardan en `%LOCALAPPDATA%\BERLIN` en Windows y `~/Library/Application Support/BERLIN` en Mac. El desinstalador de Windows conserva esa carpeta. Respalda tus datos antes de actualizar o cambiar de equipo.

El software incluye avisos de licencias de sus dependencias de terceros dentro del paquete.
