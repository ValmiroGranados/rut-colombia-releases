# RUT Colombia — Releases

Distribución pública de instaladores de **RUT Colombia**, la aplicación de escritorio para consulta masiva de estado RUT en la DIAN.

> ℹ️ Este repositorio **solo contiene los binarios** (instaladores `.dmg` y `.exe`) publicados automáticamente por el sistema de CI. El código fuente vive en un repositorio privado.

---

## 📥 Descargar la última versión

Ve a la sección de [**Releases**](https://github.com/ValmiroGranados/rut-colombia-releases/releases/latest) y descarga el instalador para tu sistema operativo:

| Plataforma | Archivo |
|---|---|
| 🍎 macOS Apple Silicon (M1/M2/M3/M4) | `RUT-Colombia-{versión}-arm64.dmg` |
| 🍎 macOS Intel | `RUT-Colombia-{versión}.dmg` |
| 🪟 Windows 10/11 | `RUT.Colombia.Setup.{versión}.exe` |

**Direct download de la última versión** (siempre apunta al release más reciente):

- macOS Apple Silicon → [releases/latest](https://github.com/ValmiroGranados/rut-colombia-releases/releases/latest) (descarga el `.dmg` con sufijo `-arm64`)
- macOS Intel → [releases/latest](https://github.com/ValmiroGranados/rut-colombia-releases/releases/latest) (descarga el `.dmg` sin sufijo)
- Windows → [releases/latest](https://github.com/ValmiroGranados/rut-colombia-releases/releases/latest) (descarga el `.exe`)

---

## 🔄 Actualizaciones automáticas

Desde la versión **1.2.0**, RUT Colombia se actualiza automáticamente:

- La app revisa silenciosamente si hay nueva versión al arrancar
- Si encuentra una, muestra un banner discreto con la opción **Actualizar ahora**
- También puedes buscar manualmente en: **Configuración → Buscar actualizaciones**
- La actualización se descarga e instala sin que tengas que reinstalar nada

---

## 🔐 Seguridad

- **macOS**: los instaladores están **firmados con Developer ID de Apple** y **notarizados** por Apple.
- **Windows**: los instaladores actualmente no están firmados; verás un aviso de SmartScreen en la primera instalación. Click en *Más información → Ejecutar de todos modos*.

---

## 📝 Licencia

El instalador es de distribución pública. El uso de la aplicación requiere una **licencia activa** (se gestiona dentro de la app al primer arranque).

---

## 🆘 Soporte

Si encuentras un problema con la instalación o actualización, escribe a **valmirogranadosf@gmail.com**.
