# IA_UMSNH Lite

Repositorio del modelo IA_UMSNH Lite, especializado exclusivamente en la Universidad Michoacana de San Nicolás de Hidalgo (UMSNH), México.

Archivos incluidos:
- `Modelfile`

El `Modelfile` contiene las instrucciones para que la IA responda siempre en español.

Nota: El archivo IA_UMSNH.gguf no se incluye debido a su gran tamaño.

## Uso

1. Descarga `IA_UMSNH.gguf` desde la sección de *releases* o desde el enlace oficial proporcionado por los mantenedores.
2. Coloca el modelo en el mismo directorio que el `Modelfile`.

### Ollama

```bash
ollama create ia_umsnh -f Modelfile
ollama run ia_umsnh
```

### LM Studio

1. Abre LM Studio y selecciona "Add local model".
2. Escoge el archivo `IA_UMSNH.gguf` y sigue los pasos para cargarlo.

### Dependencias recomendadas

- [Ollama](https://github.com/jmorganca/ollama) o [LM Studio](https://lmstudio.ai/)
- Herramientas compatibles con el formato GGUF (por ejemplo, `llama.cpp`)
