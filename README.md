# python-template
python template repo

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
