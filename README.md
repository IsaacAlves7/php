# It's a repository of PHP programming 📓🐘🔢
<img src="https://kinsta.com/pt/wp-content/uploads/sites/3/2019/05/o-que-php.png" width="1070"/>

## Introduction - Overview about the Hypertext Preprocessor-PHP language 🐘
<b>Contents:</b>
<ul>
  <li>The History of PHP language.</li>
</ul>

## 🐘 What's the PHP language? 🔢
<div align="center"><img src="https://adrisonluz.com/img/tecnologias/php.png" height="200"></div>
<p><b>HyperText Preprocessor (PHP)</b> is a programming language.</p>

## 🐘 PHP na atualidade 📅
<img src="https://www.webgeometrics.com/wp-content/uploads/2014/04/banner-php.jpg"/>
<p>Muito se discute a respeito do PHP acabar em 2020 ou a partir dos anos futuros. E a resposta correta, para essa pergunta, é que não irá! Pois o PHP ainda é amplamente usado por empresas, seus frameworks e bibliotecas são amplamente utilizadas para páginas dinâmicas, templates Web e E-commerce. Além disso, sua versão chegou a 8° em 2020.</p>

# 🎲 Implementação com Banco de dados 🏦
<div align="center"><img src="https://purepng.com/public/uploads/large/purepng.com-server-databaseservercomputingclientserverservice-providercommoditycloud-serverdatabasewindows-server-1701528389209cejn9.png" height="270"/></div>
<p>Imagine da seguinte forma, um 🎲 <b>dado</b> é um pequeno item de uma informação, como por exemplo: um nome, um número ou endereço. Já uma <b>informação</b> é um conjunto desses dados. E um <b>arquivo</b> é um conjunto dessas informações. Cada um desses significados de dados podem ser organizados da seguinte categoria: <b>Registros</b>, <b>Tabelas</b> e <b>Arquivos</b>. Que se definem como:</p>
<ul>
  <li><strong>📋 Registros</strong> fichas de informações, iguais a que preenchemos em documentos;</li>
  <li><strong>📂 Tabelas</strong> são pastas que armazenam os registros;</li>
  <li><strong>🗃️ Arquivos</strong> armazenam as tabelas, como as gavetas de ferro;</li>
</ul>
Um 🏦 <b>Banco de dados</b> 🎲 são conjuntos de arquivos relacionados entre si com registros sobre pessoas, lugares ou coisas. São coleções organizadas de dados que se relacionam de forma a criar algum sentido (Informação) e dar mais eficiência durante uma pesquisa ou estudo cientifico. Os bancos de dados armazenam informações de forma robusta, possuem segurança com os dados (Acesso com autorização), possuem integridade com os dados e integração com sistema Web.
<p>A estrutura do banco de dados é composta por:</p>
<ol>
  <li><strong>Base de dados</strong> são os dados propriamente de ditos.</li>
  <li><strong>Sistema Gerenciador</strong> são os gerenciamento de dados.</li>  
  <li><strong>Linguagem de Exploração</strong> é uma linguagem de acesso aos dados.</li>  
  <li><strong>Programas Adicionais</strong> é tudo que for extra no banco de dados, como gerência de usuários ou utilizadores de dados.</li>  
</ol>
<p>Alguns paradigmas de Banco de Dados (Modelos de Banco de Dados):</p>
<ul>
  <li><strong>Modelo Hierárquico</strong> Armazenam dados de uma maneira bem simplista, mas tudo na forma hierárquica;</li>
  <li><strong>Modelo em Redes</strong> Armazenam os dados em forma de rede inteligente, sem grau de superioridade ou inferioridade;</li>
  <li><strong>Modelo Relacional</strong> Armazenam os dados em relação entre eles, ou seja, armazena um conjunto de registros a outro conjunto de registros que está em outra tabela;</li>
