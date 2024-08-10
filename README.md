# Microservicio de búsqueda

## Descripción

Este microservicio tiene la función de buscar un post por título, contenido o ambos.

1.Clonar el repositorio
```bash
https://github.com/AvilesDanie/Microservicio-Busqueda.git
```

2. Iniciar el contenedor
```bash
docker-compose up -d
```

3. Verificar la ejecución

```bash
docker-compose ps
```

4. Acceder a la URL 

``` bash
http://localhost:8000

```

Metodo Get: 

Se obtienen todos los posts
``` bash
localhost:8000/posts/
```

Se obtiene el post por titulo
``` bash
localhost:8000/posts/?title=<nombre de un post>
```

Se obtiene el post por contenido
``` bash
localhost:8000/posts/?content=<contenido de un post>
```

Se obtiene el post por su título y contenido
``` bash
localhost:8000/posts/? title=<nombre de un post>&content=<contenido de un post>
```

