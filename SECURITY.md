# Política de seguridad

## Alcance

Esta política cubre el código Android, los workflows de GitHub Actions y los artefactos publicados por este repositorio.

## Reportar vulnerabilidades

No publiques contraseñas, claves de firma, tokens, datos personales ni pruebas de explotación en issues o pull requests públicos. Utiliza **Report a vulnerability** en la pestaña **Security** de GitHub para enviar el informe de forma privada. Si esa opción no está disponible, solicita primero un canal privado al mantenedor.

Incluye la versión o commit afectado, componente, pasos mínimos para reproducir, impacto y una mitigación sugerida. Redacta registros y datos personales. Las claves de firma Android deben permanecer exclusivamente en secretos protegidos de GitHub Actions.

## Prácticas de publicación

Los APK de release deben generarse en Actions con permisos mínimos, dependencias actualizadas y firma desde secretos. Nunca se debe volver a introducir un almacén `.jks`, `.keystore`, contraseña o clave privada en el árbol del repositorio.
