# Template

- Template no Angular é uma parte de uma página da web que contém elementos HTML e códigos Angular para exibir informações dinâmicas
- É uma forma de exibir dados em seu componente HTML; nada mais do que trabalhar com dados

  - Text interpolation
  - Template statements
  - Binding
  - Template Reference Variables
  - Control flow
  - Deferrable Views

## Text Interpolation

- No Angular, "Text interpolation" é uma maneira fácil e poderosa de exibir valores dinâmicos em seu template HTML
- Ela permite que você insira valores de variáveis diretamente no seu código HTML, tornando a exibição de dados dinâmicos muito simples

## Binding

- "Binding" é um conceito funcamental que se refere à maneira como os dados fluem entre a parte lógica de um aplicativo e a interface do usuário
- O binding permite que você conecte os dados do seu aplicativo com os elemento sdo seu template HTML, tornando-o dinâmico e interativo

- Existem cinco tipos de binding no Angular:
  1. Property Binding
  2. Attribute binding
  3. Class and style binding
  4. Event binding
  5. Two-way binding

## Template Reference Variables

- As "Template Reference Variables" são uma maneira útil de acessar elementos do seu template HTML diretamente em seu código
- Elas são definidas em seus elementos HTML como o uso do símbolo # seguido por um nome de variável
- Isso permite que você se comunique entre o código do componente e o template de uma forma mais direta

- Existem algumas formas de uso no Angular:
  - #nome
  - ViewChild('nome') nome: ElementRef

- Importante: use variáveis de referência quando não houver uma alternativa mais adequada

## Control Flow

- Os modelos angulares suportam blocos de fluxo de controle que permitem mostrar, ocultar e repetir elementos condicionalmente

## Deferrable Views

- Podem ser usadas no modelo de componente para adiar o carregamento de dependências
- Essas dependências incluem componentes, diretivas e pipes e qualquer CSS associado