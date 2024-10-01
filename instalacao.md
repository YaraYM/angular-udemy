# Instalação do Angular

- Para utilizar o Angular é bem simples, precisamos ter instalado na máquina NodeJS e npm
- Este requisito é necessário porque o Angular é instalado atavés do npm, que é o gerenciador de pacotes que é instalado junto com o NodeJS
- Após ter instalado o NodeJS e o npm, veja se eles estão funcionando em sua máquina; é muito simples, abra o terminal e digite 'node -v' e 'npm -v'; após digitar, aparacerá a versão de ambos
- Agora sim podemos instalar o Angular CLI

## Angular CLI

- Resumindo, Angular CLI é a interface de linha de comando para Angular
- O Angular CLI é uma ferramenta open source desenvolvida pelo próprio time do Angular e é utilizdo para facilitar a criação de componentes, classes, services e outros
- Comando para instalar: npm install -g @angular/cli
- Instalar versão específica: npm install -g @angular/cli@17.0.0

## Principais comandos CLI

- Lista de comandos ng: ng --help
- Lista com mais comandos ng: ng g --help
- Criar novo projeto Angular: ng n nome-do-projeto / ng new nome-do-projeto
- Rodar no servidor local: ng server / ng s

  ng add <collection>            Adds support for an external library to your project. 
  ng analytics                   Configures the gathering of Angular CLI usage metrics.
  ng build [project]             Compiles an Angular application or library into an output directory named dist/ at the given output path.                                    [aliases: b]  ng cache                       Configure persistent disk cache and retrieve cache statistics.
  ng completion                  Set up Angular CLI autocompletion for your terminal.
  ng config [json-path] [value]  Retrieves or sets Angular configuration values in the angular.json file for the workspace.
  ng deploy [project]            Invokes the deploy builder for a specified project or for the default project in the workspace.
  ng e2e [project]               Builds and serves an Angular application, then runs end-to-end tests.                                                                        [aliases: e]  ng extract-i18n [project]      Extracts i18n messages from source code.
  ng generate                    Generates and/or modifies files based on a schematic.                                                                                        [aliases: g]  ng lint [project]              Runs linting tools on Angular application code in a given project folder.
  ng new [name]                  Creates a new Angular workspace.                                                                                                             [aliases: n]  ng run <target>                Runs an Architect target with an optional custom builder configuration defined in your project.
  ng serve [project]             Builds and serves your application, rebuilding on file changes.                                                                         [aliases: dev, s]  ng test [project]              Runs unit tests in a project.                                                                                                                [aliases: t]  ng update [packages..]         Updates your workspace and its dependencies. See https://update.angular.dev/.
  ng version                     Outputs Angular CLI version.                                                                                                                 [aliases: v]
Options:
  --help     Shows a help message for this command in the console.                                                                                                               [boolean]  --version  Show Angular CLI version.                                                                                                                                           [boolean]

- Buldar a aplica��o: ng build