# Portal Segunda Vuelta 🚛

Dashboard privado para consulta de recorridos por colaborador.

## Cómo actualizar la data

1. Ve a la carpeta `data/` en este repositorio
2. Sube el archivo `BD.xlsx` (reemplaza el anterior)
3. ¡Listo! En 1-2 minutos la página se actualiza automáticamente

## Archivos en carpeta `data/`

| Archivo | Descripción |
|---|---|
| `BD.xlsx` | Base de datos de recorridos (hoja: "Segunda Vuelta") |
| `MAESTRO.xlsx` | Lista de colaboradores con DNI |

## Columnas requeridas en BD.xlsx (hoja "Segunda Vuelta")

| Columna | Contenido |
|---|---|
| A | FECHA |
| B | OT |
| F | CONDUCTOR |
| H | AUX1 |
| I | AUX2 |
| J | AUX3 |

## Columnas requeridas en MAESTRO.xlsx

| Columna | Contenido |
|---|---|
| A | Nro. Doc. (DNI) |
| C | Colaborador (nombre) |