</ul>
<p>Com isso, existem muitas opções para banco de dados:</p>
<div align="center"><img src="https://image.slidesharecdn.com/aws-esri-120923115607-phpapp01/95/aws-e-esri-solues-de-mapas-e-anlise-espacial-na-nuvem-48-728.jpg?cb=1348401582" height="400"></div>
<p>Soluções pagas e empresariais de Banco de Dados Relacional:</p>
<ul>
  <li><strong>OracleDB</strong>;</li>
  <li><strong>IBMDB2</strong>;</li>
  <li><strong>dBASE</strong>;</li>
  <li><strong>Microsoft SQL Server</strong>;</li>
</ul>
<p>Soluções gratuitas de Banco de Dados Relacional:</p>
<ul>
  <li><strong>MySQL</strong>;</li>
  <li><strong>MariaDB</strong>;</li>
  <li><strong>Firebird</strong>;</li>
  <li><strong>PostgreSQL</strong>;</li>
</ul>

<div align="center"><h1>Cap 01: 🔠 Álgebra Relacional 🔣</h1></div>
<p>No mundo digital, nossas vidas são regidas por diversos sistemas. Para funcionar, esses sistemas necessitam de grande volume de dados. Os sistemas informatizados evoluíram ao longo do tempo de <B>Sistemas Baseados em Arquivos</b> para <b>Sistemas Baseados em Banco de Dados</b>.

## 🐘 PostgreSQL Database 🏦
<div align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Postgresql_elephant.svg/1200px-Postgresql_elephant.svg.png" height="210"/></div>

Não é possível conceber, atualmente, qualquer sistema que possa prescindir de um <b>Banco de Dados</b>. Os Sistemas de Banco de Dados atuais são, majoritariamente, baseados no <b>Modelo Relacional</b>. Por isso, iremos utilizar o <strong>PostgreSQL</strong> como alternativa gratuita de modelo relacional de banco de dados.

Entretanto, de que adiantaria termos uma estrutura de armazenamento se não conseguíssemos manipular os dados ali armazenados? Como o modelo relacional teve sua origem na matemática, essa mesma ciência nos fornece a ferramenta para manipulá-lo, a <b>Álgebra Relacional</b>.</p>

## Sistema de Banco de Dados
<p>Definição de um dado:</p>
<blockquote>Dado é o “princípio em que se assenta uma discussão” ou o “elemento ou base para a formação de um juízo”. Ainda, assumindo-se um ponto de vista mais filosófico, dado é “o que se apresenta à consciência como imediato, não construído ou não elaborado”, FERREIRA et al. (1999, p. 602).</blockquote>
<p>Essas definições são úteis para exemplificar o termo "<strong>dado</strong>" e situar sua definição de um ponto de vista mais humanizado.

Computacionalmente falando, pode-se definir <strong>dado</strong> como um valor armazenado e que por si só não quer dizer muita coisa. Uma lista de números - por exemplo, <strong>10, 12, 20, 21, 23, 38</strong> - não nos fornece nenhum significado, mas, por assim dizer, são os dados obtidos e anotados de alguma forma.

A necessidade de armazenar os dados precede a criação do conceito de <strong>Sistemas de Banco de dados</strong>.
</p>

<blockquote>
  <strong>⚠️ ATENÇÃO!</strong>

Antigamente, os dados eram armazenados em arquivos. Normalmente são associados a um único sistema de aplicação, trazendo, por consequência, redundância de dados quando os mesmos se faziam necessários em outros sistemas.

A maioria das organizações desenvolve os seus Sistemas de Informação um por vez, à medida que se tornam necessários, utilizando cada um o seu próprio conjunto de programas, arquivos e usuários.</blockquote>

<p>A figura 1 mostra a estrutura de um sistema baseado em arquivo. Nela podemos notar que:</p>
<ol>
  <li>Cada aplicação possui seus próprios arquivos de dados;</li>
  <li>Se uma aplicação compartilha dados com outras, esses têm que ser duplicados;</li>
  <li>Qualquer alteração no modelo de dados implica em alteração do código da aplicação.</li>
