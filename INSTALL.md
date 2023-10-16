## Instalación

### Requisitos

- Instalar [Python](https://www.python.org/downloads/)
- Instalar [Java](https://www.java.com/en/download/help/download_options.html)
- Instalar [docker](https://docs.docker.com/engine/install/)
- Instalar [git](https://git-scm.com/) and [git-lfs](https://git-lfs.com/)

### Instalación de componentes básicos

- Descargar [synthea](https://synthetichealth.github.io/synthea/) patient data generator: [synthea-with-dependencies.jar](https://github.com/synthetichealth/synthea/releases/download/master-branch-latest/synthea-with-dependencies.jar) o descargar [data.zip](https://github.com/alabarga/pybcn22-modern-data-stack/blob/main/synthea/data.zip)
- Descargar los [vocabularios OMOP](https://b2drop.bsc.es/index.php/s/mMczQrtjBHLfmZo) 
- Instalar [PostgreSQL](https://www.postgresql.org): `docker pull postgres` 
  - Instalar [psql](https://www.timescale.com/blog/how-to-install-psql-on-mac-ubuntu-debian-windows/)
  - Instalar a SQL client such as [PgAdmin](https://www.pgadmin.org/) or [DBeaver](https://dbeaver.io/) or [VSCode SQL tools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)
