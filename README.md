# Violette POS — Releases

Punto oficial de **distribución de actualizaciones** de Violette POS, el
sistema de punto de venta con facturación electrónica para Costa Rica
(comprobantes electrónicos v4.4, Hacienda / ATV).

> Este repositorio contiene **únicamente los instaladores** publicados. El
> código fuente es **privado y propietario**. La aplicación verifica este
> repositorio automáticamente para ofrecer actualizaciones a las
> instalaciones existentes.

## Descargar

La última versión está siempre disponible en la pestaña
**[Releases](../../releases/latest)**. Descargue el instalador
`ViolettePOS_Setup_X.Y.Z.exe`.

## Verificar la descarga (opcional)

Cada release incluye un archivo `.sha256`. Para confirmar la integridad del
instalador en Windows (PowerShell):

```powershell
Get-FileHash .\ViolettePOS_Setup_X.Y.Z.exe -Algorithm SHA256
```

El valor debe coincidir con el del archivo `.sha256` del release.

## Actualizaciones automáticas

Violette POS revisa este repositorio al iniciar sesión (solo para el
administrador) y, si hay una versión más reciente, ofrece instalarla con un
clic. La actualización conserva sus datos y ventas.

## Licencia

Software **propietario**. © 2026 — Todos los derechos reservados. El uso
requiere una licencia válida otorgada por el titular. Consulte el archivo
`LICENSE`. Descargar el instalador no concede derecho de uso.# violette-pos-releases
