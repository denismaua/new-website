---
title: MAC0318 Programming Mobile Robots
linkTitle: Mobile Robots
summary: Introductions to Mobile Robots.
date: '2022-04-18'
type: book
---

{{< toc hide_on="xl" >}}

## Justificativa

Robôs inteligentes móveis estão cada vez mais presentes em nosso dia-a-dia, de aspiradores de pó a veículos aéreos não-tripulados e carros semi-autônomos. Para serem bem sucedidos, tais robôs precisam resolver questões complexas como evitar colisões com obstáculos móveis, localizar-se no ambiente a partir de <mark>sensoriamento</mark> (câmera, sonares, lidares, odômetros etc), <mark>reconhecer objetos</mark> e sinais indicativos, <mark>planejar</mark> e <mark>prever</mark> trajetórias, seguir regras pré-estabelecidas e estabelecer e <mark>executar</mark> planos de longo prazo com recompensas esparsas e atrasadas. Diferentemente dos robôs atuais que habitam ambientes industriais, os robôs do futuro próximo deverão atuar em ambientes pouco controláveis e extremamente variáveis como o interior de uma casa, os corredores de um hospital ou as ruas de uma cidade. 

## Objetivo

{{< figure src="2019pista.JPG" >}}

Esta disciplina visa introduzir alunos avançados de graduação aos desafios da robótica inteligente móvel, por meio do ensino de conceitos e técnicas de controle ótimo, processamento de imagens, raciocínio probabilístico, otimização, planejamento, aprendizado de máquina, entre outras. Ao final do semestre você aprenderá os conceitos fundamentais da robótica inteligente e deverá saber as respostas para perguntas como: O que é um robô móvel? Quais os principais desafios no desenvolvimento de robôs inteligente móveis? Quais as limitações físicas e lógicas das arquiteturas de agentes autônomos? Quais as implicações práticas das aproximações e simplificações adotas na formalização matemática dos agentes? 

## Metodologia

{{< figure src="navegação.JPG" >}}

A disciplina é baseada em atividades práticas nas quais os conceitos apresentados devem ser utilizados para implementar soluções para problemas comuns em robótica móvel. O critério de avaliação consiste na média ponderada das notas das atividades regulares resolvidas em classe e de um projeto final resolvido em grupos.

## Conteúdo

A disciplina é dividida em 8 módulos de aprendizado; cada módulo toma de 1 a 3 aulas e é acompanhado de uma ou mais atividades. Há também um projeto final em grupo.

1. Introdução aos veículos autônomos
    1. Questões fundamentais da robótica móvel
    2. Autonomia
    3. Robôs móveis: atuadores e sensores e direção diferencial
    4. Arquitetura lógica: percepção, planejamento e execução
    5. Arquiteturas sensorimotoras
    6. Veículos de Braitenberg
2. Sistemas de controle
    1. Definição e avaliação
    2. Controle de malha aberta e de malha fechada
    5. Representação de estado para robô pontual
    6. Modelo de robô diferencial no plano
    7. Controle PID
3. Navegação
    1. Planejamento de caminho reativo
    2. O algoritmo Bug
    3. Campos potenciais
4. Aprendizado de máquina supervisionado
    1. Definição
    2. Regressão
    3. Estimação de pose a partir de imagem
    4. Classificação
    5. Reconhecimento de objetos
    6. Aprendizado por imitação
    7. Metodologia
5. Estimação de estado e localização
    1. Filtro bayesiano
    2. Odometria e localização por odômetro (dead reckoning)
    3. Filtro por histograma
    4. Filtro de Monte Carlo
6. Planejamento por busca em grafo
    1. Representação do ambiente
    2. Busca em grafo
    3. Algoritmo de Dijkstra
    4. Busca A*
7. Planejamento por amostragem
    1. RRT
8. Aprendizado por reforço
    1. Processos de decisão markovianos
    2. Aprendizado temporal
    3. Q-Learning
    4. Gradiente de política

## Pré-requisitos

- Conhecimento básico de Linux (comandos usuais de terminal, gerenciamento de pacotes), Python e Git (push, pull, commit, branch, fork, merge)
- Conhecimento elementar de álgebra linear (transformação lineares, matriz de  rotação), probabilidade (variáveis aleatórias gaussianas, função de densidade, marginalização e regra de Bayes) e cálculo (sistemas de equações de derivadas parciais)
- Conhecimento básico de estruturas de dados (pilhas, filas, filas de prioridade) e teoria dos grafos (busca em profundidade, busca em largura).
- Computador com Linux instalado (de preferência Ubuntu) e acesso de administrador.

## Link para repositório

https://gitlab.uspdigital.usp.br/mac0318-2021

## Bibliografia

- P. Corke. Robotics, Vision and Control: Fundamental Algorithms in Matlab, Springer, 2a. edição, 2017.
- S. Thrun, B. Wolfram, D. Fox, Probabilistic Robotics, MIT Press, Cambridge, MA, 2005.
- G. Dudek, M. Jenkin, Computational Principles of Mobile Robotics, Cambridge University Press, 2000.
- R. Siegwart, I.R. Nourbakhsh, Introduction to Autonomous Mobile Robots, MIT Press, Cambridge, MA, 2004.
- S. Russel, P. Norvig, Artificial Intelligence: A Modern Approach. Third edition. Prentice-Hall, Englewood Cliffs, NJ, 2009.
- U. Nehmzow, Mobile Robotics: A Practical Introduction, Springer Verlag, 2000.
- R. Murphy, Introduction to AI Robotics, MIT Press, Cambridge, MA, 2000.
- R. Arkin, Behavior-based Robotics, MIT Press, Cambridge, MA, 1998.

{{< figure src="interlagos.jpg" >}}

<!-- ## Meet your instructor

{{< mention "admin" >}} -->

<!-- ## FAQs

{{< spoiler text="Are there prerequisites?" >}}
There are no prerequisites for the first course.
{{< /spoiler >}}

{{< spoiler text="How often do the courses run?" >}}
Continuously, at your own pace.
{{< /spoiler >}}
