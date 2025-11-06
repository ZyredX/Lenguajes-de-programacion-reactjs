# 🚗|🏍️ Gestión de Vehículos y Motos — App Web React  

**Proyecto académico**  
Este proyecto fue creado usando JavaScript moderno (ES6+), el cual ayuda a gestionar los vehiculos y motos, permitiendo (Crear,eliminar,modificar,mostrar), usando librerias populares para la UI, este proyecto es necesario que funcione simultaneamente junto con el backend.  

## 🧠 Objetivo del proyecto  

El propósito del proyecto es aplicar conceptos de **React.js**, algunos son:  
- Manejo de estado con *hooks* (useState, useEffect, useRef, useImperativeHandle).  
- Comunicación con APIs REST mediante.  
- Integración con Bootstrap y SweetAlert2.  
- Envío de archivos e imágenes mediante `FormData`.

## 📤 Aplicaciones Principales (Obligatorias)
‣ 🟦 **Visual Studio Code** | Esta es la App que permite editar todo el codigo, ejecutarlo y instalar las extensiones. | [Descargar](https://vscode.download.prss.microsoft.com/dbazure/download/stable/7d842fb85a0275a4a8e4d7e040d2625abbf7f084/VSCodeUserSetup-x64-1.105.1.exe)  
‣ 🟩 **Node Js** | Es la App que permite usar el servidor de manera local | [Descargar](https://nodejs.org/dist/v25.1.0/node-v25.1.0-x64.msi)

## 📂 Características

▷ CRUD completo de **Vehículos** y **Motos**.  
▷ Interfaz amigable basada en **React-Bootstrap**.  
▷ **Modales dinámicos** para agregar y editar registros.  
▷ **Gestión de imágenes** para cada elemento.  
▷ Confirmaciones y alertas con **SweetAlert2**.  
▷ Código organizado en **componentes reutilizables**.  
▷ Conexión a un **backend REST API** (por defecto en `http://localhost:8080/api`).

## ⛏️ Tecnologías utilizadas  

 **React.js (Vite)** | Framework de UI basado en componentes.   
 **Bootstrap 5 / React-Bootstrap:** | Estilos y componentes responsivos. 
 **SweetAlert2:** | Alertas personalizadas y modales de confirmación. 
 **Fetch API:** Comunicación HTTP con el backend. 
 **JavaScript (ES6+):** | Lógica del cliente. 
 **FormData:**  Manejo de formularios y subida de imágenes (Diseño). 


## 🔑 Estructura del proyecto  

src/  
├── components/  
│ ├── AlertMessage.js # Manejo de alertas  
│ ├── ItemForm.jsx # Formulario para crear/editar ítems  
│ ├── ItemList.jsx # Lista dinámica de ítems (vehículos/motos)  
│ └── ItemModal.jsx # Modal que contiene el formulario  
│  
├── App.jsx # Componente principal con tabs para Vehículos y Motos  
├── main.jsx # Punto de entrada de la aplicación  
└── index.css # Estilos globales  


## 🖥️ Vista general  

Al ejecutar la aplicación, se muestra una interfaz con **dos pestañas principales**:  

- **Vehículos** 🚘  
- **Motos** 🏍️  

Cada pestaña permite:
- Visualizar las imagenes y informacion de los vehiculos/motos existentes.    
- Agregar un nuevo elemento mediante un **modal dinámico**.  
- Editar o eliminar registros con **alertas de confirmación**.  

<img src="img/Mostrarpestañas.jpg" alt="vistaGeneral" width="550">  

## 🔌 Configuración y ejecución  

### 1️⃣ Clonar el repositorio  

abrir Cmd  
git clone https://github.com/DanielDev87/vehiculos-front.git  
cd react-vehiculos-motos-crud  

### 2️⃣ Instalar dependencias (Tienes que abrir una Terminal en visual studio code)  

npm install  

<img src="img/installnpm.jpg" alt="install" width="550">  

### 3️⃣ Ejecutar la aplicación  

npm run dev  

<img src="img/npmrundev.jpg" alt="RunNpm" width="550">  

En este caso el puerto esta configurado para **http://localhost:5173/**  

### 4️⃣ Configurar el backend  
La app se comunica con una API REST disponible en:  
http://localhost:8080/api/  

## Asegúrate de tener disponibles los siguientes endpoints:  
- GET /api/vehiculos  
- POST /api/vehiculos  
- PUT /api/vehiculos/{id}  
- DELETE /api/vehiculos/{id}  

- GET /api/motos  
- POST /api/motos  
- PUT /api/motos/{id}  
- DELETE /api/motos/{id}  

Cada registro puede incluir una imagen asociada al vehículo o moto.  

# 📷 Capturas del funcionamiento  

# 🚗 Agregar Vehiculo  
<img src="img/CrearV.jpg" alt="crear" width="550">  

# 🚗 Editar Vehiculo  
<img src="img/ActuV.jpg" alt="Delete" width="550">  

# 🚗 Eliminar Vehiculo  
<img src="img/EliminarV.jpg" alt="Delete" width="550">  

# 🏍️ Agregar Moto  
<img src="img/CrearM.jpg" alt="crear" width="550">  

# 🏍️ Editar Moto  
<img src="img/ActuM.jpg" alt="Delete" width="550">  

# 🏍️ Eliminar Moto  
<img src="img/EliminarM.jpg" alt="Delete" width="550">  

## 🔑 CREDITOS
» Este trabajo fue supervisado por Daniel Felipe, quien brindó apoyo constante para que todo funcionara correctamente.
Todo esto fue posible gracias a el!
