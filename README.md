# API con Flask

Este repositorio contiene una API sencilla creada con el framework Flask en Python. La API proporciona un endpoint que devuelve una lista de nombres de personas en formato JSON.

## Requisitos:

- Python 3 instalado.
- Warp Terminal (opcional, pero recomendado).

## Uso:

  **1.** Guarda el código de la API en un archivo llamado ```main.py```

  **2.** Ejecutar:
  
  ```sh
  python main.py
  ```
  La API estará corriendo en ```http://127.0.0.1:5000/```
  
## Endpoint:

- Método: GET
- URL: ```http://127.0.0.1:5000/personas```
- Respuesta JSON:
  
```sh
["Carlos", "Ana", "Luis", "Victor", "Pedro"]

```

## Ejemplo de consumo:

__Usando curl en la terminal:__

```sh
curl [http://127.0.0.1:5000/personas](http://127.0.0.1:5000/personas)

```


## Autor

Desarrollado por Victor Yepes.
  

