# 🏥 Aplicacion de Atención a Médicos

Aplicación de escritorio para la gestión y seguimiento en tiempo real de la atención a médicos del **Hospital Christus Muguerza**.

---

## 🚀 Tecnologías utilizadas

[![C#](https://img.shields.io/badge/C%23-.NET-512BD4?style=for-the-badge&logo=csharp&logoColor=white)](https://dotnet.microsoft.com/)
[![WinForms](https://img.shields.io/badge/UI-WinForms-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/desktop/winforms/)
[![SQL Server](https://img.shields.io/badge/SQL_Server-Database-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](https://www.microsoft.com/en-us/sql-server)

---

## 📌 ¿Qué hace?

La aplicacion de atencion a medicos permite al personal del hospital registrar y dar seguimiento al flujo de atención de médicos. A través de una interfaz sencilla, el usuario puede:

- Consultar el listado actualizado de médicos en atención
- Conocer el estatus de cada atención.
- Identificar la aseguradora y la responsabilidad asociada a cada médico
- Exportar la información a Excel para reportes

Los datos se actualizan automáticamente en tiempo real: cualquier cambio registrado en el sistema se refleja de forma inmediata en todos los equipos conectados, sin necesidad de recargar manualmente.

---

## 📷 Capturas de pantalla



---

## 📋​ Requisitos del sistema

| Requisito | Detalle |
|---|---|
| Sistema operativo | Windows 10 o superior |
| .NET Framework | 4.7.2 o superior |
| Conectividad | Red local o VPN con acceso al servidor backend |
| Permisos | Usuario estándar de Windows (no requiere administrador) |
| Resolución mínima | 1280 × 720 |

---

## 💽 Instalación

1. Descarga el instalador o el paquete `.zip` proporcionado por el equipo de desarrollo.
2. Extrae el contenido en la ubicación deseada (por ejemplo: `C:\Hospital\ApplicationATMED\`).
3. Ejecuta `Atencion_Medicos.exe`.

> No se requiere instalación adicional si el equipo ya cuenta con .NET Framework 4.7.2.  
> Si no lo tiene, descárgalo desde: https://dotnet.microsoft.com/download/dotnet-framework/net472

---

## 🧩 Configuración

Antes de usar la aplicación por primera vez, el administrador debe verificar que los siguientes parámetros estén correctamente configurados en el archivo `App.config`:

| Parámetro | Descripción |
|---|---|
| `ServerUrl` | URL del servidor backend al que se conecta la aplicación, en este caso al ser local, debe ser una URL del equipo que funcionara como servidor |
| `ConnectionString` | Cadena de conexión a la base de datos SQL Server |

> ⚠️ No compartas ni publiques el archivo `App.config` ya que contiene información sensible de conexión.

Si necesitas ajustar estos valores, contacta al equipo de desarrollo o al administrador de sistemas.

---

### 🖥️ Flujo básico

1. **Iniciar la aplicación** — Al abrirla, se establece automáticamente la conexión con el servidor. Un indicador en pantalla confirma si la conexión fue exitosa.
2. **Consultar médicos en atención** — La pantalla principal muestra el listado actualizado en tiempo real con estatus, aseguradora, responsabilidad, fecha de entrega entre muchas mas columnas.
3. **Filtrar información** — Usa los filtros disponibles para buscar por médico, aseguradora o estatus.
4. **Exportar a Excel** — Haz clic en el botón de exportación para generar un archivo `.xlsx` con la información visible en pantalla, los datos a exportar podran ser locales, filtrados desde la base de datos o todos los registros que se encuentren en la base de datos.

---

## 💻 Versiones

| Versión | Fecha | Cambios |
|---|---|---|
| v1.0.0 | — | Versión inicial |

> _Actualiza esta sección con cada nueva versión que se libere._

---

## 🧑‍💻 Equipo y contacto

Este sistema es desarrollado y mantenido por el equipo de desarrollo interno del Hospital Muguerza.

Para reportar errores, solicitar nuevas funcionalidades o escalar un problema técnico, contacta a:

- **Responsable del proyecto:** [@urlcm](https://github.com/urlcm)

---

## 🪪 Licencia

© Hospital Muguerza. Uso interno exclusivo — todos los derechos reservados.  
Prohibida su distribución, reproducción o uso fuera del ámbito institucional sin autorización expresa.
