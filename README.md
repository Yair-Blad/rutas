# RUTAS

Aplicación móvil desarrollada con **Flutter 3.44.0** que actualmente cuenta con pantalla de Login y pantalla principal.

---

## Estado del Proyecto

**Versión actual:** 0.1.0 (MVP Básico)

### Features Completadas
- Pantalla de Login con validación
- Pantalla de bienvenida (Main)
- Navegación entre pantallas
- Diseño responsive básico con Material 3

### Pendiente:
- Pantalla de formulario
- Elección de arquitectura (MVC, Clean Architecture, etc.)
- Gestor de estado (Provider, Riverpod, Bloc, etc.)
- Base de datos local (SQLite, Hive, Isar, etc.)
- Tipografía oficial
- Paleta de colores y diseño UI/UX completo
- Autenticación real (Firebase/Auth0)
- Navegación avanzada (GoRouter)
- Soporte para tema oscuro

---

## Requisitos

### Software necesario

- **Flutter**: 3.44.0 (o superior)
- **Dart**: 3.12.0 (o superior)
- **Android Studio**
- **Android SDK** / Emulador Android

### Versiones recomendadas

- Flutter: `>= 3.44.0`
- Dart: `>= 3.12.0`

---

### Instalación

```bash
# Clona el repositorio:
git clone https://github.com/Yair-Blad/rutas.git
cd carpeta

# Instala las dependencias:
flutter pub get

# Verifica que todo esté correcto:
flutter doctor
```

### Como ejecutar:

```bash
# Modo normal
flutter run

# Sin Impeller (recomendado si tienes problemas en emulador Android 16)
flutter run --no-impeller

# Con hot reload
flutter run -d <nombre-dispositivo>
```

### Comandos útiles:
```bash
# Limpia el proyecto
flutter clean

# Actualiza dependencias
flutter pub get

# Ejecuta en modo release
flutter run --release

# Genera APK
flutter build apk
```