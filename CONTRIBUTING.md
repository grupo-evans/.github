# Guía de contribución

## Flujo de trabajo

1. Crea una rama desde `main` con el formato `<tipo>/<descripcion-corta>` (por ejemplo, `feat/invoice-export`, `fix/login-timeout`).
2. Haz commits siguiendo [Conventional Commits](https://www.conventionalcommits.org/es/), escritos en inglés.
3. Abre un pull request hacia `main` y completa la plantilla.
4. `evans-admin` revisa y hace el merge. No hagas push ni merge directo a `main`.

## Convenciones

- **En inglés:** código, comentarios en el código, nombres de archivos y ramas, mensajes de commit y nombres de labels.
- **En español:** READMEs, guías y documentación, issues, pull requests, discusiones y descripciones de labels.
- Nunca subas secretos, credenciales ni datos personales. Usa el almacén de secretos del repositorio.
