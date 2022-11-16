# INTRODUÇÃO À PROGRAMAÇÃO E PENSAMENTO COMPUTACIONAL  :computer:



## Pensamento computacional



### Introdução ao pensamento computacional

​	É o processo de pensamento envolvido na expressão de soluções em passos computacionais ou algoritmos que podem ser implementados no computador. É sistemático e eficiente, tanto na formulação quanto na resolução de problemas. Tem que ser utilizado de uma maneira que humanos e máquinas sejam capazes de resolver.

​	Não é uma disciplina acadêmica, e sim uma habilidade generalista. Pode ser utilizado na matemática, na leitura, na escrita, etc.

​	É baseado em quatro pilares:

- Decomposição;
- Reconhecimento de padrões;
- Abstração;
- Design de algoritmos.



### Habilidades complementares

##### Raciocínio lógico

​	É uma forma de pensamento estruturado que permite encontrar a conclusão ou determinar a resolução de um problema.

​	Pode estar classificado em três grupos:

- Indução - vem a partir de um fenômeno observado, do qual é possível determinar leis e teorias. Esse tipo de raciocínio está muito relacionado às ciências experimentais, ao empirismo;
- Dedução - inverso da indução. A partir de leis e teorias se deduz previsões e explicações para o fenômeno. Utilizado nas ciências exatas;
- Abdução - a partir de uma conclusão observada se supõe outra coisa, uma premissa. Muito utilizada no processo investigativo, em diagnósticos.



##### Aperfeiçoamento

​	A partir de uma solução, determinar pontos de melhora e refinamento. É um processo cíclico. Ao encontrar soluções eficientes e otimizar processos, os recursos são utilizados de uma forma melhor, e simplificando linhas de códigos e definindo bem as funções, os códigos e algoritmos são otimizados.



### Pilares

##### Decomposição

​	Dado um problema complexo, é possível quebrá-lo em problemas menores, mais fáceis e gerenciáveis.

​	Estratégia:

- Análise - processo de quebrar e determinar partes menores e estudá-las, realizando um exame detalhado;
- Síntese - combinar os elementos, recompondo o problema original, fundindo-os de maneira coerente.

​	Ordem de execução:

- Sequencial - execução em fila. Utilizada principalmente quando há uma dependência entre tarefas;
- Paralela - tarefas podem ser realizadas concomitantemente.



##### Padrões

​	É um modelo de referência que determina uma estrutura invariante através de repetição. Determinamos padrões para poder generalizar, com o objetivo de obter resolução para problemas diferentes.

​	Simulamos esse comportamento num computador através da representação de atributos. A máquina então aprende os conceitos associados ao objeto e armazena esses dados para consultas posteriores a fim de utilizá-los para comparação.

​	O computador é objetivo, enquanto o ser humano é subjetivo.

​	A detecção de padrão vem da ideia de extrair características a fim de classificar seus dados.



##### Abstração

​	Abstrair é observar um ou mais elementos, avaliando características e propriedades separadamente. Abstração é o processo intelectual de isolamento de um objeto da realidade. Nesse processo pegamos os elementos principais de um determinado objeto, e os extrapolamos para um mundo abstrato.

​	Generalização, na lógica, é a operação intelectual que consiste em reunir numa classe geral, um conjunto de seres ou fenômenos similares. Os dados são classificados através de características, detectando os pontos essenciais e generalizando em detrimento dos detalhes. Em resumo: isolamos os aspectos relevantes de um todo e os consideramos de forma individual, ignorando detalhes.



##### Algoritmos

​	O processo de resolução de algoritmos é chamado de _step by step_ (na tradução, passo a passo), e utiliza instruções pré-determinadas. É necessário saber o que precisa ser feito e qual a ordem de execução para determiná-las.

​	Para o desenvolvimento de programa é preciso analisar, estudar, e definir os dados de entrada e saída. O algoritmo descreve o problema por meio de ferramentas narrativas, fluxograma, ou pseudocódigo. É codificado de acordo com a linguagem de programação escolhida.

​	Como construir um algoritmo:

- Compreensão do problema: pontos mais importantes;
- Definição dos dados de entrada: dados fornecidos inerente ao contexto;
- Definição do processamento: operações a serem realizadas para o processamento de dados;
- Definição dos dados de saída: resultados;
- Utilização de um método de construção/refinamento;
- Testes e diagnósticos.

​	Meios de construção:

- Narrativa - utiliza a linguagem natural;
- Fluxograma - utiliza uma estrutura gráfica de símbolos pré-definidos;
- Pseudocódigo - Portugol.



## Introdução à lógica de programação



### O que é a lógica?