</ol>
<div align="center"><img src="https://user-images.githubusercontent.com/61624336/97049881-c9ad2000-1552-11eb-8e19-67592bcd49ae.jpg" height="270"/></div>

<p>O esquema apresentado acaba acarretando em:</p>

### Redundância de dados
<p>Trata-se da duplicação dos mesmos dados em dois ou mais arquivos. O problema com a redundância é que as mudanças, ao serem feitas no arquivo de uma aplicação, não são automaticamente realizadas nos arquivos das outras aplicações, gerando a falta de integridade dos dados.</p>

### Dependência entre programas e dados
<p>Os aplicativos tradicionais de banco de dados de arquivos são caracterizados pela dependência entre programas e dados, isso é, programas e dados desenvolvidos e organizados para uma aplicação são incompatíveis com os programas e dados organizados diferentemente para um outro aplicativo.</p>

### Custo excessivo em software
<p>Resulta da criação, documentação e acompanhamento de muitos arquivos e aplicações diferentes.</p>
<hr>

<p>A evolução da tecnologia associada ao grande aumento do volume de dados a ser armazenado e processado levou à criação de uma nova abordagem para o problema, <strong>o Sistema de Banco de Dados</strong>.

Um <strong>banco de dados</strong> é uma coleção de dados organizados de tal forma que possam ser acessados e utilizados por muitas aplicações diferentes. Ou seja, em vez de armazenar dados em arquivos separados para utilização, os <strong>dados</strong> são armazenados e organizados em um só local, permitindo compartilhamento e inter-relacionamento por múltiplos usuários.

A fim de usar a abordagem de banco de dados para o gerenciamento de dados, foi necessário um software adicional – um <b>sistema de gerenciamento de banco de dados (SGBD)</b>. O <b>SGBD</b> consiste em um grupo de programas que podem ser usados como uma interface entre o banco de dados e um usuário ou um banco de dados e um programa aplicativo.
</p>

<img src="https://user-images.githubusercontent.com/61624336/97218661-b941b300-17a7-11eb-925d-885085b82124.jpg"/>

## Modelo Relacional
<p>Nos maiores <strong>SGBD comerciais</strong>, o modelo de dados utilizado é o <b>Modelo Relacional</b> criado com base na Teoria Matemática dos Conjuntos e na Álgebra Relacional, O Modelo de Dados Relacional tem as seguintes vantagens:</p>
<ul>
  <li>É independente das linguagens de programação;</li>
  <li>É independente dos sistemas de gestão de bases de dados;</li>
  <li>É independente dos Sistemas Operacionais.</li> 
</ul>

<blockquote>“O modelo relacional representa o banco de dados como uma coleção de relações.” ELMASRI, R.; NAVATHE, S., 2015.</blockquote>

<p>Da afirmativa acima. pode-se depreender uma relação como uma tabela de valores onde cada linha representa uma coleção de dados ou valores relacionados. Cada <b>linha da tabela</b> representa uma <b>realidade ligada ao mundo real</b>. O nome da tabela e o nome das colunas são definidos de forma que representem essa realidade. Pode-se ter uma tabela chamada <strong>ALUNO</strong> onde cada linha venha a ser o <b>Nome de um Aluno</b> a ser armazenado.

Podemos melhorar ainda mais essa representação, criando uma tabela com as colunas <b>NOME, NÚMERO DE MATRÍCULA e CLASSE</b>. Cada linha da tabela representa várias informações de um <b>ALUNO</b> e cada coluna isoladamente, representa uma informação específica desse aluno. Assim o nome da tabela e os nomes das colunas são capazes de dizer o que cada linha representa e também o que o conjunto representa.

No <b>modelo relacional</b> formal (Figura 3), <b>cada linha</b> é chamada de <b>tupla</b>, o <b>nome da coluna</b> é conhecido como <b>atributo ou variável</b>, e a <b>tabela, relação</b>. (FONSECA, 2016)</p>
<img src="https://user-images.githubusercontent.com/61624336/97340292-5c570300-1862-11eb-9581-fc7f2cf5c765.jpg"/>

