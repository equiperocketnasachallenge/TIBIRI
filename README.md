# Introdução

## 1.1. Objetivo Geral

O jogo foi desenvolvido para promover a conscientização ambiental de forma lúdica e interativa para alunos do ensino médio. Seu foco é transmitir conhecimento sobre problemas ambientais que afetam o Brasil, utilizando dados reais do Protocolo Globe da NASA, relacionados às queimadas ocorridas entre Outubro de 2023 e Outubro de 2024. O objetivo é tornar o aprendizado divertido e interativo, facilitando o engajamento dos alunos com temas importantes.

## 1.2. Visão Geral do Jogo

O jogo é single-player e utiliza um tabuleiro virtual interativo. Os jogadores percorrem um caminho que simula um rio brasileiro, enfrentando desafios e aprendendo sobre questões ambientais ao longo do percurso. Ao final, os jogadores serão incentivados a discutir um problema ambiental com seus professores e colegas em sala de aula.

## 1.3. Tecnologias Utilizadas

- **Canvas**: Utilizado para criação do design gráfico e do mapa do jogo.
- **Genially**: Plataforma de hospedagem do MVP, onde são inseridas as interações visuais e as cartas educativas.

# Descrição Técnica

## 2.1. Design do Jogo com Canvas

O design do tabuleiro do jogo foi criado utilizando a plataforma Canvas. As seguintes etapas foram seguidas:

- **ETAPA 1**: Definição do layout do mapa do jogo. O mapa representa um rio brasileiro, com áreas de interesse onde os jogadores encontram desafios ambientais.
- **ETAPA 2**: Implementação de ícones para aplicar áreas clicáveis no mapa, permitindo a interação do jogador com elementos chave do jogo.

## 2.2. Interações com Genially

Genially foi utilizado para hospedar e criar as interações do MVP do jogo. Isso permitiu que o jogo fosse facilmente acessado por qualquer dispositivo com acesso à internet.

- **ETAPA 1**: Upload de imagens do tabuleiro e seus elementos no Genially.
- **ETAPA 2**: Configuração de interações em pontos específicos do tabuleiro, como cartas educativas e perguntas.
- **ETAPA 3**: Integração de conteúdo multimídia para explicar os problemas ambientais enfrentados em cada bioma, com base nos dados fornecidos pela NASA.

# Manual do Jogo

## 3.1. Componentes do Jogo

O jogo é composto por um tabuleiro interativo, onde os jogadores percorrem um caminho simulado, inspirado em um rio brasileiro, enfrentando problemas ambientais. Ao longo do percurso, cartas educativas aparecem com informações e desafios relacionados às queimadas e outros problemas ambientais.

## 3.2. Objetivo do Jogo

O objetivo principal do jogo é conscientizar os jogadores sobre problemas ambientais do Brasil, utilizando dados reais de queimadas coletados pelo Protocolo Globe da NASA. No final do jogo, o jogador é desafiado a discutir uma questão ambiental com sua turma.

## 3.3. Como Jogar

O jogo utiliza a mecânica de point-and-click, com um sistema de múltipla escolha para os desafios. O jogador clica em áreas do tabuleiro para avançar no percurso e responder perguntas relacionadas ao tema.

1. O jogador clica no tabuleiro para mover-se ao próximo ponto de interesse.
2. Ao chegar no ponto, uma carta educativa aparece com um desafio relacionado ao problema ambiental do local.
3. O jogador escolhe a resposta que considera correta.

## 4. Como Acessar o Jogo

- **Passo 1**: Acesse a plataforma Genially através do link [Genially Interactive Game](https://view.genially.com/6702bd5284539aac21755a1c/interactive-image-tibiri) para ser redirecionado diretamente ao jogo.
- **Passo 2**: Siga as instruções no tabuleiro e divirta-se enquanto aprende sobre os problemas ambientais que afetam o Brasil!

# Próximos Passos Do Projeto

## 5.1. Implementação do Banco de Dados SQL

A próxima fase do projeto envolve a integração de um banco de dados SQL para monitorar o progresso dos jogadores e metrificar o conhecimento adquirido.

- **Objetivo do Banco de Dados**: Armazenar informações sobre os jogadores, suas pontuações e os desafios respondidos.
- **Estrutura do Banco de Dados**: O banco de dados conterá tabelas para:
  - Informações dos jogadores.
  - Histórico de pontuação por sessão de jogo.
- **Integração com o Jogo**: O banco de dados será integrado ao sistema para coletar e armazenar os dados de forma automática após cada sessão de jogo.

## 5.2. Migração para Aplicações Mobile e Web

Além da versão hospedada no Genially, a intenção é desenvolver uma versão mobile e uma aplicação web.

- **Tecnologias Sugestivas**:
  - Kotlin para a versão mobile.
  - React.js e Node.js para a versão web.
- **Fases de Migração**:
  - Primeira fase: Design responsivo, adaptando o layout para mobile.
  - Segunda fase: Integração do banco de dados para sincronização em tempo real com as sessões dos jogadores.
  - Terceira fase: Otimização das interações e feedback visual para dispositivos móveis.

# Possíveis Melhorias Futuras

- Adição de novos desafios e tópicos ambientais, como poluição e desmatamento.
- Expansão do conteúdo educacional.
- Criação de um sistema de rankings para aumentar o engajamento dos alunos.
