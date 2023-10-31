# rocketseat-discover

Aplicação produzida no curso [Discover da rocketseat](https://www.figma.com/community/file/1187422022288947321/devlinks-projeto-discover) apenas para estudo

## Aprendizados

### Display flex

Ao setar display: flex o elemento passa a ocupar todo o espaço. Por exemplo o `<a>`, ele ocupa somente seu espaço (inline), mas quando recebe o display passa a ocupar toda a largura (block)

```css
margin: 4px auto; /*Alinha no meio pois é display block*/
```css

## Alinha no meio pois é display flex

```css
display: flex; /*Trabalha com elementos dentro da caixa, deixando lado a lado*/
align-items: center; /*vertical*/
justify-content: center; /*horizontal*/
```

### alinha texto

```css
text-align: center;
```

### Media queries

- Regras css
- Funciona somente quando tem a linha abaixo no html que faz a adaptação do viewport

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
