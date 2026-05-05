# Simple Login Android

Aplicacion Android de autenticacion con pantalla de login y navegacion entre actividades, desarrollada con **Kotlin** y **Material Design**.

---

## Descripcion

App minimalista que implementa un flujo de login basico con validacion de campos, demostrando el uso de actividades multiples, intents y componentes de Material Design en Android.

---

## Caracteristicas

- Pantalla de login con campos usuario y contrasena
- Validacion de campos antes del envio
- Navegacion entre actividades con Intent
- Diseno con Material Design y ConstraintLayout
- Soporte multilenguaje (strings localizados)

---

## Stack tecnico

| Tecnologia | Version |
|---|---|
| Kotlin | 1.x |
| Android SDK | AppCompat |
| Material Design | Material Components |
| ConstraintLayout | Layouts XML |
| Gradle | Build system |

**Testing:** Espresso (UI), JUnit (unitario)

---

## Estructura del proyecto

```
app/src/main/
├── java/com/example/login/
│   ├── MainActivity.kt    # Pantalla de login
│   └── Interfaz.kt        # Pantalla post-login
└── res/
    ├── layout/
    │   ├── activity_main.xml       # Layout del login
    │   └── activity_interfaz.xml   # Layout de la interfaz principal
    └── values/
        └── strings.xml             # Textos localizados
```

---

## Requisitos

- Android Studio Electric Eel o superior
- Android SDK 21+
- Kotlin 1.8+

## Como ejecutar

```bash
git clone https://github.com/ShioriManami/SimpleLoginAndroid.git
```

1. Abrir Android Studio
2. File -> Open -> seleccionar la carpeta `Login/Login/`
3. Sincronizar Gradle
4. Run -> Run 'app'

---

## Conceptos demostrados

- **Arquitectura de actividades** en Android nativo
- **Material Design Components** — TextInputLayout, Button
- **ConstraintLayout** — disenos flexibles y responsivos
- **Navegacion con Intents** — paso de datos entre actividades
- **Validacion de formularios** — logica de UI sin frameworks externos