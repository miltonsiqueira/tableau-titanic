# Tableau Titanic

## Resumo

Mostra informações sobre os passageiros do Titanic, relacionados sobre os sobreviventes e mortos.

## Design

* 26/04/2018

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

[Titanic - Tableau - Última versão](https://public.tableau.com/profile/milton.siqueira#!/vizhome/Titanic/Story)
[Titanic - Tableau - Primeira versão](https://public.tableau.com/profile/milton.siqueira#!/vizhome/Titanic_1st_version/Story)
[Titanic Data Set][latitude-longitude.csv](https://raw.githubusercontent.com/titomilton/tableau-titanic/master/latitude-longitude.csv)
[titanic-data.csv](https://raw.githubusercontent.com/titomilton/tableau-titanic/master/titanic-data.csv)
