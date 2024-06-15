# Projeto de Exemplo com Metodologia BEM

Este é um projeto simples demonstrando o uso da Metodologia BEM (Block Element Modifier) para estilização de um conjunto de produtos.

## Estrutura do Projeto

/meu-projeto
├── index.html
└── main.css


- `index.html`: Arquivo HTML principal.
- `main.css`: Arquivo CSS principal onde são escritos os estilos.

## Metodologia BEM

A Metodologia BEM (Block Element Modifier) foi utilizada para organizar e nomear as classes CSS de forma a tornar o código mais claro e modular.

- **Bloco**: `.produto`
- **Elementos**: `.produto__imagem`, `.produto__nome`, `.produto__descricao`
- **Modificador**: `.produto--destaque`

## Funcionalidades do Projeto

O projeto demonstra o uso de classes BEM para organizar os estilos CSS dos produtos.

Exemplo de uso de modificador BEM:

```css
.produto--destaque {
    border: 2px solid gold;
    padding: 8px;
    background-color: #ffff42;
}
