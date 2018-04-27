# Tableau Titanic

[Titanic - Tableau - Última versão](https://public.tableau.com/profile/milton.siqueira#!/vizhome/Titanic_538/Story).

[Titanic - Tableau - Primeira versão](https://public.tableau.com/profile/milton.siqueira#!/vizhome/Titanic_1st_version/Story).

## Resumo

Analisa os dados demográficos sobre os passageiros do Titanic, demonstrando informações sobre os lugares de embarque, classes, custo da passagem, sobreviventes e vítimas.
Com isso, foi possível traçar o perfil dos sobreviventes, que crianças, mulheres ou que embarcaram na primeira classe.

## Design

Decidi demonstrar as informações em 3 histórias, uma com os dados sobre o embarque, o outro sobre as classes sociais com preço pago pela passagem, e por último, concluíndo com as relaçõoes entre sobreviventes e mortos.

Na primeira etapa, usei mapas para mostrando os lugares de embarque e população embarcada. Gráfico de pizza para os sexos para demonstrar uma composição simples, assim como, no barra para as classes sociais. E para as idades um histograma com a distribuição.

Já na segunda, usei um scatter graph para representar os dados contínuos de custo da passagem e população, associando com a classe. Mais uma vez um gráfico de pizza para o gênero e custo de passagem. Gráfico de barras para o embarque e população fazendo uma comparação. E mais uma vez o histograma com a idade e custo de passagem.

Para a conclusão, realizei as comparações entre sobreviventes e mortos, destaco o uso do gráfico de bolhas para representar a relação entre as classes, população, sobreviventes e mortos. Fechando um histograma das idades, onde cada barra mostra a porcentagem de sobreviventes e vítimas.

* 28/04/2018

  * Criado grupo de idade: crianças(0-17), adultos (18-59) e idoso (>60). Fazendo uma relação dele com os sobreviventes e mortos.

* 26/04/2018

  * Adicionado filtro de cidade de embarque no dashboard de sobreviventes.
  * Cor padrão para o gênero modificado.
  * Títulos revisados.
  * Cor azul adotada para os sobreviventes, inventendo com o vítimas, que agora passa a ser laranja, dando maior destaque as vítimas.
  * Adicionado novo gráfico Survived x Dead x Age, que foi sugestão dos itens:
    * `Com relação aos sobreviventes, qual a idade média dos mortos e dos sobreviventes?`
    * `* Com relação aos sobreviventes, qual a idade média dos mortos e dos sobreviventes?`
  * Layout do dashboard e story ajustado para `automático`. Para aproveitar melhor a área disponível.
  * Para resolver `No gráfico de bolhas sobreviventes e mortos por classe, algumas não mostram a porcentagem.`, removi a label de `survived/dead` dos círculos, identificando isso através das cores, com isso foi ganho mais espaço na área possibilitando a exibição.

* 22/04/2018 - O dashboard sobre o embarque estava com muitos dados. Então passei os dados sobre as classes sociais para outro dashboard.

* 21/04/2018
  * Utilizado para visualização o [Tableau](https://www.tableau.com). Com 3 histórias:
    * Embarque: Lugares de embarque, idade e classe dos passageiros.
    * Classe: Apresenta informações sobre as classe dos passageiros.
    * Acidente: Mostra relação entre os sobreviventes e mortos.

## Comentários

* 26/04/2018

  * Ao filtrar por sobreviventes e mortos, os gráficos dessa relação com gênero e classe ficam 100%.

* 25/04/2018
  * Com relação aos sobreviventes, qual a idade média dos mortos e dos sobreviventes?
  * Poderia ter um gráfico com a relação de mortos e sobreviventes com relação as classes e seus preços.
  * Os histogramas sobre a idade, não estão mostrando a idade na coluna, e sim a quantidade de vezes.
  * No gráfico de bolhas sobreviventes e mortos por classe, algumas não mostram a porcentagem.
  * Poderia ter a média de idade dos sobreviventes e mortos.
  * A primeira classe, por ser mais cara e ter mais prioridade sobre as demais, assim como as mulheres sobre os homens, teve o maior numero de sobreviventes. Como o porto de embarque de maior lucro foi o de Southampton, logo, o maior numero de sobreviventes também foi de la.
  * No geral, mais homens embarcaram, porém mais mulheres sobreviveram

## Recursos

[Titanic - Tableau - Última versão](https://public.tableau.com/profile/milton.siqueira#!/vizhome/Titanic_538/Story).

[Titanic - Tableau - Primeira versão](https://public.tableau.com/profile/milton.siqueira#!/vizhome/Titanic_1st_version/Story).

[Titanic Data Set][latitude-longitude.csv](https://raw.githubusercontent.com/titomilton/tableau-titanic/master/latitude-longitude.csv).

[titanic-data.csv](https://raw.githubusercontent.com/titomilton/tableau-titanic/master/titanic-data.csv).
