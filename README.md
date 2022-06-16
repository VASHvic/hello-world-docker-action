# Docker action "Hola mundo"

Imprime Hola mundo o Hola + el nombre de la persona

## Inputs

### `who-to-greet`

**Requerido** Nombre de la persona a quién saludar

## Outputs

### `time`

La fecha en la que te saludé

## Example usage

```
uses: pablokbs/hello-world-docker-action@v1
with:
  who-to-greet: 'Pelades'
```
