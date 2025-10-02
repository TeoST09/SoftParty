Sistema de Parqueadero 

Descripción
Proyecto en PHP orientado a objetos (POO) con HTML, CSS y un poco de Bootstrap. Es un sistema de parqueadero que permite registrar ingresos (facturas), guardar y descargar PDFs de facturas (usa mpdf), revisar fechas, y buscar registros por estado (activo / inactivo). Código pensado para ser simple, funcional y fácil de entender.

Características principales

Arquitectura en POO (PHP) para modelos, controladores y lógica.

Interfaz con HTML / CSS y Bootstrap para estilos rápidos y responsivos.

Generación de facturas en PDF con mpdf (se instala vía Composer).

Guardado de PDFs en una carpeta (y opción para descargar).

Búsqueda por fecha y filtrado por activo / inactivo.

CRUD básico para tarifas y registros de ingreso/salida de vehículos.

Exportar / descargar facturas, ver historial, y consultar por rango de fecha.

Tecnologías

PHP (procedimental + POO en partes clave)

HTML5 / CSS3 + Bootstrap (v4 o v5)

Composer (para librería PDF mpdf/mpdf)

MySQL (o MariaDB)

JS mínimo (solo para interacciones simples, p. ej. confirmaciones)

Requisitos

PHP >= 7.4 (recomendado 8.x)

MySQL / MariaDB

Composer instalado globalmente

Apache / Nginx o servidor local (XAMPP, Laragon, etc.)
