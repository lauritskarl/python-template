# python-template
python template repo

## uv github actions
https://docs.astral.sh/uv/guides/integration/github/#using-uv-pip

## uv fast-api example
https://docs.astral.sh/uv/guides/integration/fastapi/#migrating-an-existing-fastapi-project

## uv pre-commit hook
https://docs.astral.sh/uv/guides/integration/pre-commit/

## docker runner image candidates
https://docs.astral.sh/uv/guides/integration/docker/

uv provides both distroless Docker images,
which are useful for copying uv binaries into your own image builds,
and images derived from popular base images,
which are useful for using uv in a container.
The distroless images do not contain anything but the uv binaries.
In contrast, the derived images include an operating system with uv pre-installed.

ghcr.io/astral-sh/uv


docker.io/jdxcode/mise

## Set up development environment

```bash
mise set MISE_ENV=dev --file mise.local.toml
mise install
```

## mise-tasks
This project uses mise-en-place.

To quickly install mise on your system, run bin/mise
Various tasks are already configured and accessible as seen below.

If you do not have mise installed, use task shims at bin/.

After editing/changing mise tasks, run the following commands:

```bash
mise generate task-docs --inject --output README.md
mise generate task-stubs
```

<!-- mise-tasks -->
<!-- /mise-tasks -->
