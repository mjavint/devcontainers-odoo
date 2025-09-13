# Odoo 19 Devcontainers

[![Watch the video](https://github.com/mjavint/devcontainers-odoo/blob/main/img/miniatura.png?raw=true)](https://youtu.be/I4vswyVg2K0)

## Instalación y Configuración

1. Clonar el repositorio

```bash
git clone https://github.com/mjavint/devcontainers-odoo
```

2. Configurar entorno virtual de python

```bash
# Entrar al proyecto
cd devcontainers-odoo
# Sncronizar el proyecto
uv sync
# Activar el entorno
source .venv/bin/activate
```

3. Instalar dependencias de odoo

```bash
uv pip install -r odoo.19.0/requirements.txt
```

4. Configurar el role odoo en la base de datos usando el servicio `pgadmin` instalado.
   ![pgadmin](https://github.com/mjavint/devcontainers-odoo/blob/main/img/pgadmin.png?raw=true)

5. Iniciar el servidor de odoo

```bash
python odoo.19.0/odoo-bin -c odoo.conf
```

## Enlaces útiles

- [Docker Desktop](https://docs.docker.com/get-started/get-docker/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Ultraviolet (UV) y Ruff](https://docs.astral.sh/)
- [Devcontainers](https://containers.dev)
