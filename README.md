# Sistema Gamificado de Alto Desempenho (ENGETAK)
### Solução desenvolvida para medir, incentivar e engajar colaboradores através de mecânicas de jogos aplicadas ao ambiente corporativo.

## Objetivo do Projeto

Este sistema foi projetado para a empresa ENGETAK Engenharia Mecânica com o intuito de implementar uma gestão de produtividade disruptiva. O software permite que funcionários acumulem pontos ao realizar tarefas e avancem por fases, transformando metas operacionais em uma experiência dinâmica e motivadora.

## O que é Gamificação?

A gamificação é a estratégia de aplicar elementos, dinâmicas e mecânicas típicas de jogos em contextos que não são recreativos, como empresas, escolas ou rotinas de saúde. 
O objetivo principal é aumentar o engajamento, a motivação e a produtividade, transformando tarefas muitas vezes monótonas em experiências mais interativas e gratificantes. 
Através de sistemas de pontos, rankings, medalhas e feedbacks imediatos, a gamificação estimula o comportamento humano e facilita o alcance de metas de forma mais leve e envolvente. 

## Tecnologias e Arquitetura

A aplicação foi construída utilizando boas práticas de engenharia de software, garantindo separação de responsabilidades e escalabilidade.
  - Linguagem: C#
  - Plataforma: Windows Forms (WinForms)
  - Banco de Dados: MySQL
  - Integração: Exportação de dados para Excel para relatórios gerenciais;

## Estrutura de Camadas (Namespaces)

O código segue uma organização modular para facilitar a manutenção:
  - Models: Definição das classes de entidades principais como Funcionario, Projeto e Pontuacao;
  - Services: Camada de lógica de negócio e persistência, incluindo o gerenciamento da conexão com banco de dados;
  - Forms: Camada de interface gráfica e interação com o usuário;

## Funcionalidades Principais

  - Gestão de Talentos: Cadastro completo de colaboradores com segmentação por setor;
  - Controle de Projetos: Registro e acompanhamento de projetos vinculados a clientes específicos.
  - Motor de Gamificação: Sistema automatizado de atribuição de pontos e progressão de fases conforme a execução de tarefas.
  - Análise Gerencial: Geração de rankings de desempenho e relatórios organizados para tomada de decisão.

## Diagrama de Caso de Uso

<img width="629" height="276" alt="image" src="https://github.com/user-attachments/assets/462690f8-8cd8-4d6c-98cf-f25e275dc70f" />

## Estrutura do Repositório

   - Forms: Interfaces gráficas do sistema;
   - Models: Entidades de dados;
   - Services: Lógica de negócio e serviços SQL;
   - Program.cs: Ponto de entrada da aplicação;
   - .gitignore: Filtro de artefatos de compilação;
