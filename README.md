# FallaAmics

**FallaAmics** es la aplicación oficial de la falla “Amics”, desarrollada con .NET MAUI. Su objetivo es ofrecer una plataforma para gestionar eventos, falleros/falleras, noticias y agenda de la falla, facilitando la organización y comunicación interna de la comunidad.

## 📋 Estado actual

- Proyecto en desarrollo.  
- Estructura básica del proyecto creada (carpetas de Views, ViewModels, Services, Models…).  
- Funcionalidades planificadas: gestión de eventos, noticias, miembros, agenda, notificaciones, almacenamiento en base de datos / servicios cloud.  
- Diseño de vistas y estructura MVVM en marcha.  

## ✨ Funcionalidades previstas

- Gestión de usuarios / miembros de la falla (alta, edición, roles).  
- Creación, edición y eliminación de eventos.  
- Agenda con calendario integrado y vista de eventos.  
- Gestión de noticias/información interna.  
- Subida de imágenes a servicio externo (por ejemplo, imgbb) para eventos o noticias.  
- Integración con base de datos o backend para persistencia y sincronización.  
- Interfaz multiplataforma (Android / iOS / Windows — según soporte de .NET MAUI).


<img width="361" height="587" alt="loginamics (1) (1)" src="https://github.com/user-attachments/assets/c9112752-485a-41ba-8a31-1835b80117f3" />



<img width="300" height="588" alt="mainpagefallaamics (1)" src="https://github.com/user-attachments/assets/2061d896-35d5-4676-8137-040034d749a2" />



<img width="304" height="588" alt="sdfg (1)" src="https://github.com/user-attachments/assets/242ba42d-492c-469b-ae01-4a383afbda95" />



<img width="394" height="652" alt="image" src="https://github.com/user-attachments/assets/939ee2d7-b70d-4e4a-88b4-bcc5fb5c1973" />



<img width="304" height="588" alt="sdfg (2)" src="https://github.com/user-attachments/assets/e94e1e2b-afe9-4ebd-bff2-7e93196c4af5" />







## 📂 Estructura del proyecto

FallaAmics/
│
├── Models/ → Clases de dominio (Evento, Noticia, Usuario, etc.)
├── ViewModels/ → Lógica de vista y binding
├── Views/ → Páginas/XAML de la interfaz de usuario
├── Services/ → Servicios de acceso a datos, cloud, storage, etc.
├── Resources/ → Recursos gráficos, estilos, imágenes, etc.
└── App.xaml(.cs) → Configuración general de la aplicación


Esta estructura sigue un patrón MVVM, ideal para mantener separación de lógica, interfaz y datos.  

## 🛠️ Tecnologías / Herramientas

- .NET MAUI — para desarrollo multiplataforma.  
- C# — lenguaje principal.  
- MVVM — patrón arquitectónico.  
- Posible integración con servicios cloud / base de datos para persistencia.  
- Librerías / paquetes NuGet según necesidad (data binding, acceso a APIs, etc.).  
