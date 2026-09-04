# OjoAlTicker · Lab

Laboratorio metodológico de **[OjoAlTicker](https://ojoalticker.com)**, la app de optimización de carteras. Aquí vive la investigación y validación que luego se traduce (o no) a producción — cada notebook es autocontenido y no depende de la app.

## Contenido

- **[`MonteCarlo/`](MonteCarlo/README.md)** — base matemática de la optimización de carteras: simulación Monte Carlo vectorizada, frontera eficiente y optimización exacta (scipy SLSQP) sobre Min Volatilidad, Max Sharpe y Max Sortino.
- **[`tries/TimesFM/`](tries/TimesFM/README.md)** — evaluación zero-shot de TimesFM 2.5 (Google) como forecaster de precio sobre la misma cesta de activos, con backtest walk-forward contra random-walk y tests estadísticos (Diebold-Mariano, Pesaran-Timmermann).

## Cómo ejecutar

```bash
pip install -r requirements-notebook.txt
```

Cada notebook documenta su propio tiempo de ejecución y cache en su README.

## Licencia

MIT — ver [`LICENSE`](LICENSE).
