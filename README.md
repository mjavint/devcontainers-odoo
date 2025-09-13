# Odoo 19 Devcontainers

## How to install

1. Clone repository
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
5. Iniciar el servidor de odoo
```bash
python odoo.19.0/odoo-bin -c odoo.conf
```

## Enlaces utiles
- [Docker Desktop](https://docs.docker.com/get-started/get-docker/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Ultraviolet (UV) y Ruff](https://docs.astral.sh/)

