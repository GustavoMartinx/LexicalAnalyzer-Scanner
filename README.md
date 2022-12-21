<h1 align='center'> Lexical Analyzer (Scanner) </h1>

<p align='center'> This Lexical Analyzer (or Scanner) for the C- language was made in Python using a Moore Machine applying knowledge from Theory of Computing.</p> 

<br>


<h2 align='center'> How to Execute and How It Works </h2>

The program receives a source code as input
in the C- language and as output generates a list of tokens.

<br>Before executing it, it is necessary to install some dependencies, such as the Python programming language and after having it properly installed, it will be necessary to install one of its libraries, the ```automata-python``` . For that: <br>
* Access the [official website](https://www.python.org/downloads/) for more information about the Python language and install it. <br>
* Install the mentioned library using the command: ```pip install automata-python```.

<br>To use the Lexical Analyzer just insert a
source code in the C- language in the same directory where
the file ```lexical_analyzer.py``` is found and run
the following command: <br>
```
python lexical_analyzer.py <test_file.cm>
```
where ```<test_file.cm>``` is the name of the C- source file that will be received as input.


<br> <br> <br>


<h1 align='center'> Analizador Léxico </h1>

<p align='center'> O objetivo deste trabalho foi projetar e implementar um autômato com saída, do tipo
Máquina de Moore que funcione como um Analisador Léxico para a linguagem de programação C-, colocando
em prática, dessa forma, conceitos estudados da disciplina de Teoria da Computação (ou Linguagens Formais, Autômatos e Computabilidade).</p> <br>


<br>


<h2 align='center'> Como Executar e Funcionamento </h2>

O programa recebe como entrada um código-fonte
na linguagem C- e, como saída, gera uma lista de tokens. Veja mais detalhes sobre como este trabalho foi feito no relatório técnico -  `Report.pdf`

<br>Antes de executar, faz-se necessário a instalação de dependências, como a linguagem de programação Python e após tê-la devidamente instalada, será necessária a instalação de uma de suas bibliotecas, a ```automata-python```. Para tanto: <br>
* Acesse o [site oficial](https://www.python.org/downloads/) para obter mais informações sobre a linguagem Python e realize sua instalação. <br> 
* Instale a biblioteca mencionada através do comando: ```pip install automata-python```.

<br>Para utilizar o Analisador Léxico basta inserir um 
código-fonte na linguagem C- no mesmo diretório em que 
o arquivo ```lexical_analyzer.py``` se encontra e executar 
o seguinte comando: <br>
```
python lexical_analyzer.py <test_file.cm>
```
onde ```<test_file.cm>``` é o nome do arquivo-fonte em C- que será recebido como entrada.
