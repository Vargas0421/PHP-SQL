# PHP-SQL
📚 Sistema de gestión de cursos y estudiantes (MVC en PHP)

Este proyecto consiste en un sistema web desarrollado en **PHP** bajo el patrón **MVC**, diseñado para la gestión de cursos y estudiantes dentro de una institución académica.  

---

## 🚀 Guía para iniciar el proyecto en XAMPP

### 1️⃣ Clonar o descargar el repositorio
- Dirígete al repositorio del proyecto en GitHub.  
- Haz clic en el botón verde **Code**.  
- Selecciona **Download ZIP** y descomprime el archivo en tu computadora.  

---

### 2️⃣ Instalar y configurar XAMPP
- Asegúrate de tener **XAMPP** instalado en tu computadora.  
- Si no lo tienes, descárgalo desde:  
  👉 [https://www.apachefriends.org/es/index.html](https://www.apachefriends.org/es/index.html)

---

### 3️⃣ Mover el proyecto a la carpeta `htdocs`
- Copia la carpeta del repositorio descargado.  
- Pégala en la ruta:  


👉 Ejemplo:  
Si el proyecto se llama **SC502-1C2025-GRUPO7**, la ruta quedará:  


---

### 4️⃣ Abrir XAMPP y acceder a phpMyAdmin
1. Abre **XAMPP Control Panel**.  
2. Haz clic en **Start** en los servicios de **Apache** y **MySQL**.  
3. Presiona el botón **Admin** (a la derecha de MySQL) para abrir **phpMyAdmin** en el navegador.  

---

### 5️⃣ Importar la base de datos
1. En **phpMyAdmin**, haz clic en la pestaña **SQL**.  
2. Abre el archivo del proyecto que contiene el código SQL (termina en `.sql`).  
3. Copia todo el contenido de ese archivo.  
4. Pégalo en el cuadro SQL de phpMyAdmin y presiona **Continuar**.  

---

### 6️⃣ Configurar la conexión a la base de datos
Busca el archivo de conexión (ejemplo: `conexion.php`) y asegúrate de que los valores sean los siguientes:

```php
$host = "localhost";
$user = "root";
$pass = "";
$dbname = "sc502_1c2025_grupo7";
7️⃣ Abrir el proyecto en el navegador

En el XAMPP Control Panel, haz clic en Admin al lado de Apache.

Se abrirá la página principal en http://localhost.

Escribe el nombre de la carpeta del proyecto en la barra de direcciones.

👉 Ejemplo:http://localhost/SC502-1C2025-GRUPO7

4.Ingresa a la carpeta proyecto/app para acceder al sistema.

La ruta final puede verse así:

http://localhost/SC502-1C2025-GRUPO7/proyecto/app

🛠️ Tecnologías utilizadas

PHP (MVC)

MySQL (Base de datos)

XAMPP (Entorno local)

HTML, CSS, JavaScript (Frontend)
