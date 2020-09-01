# AnaliseHypercloud
Teste Técnico HyperCloud


<b>Perguntas teóricas:</b>

<i>1. Para você, o que significa Business Inteligence? </i> <br>
Business Inteligente é uma metodologia de análise dos dados previamente armazenados de uma organização, com o objetivo de realizar tomadas de decisão orientadas a dados com foco no negócio de interesse.
  

<i>2. Cite duas ferramentas de ETL: </i> <br>
a) Microsoft PowerBI; <br>
b) Tableau.



<i>3. Cite três ferramentas de apresentação de Dados:</i> <br>
a) Microsoft PowerPoint; <br>
b) Canva; e <br>
c) Google Presentation.


<i>4. O que é uma Tabela Fato e o que é uma tabela Dimensão?</i> <br>
Tabela Fato: É a tabela que armazena as entradas das variáveis do processo de interesse (fatos) de um negócio. <br>

Tabela Dimensão: É a tabela que armazena as informações explicativas de cada variável da Tabela Fato, podendo ser mais de uma tabela utilizada na análise de interesse.


<i>5. Quais tipos de modelagens são as mais utilizadas em um projeto de BI?</i> <br>
a) Modelo Esquema Estrela; e <br>
b) Modelo Esquema Floco de neve.


<i>6. O que significa Surrogate Key? </i> <br>
Surrogate Key é uma chave artificial que relaciona a Primary Key da Tabela Dimensão com a entrada da Tabela Fato, sendo atualizada a cada nova entrada na Tabela Fato, com o objetivo de garantir a unicidade da entrada e relações entre as tabelas utilizadas.


<i>7. Explique a diferença entre relacionamento 1 para 1 e 1 para N: </i> <br>
O Relacionamento 1 para 1 indica que a variável de interesse possui apenas uma correspondência em outra variável. Exemplo: Um IMEI de um aparelho celular vinculado a um SIM card (número de celular). <br>

O Relacionamento 1 para N indica que a variável de interesse possui mais de uma correspondência em outra variável. Exemplo: Um CNPJ de uma empresa vinculado a 3 e-mails do departamento de vendas. 


<i>8. O que significa Drill Down / Drill Up? </i> <br>
São ferramentas de filtro de gráficos que permitem o maior detalhamento das variáveis utilizadas. <br>

Drill Down: Ferramenta que apresenta os dados com todos seus níveis de detalhes, como se fosse escavar para obter uma informação precisa e/ou pontual. Exemplo: vendas de bicicleta no ano de 2019 da marca Kona da cor Prata, sendo que na base de dados possui as variáveis marca (Caloi, Kona, Soul e Specialized), cor (Prata, Preto, Vermelho e Amarelo) e ano de venda (de 2010 a 2019). <br>

Drill Up: Ferramenta que permite retornar um nível de detalhamento dos dados, pois na análise de interesse pode acontecer de precisar somente de um nível de detalhamento mas na hora de gerar o gráfico, solicitou dois níveis e será necessário retornar um nível. Exemplo: considerando a base de dados citada acima, seria obter o número de vendas de bicicleta no ano de 2019 da marca Kona. <br>


A modelagem projetada segue o Modelo Esquema Floco de Neve.
