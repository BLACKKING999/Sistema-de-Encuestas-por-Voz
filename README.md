# Sistema de Encuestas por Voz

Una aplicación web de encuestas por voz similar a Google Forms, donde la interacción con el encuestado se realiza mediante diálogos hablados.

## Visión General

El sistema permite crear encuestas interactivas que:
- Saludan al encuestado por voz
- Preguntan su nombre
- Realizan las preguntas de la encuesta de forma hablada
- Reciben respuestas por voz
- Analizan respuestas en tiempo real
- Generan gráficos y estadísticas con los resultados

## Tecnologías

### Frontend
- React.js
- Web Speech API para reconocimiento y síntesis de voz
- Chart.js para visualización de resultados
- Tailwind CSS para estilos
- Firebase Authentication para autenticación

### Backend
- Node.js con Express
- MongoDB para almacenamiento de datos
- Firebase Authentication para gestión de usuarios
- compromise.js para procesamiento básico de lenguaje natural

## Estructura del Proyecto

- `/client` - Aplicación frontend en React
- `/server` - API RESTful con Node.js y Express

## Configuración y Despliegue

### Requisitos previos
- Node.js v14 o superior
- MongoDB Atlas cuenta
- Cuenta de Firebase

### Instalación
1. Clonar el repositorio
2. Configurar variables de entorno
3. Instalar dependencias del cliente y servidor
4. Ejecutar aplicación en modo desarrollo

## Funcionalidades
- Creación de encuestas personalizadas
- Interacción por voz con los encuestados
- Análisis de respuestas y visualización de resultados
- Exportación de datos en formatos CSV y PDF
