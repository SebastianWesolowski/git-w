# Markdown v2

Lorem, ipsum dolor.
Lorem, ipsum dolor.
Język znaczników przeznaczony do formatowania tekstu. Został stworzony w celu jak najbardziej uproszczonego tworzenia i formatowania tekstu.

## Formatowanie treści

Składnia Markdown zaprojektowana jest w taki by usprawnić formatowanie tekstu.

Przykłady:

```markdown
# Nagłówek pierwszego poziomu

## Nagłówek drugiego poziomu

Now is the time for all good men to come to
the aid of their country. This is just a
regular paragraph.

Pójdźże, kiń tę chmurność w głąb flaszy!

### Nagłówek trzeciego poziomu

> To jest blok cytatu.
>
> To jest drugi akapit w bloku cytatu.
>
> ## To jest H2 w bloku cytatu
```

W efekcie zostanie on przetworzony przez silnik markdown i zamiast charakterystycznych znaczników wstawione zostaną znaczniki HTML

Efekt:

```html
<h1>Nagłówek pierwszego poziomu</h1>

<h2>Nagłówek drugiego poziomu</h2>

<p>
  Now is the time for all good men to come to the aid of their country. This is
  just a regular paragraph.
</p>

<p>Pójdźże, kiń tę chmurność w głąb flaszy!</p>

<h3>Nagłówek 3.</h3>

<blockquote>
  <p>To jest blok cytatu.</p>

  <p>To jest drugi akapit w bloku cytatu.</p>

  <h2>To jest H2 w bloku cytatu</h2>
</blockquote>
```
