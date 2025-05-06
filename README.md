# Levantamiento-de-Requerimientos-Julian-Lozano
# 📝 Requisitos Funcionales  

## 📜 Descripción  
Este documento describe los **requisitos funcionales** del sistema, detallando las funcionalidades esenciales que debe cumplir para garantizar su correcto funcionamiento.  

## 🔍 Estructura de los Requisitos  
Los requisitos funcionales están organizados en distintas categorías según su propósito dentro del sistema.  

### 1️⃣ GESTIÓN DE USUARIOS Y AUTENTICACIÓN  
- **RF 1.1**: Registro de nuevos usuarios con nombre, correo electrónico y contraseña.  
- **RF 1.2**: Inicio de sesión seguro mediante credenciales válidas.  
- **RF 1.3**: Recuperación de contraseña vía correo electrónico.  
- **RF 1.4**: Gestión de roles (Administrador, Cliente, Vendedor, Gerente).  
- **RF 1.5**: Administración de permisos por parte del administrador.  

### 2️⃣ GESTIÓN DE PRODUCTOS E INVENTARIO  
- **RF 2.1**: Creación, edición y eliminación de productos por administradores.  
- **RF 2.2**: Cada producto incluirá nombre, descripción, precio, stock e imagen.  
- **RF 2.3**: Catálogo digital con filtros y búsquedas avanzadas.  
- **RF 2.4**: Alertas de stock bajo cuando un producto tenga menos de cinco unidades.  
- **RF 2.5**: Actualización automática del estado de disponibilidad de productos agotados.  

### 3️⃣ PROCESAMIENTO DE VENTAS Y PEDIDOS  
- **RF 3.1**: Los clientes podrán agregar productos al carrito de compras.  
- **RF 3.2**: Modificación de cantidad de productos antes de pagar.  
- **RF 3.3**: Integración con pasarelas de pago como PayU y MercadoPago.  
- **RF 3.4**: Generación de números de orden únicos por compra.  
- **RF 3.5**: Seguimiento en tiempo real del estado de los pedidos.  
- **RF 3.6**: Notificación de confirmación de compra vía correo electrónico.  

### 4️⃣ ADMINISTRACIÓN DE REPORTES Y FINANZAS  
- **RF 4.1**: Generación de reportes de ventas (diarios, semanales, mensuales).  
- **RF 4.2**: Exportación de reportes en formatos PDF y Excel.  
- **RF 4.3**: Implementación de gráficos de tendencias de ventas.  
- **RF 4.4**: Registro de gastos operativos para control financiero.  
- **RF 4.5**: Panel de estadísticas con ingresos y productos más vendidos.  

### 5️⃣ SEGURIDAD Y PROTECCIÓN DE DATOS  
- **RF 5.1**: Implementación de cifrado de contraseñas para protección de datos sensibles.  
- **RF 5.2**: Uso de permisos y roles para control de acceso.  
- **RF 5.3**: Copias de seguridad automáticas cada 24 horas.  
- **RF 5.4**: Protección contra ataques XSS e inyección SQL en formularios y bases de datos.  

## 🏗 Consideraciones  
- Este documento debe actualizarse en cada versión del sistema.  
- Cualquier cambio en los requisitos funcionales debe ser validado por el equipo de desarrollo.  
- La implementación debe garantizar la **seguridad**, **usabilidad** y **eficiencia** del sistema.
- # ⚙️ Requisitos No Funcionales

## 📜 Descripción  
Este documento describe los **requisitos no funcionales** del sistema, estableciendo parámetros clave como rendimiento, compatibilidad, seguridad y mantenimiento.

## 🚀 Rendimiento y Escalabilidad  
- **RNF 6.1**: La plataforma debe soportar hasta **500 usuarios simultáneos** sin degradación en el rendimiento.  
- **RNF 6.2**: La interfaz debe cargar en menos de **3 segundos** en condiciones óptimas.  
- **RNF 6.3**: Diseño **responsivo**, adaptándose a dispositivos móviles y de escritorio.  
- **RNF 6.4**: La base de datos debe ser capaz de escalar hasta **50,000 registros** sin comprometer la velocidad de consulta.  

## 🔄 Compatibilidad y Accesibilidad  
- **RNF 7.1**: Compatible con **Google Chrome, Mozilla Firefox y Microsoft Edge**.  
- **RNF 7.2**: Cumplimiento con **WCAG 2.1** para accesibilidad a personas con discapacidad.  
- **RNF 7.3**: Diseño adaptativo con opción de **modo oscuro**.  

## 🔐 Seguridad y Privacidad  
- **RNF 8.1**: Uso de **HTTPS y cifrado SSL/TLS** para la transmisión de datos.  
- **RNF 8.2**: Expiración automática de sesión tras **30 minutos de inactividad**.  
- **RNF 8.3**: **Autenticación en dos pasos (2FA)** para administradores.  

## 🛠 Mantenimiento y Soporte  
- **RNF 9.1**: **Documentación del código** para facilitar futuras mejoras.  
- **RNF 9.2**: Implementación de un **sistema de logs** para el registro de errores.  
- **RNF 9.3**: Establecer un **mecanismo de actualizaciones periódicas** sin afectar la operatividad.  

## 📌 Consideraciones  
- Este documento debe actualizarse con cada versión del sistema.  
- Se recomienda realizar **pruebas de rendimiento** periódicas para asegurar la escalabilidad.  
- La seguridad y accesibilidad deben revisarse conforme a normativas vigentes.  
 

