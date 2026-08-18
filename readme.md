# Seletores de pseudo-classes

As pseudo-classes são seletores usados em CSS para aplicar estilos a elementos em estados específicos ou em posições determinadas dentro do documento. Elas permitem criar páginas mais interativas e visualmente mais dinâmicas sem a necessidade de adicionar classes extras no HTML.

## O que são?

Uma pseudo-classe é escrita com dois pontos depois do seletor, por exemplo:

```css
button:hover {
  background-color: #4caf50;
  color: white;
}
```

Nesse exemplo, o botão muda de aparência quando o mouse passa por cima dele.

## Exemplos de pseudo-classes

### :hover
Aplica estilo quando o cursor está sobre o elemento.

```css
.hover:hover {
  color: red;
  text-decoration: underline;
}
```

### :focus
Aplica estilo quando o elemento recebe foco, como um campo de input.

```css
focus:focus {
  border: 2px solid blue;
  outline: none;
}
```

### :active
Aplica estilo quando o elemento está sendo pressionado.

```css
.active:active {
  color: orange;
}
```

### :link
Usada para links ainda não visitados.

```css
.link:link {
  color: green;
  text-decoration: none;
}
```

### :visited
Usada para links já acessados.

```css
.visited:visited {
  color: purple;
}
```

## Importância no desenvolvimento web

As pseudo-classes tornam o CSS mais poderoso, pois permitem responder a interações do usuário e a estrutura do HTML sem alterar o conteúdo da página. Elas são muito usadas em menus, formulários, botões, links e listas.

## Conclusão

Os seletores de pseudo-classes são ferramentas essenciais para criar interfaces mais intuitivas e responsivas. Com eles, é possível estilizar elementos conforme o estado em que se encontram, melhorando tanto a experiência visual quanto a experiência do usuário.
