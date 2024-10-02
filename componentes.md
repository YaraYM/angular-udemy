# Componentes

- Uma aplica��o Angular � baseada em componentes
- Com eles, n�s podemos escapsular comportamentos e regras de interface, tornando a cria��o de aplica��es algo mais simples
- Inclusive, um componente pode encapsular outros componentes
- Componentes permitem voc� dividir a UI em partes independentes, reutiliz�veis
- Trata cada parte da aplica��o como um bloco isolado, livre de outras depend�ncias externas
- Eles aceitam entradas e retornam elementos que descrevem o que deve aparecer na tela

- Um componente � uma unidade de c�digo respons�vel por uma �nica tarefa ou funcionalidade
- Ele � composto por tr�s partes principais:
  - Template: � o c�digo HTML que define a interface visual do componente
  - Estilo: � o c�digo CSS que define o estilo visual do componente
  - Classe: � a classe JavaScript que define a l�gica de funcionamento do componente

- Os componentes s�o usados para organizar e modularizar o c�digo Angular
- Permitem que voc� desenvolva aplica��es mais complexas e escal�veis, mantendo o c�digo mais organizado e f�cil de manter

- Aqui est�o alguns dos benef�cios de usar componentes no Angular:
  - Reutiliza��o: os componentes podem sesr reutilizados em diferentes partes da aplica��o; isso ajuda a reduzir a duplia��o de c�digo e a melhorar a produtividade
  - Testabilidade: os componentes podem ser testados de forma indepenente, o que ajuda a garantir a qualidade do c�digo
  - Organiza��o: os componentes ajudam a organizar o c�digo Angular, tornando-o mais f�cil de entender e manter

- Alguns exemplos de componentes Angular s�o:
  - Componentes de formul�rio: s�o usados para criar formul�rios para coletar dados do usu�rio
  - Componentes de listagem: s�o usados para exibir uma lista de itens
  - Componentes de navega��o: s�o usados para controlar a navega��o entre diferentes p�ginas da aplica��o

- Os componentes s�o uma ferramenta fundamental para o desenvolvimento de aplica��o Angular
- Permitem que voc� desenvolva aplica��es mais complexas e escal�veis, mantendo o c�digo organizado e f�cil de manter

Componente = Template HTML + Style (CSS) + Classe TS

## Criando um componente

- Criar pasta components com o componente new-component: ng g component/new-component
- Criar component teste na pasta components: ng g c components/teste