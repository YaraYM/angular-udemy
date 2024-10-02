# Seletores Especiais

## :host

- Seletor especial que se refere ao componente em que está sendo usado
- É usado para aplicar estilos diretamente ao componente em si em vez de seus elementos filhos
- Você pode definir estilos específicos para o componente raiz, por exemplo, alterando a cor de fundo ou a borda do componente

## :host-context() 

- Seletor que permite aplicar estilos com base no  contexto do componente-pai
- Isso é útil quando você deseja aplicar estilos com base em condições no componente-pai
- Por exemplo, você pode alterar a cor de fundo de um componente-fiho com base em um valor definido em seu componente-pai

      :host-context(.theme-dark) {
        h2 {
          background: #000;
          color: #fff;
        }
      }

## ::ng-deep

- Ele é um mecanismo que permite que os estilos definidos em um componente sejam aplicados aos elementos
- Em outras palavras, ele permite que você contorne o encapsulamento de estilos em componentes
- No entanto, é importante notar que o uso excessivo de ::ng-deep pode tornar o código mais difícil de manter e pode não ser a melhor prática em muitos casos