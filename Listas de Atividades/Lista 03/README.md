<h1>P.S. 2020.2 Lista 03 - Substituição Aritmética</h1>

<p>1 - Escreva um script que peça para o usuário digitar um número inteiro. Armazene este número da variável x. Faça a variável x receber o valor x + 21. Imprima na tela o valor de x.</p>

</br>
<p>2 - Escreva um script que soma 3 números passados como argumentos de linha de comando. Por exemplo:<p>

<p>$ ./a.sh 10 20 30</br>
> 60</p>

</br>
<p> 3 - Escreva um script que receba dois argumentos passados pela linha de comando, digamos a e b, e imprima o valor da expressão (a+10)b - 5. Por exemplo:</p>

<p>$ ./b.sh 0 2</br>
>95</p>

</br>
<p>4 - Escreva um script que recebe 3 nomes de arquivo como parâmetros de linha de comando e imprime a soma dos números de linhas dos 3 arquivos. Utilize a substituição de shell e o comando wc -l para contar o número de linhas de cada arquivo. Por exemplo:</p>

<p>$ ./c.sh a.txt b.txt c.txt</br>
> 13</p>

Supondo que os arquivos a.txt, b.txt e c.txt possuam o seguinte conteúdo:

#a.txt:
<p>1</p>
<p>2</p>
<p>3</p>

#b.txt:
<p>0</p>
<p>0</p>
<p>0</p>
<p>0</p>
<p>0</p>
<p>0</p>

#c.txt:
<p>a</p>
<p>b</p>
<p>c</p>
<p>d</p>