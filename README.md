# API Flask de Upload e Download

API RESTful para upload e download de ficheiros com registo em SQLite.

## Como Executar
- Instalar dependências: `pip install -r requirements.txt`
- Executar: `python app.py`

## Rotas
- `POST /uploads/upload` - Envio de ficheiros
- `GET /downloads/download/<filename>` - Transferência de ficheiros
