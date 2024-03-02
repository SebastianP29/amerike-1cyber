# _Markdown_

_Markdown_ es un lenguaje de marcado que sirve para definir contenido. Es muy usado para documentar proyectos de _software_, es el estándar en que se redacta la documentación. También es utilizado para crear contenido estático que posteriormente se pueda compilar a código _HTML_.

## Índice de Contenidos

- [Introducción](#markdown).
- [Párrafos](#párrafos).
- [Encabezados](#encabezados).
- [Divisiones](#divisiones).
- [Enlaces](#enlaces).
- [Listas](#listas).
- [Imágenes](#imágenes).
- [Tablas](#tablas).
- [Citas](#citas).
- [Código](#codigo).
- [Comentarios](#comentarios).

---

## Párrafos

Un párrafo es una extensión de texto que finaliza cuando hay un saltop de línea.

Este sería otro párrafo.

En _Markdown_ podemos escribir texto con **negritas** y _cursiva_.

_**Este es un texto que esta en negritas y cursiva.**_

[Regresar al inicio ☝🏻](#markdown)

---

## Encabezados

# Título de nivel 1

## Título de nivel 2

### Título de nivel 3

#### Título de nivel 4

##### Título de nivel 5

###### Título de nivel 6

[Regresar al inicio ☝🏻](#markdown)

---

## Divisiones

Cuando necesites separar un tema de otro puedes usar una división.

[Regresar al inicio ☝🏻](#markdown)

---

## Enlaces

[Más información sobre _Markdown_](https://jonmircha.com/markdown)

[Ir al documento hola-mundo](hola-mundo.txt)

[Ir al título 3](#título-de-nivel-3)

[Regresar al inicio ☝🏻](#markdown)

---

## Listas

### Listas Desordenadas

- Primavera
- Verano
- Otoño
- Invierno

### Listas Ordenadas

1. Primavera
1. Verano
1. Otoño
1. Invierno

### Listas multi nivel

- Primavera
  - Abril
  - Mayo
    - Día del Trabajo
    - Día de las Madres
    - Día del Maestro
  - Junio
- Verano
  - Julio
  - Agosto
  - Septiembre
- Otoño
- Invierno

1. Primavera
   1. Abril
   1. Mayo
   1. Junio
1. Verano
1. Otoño
1. Invierno

[Regresar al inicio ☝🏻](#markdown)

---

## Imágenes

![Flujo básico de Git](https://jonmircha.com/img/blog/git-flow.png)

![Dino Dev](img/dino-dev.jpg)

[Regresar al inicio ☝🏻](#markdown)

---

## Tablas

| País    | Ciudad | Continente |
| ------- | ------ | ---------- |
| México  | CDMX   | América    |
| Japón   | Tokyo  | Asia       |
| Francia | París  | Europa     |

[Regresar al inicio ☝🏻](#markdown)

---

## Citas

### Cita en línea

> Yo sólo sé, que no sé nada - Sócrates

### Cita en bloque

> Yo sólo sé,
> que no sé nada
>
> Sócrates

[Regresar al inicio ☝🏻](#markdown)

---

## Código

### Bloques de Código

```jsx
function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById("container"));
root.render(<HelloMessage name="Taylor" />);
```

```html
<ul class="list-unstyled">
  <li>This is a list.</li>
  <li>It appears completely unstyled.</li>
  <li>Structurally, it's still a list.</li>
  <li>However, this style only applies to immediate child elements.</li>
  <li>
    Nested lists:
    <ul>
      <li>are unaffected by this style</li>
      <li>will still show a bullet</li>
      <li>and have appropriate left margin</li>
    </ul>
  </li>
  <li>This may still come in handy in some situations.</li>
</ul>
```

### Código HTML

<input type="text">
<button>Presionar</button>

[Regresar al inicio ☝🏻](#markdown)

---

## Comentarios

<!-- Un comentario es una nota que escribe el progrmador, pero que no se va a ejecutar o a compilar. -->

### Escape de caracteres

\*\*Esto esta en negritas\*\*

\# Título

\\

[Regresar al inicio ☝🏻](#markdown)

---