## Regras de Integridade relacional
<p>As <strong>regras de Integridade Relacional</strong> visam garantir a fidelidade de informações em um banco de dados. Basicamente, são três as formas mais comuns:</p>
<ul>
  <li><strong>Integridade de Domínio</strong> <i>diz respeito aos dados que são permitidos nas colunas da relação (tabela)</i>. Um <b>domínio</b> é um conjunto de valores do mesmo tipo. Os domínios são, portanto, conjuntos/faixas de valores a partir dos quais os valores reais são adicionados às colunas de uma tabela.</li>
  <li><strong>Integridade de Continuidade</strong> <em>diz respeito à unicidade de linhas da relação</em>. Para tal, cada tabela deve ter uma chave primária (Primary Key - PK). Dessa forma., as colunas escolhidas para PK devem ser únicas e de preenchimento obrigatório (não nulas), como, por exemplo, as colunas Código na tabela Emp e Codigodepto na tabela Depto (Fig 3);</li>
  <li><strong>Integridade Referencial</strong> <i>diz respeito à consistência entre as tuplas de relações</i>. Para tal, as tabelas devem possuir chaves estrangeiras (Foreign Key – FK). A FK de uma tabela com, por exemplo, CodigoDepto na tabela EMP (Fig3) deve referenciar uma PK de outra tabela, no caso CodigoDepto da tabela Depto.(Fig3). Os valores possíveis em uma FK são limitados aos existentes na PK referenciada. Se em um banco de dados você tentar incluir uma linha com valor de FK não existente na PK da outra tabela, o SGBD gerará um erro e não permitirá a operação, garantindo assim a consistência dos dados.</li>
</ul>

## Álgebra Relacional
<p>É o conjunto básico de operações para o modelo relacional. Essas operações permitem a recuperação de tuplas mediante instruções de consulta aplicadas ao banco de dados. O resultado dessa recuperação também será uma relação, que pode ser usada em outras operações de consulta.

A importância da álgebra relacional:</p>
<ul>
  <li>Provê fundamento formal para operações do modelo relacional;</li>
  <li>Alguns de seus conceitos são incorporados na linguagem SQL padrão.</li>
  <li>E o mais importante: é usada como base para implementar e otimizar as consultas em sistemas de banco de dados relacional. (FONSECA, 2016, p. 15)</li>
</ul>

<p>As principais operações da álgebra relacional são:</p>
<ul>
  <li>Seleção;</li>
  <li>Projeção;</li>
  <li>Produto Cartesiano;</li>
  <li>Operações de Conjunto (União, Intersecção, Diferença).</li>  
</ul>

<blockquote>As operações de <strong>SELECT</strong> (SELEÇÃO) E <strong>PROJECT</strong> (PROJEÇÃO) são ditas operações unárias, pois atuam em relações únicas (ELMASRI, R.; NAVATHE, S., 2015).</blockquote>

## Operação de seleção (SELECT)
<p>A <strong>operação de Seleção (SELECT)</strong> recupera os dados de uma ou mais tabelas, selecionando um subconjunto de tuplas que satisfaça determinada condição de seleção. Essa condição de seleção é usada para dividir horizontalmente uma relação em dois conjuntos de tuplas – as tuplas que satisfazem a condição e são retornadas e as tuplas que não satisfazem a condição e são ignoradas. (FONSECA, 2016, p.16)

A forma geral de uma operação de seleção é:</p>
<pre>(nome da relação) &lt;condição de seleção&gt; σ</pre>

<p>Onde: <strong>&lt;condição de seleção&gt;</strong> é a condição que a linha deve atender para ser selecionada.</p>

<p>Constituindo-se em uma expressão lógica, é construída a partir de cláusulas da forma:</p>

