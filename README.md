# Widgets Flutter 05


## Getting Started 🚀

Este proyecto contiene 3 sabores.:

- development
- staging
- production

Para ejecutar el sabor deseado, use la configuración de inicio en VSCode/Android Studio o use el siguiente comandos:

```sh
# Development
$ flutter run --flavor development --target lib/main_development.dart

# Staging
$ flutter run --flavor staging --target lib/main_staging.dart

# Production
$ flutter run --flavor production --target lib/main_production.dart
```

_\*Widgets Flutter 05 corre  Android, Web, IOS _

---

## Running Tests 🧪

Para ejecutar todas las pruebas unitarias y de widgets, use el siguiente comando:

```sh
$ flutter test --coverage --test-randomize-ordering-seed random
```
---

## Working with Translations 🌐

This project relies on [flutter_localizations][flutter_localizations_link] and follows the [official internationalization guide for Flutter][internationalization_link].

