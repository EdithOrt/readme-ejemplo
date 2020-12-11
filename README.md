# Chile Marca Preferencia

**Índice**
1. [¿Qué es chile marca preferencia?](#id1)
2. [Guía de instalación](#id2)
4. [¿Cómo ejecutar pruebas unitarias?](#id3)
5. [Tecnologías utilizadas](#id4)
6. [¿Cómo contribuir?](#id5)
7. [Autores](#id6)


## ¿Qué es chile marca preferencia?<a name="id1"></a>

Chile Marca Preferencia es un proyecto de FCI que tiene como objetivo entregar a lxs ciudadanxs datos actualizados respecto de las posturas y definiciones políticas de determinadxs actorxs.

<details>
<summary>Metodología y creadores</summary>

### Metodología:

La metodología de Marca Preferencia se centra principalmente en dos objetivos: 
La definición de una escala de posiciones políticas que represente de forma comprensiva y balanceada las posturas respecto a 22 preguntas clave para el futuro del país. Y la segunda es establecer un mecanismo para la recopilación de posiciones que permita su visualización de forma amigable, simple y comparable.

### Creadores:

Chile marca preferencia es un proyecto elaborado por Ciudadanía Inteligente una organización sin fines de lucro y apartidista que lucha por la justicia social y por la transformación de las democracias. Y Friedrich-Ebert-Stiftung fundación política alemana de cooperación internacional con oficinas en más de 100 países. 
</details>

## Guía de instalación<a name="id2"></a>

Es una aplicación desarrollada con el framework Ruby on Rails, desarrollada para Chile. Con conocimiento en Rails se puede adaptar para cualquier país.

Se debe clonar con:

```
git clone https://gitlab.com/ciudadaniai/chilemarcapreferencia.git
```

En la terminal dirigirse al directorio con:

```
cd chilemarcaprefererencia
```

Para instalar una versión local de la app se necesita: 

- Ruby 2.6.6
Se recomienda manejar las versiones de Ruby con rbenv. La forma básica es:
```
rbenv install 2.6.6
```

- Postgresql
Dependera de la plataforma o sistema operativo.

- Instalar gemas con:
```
bundle install
```

- Ejecutar
```
bundle exec rails webpacker:install
```

- Si se genera error de yarn, resolver con:
```
yarn install --check-files
```

## ¿Cómo ejecutar pruebas unitarias?<a name="id3"></a>

----

## Tecnologías utilizadas<a name="id4"></a>

- [Ruby 6.6.0](https://www.ruby-lang.org/es/)
- Javascript
- HTML
- [Yarn](https://classic.yarnpkg.com/es-ES)
- CSS
- [Sass](https://sass-lang.com/)
- [rbenv](https://github.com/rbenv/rbenv)
- [Postgresql](https://www.postgresql.org/)


## ¿Cómo contribuir?<a name="id5"></a>

----


## Autores<a name="id6"></a>

Contacto: info@ciudadaniai.org
