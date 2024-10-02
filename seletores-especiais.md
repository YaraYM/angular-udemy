# Seletores Especiais

## :host

- Seletor especial que se refere ao componente em que est� sendo usado
- � usado para aplicar estilos diretamente ao componente em si em vez de seus elementos filhos
- Voc� pode definir estilos espec�ficos para o componente raiz, por exemplo, alterando a cor de fundo ou a borda do componente

## :host-context() 

- Seletor que permite aplicar estilos com base no  contexto do componente-pai
- Isso � �til quando voc� deseja aplicar estilos com base em condi��es no componente-pai
- Por exemplo, voc� pode alterar a cor de fundo de um componente-fiho com base em um valor definido em seu componente-pai

      :host-context(.theme-dark) {
        h2 {
          background: #000;
          color: #fff;
        }
      }

## ::ng-deep

- Ele � um mecanismo que permite que os estilos definidos em um componente sejam aplicados aos elementos
- Em outras palavras, ele permite que voc� contorne o encapsulamento de estilos em componentes
- No entanto, � importante notar que o uso excessivo de ::ng-deep pode tornar o c�digo mais dif�cil de manter e pode n�o ser a melhor pr�tica em muitos casos