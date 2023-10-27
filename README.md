# Dremio dbt Primer

This is a minimal project using dbt and Dremio via [dbt-dremio-adapter](https://github.com/dremio/dbt-dremio) illustrating some nuance of it.

Specifically:
- How to set up Visual Studio Code IDE to use Dev Containers and have a reproduceable dbt development environment.
- How to work with multiple dbt targets in Dremio.
- How to configure [sqlfluff](https://sqlfluff.com/) linter to work with Dremio because Dremio dialect is not yet supported.
- How to use dbt to create reflections for models materialised as views in Dremio.
