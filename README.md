# Mercy Tracker Companion — Releases

Este repositorio contiene únicamente binarios publicados del companion nativo
de macOS para [Mercy Tracker](https://app.raid-mercy-tracker.space). No hay
código fuente aquí — el código vive en un repositorio privado aparte.

- Cada [Release](../../releases) incluye el `.dmg` instalable de esa versión.
- `appcast.xml` es el feed de actualizaciones que consulta
  [Sparkle](https://sparkle-project.org) desde la propia app para ofrecer
  actualizaciones automáticas.

Publicado automáticamente por el workflow `macos-companion-release.yml` del
repositorio de código en cada push a `main` que toque `apps/macos-companion/**`.
