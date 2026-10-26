# Heretic IDP

Heretic IDP is the custom Identity Provider (IdP) backend for the Heretic ecosystem, providing authentication and session management services designed to replace standard Microsoft/Mojang auth for custom Minecraft clients like Heretic Launcher.

## Tech Stack

- **Backend:** PHP 8.5 (Slim Framework 4)
- **Dependency Management**: Composer
- **Auth Protocol:** Custom Yggdrasil implementation
- **Database**: MariaDB

## Documentation

Full project documentation, setup guides, and architecture specifications can be found in the [docs/](./docs) directory:

- [Architecture & Auth Flow](./docs/architecture.md)
- [Development Setup Guide](./docs/setup.md)
- [API Reference](./docs/api.md)

## Development Setup

```bash
git clone https://github.com/official-afterchange/heretic-idp.git
cd heretic-idp
composer install

```

## Heretic Ecosystem
- [Heretic Launcher](https://https://github.com/official-afterchange/heretic-launcher) - The Custom Minecraft Client / Launcher