<p><strong>&lt;nome de atributo&gt; &lt;operador de comparação&gt; &lt;valor constante&gt;, ou &lt;nome de atributo&gt; &lt;operador de comparação&gt; &lt;nome de atributo&gt;</strong></p>

<p>Onde:</p>

<p><strong>&lt;nome de atributo&gt;</strong> é um atributo da relação definida em <strong>&lt;nome da relação&gt;</strong></p>

<p><strong>&lt;operador de comparação&gt;</strong> é normalmente um dos <strong>operadores relacionais {=, <, ≤, ≥, ≠} e</strong></p>

<div align="left">
<p><b>&lt;valor constante&gt;</b> é um literal.

As <b>cláusulas</b> podem ser utilizadas em conjunto com os <b>operadores lógicos {AND, OR NOT}</b>, seguindo a <b>Lógica Booleana</b>, para formar uma condição de seleção composta.</p></div>

<div align="center"><img src="https://user-images.githubusercontent.com/61624336/97483248-fa67cd80-1935-11eb-9deb-8ed7f747fdff.jpg"/></div>

<p>&lt;nome da relação&gt; é o nome da relação sobre a qual será aplicada a operação de <b>Seleção</b>.

A <strong>relação resultante</strong> da operação tem os mesmos atributos da relação especificada em nome da <strong>&lt;relação&gt;</strong>.</p>

### Exemplo:
<p>Considere a Tabela <strong>Disciplina_Nota</strong>:</p>
<table border="2" align="center">
  <tr>
    <td>&nbsp;</td>
    <td>NOME_ALUNO</td>
    <td>NOME_DISCIPLINA</td>
    <td>NOTA</td>
  </tr>
    <tr>
    <td>1</td>
    <td>José Geraldo</td>
    <td>Álgebra</td>
    <td>8</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Eduardo Tomaz</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Cleber Dutra</td>
    <td>Álgebra</td>
    <td>9</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Hernesto Paula</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Josué José</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
</table>

<p>Para selecionar os alunos da disciplina ‘álgebra’ cuja nota foi integral, pode-se especificar cada uma dessas condições em uma operação de SELEÇÃO:</p>

<pre>NOME_DISCIPLINA = ‘ALGEBRA’ AND NOTA = 10 (Disciplina_Nota)</pre>
<pre>NOME_DISCIPLINA = ‘ALGEBRA’ AND NOTA = 10</pre>

### Resultado:
<table border="2" align="center">
  <tr>
    <td></td>
    <td>NOME_ALUNO</td>
    <td>NOME_DISCIPLINA</td>
    <td>NOTA</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Eduardo Tomaz</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Josué José</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
</table>

<hr>

## Operação de Projeção (PROJECT)
<p>A <strong>operação de Projeção</strong> recupera os dados de certas colunas de uma tabela e descarta outras. Se existir a necessidade de mostrar apenas alguns atributos de uma tabela em detrimento de outros, usa-se a operação <strong>PROJEÇÃO</strong>. (FONSECA, 2016, p. 17)

A forma geral da operação de projeção é:</p>

<pre>π &lt;lista de atributos&gt; (&lt;nome da relação&gt;)</pre>

<p>Onde:</p>

<p><strong>&lt;lista de atributos&gt;</strong> representa a lista de atributos que o usuário deseja selecionar e

<strong>&lt;nome da relação&gt;</strong> representa a relação sobre a qual a operação projeção será aplicada.</p>

<div align="center"><img src="https://user-images.githubusercontent.com/61624336/97619999-afb28800-19ff-11eb-9a62-3dc7ab331e2e.jpg"/></div>

### Exemplo:
<p>Para selecionar as disciplinas e as ocorrências de notas nas disciplinas na tabela da fig 4, teremos:

<pre>π &lt;Nome_Disciplina, Nota&gt; (&lt;Disciplina_Nota&gt;)</pre>

Resultando na relação:</p>

