# Resolusoção-de-Lógica-Proposicional-Representa-o-e-Tabelas-Verdade
Abaixo estão as soluções para as frases apresentadas. Para cada caso, foram definidas as proposições simples ($P$, $Q$, $R$) e construída a tabela verdade com todas as combinações possíveis de Verdadeiro (V) e Falso (F).

---

### Legenda dos Conectivos
* **e ($\land$):** Conjunção (Só é V se tudo for V).
* **ou ($\lor$):** Disjunção (É V se pelo menos um for V).
* **Se... então ($\rightarrow$):** Condicional (Só é F se a primeira for V e a segunda for F).
* **Se e somente se ($\leftrightarrow$):** Bicondicional (É V se os valores forem iguais).

---

### 1. "Eu estudei para a prova e fiz todos os exercícios."

* **Proposição $P$:** Eu estudei para a prova.
* **Proposição $Q$:** Fiz todos os exercícios.
* **Representação Lógica:** $P \land Q$ (Conjunção)

| P | Q | P $\land$ Q |
|:-:|:-:|:---------:|
| V | V | **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **F** |

---

### 2. "Eu vou ao cinema ou fico em casa assistindo séries."

* **Proposição $P$:** Eu vou ao cinema.
* **Proposição $Q$:** Fico em casa assistindo séries.
* **Representação Lógica:** $P \lor Q$ (Disjunção Inclusiva)

| P | Q | P $\lor$ Q |
|:-:|:-:|:---------:|
| V | V | **V** |
| V | F | **V** |
| F | V | **V** |
| F | F | **F** |

---

### 3. "Se eu acordar cedo, então conseguirei pegar o ônibus."

* **Proposição $P$:** Eu acordar cedo.
* **Proposição $Q$:** Conseguirei pegar o ônibus.
* **Representação Lógica:** $P \rightarrow Q$ (Condicional)

| P | Q | P $\rightarrow$ Q |
|:-:|:-:|:-----------:|
| V | V | **V** |
| V | F | **F** |
| F | V | **V** |
| F | F | **V** |

---

### 4. "Se eu estudar muito, então passarei na prova e ganharei um presente."

* **Proposição $P$:** Eu estudar muito.
* **Proposição $Q$:** Passarei na prova.
* **Proposição $R$:** Ganharei um presente.
* **Representação Lógica:** $P \rightarrow (Q \land R)$

| P | Q | R | (Q $\land$ R) | P $\rightarrow$ (Q $\land$ R) |
|:-:|:-:|:-:|:-----------:|:-----------------------:|
| V | V | V | V | **V** |
| V | V | F | F | **F** |
| V | F | V | F | **F** |
| V | F | F | F | **F** |
| F | V | V | V | **V** |
| F | V | F | F | **V** |
| F | F | V | F | **V** |
| F | F | F | F | **V** |

---

### 5. "Eu vou jogar videogame ou vou estudar lógica de programação."

* **Proposição $P$:** Eu vou jogar videogame.
* **Proposição $Q$:** Vou estudar lógica de programação.
* **Representação Lógica:** $P \lor Q$ (Disjunção)

| P | Q | P $\lor$ Q |
|:-:|:-:|:---------:|
| V | V | **V** |
| V | F | **V** |
| F | V | **V** |
| F | F | **F** |

---

### 6. "Eu comi pizza e tomei refrigerante."

* **Proposição $P$:** Eu comi pizza.
* **Proposição $Q$:** Tomei refrigerante.
* **Representação Lógica:** $P \land Q$ (Conjunção)

| P | Q | P $\land$ Q |
|:-:|:-:|:---------:|
| V | V | **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **F** |

---

### 7. "Se eu tiver dinheiro, então viajarei nas férias."

* **Proposição $P$:** Eu tiver dinheiro.
* **Proposição $Q$:** Viajarei nas férias.
* **Representação Lógica:** $P \rightarrow Q$ (Condicional)

| P | Q | P $\rightarrow$ Q |
|:-:|:-:|:-----------:|
| V | V | **V** |
| V | F | **F** |
| F | V | **V** |
| F | F | **V** |

---

### 8. "Eu lerei um livro se e somente se terminar meu trabalho."

* **Proposição $P$:** Eu lerei um livro.
* **Proposição $Q$:** Terminar meu trabalho.
* **Representação Lógica:** $P \leftrightarrow Q$ (Bicondicional)

| P | Q | P $\leftrightarrow$ Q |
|:-:|:-:|:-------------:|
| V | V | **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **V** |

---

### 9. "Se estiver sol, então irei à praia ou ao parque."

* **Proposição $P$:** Estiver sol.
* **Proposição $Q$:** Irei à praia.
* **Proposição $R$:** Irei ao parque.
* **Representação Lógica:** $P \rightarrow (Q \lor R)$

| P | Q | R | (Q $\lor$ R) | P $\rightarrow$ (Q $\lor$ R) |
|:-:|:-:|:-:|:----------:|:----------------------:|
| V | V | V | V | **V** |
| V | V | F | V | **V** |
| V | F | V | V | **V** |
| V | F | F | F | **F** |
| F | V | V | V | **V** |
| F | V | F | V | **V** |
| F | F | V | V | **V** |
| F | F | F | F | **V** |

---

### 10. "Eu farei um bolo se e somente se comprar os ingredientes."

* **Proposição $P$:** Eu farei um bolo.
* **Proposição $Q$:** Comprar os ingredientes.
* **Representação Lógica:** $P \leftrightarrow Q$ (Bicondicional)

| P | Q | P $\leftrightarrow$ Q |
|:-:|:-:|:-------------:|
| V | V | **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **V** |
