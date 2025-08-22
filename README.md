
# 💻 Técnicas de Desenvolvimento de Algoritmos

[](https://opensource.org/licenses/MIT)

Repositório oficial da disciplina de Técnicas de Desenvolvimento de Algoritmos do curso de **Sistema de Informação** da **Pedro Henrique**.

**Professor(a):** Kadidja
**Semestre:** [Ano/Semestre, ex: 2025.2]  
**Contato:** `[email@universidade.br]`

-----

## 🎯 Objetivo da Disciplina

Esta disciplina tem como objetivo principal capacitar o aluno a analisar problemas e projetar, implementar e avaliar soluções algorítmicas eficientes. Serão abordados conceitos fundamentais de análise de complexidade, estruturas de dados avançadas e os principais paradigmas de projeto de algoritmos. Ao final do curso, o aluno deverá ser capaz de:

  - Analisar a complexidade de tempo e espaço de algoritmos.
  - Escolher e implementar as estruturas de dados mais adequadas para diferentes problemas.
  - Aplicar paradigmas como divisão e conquista, programação dinâmica, algoritmos gulosos e backtracking.
  - Modelar problemas do mundo real utilizando grafos e aplicar seus principais algoritmos.

-----

## 📚 Ementa

1.  **Introdução à Análise de Algoritmos**
      - Complexidade de tempo e espaço.
      - Notações Assintóticas (Big-O, Big-Omega, Theta).
      - Análise de algoritmos iterativos e recursivos.
2.  **Estruturas de Dados Avançadas**
      - Heaps (Binário, Binomial).
      - Árvores Balanceadas (AVL, Rubro-Negra).
      - Tabelas Hash.
3.  **Paradigmas de Projeto de Algoritmos**
      - Divisão e Conquista.
      - Programação Dinâmica.
      - Algoritmos Gulosos (Greedy).
      - Backtracking e Branch-and-Bound.
4.  **Algoritmos em Grafos**
      - Representações de Grafos.
      - Busca em Largura (BFS) e Profundidade (DFS).
      - Árvore Geradora Mínima (Kruskal, Prim).
      - Caminho Mínimo (Dijkstra, Bellman-Ford).
5.  **Tópicos Especiais (se houver tempo)**
      - Fluxo Máximo.
      - Complexidade Computacional (P, NP, NP-Completo).

-----

## 🗓️ Cronograma e Materiais de Aula

O cronograma detalhado e os materiais de apoio (slides, artigos, etc.) serão organizados por semana na pasta `/aulas`.

| Semana | Data (Aproximada) | Tópico Abordado                                | Atividades / Entregas                                    |
| :----: | :---------------: | ---------------------------------------------- | -------------------------------------------------------- |
|   01   |    `[dd/mm]`    | Apresentação da Disciplina e Análise de Algoritmos | Leitura do Cap. 1 do livro base                            |
|   02   |    `[dd/mm]`    | Notação Assintótica e Análise de Recorrências      | **Entrega da Lista 01** |
|   03   |    `[dd/mm]`    | Divisão e Conquista (Mergesort, Quicksort)         |                                                          |
|   04   |    `[dd/mm]`    | Estruturas de Dados: Heaps e Heapsort              | Início do Trabalho Prático 01                            |
|  ...   |        ...      | ...                                            | ...                                                      |
|   16   |    `[dd/mm]`    | **Prova Final / Apresentação do Projeto** | **Entrega Final do Projeto** |

-----

## 📝 Avaliação

A nota final ($N\_F$) será calculada com base nas seguintes atividades:

| Atividade            | Peso | Descrição                                                       |
| -------------------- | :--: | ----------------------------------------------------------------- |
| Listas de Exercícios | 20%  | Resolução de problemas teóricos e de implementação.               |
| Trabalhos Práticos   | 40%  | 2 trabalhos com implementação de algoritmos e análise de resultados. |
| Prova Final          | 40%  | Avaliação individual sobre todo o conteúdo da disciplina.         |

A nota final será calculada pela fórmula:

$$N_F = (Listas \cdot 0.2) + (Trabalhos \cdot 0.4) + (Prova \cdot 0.4)$$

**Observação:** A presença nas aulas é fundamental. As datas das avaliações não serão alteradas, exceto em casos excepcionais e previamente comunicados.

-----

## 🛠️ Ambiente de Desenvolvimento

Para a realização dos trabalhos e estudos, recomendamos o seguinte ambiente:

  * **Linguagem de Programação:** **[Python 3 / C++17 / Java 11]**. Todo o código de exemplo será fornecido nesta linguagem.
  * **Editor/IDE:** [VS Code](https://code.visualstudio.com/), [CLion](https://www.jetbrains.com/clion/), [IntelliJ IDEA](https://www.jetbrains.com/idea/) ou qualquer outro de sua preferência.
  * **Controle de Versão:** **Git** e **GitHub**. É altamente recomendável que você utilize Git para gerenciar seus projetos.

Para instalar as ferramentas básicas em um sistema baseado em Debian/Ubuntu:

```bash
sudo apt update
sudo apt install build-essential git
```

-----

## 📂 Estrutura do Repositório

```
/
├── 📄 .gitignore             # Arquivo para ignorar arquivos desnecessários no Git
├── 📂 aulas/                 # Slides e materiais de cada aula, organizados por semana
├── 📂 codigos/               # Códigos de exemplo desenvolvidos em aula
├── 📂 listas-de-exercicios/   # Enunciados e materiais das listas de exercícios
├── 📂 trabalhos-praticos/    # Especificações dos trabalhos práticos
└── 📄 README.md               # Este arquivo que você está lendo
```

-----

## 📖 Bibliografia

### Básica

  * CORMEN, T. H. et al. **Algoritmos: Teoria e Prática**. 3ª ed. Campus, 2012. (Livro principal)
  * SEDGEWICK, R.; WAYNE, K. **Algorithms**. 4ª ed. Addison-Wesley, 2011.

### Complementar

  * KLEINBERG, J.; TARDOS, E. **Algorithm Design**. Addison-Wesley, 2005.
  * LEVITIN, A. **The Design and Analysis of Algorithms**. 3ª ed. Pearson, 2012.
  * SKJENA, S. S. **The Algorithm Design Manual**. 2ª ed. Springer, 2008.

-----

## 📜 Licença

Este projeto e todos os seus materiais são distribuídos sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