<table border="2" align="center">
  <tr>
    <td></td>
    <td>NOME_DISCIPLINA</td>
    <td>NOTA</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Álgebra</td>
    <td>8</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Álgebra</td>
    <td>9</td>
  </tr>  
  <tr>
    <td>4</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
</table>

<hr>

## Sequencialidade de Operações
<p>A <strong>Projeção</strong> e a <strong>Seleção</strong> podem ser combinadas, de forma que apenas algumas linhas e algumas colunas retornem na operação. A forma geral de uma operação sequencializada é:</p>
<pre>π &lt;lista de atributos&gt; (σ &lt;condição de seleção&gt; (&lt;nome da relação&gt;) )</pre>

<p>Onde:

<strong>π</strong> representa a operação de projeção;

<strong>&lt;lista de atributos&gt;</strong> representa a lista de atributos que o usuário deseja selecionar;

<strong>σ</strong> representa a operação de seleção;

<strong><condição de seleção></strong> é a condição que a linha deve atender para ser selecionada;

<strong><nome da relação></strong> é o nome da relação sobre a qual será aplicada a operação de <strong>Seleção</strong> e <strong>Projeção</strong></p>

<img src="https://user-images.githubusercontent.com/61624336/97651843-e27a7180-1a3b-11eb-9dbb-99ca416a1354.jpg"/>

### Exemplo:
<p>Para projetar a partir da Tabela Disciplina_Nota, o nome das disciplinas e a nota para alunos com nota diferente de 10 a expressão seria:

<div align="center"><strong>π Nome_Disciplina, Nota ( σ <> 10 (Disciplina_Nota) )</strong></p></div>
  
<table border="2" align="center">
  <tr>
    <td></td>
    <td>NOME_DISCIPLINA</td>
    <td>NOTA</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Álgebra</td>
    <td>8</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Álgebra</td>
    <td>9</td>
  </tr>
</table>

<hr>

## Operação Produto Cartesiano
<p>O <b>produto cartesiano</b> é uma operação binária que combina todas as tuplas de duas tabelas. O resultado de um produto cartesiano é uma nova tabela formada pela combinação das tuplas das tabelas sobre as quais aplicou-se a operação.

O formato geral do produto cartesiano entre duas tabelas A e B é:</p>
<img src="https://user-images.githubusercontent.com/61624336/97745534-c58b8000-1ac7-11eb-9e5d-231052a592bf.jpg"/>

<hr>

## Operação Junção (JOIN)
<p>A <b>operação Join (Junção)</b> é usada para combinar as tuplas relacionadas em duas relações dentro de uma única tupla. Essa operação é uma das mais importantes em um banco de dados relacional, pois ela nos permite retornar os relacionamentos entre as relações (tabelas).

A forma geral da operação junção entre duas tabelas A e B é a seguinte:</p>

<div align="center"><strong>A X B &lt;condição de junção&gt;</strong></div>

<p>Onde: <strong>&lt;condição de junção&gt;</strong> é uma expressão relacional, normalmente utilizando o operador =, que determina qual coluna da tabela A deve ser comparada com qual coluna da tabela B.

Observação: normalmente as colunas envolvidas na condição de junção são a Chave Primária de uma tabela e a Chave Estrangeira na outra.</p>
<div align="center"><img src="https://user-images.githubusercontent.com/61624336/97770723-92231280-1b14-11eb-85db-b19c9dab04f9.jpg"/></div>

### Exemplo:
<p>
Considere o banco de dados composto pela tabela Disciplina_Nota (Fig 4).

Imagine que nosso modelo de banco de dados definido anteriormente com a tabela DISCIPLINA_NOTA (Fig4) seja redefinido para um modelo mais trabalhado com as tabelas:

DISCIPLINA_NOTA, DISCIPLINA E PESSOA, inserindo uma chave primária (PK) que identifica unicamente um nome, a tabela DISCIPLINA_NOTA com a chave estrangeira (FK) FK_NOME_ALUNO relacionando com a tabela PESSOA e a FK_NOME_DISCIPLINA relacionando com a tabela DISCIPLINA. Temos, então, a seguinte melhoria em nosso banco de dados (FIG 8):

