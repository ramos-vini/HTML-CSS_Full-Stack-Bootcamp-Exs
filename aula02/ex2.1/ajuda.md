# Links internos e externos

## Externos
São links que nos permitem navegar para páginas fora do nosso site.

```html
<a href="https://google.com" target="_blank">Abrir página do Google</a>
```

## Internos
São links que nos permitem navegar entre páginas do mesmo site.

```html
<ul>
  <li>
    <a href="./index.html" target="_blank">Home</a>
  </li>
  <li>
    <a href="./sobre.html" target="_blank">Sobre mim</a>
  </li>
  <li>
    <a href="./galeria.html" target="_blank">Fotos</a>
  </li>
  <li>
    <a href="./contato.html" target="_blank">Fale Conosco</a>
  </li>
</ul>
```

## Âncoras
São links que nos permitem navegar dentro da mesma página.

```html
  <ul>
    <li>
      <a href="#secao1">Seção 1 do site</a>
    </li>
    <li>
      <a href="#secao2">Seção 2 do site</a>
    </li>
    <li>
      <a href="#secao3">Seção 3 do site</a>
    </li>
    <li>
      <a href="#secao4">Seção 4 do site</a>
    </li>
  </ul>

  <div id="secao1">Aqui teremos o conteúdo da seção 1 do site</div>
  <div id="secao2">Aqui teremos o conteúdo da seção 2 do site</div>
  <div id="secao3">Aqui teremos o conteúdo da seção 3 do site</div>
  <div id="secao4">Aqui teremos o conteúdo da seção 4 do site</div>
```