# Projeto de Bloco: Estruturas de Dados e Algoritmos de Alto Desempenho

Este repositório reúne todos os trabalhos práticos e o projeto de consolidação final desenvolvidos ao longo do Projeto de Bloco. O objetivo do curso é o estudo e implementação de algoritmos de ordenação, estruturas de dados clássicas, programação concorrente e assíncrona, grafos, heurísticas de otimização e redes de computadores.

Todas as soluções foram desenvolvidas em Python e estruturadas para rodar de forma nativa e direta na plataforma do Google Colab.

---

## Conteúdo do Repositório

### Teste de Performance 1 (TP1)
Implementação de algoritmos clássicos de ordenação (Bubble Sort, Selection Sort e Insertion Sort) com análise comparativa de suas curvas de desempenho por meio de gráficos gerados com matplotlib. Construção de estruturas de dados lineares em memória: Pilha, Fila e uma classe personalizada de Tabela Hash com tratamento de colisões. Avaliação prática do tempo de carga, picos de memória e tempo de recuperação em cada uma das estruturas implementadas.
* **Acessar no Google Colab:** [Executar TP1](https://colab.research.google.com/drive/1mOMhCkTYUvx3ytSRvRrgk6T35L180C1F#scrollTo=BcjkOzhyhiqf)

### Teste de Performance 2 (TP2)
Desenvolvimento de rotinas assíncronas utilizando asyncio para simulação de fluxos concorrentes (pipeline) e servidores TCP. Implementação de algoritmos de ordenação avançada com QuickSelect e QuickSort híbrido acoplado a Insertion Sort. Construção de estruturas de dados encadeadas circulares e duplamente ordenadas. Desenvolvimento de lógicas paralelas com ThreadPoolExecutor para soma, escalonamento round-robin de blocos, balanceamento dinâmico via prefix sums e multiplicação de matrizes.
* **Acessar no Google Colab:** [Executar TP2](https://colab.research.google.com/drive/1WPHYuYETZ90nRQhVSil1oi4wUVqZCnLK)

### Teste de Performance 3 (TP3)
Implementação de Árvores Binárias de Busca (BST) contendo operações de inserção, remoção, cálculo de altura e buscas ordenadas com relatórios de performance em escalas crescentes. Construção de uma Árvore Trie direcionada à identificação de rotas IPv4 e correspondência por maior prefixo (Longest Prefix Match - LPM). Paralelização de processamento vetorial, produto escalar e contagem de números primos utilizando ThreadPoolExecutor em Python.
* **Acessar no Google Colab:** [Executar TP3](https://colab.research.google.com/drive/1nOWwzyzsMtWTENmqVMLl-wYySI2M5TCX)

### Teste de Performance 4 (TP4)
Construção de Min-Heaps e Max-Heaps com aplicação prática na modelagem de um sistema de prioridades de pouso de aviões com base no nível de combustível. Desenvolvimento de uma Árvore Trie de palavras com funcionalidade de autocomplete por busca de prefixo. Criação de representações de grafos com caminhamento em largura (BFS). Construção de servidores e clientes sockets TCP/UDP locais rodando sob threads paralelas em segundo plano.
* **Acessar no Google Colab:** [Executar TP4](https://colab.research.google.com/drive/1FDYieoN9SIIE2gR68v-MPD8OgNlVb4Ef)

### Teste de Performance 5 (TP5)
Uso do algoritmo de Dijkstra para determinação de caminhos mínimos em grafos valorados. Implementação de estratégias gulosas e heurísticas de otimização aplicadas ao problema da Mochila Fracionária e ao problema do Caixeiro Viajante (TSP). Simulação conceitual de sockets seguros com TLS em Python. Desenvolvimento de rotinas para varredura de portas de rede (port scanner) e medição de latência em requisições de consulta DNS externas.
* **Acessar no Google Colab:** [Executar TP5](https://colab.research.google.com/drive/155fHZpXadIlyL-VIC1yOkzNW3suLuLKT)

### Assessment de Bloco (AT)
Compilação integral de todas as resoluções e códigos desenvolvidos do TP1 ao TP5 em um único caderno unificado. Todo o código do projeto foi estruturado, comentado e revisado em Python puro, eliminando dependências compiladas em C++ para assegurar portabilidade total de execução na nuvem. Contém relatórios teóricos consolidados e verificações de tempo e uso de memória para todas as partes integradas.
* **Acessar no Google Colab:** [Executar AT (Consolidado)](https://colab.research.google.com/drive/1OaCi4WfCW-ddzHXuLAPTNUHyQYy_eo8c)
