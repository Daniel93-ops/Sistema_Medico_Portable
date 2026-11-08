# Sistema Web de Citas Médicas Portable

Sistema web para registrar citas médicas que funciona desde una sola carpeta, sin instalar servidores ni bases de datos.
Proyecto de la asignatura **Interacción Humano-Computador** – UNEMI, Guía de práctica N.º 4.

## Tecnologías
- PHP 8.5 (servidor web embebido `php -S`)
- SQLite mediante PDO (`pdo_sqlite`)
- HTML5 y CSS3

## Estructura
```
Sistema_Medico_Portable/
├── EJECUTAR_SISTEMA.bat   # Lanzador: abre el navegador e inicia el servidor
├── index.php              # Login, registro y reporte de citas
├── db_config.php          # Conexión a SQLite y creación automática de tablas
├── css/style.css          # Estilos de la interfaz
└── php/php.ini            # Configuración (extension=pdo_sqlite activa)
```

## Instalación
1. Descargar este repositorio (botón **Code → Download ZIP**) y extraerlo.
2. Descargar PHP 8.5 para Windows x64, versión *Thread Safe* (ZIP), desde https://windows.php.net/download/
   y copiar su contenido dentro de la carpeta `php/`, **sin reemplazar** el `php.ini` incluido.
3. Doble clic en `EJECUTAR_SISTEMA.bat`. Se abre http://127.0.0.1:8080 (si no carga, presionar F5).
4. La base de datos `citas_medicas.db` se crea automáticamente en la primera ejecución.

**Credenciales de demostración:** usuario `admin` · contraseña `1234`

## Manual
El manual de usuario y técnico completo se entrega en PDF en el aula virtual.
