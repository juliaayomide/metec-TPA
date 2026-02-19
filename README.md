# 🔁 Estruturas de Repetição: do while e for

## 📌 Laço do while

O laço **`do while`** é uma estrutura de repetição utilizada quando é necessário que o bloco de código seja executado **pelo menos uma vez**, independentemente da condição.

Diferente do `while`, no `do while` a condição é verificada **após** a execução do bloco de código.

### 🧠 Como funciona?

- O bloco de código é executado  
- A condição é verificada  
- Se a condição for verdadeira, o laço continua  
- Se for falsa, o laço é encerrado  

### 💻 Exemplo simples

```java
int contador = 1;

do {
    System.out.println(contador);
    contador++;
} while (contador <= 5);
