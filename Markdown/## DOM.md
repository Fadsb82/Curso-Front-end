## DOM

- Document Object Model
- Estrutura de um arquivo na web
- Representa elemntos HTML ou XML
- Interface de programação
- NÃo é uma linguagem de programação
- É essencial para o Js entender o modelo de páginas web

## Para que serve?

- Alterar a estrutura
- Alterar o estilo
- Alterar o conteúdo

## Como acontece?

- Disponibilizando API (Application Programmig Interface)
- Rotina e padrões estabelecidos
- Métodos (Funções)
- Árvore de elementos 
- Seletores
- Objetos (nós / nodes)


## Exemplo HTML
```
<html>
    <head><head>
    <body><body>
<html>


## Exemplo objeto
```
objeto = {
    html : {
        head : {

        }
        body : {
            h1 : {

            }
        }
    }
}
```

## DOM x JS

- DOM pode ser usado por outras linguagens
- Sem o DOM o JavaScript não teria noção da página

### Vantagens de usar o JavaScript

- Código é executado por navegadores
- Tornar as páginas dinâmicas
- Evitar requisições desnecessárias (performance)
- SPA (Simple Page Applications)
- Reagir rapidamente a ações dos outros

### Desvantagens de usar o JavaScript

- Código executado por navegadores
- O conteúdo NÃO fica visível para indexadores de busca
- Alterções em tempo de excução não ficam salvas no documento

### Exemplos
Seleciona o objeto e disponibiliza (métodos / funções).callback

- document.get.ElementById(id)
- document.get.ElementByTagName('div')
- document.create.Element(name ou 'div')
- parentNode.appendChild(node) // html.appendChild('body')
- element.innerHTML
- element.style
- element.setAttribute('name')
- element.getAttribute('name')
- element.addEventListener()
- window.location
- window.onload(en-US)
- console.log()
- window.scrollTo(x, y)

## Seletores

- Tipos de seletores: Tag, ID, Class, Name, Query
- Callback
- get.ElementById()
- get.ElementsByTagName()
- get.ElementsByName()
- get.ElementsByClassName()


### Referências

- DOM: https://dom.spec.whatwg.org
- Tecnologias JS: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/JavaScript_tecnologies_overview
- Monitores de execução: https://pt.wwikipedia.org/wiki/Lista_de_motores_de_renderiza%C3%A7%C3%A3o 
- Expressões Regulares: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Regular_Expressions