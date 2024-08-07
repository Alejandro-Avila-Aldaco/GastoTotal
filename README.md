# GastoTotal

## Tabla de Contenido
1. [Resumen](#resumen)
2. [Requerimientos](#requerimientos)
3. [Instalación](#instalación)
4. [Configuración](#configuración)
5. [Uso](#uso)
6. [Contribución](#contribución)
7. [Roadmap](#roadmap)

## Resumen

### Descripción
GastoTotal es una aplicación web diseñada para ayudar a las pequeñas empresas a gestionar sus gastos mensuales de manera eficiente. Permite a los usuarios registrar y visualizar los montos de los tickets de compra, con un historial de gastos totales por mes y año. 

### Problema Identificado
La empresa familiar Dulcería del 8 tiene deficiencias tecnológicas, utilizando un punto de venta obsoleto y calculando los gastos manualmente con papel y calculadora. Este proceso es ineficiente y propenso a errores.

### Solución
GastoTotal proporciona una solución moderna y automatizada para registrar y visualizar los gastos mensuales, mejorando la precisión y eficiencia del proceso. La aplicación cuenta con una interfaz intuitiva, una base de datos para almacenar los datos y funcionalidades de registro e inicio de sesión para usuarios autorizados.

### Arquitectura
La arquitectura de la aplicación se basa en una estructura de cliente-servidor utilizando tecnologías Java EE, JSP, CSS y MySQL. El servidor de aplicaciones es Tomcat 10.1 y la base de datos se gestiona con MySQL a través de PhpMyAdmin.

## Requerimientos

### Servidores
- Servidor de Aplicaciones: Tomcat v10.1
- Base de Datos: MySQL con PhpMyAdmin

### Paquetes Adicionales
- JDBC para MySQL
- Jakarta EE

### Versión de Java
- Java SE 11

## Instalación

### ¿Cómo instalar el ambiente de desarrollo?
1. Clonar el repositorio:
   
   git clone https://github.com/Alejandro-Avila-Aldaco/GastoTotal.git

2. Importar el proyecto en Eclipse como un proyecto Maven.
   
3. Configurar el servidor Tomcat en Eclipse.

4. Añadir las dependencias necesarias en el archivo pom.xml

### ¿Cómo ejecutar pruebas manualmente?
1. Iniciar el servidor Tomcat desde Eclipse.

2. Acceder a la aplicación a través de http://localhost:8080/GastoTotal.

3. Probar las funcionalidades de login, registro e ingreso de montos manualmente.

### ¿Cómo implementar la solución en producción en un ambiente local?
1. Generar el archivo WAR del proyecto desde Eclipse.

2. Desplegar el archivo WAR en el servidor Tomcat configurado en producción.

3. Asegurarse de que la base de datos MySQL esté configurada y accesible.

## Configuración

### Configuración del producto
- web.xml Configuración del despliegue de la aplicación.
- DBConnection.java Configuración de la conexión a la base de datos MySQL.

### Configuración de los requerimientos
Asegurarse de que el servidor Tomcat y MySQL estén instalados y configurados correctamente.
Configurar las credenciales de la base de datos en DBConnection.java.

## Uso

### Referencia para usuario
Login: Ingresar credenciales de usuario para acceder a la aplicación.

Registro: Crear una nueva cuenta de usuario.

Ingreso de Monto: Registrar el monto de los tickets de compra.

Historial de Gastos: Visualizar el historial de gastos por mes y año.

### Referencia para usuario administrador
Administrar usuarios y permisos.

Gestionar la base de datos y realizar copias de seguridad.

## Contribución

### Guía de contribución para usuarios
1. Clonar el repositorio:
   
  git clone https://github.com/Alejandro-Avila-Aldaco/GastoTotal.git

2. Crear un nuevo branch:
   
  git checkout -b feature/nueva-funcionalidad

3. Realizar los cambios y hacer commit:
   
  git add .
  git commit -m "Descripción de los cambios"

4. Enviar el pull request:
   
  git push origin feature/nueva-funcionalidad

## Roadmap

### Requerimientos Futuros
1. Reportes Personalizados Avanzados: Implementar reportes detallados y gráficos avanzados.

2. Notificaciones Automáticas: Añadir funcionalidades de notificaciones automáticas por correo electrónico o SMS.

3. Integración con Otros Sistemas Externos: Permitir la integración con sistemas de contabilidad y gestión.

4. Análisis de Datos Avanzado: Implementar funcionalidades de análisis de datos para obtener insights valiosos.

