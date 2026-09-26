# Modded Minecraft Server 1.12.2

A historical Minecraft 1.12.2 server snapshot configured with a large mod collection.

## Run

The repository includes Linux and Windows launch scripts:

```bash
chmod +x run.sh
./run.sh
```

Before starting the server:

1. Install the Java version required by the selected Forge/modpack build.
2. Review the memory settings in the launch script.
3. Read the Minecraft EULA and set `eula=true` only if you agree to it.
4. Review ports, operator permissions, whitelist settings, and server properties.
5. Back up the world outside the repository.

## Repository hygiene

A production server repository should normally contain reproducible configuration and automation—not runtime data. World saves, logs, caches, generated libraries, server JARs, and player data should live in private storage or release artifacts.

Recommended next step: rebuild this project as a minimal configuration repository with a documented mod manifest and an automated download/bootstrap process.

> This snapshot may contain historical runtime and player data. Review and sanitize it before sharing or deploying.
