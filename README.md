## ⚙️ Arquitetura e Estruturas de Dados

### 1. Estrutura Principal: Lista Encadeada
A base do projeto é uma **[ESCOLHA: Lista Simplesmente Encadeada / Lista Duplamente Encadeada]**.
Diferente de vetores estáticos (arrays), esta lista permite o crescimento dinâmico da memória.

**Funcionalidades implementadas:**
- [x] **Inserção:** Adiciona novos nós mantendo os ponteiros atualizados.
- [x] **Remoção:** Remove nós por valor ou índice, liberando a memória.
- [x] **Busca:** Percorre a lista para localizar elementos.
- [x] **Display:** Imprime o estado atual da lista no console.



---

### 2. Estrutura Auxiliar: Pilha (Stack)
Para o controle de operações, foi implementada uma **Pilha**.
- **Comportamento:** LIFO (*Last In, First Out*).
- **Objetivo:** Armazena o histórico de ações para permitir funcionalidades de "Desfazer" ou auditoria de inserções.
- **Operações:** `push` (empilhar), `pop` (desempilhar), `top` (topo).



[Image of stack data structure operations push and pop]


### 2. Estrutura Auxiliar: Fila (Queue)
Para o controle de operações, foi implementada uma **Fila**.
- **Comportamento:** FIFO (*First In, First Out*).
- **Objetivo:** Simula uma fila de processamento onde as operações na lista são agendadas e executadas em ordem de chegada.
- **Operações:** `enqueue` (enfileirar), `dequeue` (desenfileirar), `front` (frente).

---

### 3. Algoritmo de Ordenação
Para organizar os elementos da lista, implementamos manualmente o algoritmo **[NOME DO ALGORITMO, EX: Bubble Sort]**.

* **Justificativa:** O algoritmo foi escolhido devido à sua [inserir motivo: simplicidade de implementação / eficiência O(n log n) / estabilidade].
* **Implementação:** A ordenação ocorre através da manipulação direta dos ponteiros dos nós, evitando a criação de cópias desnecessárias dos dados.
* **Complexidade:** $O(n^2)$ ou $O(n \log n)$ ---

## 🚀 Como Executar

### Pré-requisitos
* Compilador [GCC / Clang / Javac / Python] instalado.

### Passo a passo

1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/seu-repo.git](https://github.com/seu-usuario/seu-repo.git)
