# CodasisAi-Hosted shared workflows

- `register-artifact.yml`: builds a container image, pushes it to GHCR and registers its digest with Pedestal. Called by every hosted app (see the `app-template` repository).