<pre><b>π</b> NOME_DISCIPLINA, NOME_ALUNO, NOTA(PESSOA <b>X</b> DISCIPLINA_NOTA <b>X</b> Disciplina)
PK_NOME_PESSOA = FK_NOME_ALUNO FK_NOME DISCIPLINA = PK_DISCIPLINA</p></pre>

<table border="2" align="center">
  <tr>
    <td>NOME_ALUNO</td>
    <td>NOME_DISCIPLINA</td>
    <td>NOTA</td>
  </tr>
  <tr>
    <td>José Geraldo</td>
    <td>Álgebra</td>
    <td>8</td>
  </tr>
  <tr>
    <td>Eduardo Tomaz</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
  <tr>
    <td>Cleber Dutra</td>
    <td>Álgebra</td>
    <td>9</td>
  </tr>
  <tr>
    <td>Hernesto Paula</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
  <tr>
    <td>Josué José</td>
    <td>Álgebra</td>
    <td>10</td>
  </tr>
</table>

## Operação de Conjuntos
<p>São operações derivadas das operações matemáticas padrão definidas a partir da teoria dos conjuntos. (FONSECA, 2016, p. 18)

São elas:</p>

### UNION
<p><strong>UNION</strong> é a operação de UNIÃO da teoria de conjuntos. Se temos as relações R(A1, A2, ..., An) e S(B1, B2, ..., Bn) para haver a operação União, os atributos de cada relação devem ser compatíveis entre si, ou seja, devem ter o mesmo grau (n) e os domínios de cada atributo devem ser iguais ao domínio do outro atributo, ou seja, dom(A1) = dom(B1). Significando que cada relação possui o mesmo grau e que cada par de atributos possuem o mesmo domínio. Sendo assim, a operação UNION pode ser aplicada. (FONSECA, 2016, p. 18)

A forma geral da operação junção entre duas tabelas A e B é a seguinte:

<div align="center"><strong>A U B</strong></div>

A Operação de União é comutativa, ou seja, A U B produz o mesmo resultado de B U A.

<img src="https://user-images.githubusercontent.com/61624336/97790460-7b79cb80-1ba7-11eb-9033-bdc2b758c832.jpg"/>

<p><strong>Exemplo:</strong> Temos a tabela DISCIPLINA_NOTA (Fig 4) e a nova tabela PROFESSOR (Fig10). Podemos fazer a união dos domínios ‘NOME_PESSOA’ com os nomes dos alunos e os nomes dos professores.</p>

<table border="2" align="center">
  <tr>
    <td></td>
    <td>NOME_PROFESSOR</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Fagundes Teles</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Ferreira</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Elmasri</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Navathe</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Cleber Dutra</td>
  </tr>
</table>

<div align="center"><strong>π NOME_ALUNO (DISCIPLINA_NOTA) U PROFESSOR</strong></div>

<table border="2" align="center">
  <tr>
    <td></td>
    <td>NOME_PESSOA</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Cleber Dutra</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Eduardo Tomaz</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Elmasri</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Fagundes Teles</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Ferreira</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Hernesto Paula</td>
  </tr>
  <tr>
    <td>7</td>
    <td>José Geraldo</td>
  </tr>
  <tr>
    <td>8</td>
    <td>Josué José</td>
  </tr>
  <tr>
    <td>9</td>
    <td>Navathe</td>
  </tr>
</table>

<p><strong>Atenção:</strong> Repare que a operação UNION não trouxe o nome repetido do Professor e aluno Cleber Dutra, essa operação garante tuplas únicas.</p>

### INTERSECTION
<p>Da mesma forma como foi apresentada a operação UNION, pode-se usar a definição matemática de interseção para definirmos a operação de interseção entre as relações. As observações feitas para a operação UNION, no que diz respeito ao domínio dos atributos e ao grau da relação, também devem ser seguidas para a operação de INTERSECTION. (FONSECA, 2016, p. 20)</p>

