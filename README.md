# UniTrack - Gestión Académica (Fase 1) 🎓

Este proyecto es una aplicación **Full-Stack** diseñada para la gestión de estudiantes y sus historiales académicos, desarrollada como parte del tercer semestre de la **Licenciatura en Administración de Sistemas Informáticos** en la **Universidad Regional de Guatemala**.

## 🚀 Funcionalidades Principales

### 1. Gestión de Estudiantes (Lista Simple Enlazada)
* **Registro**: Formulario para dar de alta estudiantes con Carnet, Nombres, Apellidos y Correo.
* **Visualización**: Representación gráfica de los nodos con punteros simples (`→`) apuntando al siguiente elemento y finalizando en `NULL`.
* **Inversión**: Función para invertir el orden de los punteros de la lista.

### 2. Historial Académico (Lista Doble Enlazada)
* **Interactividad**: Al seleccionar un estudiante, se despliega su historial de cursos.
* **Estructura Doble**: Visualización de nodos con punteros anterior y siguiente (`↔`), demostrando el manejo de listas doblemente enlazadas.
* **Ordenamiento**: Implementación de algoritmo de ordenamiento (QuickSort/Bubble) para organizar las notas de mayor a menor.

## 🛠️ Tecnologías Utilizadas

* **Frontend**: Angular 17+ (Standalone Components).
* **Lenguaje**: TypeScript.
* **Estilos**: CSS3 con diseño responsivo.
* **Backend**: Node.js / Express (Repositorio independiente).
* **Control de Versiones**: Git & GitHub.

## 📋 Estructura del Proyecto

* `src/app/components/gestion-academica`: Lógica y diseño de la interfaz principal.
* `src/app/services/estudiante.service.ts`: Capa de servicio para la comunicación con la API.
* Visualización Gráfica:
  * **Nodos Azules**: Representan la Lista Simple (Estudiantes).
  * **Nodos Verdes**: Representan la Lista Doble (Cursos/Notas).

## 👤 Autor
* **Nombre**: Jose Milian
* **Carnet**: 2527304
* **Universidad**: Universidad Regional de Guatemala
