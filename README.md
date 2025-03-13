# programacion-avanzada
Versión pythonística del curso de programación avanzada.


## Pushing the book

Agrego `ghp-import` al proyecto
```bash
uv add ghp-import
```

Push a `clases-2025`:
```bash
uv run ghp-import -n -p -f -b clases-2025 _build/html
````

El libro se encuentra [acá]().


[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://flavio.colavecchia.net/programacion-avanzada-clases/intro.html)

## Clean up

```bash
uv run jupyter-book clean .
```

## Knowledge Base

- Pygment lexer no reconoce `cmd` como un lexer válido para colorear código correspondiente
  al `cmd.exe` de windows. En su lugar, usar `batch`.
  