<div align="center"><strong>A ∩ B</strong></div>

<p>Essa operação é comutativa, ou seja, A ∩ B produz o mesmo resultado de B ∩ A.</p>

<img src="https://user-images.githubusercontent.com/61624336/97796333-717bbb00-1bef-11eb-9a90-7bd664a5e1ce.jpg"/>

### Exemplo:
<p>De acordo com Fonseca (2016), para a interseção entre os nomes de professores e alunos, temos:</p>

<div align="center"><strong>π NOME_ALUNO (DISCIPLINA_NOTA) U PROFESSOR</strong></div>

<table border="2" align="center">
  <tr>
    <td></td>
    <td>NOME_PESSOA</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Cleber Dutra</td>
  </tr>
</table>

## MINUS
<p>Por fim, apresentamos a operação MINUS (SUBTRAÇÃO), que representa a diferença de conjunto. O resultado dessa operação, tomando-se nossas relações S e R apresentadas anteriormente, é uma relação que inclui todas as tuplas que estão em R, mas não estão em S. As observações feitas para a operação UNION e INTERSECTION, no que diz respeito ao domínio dos atributos e ao grau da relação, também devem ser seguidas para a operação MINUS. (FONSECA, 2016, p. 20)

A forma geral da operação Diferença entre duas tabelas A e B é a seguinte:</p>

<div align="center"><strong>A - B</strong></div>

<p>Essa operação não é comutativa, ou seja, A - B produz um resultado diferente de B – A.</p>

<div align="center"><img src="https://user-images.githubusercontent.com/61624336/97823670-72b4f280-1c98-11eb-956d-3d0bb0d287f5.jpg"/></div>

<p>Para obtermos o nome dos Professores que não são homônimos de alunos (FONSECA, 2016, p. 20), a expressão seria:</p>

<div align="center"><p>PROFESSOR - π NOME_ALUNO (DISCIPLINA_NOTA)</p></div>

<p>Resultando:</p>

<table border="2" align="center">
  <tr>
    <td></td>
    <td>NOME_PESSOA</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Elmasri</td>
  </tr>
    <tr>
    <td>1</td>
    <td>Elmasri</td>
  </tr>  
  <tr>
    <td>2</td>
    <td>Cleber Dutra</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Fagundes Teles</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Navathe</td>
  </tr>
</table>











# 2. 🏦🎲🔢 Linguagem SQL - DML e DDL
<div align="center"><img src="https://rapidthumbs.files.wordpress.com/2014/04/sql.png" height="270"/></div>
<p>O <b>Structured Query Language (SQL)</b> é uma linguagem padrão de gerenciamento de dados que interage com os principais bancos de dados baseados no modelo relacional, dentre eles: MySQL, PostgreSQL, Oracle, SQL Server, MariaDB e Access.

Ou seja, dar instruções ao meio ambiente do banco de dados e ele te retornará uma <i>Query</i>, ou seja, uma solicitação ou resposta.</p>

## 3. 💉🏦🎲 SQL Injection
<div align="center"><img src="https://trustaira.com/files/2018/03/sql-injection-protection-300x263.png" height="270"/></div>
<p>O <b>SQL Injection</b></p>

## What's the MySQL Database?
<div align="center"><img src="https://i1.wp.com/sempreupdate.com.br/wp-content/uploads/2017/10/MySQL-Logo-Large-Orignal.png?fit=1152%2C864&ssl=1" height="200"></div>

## Configurações do Apache XAMPP?
<div align="center"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/78/XAMPP_logo.svg/220px-XAMPP_logo.svg.png" height="200"></div>

## MySQL e phpMyAdmin
<div align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/9/95/PhpMyAdmin_logo.png" height="200"></div>

## Composer
<div align="center"><img src="https://magenteiro.com/blog/wp-content/uploads/2017/07/Logo-composer-transparent.png" height="270"/></div>
