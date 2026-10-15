## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)

## Reglas del proyecto

- Astro + TypeScript strict + Tailwind CSS. No agregar librerías sin preguntar.
- Estilos SOLO con clases de Tailwind. Nada de <style> ni CSS suelto, salvo en global.css.
- Colores, fuentes y espaciados del diseño se definen como tokens en src/styles/global.css (bloque @theme) y se usan vía clases de Tailwind. No usar valores arbitrarios tipo `text-[#ff0000]` ni inventar tokens nuevos sin avisar.
- Componentes en src/components, PascalCase, extensión .astro.
- Props tipadas con `interface Props`.
- Mobile first: clases base para celular, `md:` y `lg:` para pantallas grandes.
- La referencia de diseño está en /reference (estructura.html, DESIGN.md y los PNG). No modificar esa carpeta.
- Trabajar de a una sección por vez y esperar mi confirmación.
- Explicá brevemente qué hiciste y por qué, soy principiante en frontend.