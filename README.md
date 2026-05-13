# Taller 7.1 MaterialExplorer: Implementación de Material You en Jetpack Compose
### Descripción
Contiene un explorador de superficies desarrollado para demostrar la integración de Material Design 3 (MD3) en entornos Android modernos. La aplicación implementa un sistema de diseño reactivo donde los esquemas de color de los componentes visuales (botones, tarjetas y barras) se derivan dinámicamente del fondo de pantalla del usuario. 
### Características Técnicas
•	Scaffold: Estructura base que organiza de forma jerárquica la TopAppBar, el FloatingActionButton (FAB) y el contenedor de contenido principal. 

•	Color Dinámico (Material You): Uso de MaterialTheme.colorScheme para vincular tonalidades primarias, secundarias y terciarias directamente al fondo del sistema mediante el soporte de API 31+. 

•	Diseño Responsivo: Implementación de componentes Card y Button que ajustan automáticamente su contraste y tonalidad para garantizar la legibilidad y armonía visual. 

•	Tipografía y Fuentes: Integración de la librería ui-text-google-fonts para el manejo de tipografías externas siguiendo los estándares actuales de Compose. 

### Requisitos de Entorno
•	IDE: Android Studio Ladybug 2024.2.1 o superior. 

•	Minimum SDK: API 31 (Android 12.0). 

•	Target SDK: API 35/36. 

•	Herramientas: Jetpack Compose con soporte para Material Design 3. 

### Estructura de Componentes Clave
1.	TopAppBar: Utiliza primaryContainer para la barra de navegación superior. 
2.	FloatingActionButton: Implementado con tertiaryContainer para destacar acciones principales. 
3.	Surface Cards: Empleo de secondaryContainer para superficies de información secundaria. 
4.	OutlinedButton (Desafío): Componente de contorno que utiliza el token outline del esquema de colores para verificar la adaptabilidad del borde. 
### Instrucciones de Verificación
1.	Ejecutar la aplicación en un emulador con API 31 o superior. 
2.	Minimizar la aplicación y acceder a los ajustes de "Wallpaper & style" del sistema. 
3.	Cambiar el fondo de pantalla por uno con una paleta cromática distinta. 
4.	Regresar a la aplicación para observar la actualización automática del esquema cromático en todos los componentes visuales
