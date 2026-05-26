<img width="1015" height="231" alt="image" src="https://github.com/user-attachments/assets/2b27e1f2-b832-4596-9c71-67099e5b1db1" />

# ISOLATION AI
> Inteligência Artificial aplicada a jogos adversariais utilizando Minimax, Poda Alfa-Beta e Heurística de Liberdade Relativa.

---

## Sobre o Projeto

O projeto **ISOLATION** foi desenvolvido com o objetivo de explorar conceitos clássicos de Inteligência Artificial aplicados a jogos adversariais, combinando algoritmos de busca, sistemas heurísticos e visualização interativa de decisões estratégicas.

A aplicação implementa uma versão completa e estilizada do jogo Isolation, no qual dois jogadores disputam controle territorial em um tabuleiro dinâmico. A cada turno, os espaços utilizados tornam-se bloqueados, reduzindo progressivamente as possibilidades de movimentação até que um dos jogadores fique completamente isolado.

Dentro desse cenário competitivo, a IA toma decisões utilizando algoritmos clássicos de busca adversarial, avaliando estados futuros do jogo, prevendo respostas do oponente e selecionando jogadas estrategicamente vantajosas.

O projeto foi pensado não apenas como uma implementação funcional de IA, mas também como uma experiência visual e educacional capaz de demonstrar, de forma intuitiva, o funcionamento interno dos algoritmos utilizados.

Além da lógica do jogo, o sistema inclui:
- visualização da árvore Minimax
- demonstrações interativas da heurística
- heatmaps estratégicos
- comparação entre algoritmos
- feedback visual em tempo real
- logs das decisões da IA
- interface temática cyber/metallic

---

# Preview

## Gameplay

<img width="1387" height="920" alt="image" src="https://github.com/user-attachments/assets/6c0c8135-d5e1-4783-ac4d-1fd216a976bb" />


## Visualização da Heurística

<img width="1306" height="653" alt="image" src="https://github.com/user-attachments/assets/0bc4dc75-fda6-422b-a079-7efef4f48afe" />


## Visualização da Árvore Poda Alfa-Beta

<img width="1319" height="811" alt="image" src="https://github.com/user-attachments/assets/4d934162-613f-4237-b842-9f4a3a274552" />

---

# Principais Funcionalidades

- Sistema completo do jogo Isolation
- Inteligência Artificial baseada em Minimax
- Otimização utilizando Poda Alfa-Beta
- Heurística personalizada de Liberdade Relativa
- Avaliação estratégica de mobilidade
- Heatmap de decisões da IA
- Visualização interativa da árvore Minimax
- Logs de jogadas e decisões em tempo real
- Diferentes níveis de dificuldade
- Interface responsiva com animações e efeitos visuais

---

# Inteligência Artificial

## Minimax

O algoritmo Minimax é responsável pela tomada de decisão da IA.

A busca ocorre através da simulação de possíveis jogadas futuras, alternando entre:
- maximização das vantagens da IA
- minimização das oportunidades do adversário

Cada estado do jogo é avaliado recursivamente até uma determinada profundidade, permitindo que a IA escolha movimentos estrategicamente mais vantajosos.

---

## Poda Alfa-Beta

A poda Alfa-Beta foi implementada como otimização do algoritmo Minimax.

Durante a exploração da árvore de decisão, ramos irrelevantes são descartados antecipadamente quando não possuem potencial para alterar o resultado final da busca.

Isso reduz significativamente:
- o número de estados avaliados
- o custo computacional
- o tempo de resposta da IA

Sem comprometer a qualidade da decisão final.

---

## Heurística de Liberdade Relativa

A IA utiliza uma heurística personalizada baseada na diferença de mobilidade entre os jogadores.

A avaliação do estado do jogo ocorre através da seguinte função:

$$
H(s)=M_{IA}-M_{Jogador}
$$

Onde:
- \(M_{IA}\) representa a quantidade de movimentos válidos disponíveis para a IA
- \(M_{Jogador}\) representa os movimentos válidos do adversário

Quanto maior o valor da função heurística:
- maior o controle territorial da IA
- maior sua liberdade estratégica
- maior a capacidade de restringir o oponente

Essa abordagem permite que a IA priorize posições mais dominantes ao longo da partida.

---

# Comparação dos Algoritmos

| Algoritmo | Objetivo | Impacto |
|---|---|---|
| Minimax | Explorar possibilidades futuras | Base da tomada de decisão |
| Alfa-Beta | Eliminar ramos irrelevantes | Otimização de performance |
| Heurística Relativa | Avaliar vantagem posicional | Melhor qualidade estratégica |

---

# Interface e Visualização

O projeto foi desenvolvido com forte foco em experiência visual e demonstração didática dos conceitos de IA.

A interface utiliza uma identidade visual cyber/metallic com:
- animações dinâmicas
- efeitos visuais responsivos
- feedback em tempo real
- componentes interativos
- visualizações estratégicas

Além da jogabilidade, a aplicação busca transformar conceitos abstratos de Inteligência Artificial em uma experiência visual compreensível e intuitiva.

---

# Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Minimax Algorithm
- Alpha-Beta Pruning
- Heuristic Evaluation Functions

---

# Objetivos do Projeto

Este projeto foi desenvolvido com o objetivo de explorar:

- Inteligência Artificial aplicada a jogos
- Busca adversarial
- Algoritmos de tomada de decisão
- Sistemas heurísticos
- Otimização computacional
- Controle territorial em jogos competitivos
- Visualização interativa de algoritmos
- Design de interfaces experimentais

---

# Autor

Desenvolvido por **Arthur Xavier**.

---


Este projeto está sob a licença MIT.
