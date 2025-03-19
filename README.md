
# FUTOS - Tu Shell de Fútbol

FUTOS es un script en Bash que combina una interfaz interactiva con un mini-juego de penales, consultas de fútbol y más, todo con efectos visuales y colores llamativos.

## Comandos disponibles:
- `install`: Instala archivos y dependencias, incluyendo `jq` si no está instalado.
- `uninstall`: Desinstala y borra los archivos creados.
- `penalti-game`: Juega un mini-juego de tirar penaltis.
- `date-time`: Muestra la fecha y hora actual.
- `interactive`: Inicia la shell interactiva.
- `resultados`: Muestra los resultados de los últimos 5 partidos.
- `posiciones`: Muestra la tabla de posiciones de la competición.
- `competencia-penalti`: Juega un mini-juego de parar penaltis.
- `mostrar-pid`: Muestra el PID del proceso actual.
- `matar-proceso`: Mata el proceso del PID que introduzcas.
- `crear-proceso`: Crea un proceso hijo que dura 10 segundos.
- `help`: Muestra este menú de ayuda.
- `betting`: Abre el sitio de apuestas Bet365.

## Instalación:
### Instalar desde GitHub:

1. **Para instalar el script**, ejecuta el siguiente comando desde tu terminal:
   
   ```bash
   curl -s https://raw.githubusercontent.com/Soup-Sopas/Futball-shell/refs/heads/main/futshell.sh | bash -s install
   ```

### Instalar con el archivo 

2. **Para instalar el script**, simplemente ejecuta:

   ```bash
   ./futshell.sh install
   ```

## Uso:
Para iniciar la shell interactiva, ejecuta:

```bash
./futshell.sh interactive
```

Desde ahí, puedes elegir entre varios comandos disponibles como jugar al penalti, consultar la fecha y hora, o obtener la tabla de posiciones.

## Requisitos:
- `curl` para hacer solicitudes a la API.

## Créditos:
El script utiliza la API de [Football-Data.org](https://www.football-data.org/) para obtener los resultados y la tabla de posiciones.

¡Diviértete y disfruta de la experiencia FUTOS!
