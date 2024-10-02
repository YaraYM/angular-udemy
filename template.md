# Template

- Template no Angular � uma parte de uma p�gina da web que cont�m elementos HTML e c�digos Angular para exibir informa��es din�micas
- � uma forma de exibir dados em seu componente HTML; nada mais do que trabalhar com dados

  - Text interpolation
  - Template statements
  - Binding
  - Template Reference Variables
  - Control flow
  - Deferrable Views

## Text Interpolation

- No Angular, "Text interpolation" � uma maneira f�cil e poderosa de exibir valores din�micos em seu template HTML
- Ela permite que voc� insira valores de vari�veis diretamente no seu c�digo HTML, tornando a exibi��o de dados din�micos muito simples

## Binding

- "Binding" � um conceito funcamental que se refere � maneira como os dados fluem entre a parte l�gica de um aplicativo e a interface do usu�rio
- O binding permite que voc� conecte os dados do seu aplicativo com os elemento sdo seu template HTML, tornando-o din�mico e interativo

- Existem cinco tipos de binding no Angular:
  1. Property Binding
  2. Attribute binding
  3. Class and style binding
  4. Event binding
  5. Two-way binding

## Template Reference Variables

- As "Template Reference Variables" s�o uma maneira �til de acessar elementos do seu template HTML diretamente em seu c�digo
- Elas s�o definidas em seus elementos HTML como o uso do s�mbolo # seguido por um nome de vari�vel
- Isso permite que voc� se comunique entre o c�digo do componente e o template de uma forma mais direta

- Existem algumas formas de uso no Angular:
  - #nome
  - ViewChild('nome') nome: ElementRef

- Importante: use vari�veis de refer�ncia quando n�o houver uma alternativa mais adequada

## Control Flow

- Os modelos angulares suportam blocos de fluxo de controle que permitem mostrar, ocultar e repetir elementos condicionalmente

## Deferrable Views

- Podem ser usadas no modelo de componente para adiar o carregamento de depend�ncias
- Essas depend�ncias incluem componentes, diretivas e pipes e qualquer CSS associado