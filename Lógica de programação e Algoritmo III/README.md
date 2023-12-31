# Sumário: Introdução ao Treinamento e Plano de Estudo

- 1 - **Introdução ao treinamento e plano de estudo**

- 2 - **Linguagem JAVA**
   - 2.1 Conhecendo sua ferramenta de desenvolvimento [(NetBeans)](https://netbeans.apache.org/front/main/)
   - 2.2 Diferença entre [Portugol](https://dgadelha.github.io/Portugol-Webstudio/) e o [Java](https://www.oracle.com/br/java/technologies/downloads/)
   - 2.3 Comentários
   - 2.4 Comando de leitura e Gravação
   - 2.5 Variáveis, tipos e operadores
   - 2.6 Estrutura condicionais
      - 2.6.1 Estrutura `if`
      - 2.6.2 Esrutura `switch`
      - 2.6.3 Exercícios estruturas condicionais 
   - 2.7 Estruturas de repetição
      - 2.7.1 Estrutura `while`
      - 2.7.2 Esrutura `for`
      - 2.7.2 Exercícios de estruuras de repetição
   - 2.8 Classes
   - 2.9 Métodos
   - 2.10 Objetos
   - 2.11 Modificadores e acesso
   - 2.12 Métodos construtores
   - 2.13 Herança (Parte I)
   - 2.14 Herança (Parte II)
   - 2.15 Exercício Java

- 3 - **Conceitos básicos para a criação de uma interface gráfica em Java utilizando o SWING**
   - 3.1 Criando uma tela
   - 3.2 Paleta de Componentes
      - 3.2.1 Componentes
      - 3.2.2 Propriedades
      - 3.2.3 Eventos (Programação orientada a eventos)
         - 3.2.3.1 Implementando eventos
   - 3.3 Arvore de componentes
   - 3.4 Detalhes importantes
   - 3.5 Exercícios (criação de uma de login)

- 4 - **Iniciando um projeto**
   - 4.1 Definição de um projeto básico
      - 4.1.1 Requisitos do projeto
      - 4.1.2 Regras de negócio
      - 4.1.3 Definição da tecnologia

- 5 - **Especificando o Projeto**
   - 5.1 MER e banco de dados
      - 5.1.1 Conhecendo sua ferramenta (MySQL Workbench)
      - 5.1.2 Criando o MER da aplicação (Parte I)
      - 5.1.2 Criando o MER da aplicação (Parte II)
   - 5.2 Definição das classes modelo
   - 5.3 Interface gráfica
      - 5.3.1 Ferramenta de prototipagem

- 6 - **Codificando o projeto**
   - 6.1 O padrão de desenvolvimento MVC
   - 6.2 Criação das classes do modelo (Parte I)
   - 6.2 Criação das classes do modelo (Parte II)
   - 6.3 Criação do banco e dados (Parte I)
   - 6.3 Criação do banco e dados (Parte II)
   - 6.4 Criação da conexão com o banco de dados
   - 6.5 Construção da interface gráfica (Parte I)
   - 6.5 Construção da interface gráfica (Parte II)
      - 6.5.1 Entendendo o código fonte da interface gráfica

- 7 - **Finalizando e testando a aplicação**
   - 7.1 Finalização do Projeto (criação dos construtores)
      - 7.1.1 Interligando os controladores com a interface
      - 7.1.2 Validando campos
      - 7.1.3 Tratamento de erros
      - 7.1.4 Melhorias na interface
   - 7.2 Rodando a aplicação em modo debug
   - 7.3 Testes unitários

## Comparação entre Maven, Gradle e Ant em Projetos Java

### Maven

- **Objetivo Principal:** Gerenciamento de build, dependências e documentação.
- **Configuração:** Utiliza um arquivo XML chamado `pom.xml` para configurar o projeto.
- **Convenção sobre Configuração:** Segue uma abordagem "opinionated" onde há uma convenção padrão para a estrutura de diretórios e configurações, facilitando a configuração mínima do projeto.
- **Plugins:** Usa plugins Maven para execução de tarefas específicas.
- **Central Repository:** Utiliza o repositório central do Maven para armazenar bibliotecas e dependências.

### Gradle

- **Objetivo Principal:** Automatização de build, com uma abordagem mais flexível e extensível.
- **Configuração:** Utiliza um DSL (Domain Specific Language) baseado em Groovy ou Kotlin para configurar o projeto.
- **Convenção sobre Configuração:** Pode seguir uma convenção, mas é mais flexível em comparação com Maven, permitindo configurações personalizadas.
- **Plugins:** Usa plugins do próprio Gradle, e pode incorporar dependências do Maven.
- **Desempenho:** Geralmente considerado mais rápido do que o Maven.

### Ant

- **Objetivo Principal:** Automação de build.
- **Configuração:** Utiliza um arquivo XML chamado `build.xml` para configurar o projeto.
- **Convenção sobre Configuração:** Menos estruturado que o Maven, você precisa configurar muitos detalhes manualmente.
- **Plugins:** Não possui um sistema de plugins integrado como Maven e Gradle, e geralmente requer mais scripts personalizados.
- **Flexibilidade:** Oferece muita flexibilidade, mas com essa flexibilidade vem a responsabilidade de configurar detalhes específicos.

> **Resumo:**
> - Maven é conhecido por suas convenções estritas e facilidade de uso para projetos com estrutura padrão.
> - Gradle oferece mais flexibilidade e é altamente extensível, tornando-o uma escolha poderosa para projetos mais complexos.
> - Ant é mais antigo e fornece flexibilidade, mas muitas tarefas precisam ser configuradas manualmente.