​	Lógica é utilizada para solucionar algum problema, que é uma questão que foge a uma determinada regra, ou melhor, é um desvio de percurso, que impede de atingir um objetivo com eficácia e eficiência. É uma parte da filosofia que trata das formas do pensamento em geral ( dedução, indução, hipótese, inferência, etc) e das operações intelectuais que visam à determinação do que é verdadeiro ou não. Pode ser definida como organização e planejamento das instruções, assertivas em um algoritmo, a fim de viabilizar a implantação de um programa.



### Técnicas de lógica de programação

##### Técnica linear

- Modelo tradicional;
- Não tem vínculo;
- Estrutura hierárquica;
- Execução sequenciada;
- Recursos limitados;
- Voltada para a solução de problemas matemáticos complexos.



##### Técnica estruturada

- Pode ter mais de uma opção;
- Preconiza que todos os programas possíveis podem ser reduzidos a apenas três estruturas: sequência, decisão, e repetição.



##### Técnica modular

- Partes independentes controladas por um conjunto de regras.



## Fundamentos de algoritmos



### Tipologia e variáveis

​	A função de um computador é processar informações, compostas por dados (sendo eles numéricos, caracteres, e lógicos) e instruções.

​	Variável é um tipo de estrutura mutável e inconstante, que pode receber mais de um valor e modificar seu conteúdo, estando contudo restrita ao seu tipo.

​	Regras para nomear variáveis:

- Atribuição de um ou mais caracteres (ex.: "x" ou "matrícula");
- Primeira letra;
- Sem espaços em branco;
- Não podem ser utilizadas palavras reservadas de uma determinada linguagem de programação;
- Caracteres, números e lógicos (booleanos) são aceitos.

​	Papéis de uma variável:

- Ação: modificação do estado de um algoritmo;
- Controle: vigia e controle de alguma estrutura, etc.



### Instruções primitivas

​	Instruções determinam ações executadas com os dados. Geralmente são cálculos matemáticos, e é para isso que são usados operadores. Dentro desses cálculos são utilizadas as variáveis e constantes como _input_ (entrada). Os operadores podem ser binários ou unários.

​	São comandos básicos existentes nas linguagens de programação, palavras-chave que tem por finalidade comandar um computador que irá tratar os dados.



##### Entrada, processamento e saída

​	Os dados são importados de algum lugar (arquivo, diretório, etc) e levados ao ambiente computacional para serem processados e depois imprimidos.



### Estruturas condicionais e operadores

​	Condicional: que expressa uma condição ou suposição; contém ou implica uma suposição ou hipótese.

​	Há três tipos de estrutura:

- Simples - verifica se a condição foi satisfeita;
- Composta - verifica também a exceção;
- Encadeada - uma sucessão de estruturas.



##### Operadores lógicos

​	Utilizados para respostas simplificadas, como de V (verdadeiro) ou F (falso).

- _AND_ - todas as condições devem ser satisfeitas;
- _OR_ - apenas uma das condições pode ser verdadeira;
- _NOT_ - inversão do resultado lógico.



### Estruturas de repetição

​	É uma estrutura que irá executar um determinado trecho de um programa a partir de certos parâmetros que serão estabelecidos dentro dessa estrutura. Para haver essa repetição sem que ocorra um _loop_ infinito é necessário uma condição de parada, que pode ser um número de repetições pré-fixado ou uma condição a ser satisfeita.

​	Algumas vantagens dessa estrutura sobre a repetição do código:

- Redução de linhas;
- Compreensão facilitada;
- Redução de erro.

​	É possível utilizar uma estrutura condicional dentro de uma estrutura de repetição.



### Vetores e matrizes

​	Um vetor é caracterizado por uma variável dimensionada com tamanho pré-fixado. Pode ser visto como um _container_ ou uma matriz unidimensional.

​	Matriz é uma tabela organizada em linhas e colunas no formato m x n, onde m representa o número de linhas (horizontal), e n o número de colunas (vertical).



### O que são funções?

​	As funções, ou sub-rotinas, são blocos de instruções que realizam tarefas específicas, ou seja, é a modularização do problema. São identificados por nomes e parâmetros.



### Instruções de entrada/saída

##### Entrada

​	Consiste na inserção e recebimento de dados do mundo real por meio de ação de alguma interface, seja ela um teclado, mouse, arquivo, entre outros.



##### Saída

​	Consiste na impressão dos dados do mundo abstrato por meio da ação de alguma interface. Os formatos podem variar desde simples arquivos binários até complexas _queries_ de banco de dados.

​	Existem dois tipos de saída: programada e por interrupção. Ela pode ser bem sucedida, ou pode haver problemas com a interface, erros de programação, de sintaxe, etc.



## Linguagens de programação



### Introdução à linguagem de programação

