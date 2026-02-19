<h1>🔁 Estruturas de Repetição: do while e for</h1>

<h2>📌 Introdução</h2>
<p>
As estruturas de repetição <strong>do while</strong> e <strong>for</strong> são utilizadas na programação
para executar um mesmo bloco de código várias vezes, de forma organizada e eficiente.
Elas evitam repetição desnecessária de código e facilitam a resolução de problemas
que envolvem contagens, listas e repetições condicionais.
</p>

<h2>🧠 Laço do while</h2>
<p>
O <strong>do while</strong> é uma estrutura de repetição que garante que o bloco de código
seja executado pelo menos uma vez, pois a verificação da condição acontece somente
após a execução do código.
</p>

<p>
Esse laço é indicado quando é necessário executar uma ação inicial antes de validar
uma condição, como em interações com o usuário ou validações de entrada.
</p>

<h3>💻 Exemplo de do while</h3>
<pre><code>
int contador = 1;

do {
    System.out.println(contador);
    contador++;
} while (contador <= 5);
</code></pre>

<p>
Nesse exemplo, o código imprime os números de 1 a 5.
Mesmo que a condição fosse falsa no início, o bloco seria executado ao menos uma vez.
</p>

<h2>🧠 Laço for</h2>
<p>
O <strong>for</strong> é uma estrutura de repetição utilizada quando se sabe exatamente
quantas vezes o código deve ser executado. Ele concentra a inicialização,
a condição e o incremento em uma única linha.
</p>

<p>
Esse laço é muito utilizado para percorrer listas, vetores, matrizes
ou executar repetições com quantidade definida.
</p>

<h3>💻 Exemplo de for</h3>
<pre><code>
for (int contador = 1; contador <= 5; contador++) {
    System.out.println(contador);
}
</code></pre>

<p>
Nesse caso, o código também imprime os números de 1 a 5,
porém de forma mais compacta e organizada.
</p>

<h2>✅ Quando usar cada um?</h2>
<ul>
  <li>
    <strong>do while</strong>: quando o código precisa ser executado pelo menos uma vez,
    independentemente da condição inicial.
  </li>
  <li>
    <strong>for</strong>: quando a quantidade de repetições é conhecida ou controlada.
  </li>
</ul>

<h2>📌 Conclusão</h2>
<p>
As estruturas <strong>do while</strong> e <strong>for</strong> são fundamentais na lógica de programação.
Saber quando utilizar cada uma delas contribui para um código mais claro,
organizado e eficiente, além de facilitar a manutenção e leitura do programa.
</p>
