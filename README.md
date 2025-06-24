# 💬 Chat Simulator

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Material 3](https://img.shields.io/badge/Material%203-757575?style=for-the-badge&logo=material-design&logoColor=white)

Una aplicación de chat que simula conversaciones entre dos personas, donde puedes cambiar de usuarios fácilmente y ver timestamps de las conversaciones.

## 📱 Características

- **🔄 Cambio dinámico entre usuarios**: Alterna fácilmente entre diferentes usuarios en la conversación
- **💬 Interfaz de chat intuitiva**: Diseño familiar y fácil de usar
- **⏰ Timestamp automático**: Marca de tiempo automática en todos los mensajes
- **🎨 Diseño moderno y responsivo**: Interfaz adaptable con Material 3
- **✨ Animaciones fluidas**: Transiciones suaves y elegantes

## 🛠️ Tecnologías Utilizadas

- **Flutter**: Framework de UI multiplataforma
- **Dart**: Lenguaje de programación
- **Provider**: Gestión de estado
- **Material 3**: Sistema de diseño moderno
- **Intl**: Internacionalización y formato de fechas

## 📋 Requisitos

- Flutter SDK (>= 3.7.2)
- Dart SDK
- Android Studio / VS Code
- Android SDK (para desarrollo Android)
- Xcode (para desarrollo iOS - solo macOS)

## 🚀 Instalación

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/tuusuario/app-chat-sim.git
   cd app-chat-sim
   ```

2. **Instala las dependencias**
   ```bash
   flutter pub get
   ```

3. **Genera los iconos de la aplicación**
   ```bash
   dart run flutter_launcher_icons
   ```

4. **Genera el splash screen**
   ```bash
   dart run flutter_native_splash:create
   ```

5. **Ejecuta la aplicación**
   ```bash
   flutter run
   ```

## 📱 Plataformas Soportadas

- ✅ **Android** (API 21+)
- ✅ **iOS** (iOS 11+)
- ✅ **Web**
- ✅ **Windows**
- ✅ **macOS**
- ✅ **Linux**

## 📂 Estructura del Proyecto

```
lib/
├── assets/                 # Recursos (imágenes, iconos)
├── config/
│   └── theme/             # Configuración de temas
├── domain/
│   └── entities/          # Entidades del dominio
├── presentation/
│   ├── chat/              # Pantalla principal de chat
│   ├── providers/         # Gestión de estado
│   ├── screens/           # Pantallas adicionales
│   └── widgets/           # Widgets reutilizables
└── routes/                # Configuración de rutas
```

## 🎯 Uso

1. **Iniciar conversación**: Abre la aplicación y comienza a escribir mensajes
2. **Cambiar usuario**: Usa el botón de cambio para alternar entre usuarios
3. **Ver historial**: Todos los mensajes se mantienen con sus timestamps
4. **Navegar**: Accede a los créditos y configuraciones desde el menú

## 🔧 Configuración de Desarrollo

### Configurar iconos personalizados
```bash
# Edita flutter_launcher_icons.yaml con tu imagen
dart run flutter_launcher_icons
```

### Configurar splash screen
```bash
# Edita la configuración en pubspec.yaml
dart run flutter_native_splash:create
```

### Limpiar proyecto
```bash
flutter clean
flutter pub get
```

## 📸 Capturas de Pantalla

> *Próximamente: Capturas de pantalla de la aplicación*

## 🤝 Contribuir

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver `LICENSE` para más detalles.

## 👨‍💻 Desarrollador

**Cristhian Recalde**
- 📧 Email: [isnotcristhian@gmail.com](mailto:isnotcristhian@gmail.com)
- 🌐 Portfolio: [www.isnotcristhianr.dev](https://www.isnotcristhianr.dev)
- 💼 GitHub: [@cristhianrecalde](https://github.com/cristhianrecalde)

## 🙏 Agradecimientos

Esta aplicación fue desarrollada con 💙 usando Flutter. Gracias por usar Chat Simulator y espero que disfrutes simulando conversaciones.

---

**Versión**: 1.0.0  
**Última actualización**: 2024

> ¿Te gusta el proyecto? ¡Dale una ⭐ en GitHub!
