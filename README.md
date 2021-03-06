# PRUEBA FRONT-END

## INTRODUCCIÓN

Hola humano! Hoy tienes como cometido crear un producto que hemos decidido apodar 'Cristóbal'. Cristóbal, como su propio nombre indica, tiene facilidad para explorar y descubrir. En concreto, su especialidad es buscar becas para cursar estudios y no tener que preocuparse por el elevado coste de los mismos. Como puedes ver, esto es una herramienta muy útil para cualquier estudiante.

El buscador tiene un funcionamiento relativamente sencillo. El estudiante introduce sus datos personales y, en base a los mismos, le indicamos para cuál de nuestras becas es 'apto' o 'no apto'.

Para poder ver el resultado de la búsqueda, el usuario tiene que introducir su correo electrónico. **No hace falta que hagas un proceso de autenticación**. La única limitación es que a la hora de introducir el email, vamos a restringir los emails permitidos, debe ser alguno de los que aparece en esta lista: https://jsonplaceholder.typicode.com/users.
Deberás de realizar una petición a ese endpoint y comprobar si el email que ha introducido el usuario se encuentra entre los resultados.

## DISEÑO DE CRISTÓBAL

Puedes encontrar el diseño y la interacción de Cristóbal aquí https://www.figma.com/file/EaaDXqWeMlBdaDtriHPyvc/Prueba-técnica-Cristóbal?node-id=0%3A1

## DOCUMENTACIÓN

Array de becas:
```
[
  { 
    Name:Becas escolares curso 2021 -2022 primer ciclo educación infantil,
    minimumAge: 18,
    province: Madrid,
    minimumMark: none
  },
  { 
    Name:Becas para el estudio de Programas de Segunda Oportunidad, correspondiente al curso 2021-2022,
    minimumAge: 18,
    province: Cataluña,
    minimumMark: none
  },
  { 
    Name:Subvenciones de comedor en los centros docentes públicos no universitarios para el curso escolar 2021-2022.,
    minimumAge: none,
    province: Galicia,
    minimumMark: 5
  },
  { 
    Name:Beca MEC,
    minimumAge: none,
    province: Andalucia,
    minimumMark: 5
  },
]
```

## REQUISITOS DE LA PRUEBA
Debes montar tu proyecto:
1. Crear un proyecto con https://create-react-app.dev/
2. Agregar eslint (seguir un estilo de código)
3. Añadir routing
4. Hacer una llamada a la API para comprobar el user
5. Filtrar array de becas según la información que haya introducido el usuario
6. Ofrecer un resultado de becas que están disponibles según sus datos
7. Subir el proyecto a un repositorio

## EXTRAS
1. Desplegar la applicación en Firebase

## SE VALORARÁ
1. Similitud de la applicación con el diseño.
2. Uniformidad y limpieza del código.
3. Estructura del código.
