# Estrutura de Dados em C

Implementações e exercícios da disciplina de **Estrutura de Dados I** (Ciência da Computação, UFPB), escritos em C.

## Conteúdo

| Pasta / arquivo | O que tem |
|---|---|
| `variaveis e ponteiros/` | Variáveis, tamanho de tipos, ponteiros e ponteiro para ponteiro |
| `funcoes/` | Passagem por valor e por referência |
| `vetores e matrizes/` | Vetores e matrizes estáticos e dinâmicos (incluindo 3D) |
| `struct/` | Structs e um CRUD simples de livros |
| `tad/` | Tipo Abstrato de Dados: vetor de floats |
| `listas encadeadas/` | Lista simplesmente encadeada, com testes e exercícios |
| `listas duplamente encadeadas/` | Lista duplamente encadeada, com testes |
| `listas circulares/` | Lista circular |
| `pilhas/` | Pilha estática e dinâmica, com testes |
| `filas/` | Fila estática e dinâmica, com testes |
| `tree.c`, `avltree.c` | Árvore binária e árvore AVL |

## Como compilar

Cada estrutura tem um arquivo de teste que já inclui a implementação. Por exemplo, a pilha:

```bash
gcc pilhas/test_stack.c -o test_stack
./test_stack
```

Os executáveis gerados ficam fora do repositório (veja o `.gitignore`).
