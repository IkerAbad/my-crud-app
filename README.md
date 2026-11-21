# my-crud-app

Aplicación Angular 15 (abril de 2023) con un CRUD de publicaciones (`posts`) que se conecta a la API de pruebas pública [JSONPlaceholder](https://jsonplaceholder.typicode.com). Es un ejercicio del ciclo de DAM para practicar servicios con `HttpClient`, módulos y rutas.

## Qué hay

- Un módulo `post` con cuatro pantallas: listado (`index`), crear, editar y ver una publicación.
- `post.service.ts`: llamadas GET, POST, PUT y DELETE a `https://jsonplaceholder.typicode.com/posts` con manejo de errores.
- JSONPlaceholder simula las escrituras pero no guarda nada, así que crear, editar o borrar no persiste de verdad.
- `ng build` compila sin errores. No he abierto la aplicación en un navegador desde aquí ni he pasado los tests.

## Cómo probarlo

```
npm ci
npx ng serve
```

y abre `http://localhost:4200/`.

## Licencia

MIT, ver [LICENSE](LICENSE).

---

# my-crud-app (English)

An Angular 15 app (April 2023) with a CRUD for posts that talks to the public test API [JSONPlaceholder](https://jsonplaceholder.typicode.com). It is an exercise from my DAM vocational course to practice services with `HttpClient`, modules and routing.

## What's inside

- A `post` module with four screens: list (`index`), create, edit and view a post.
- `post.service.ts`: GET, POST, PUT and DELETE calls to `https://jsonplaceholder.typicode.com/posts` with error handling.
- JSONPlaceholder fakes writes but does not store anything, so creating, editing or deleting does not really persist.
- `ng build` compiles without errors. I have not opened the app in a browser from here nor run the tests.

## Trying it

```
npm ci
npx ng serve
```

then open `http://localhost:4200/`.

## License

MIT, see [LICENSE](LICENSE).
