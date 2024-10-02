# Componentes

- Uma aplicação Angular é baseada em componentes
- Com eles, nós podemos escapsular comportamentos e regras de interface, tornando a criação de aplicações algo mais simples
- Inclusive, um componente pode encapsular outros componentes
- Componentes permitem você dividir a UI em partes independentes, reutilizáveis
- Trata cada parte da aplicação como um bloco isolado, livre de outras dependências externas
- Eles aceitam entradas e retornam elementos que descrevem o que deve aparecer na tela

- Um componente é uma unidade de código responsável por uma única tarefa ou funcionalidade
- Ele é composto por três partes principais:
  - Template: é o código HTML que define a interface visual do componente
  - Estilo: é o código CSS que define o estilo visual do componente
  - Classe: é a classe JavaScript que define a lógica de funcionamento do componente

- Os componentes são usados para organizar e modularizar o código Angular
- Permitem que você desenvolva aplicações mais complexas e escaláveis, mantendo o código mais organizado e fácil de manter

- Aqui estão alguns dos benefícios de usar componentes no Angular:
  - Reutilização: os componentes podem sesr reutilizados em diferentes partes da aplicação; isso ajuda a reduzir a dupliação de código e a melhorar a produtividade
  - Testabilidade: os componentes podem ser testados de forma indepenente, o que ajuda a garantir a qualidade do código
  - Organização: os componentes ajudam a organizar o código Angular, tornando-o mais fácil de entender e manter

- Alguns exemplos de componentes Angular são:
  - Componentes de formulário: são usados para criar formulários para coletar dados do usuário
  - Componentes de listagem: são usados para exibir uma lista de itens
  - Componentes de navegação: são usados para controlar a navegação entre diferentes páginas da aplicação

- Os componentes são uma ferramenta fundamental para o desenvolvimento de aplicação Angular
- Permitem que você desenvolva aplicações mais complexas e escaláveis, mantendo o código organizado e fácil de manter

Componente = Template HTML + Style (CSS) + Classe TS

## Criando um componente

- Criar pasta components com o componente new-component: ng g component/new-component
- Criar component teste na pasta components: ng g c components/teste