​	Quando compreendemos as dificuldades enfrentadas no passado, conseguimos fazer um paralelo com os dias de hoje, e percebemos que os fundamentos da computação são os mesmo. Também entendemos qual foi o processo de pensamento utilizado para que a tecnologia evoluísse da maneira que evoluiu.

​	Toda evolução tecnológica inicia-se pelo hardware e depois segue para o software.



##### História da computação

- 3000 A.C. - primeiro dispositivo de cálculo (ábaco);
- 1820 - instrumentos computacionais (_arithmometer_);
- 1837 - conceito de software de Charles Babbage;
- 1940 - Alan Turing e cia. decifram a Enigma;
- 1942-43 - transcrição de Ada Lovelace;
- Entre 40 e 50 - projeto Dilab USA (codificador de voz) de Turing, Neumann e Shannon;
- 1946 - ACE de Turing e Neumann;
- 1948 - álgebra booleana de Claude Shannon;
- 1950 - IA por Alan Turing.



- 1975 - Intel 8080, linguagem Basic e Microsoft;
- 1976 - Apple;
- 1977 - Apple II;
- 1980 - Apple III;
- 1981 - IBM-PC, _opensource_;
- 1983 - Lisa (fracasso da Apple);
- 1985 - Windows 1.0;
- 1988 - Windows 2000;
- 2001 - Windows XP.



- 1949 - primeira linguagem de máquina (Assembly);
- Anos 50 - primeiras linguagens de programação (COBOL, Fortran, Lisp);
- Entre 60 e 70 - paradigmas (C, Machine Learning, Prolog);
- Anos 90 - alto nível (C#, Python, Ruby, Java, JavaScript);
- 2000 - novos conceitos (TypeScript, Go, Swift).



##### O que é uma linguagem de programação?

​	É um método padronizado composto por um conjunto de regras sintáticas e semânticas de implementação de um código fonte.



### Como um computador entende um programa?

​	Através de um destes dois métodos: tradução ou interpretação. No processo de tradução, a linguagem de alto nível é enviada para o compilador, que executa a análise desse programa. Esse compilador irá traduzir o programa de alto nível em um código de baixo nível, de linguagem de máquina, chamado de programa objeto. Já na interpretação o programa fonte é executado diretamente.



### Características de um programa

​	Existem importantes características a serem consideradas quando se cria um programa. Na área de desenvolvimento de programas há algumas diretrizes a serem levadas em consideração na hora de codificar o algoritmo. Elas são:

- Legibilidade - facilidade de leitura, compreensão, ortogonalidade, definição adequada das estruturas;
- Redigibilidade - ortogonalidade, simplicidade da escrita (pode conflitar com a legibilidade, pois prioriza a facilidade de escrita do código), suporte à abstração, reuso do código, expressividade;
- Confiabilidade - verificação de tipos, tratamento de exceções, uso de ponteiros, compatibilidade entre compiladores;
- Custo.

​	Outras características que devem ser levadas em consideração são atualizações, uso para IA, disponibilidade de ferramentas, comunidade ativa, e adoção pelo mercado.



### Análises de código

​	Existem três tipos de análises que são feitas no código fonte com o compilador:

- Análise léxica - também conhecida como _scanner_. É a primeira fase de um processo de compilação, e sua função é fazer a leitura do programa fonte e agrupar os caracteres em lexemas, produzir uma sequência de símbolos léxicos conhecidos como _tolkens_. Nesse processo ela irá particionar (identificar _tolkens_), classificar, e então eliminar. Esses _tolkens_ são identificadores, palavras reservadas, números, _strings_. Ela irá eliminar caracteres de espaços em branco, comentários, tudo o que é utilizado para maior entendimento do programa que o compilador não precisa;
- Análise sintática - a sintaxe de um programa é a forma que ele define, através de palavras reservadas, de indexação, de símbolos especiais, qualquer estrutura dentro daquela linguagem específica. Define então a corretude do programa;
- Análise semântica - define a lógica do programa.



### Paradigmas de programação

​	Um paradigma é a forma de resolução de problemas com diretrizes e limitações específicas de cada linguagem de programação. São classificados em:

- Procedural - está relacionado às chamadas sucessivas e procedimentos separados;
- Funcional - fundamentado em instruções baseadas em funções; 
- Estruturado - atrelado a estruturas de blocos aninhados;
- Computação distribuída - possui funções executadas de forma independente;
- Orientação a objeto;
- Lógico.

​	Os paradigmas mais utilizados são o estruturado e a orientação a objeto.



## Primeiro contato com a programação



### Algoritmos em Portugol

[Portugol Webstudio](https://dgadelha.github.io/Portugol-Webstudio/)