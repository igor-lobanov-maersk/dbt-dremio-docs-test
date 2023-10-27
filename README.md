# Dremio dbt Primer

This is a minimal project using dbt and Dremio via [dbt-dremio-adapter]() illustrating some nuance of it.

Specifically:
- How to configure [sqlfluff]() linter to work with Dremio because Dremio dialect is not yet supported
- How to use dbt to create reflections for models materialised as views in Dremio
