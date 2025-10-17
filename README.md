# Tatoodenda Frontend

Aplicación frontend desarrollada con **Angular** para la plataforma Tatoodenda, un sistema de gestión para estudios de tatuajes.

## 📋 Descripción

Tatoodenda Frontend es una aplicación web que proporciona una interfaz intuitiva para la gestión de tatuajes, citas, clientes y servicios en estudios de tatuaje. Está conectada a una base de datos MySQL y ofrece funcionalidades completas para la administración del negocio.

## 🛠️ Tecnologías

- **Framework**: Angular
- **Lenguaje**: TypeScript
- **Base de Datos**: MySQL
- **Styling**: CSS / SCSS
- **Gestor de Paquetes**: npm

## 📦 Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

- **Node.js** (versión 14.0 o superior)
- **npm** (gestor de paquetes de Node.js)
- **Angular CLI** (versión compatible con tu proyecto)

## 🚀 Instalación

1. **Clona el repositorio**:

```bash
git clone https://github.com/jsersan/tatoodenda-frontend-reducido.git
cd tatoodenda-frontend-reducido
```

2. **Instala las dependencias**:

```bash
npm install
```

3. **Configura las variables de entorno** (si es necesario):

Copia el archivo `.env.example` a `.env` y configura las rutas de tu API backend.

## 🎯 Desarrollo

Para iniciar el servidor de desarrollo:

```bash
ng serve
```

La aplicación estará disponible en `http://localhost:4200/`

El servidor se recargará automáticamente cuando hagas cambios en los archivos del proyecto.

## 🔨 Build para Producción

Para compilar el proyecto para producción:

```bash
ng build --prod
```

Los archivos compilados se generarán en el directorio `dist/`.

## 📁 Estructura del Proyecto

```
src/
├── app/
│   ├── components/        # Componentes reutilizables
│   ├── pages/            # Páginas principales
│   ├── services/         # Servicios para comunicación con la API
│   ├── models/           # Modelos de datos
│   └── app.component.*   # Componente raíz
├── assets/               # Recursos estáticos (imágenes, iconos)
├── environments/         # Configuración de entornos
└── styles/               # Estilos globales
```

## 🔌 API Backend

Esta aplicación se conecta a una API backend que debe estar disponible en:

```
http://localhost:[PUERTO_BACKEND]/api
```

Asegúrate de que el servidor backend está ejecutándose antes de iniciar la aplicación frontend.

## 🧪 Testing

Para ejecutar las pruebas unitarias:

```bash
ng test
```

Para ejecutar pruebas con cobertura:

```bash
ng test --code-coverage
```

## 📱 Características Principales

- Gestión de clientes y tatuadores
- Reserva y gestión de citas
- Catálogo de diseños de tatuajes
- Registro de servicios realizados
- Panel de administración
- Reportes y estadísticas

## 🤝 Contribuir

Si deseas contribuir a este proyecto:

1. Haz un fork del repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo licencia [Especifica la licencia]. Para más detalles, consulta el archivo LICENSE.

## 👤 Autor

**jsersan**

- GitHub: [@jsersan](https://github.com/jsersan)

## 📞 Soporte

Si tienes preguntas o problemas, por favor abre un issue en el repositorio de GitHub.

## 🔗 Recursos Útiles

- [Documentación oficial de Angular](https://angular.io/docs)
- [Guía de TypeScript](https://www.typescriptlang.org/docs/)
- [MySQL Documentation](https://dev.mysql.com/doc/)

---

**Última actualización**: Octubre 2025
