# Alesp tem alta de 17,8% em gastos com locação de carros em meia a pandemia da Covid-19
Códigos que demostraram como deputados da Alesp aumentaram custos com aluguel de carros em empresa ligada a ex-parlamentar em meio a pandemia

Este foi o conjunto de códigos utilizados na reportagem ["Alesp tem alta de 17,8% em gastos com locação de carros no 1º semestre"](https://www.metropoles.com/brasil/alesp-tem-alta-de-178-em-gastos-com-locacao-de-carros-no-1o-semestre), publicado no Portal Metrópoles. 

Além do aumento dos custos com locação de veículos em meio a restriçõpes sanitárias e interrupção de atividades presenciais, deputados locaram automóveis em empresa ligada a ex-parlamentar da Casa.

## Metodologia

A primeira parte deste trabalho foi conseguir baixar os dados relativos a todas as despesas feitas pelos parlamentares em um formato amigável para análise -> [scrapper_alesp](https://github.com/juditecypreste/os-carros-da-alesp-na-pandemia/blob/main/scrapper_alesp.ipynb)

Como estes dados não possuem o nome dos parlamentares, fica impossível saber quem realmente gastou com o que. Para contornar este problema de transparência governamental, foi preciso cruzar os números de matrículas dos deputados com os seus nomes -> [matriculas_alesp](https://github.com/juditecypreste/os-carros-da-alesp-na-pandemia/blob/main/matriculas_alesp.ipynb)

Por fim, o código da análise dos gastos foi feita -> [analise_alesp](https://github.com/juditecypreste/os-carros-da-alesp-na-pandemia/blob/main/analise_alesp.ipynb)

*NOTA: Agora a Alesp divulga os dados de despesas com o nome correspondente do deputado.*

### Neste trabalho foi usada as seguinte base de dados:
### - [Portal de dados abertos da Alesp](https://www.al.sp.gov.br/dados-abertos/recurso/21) 

## Bibliotecas utilizadas

Pandas: https://pandas.pydata.org/  
CSV: https://docs.python.org/3/library/csv.html  
Numpy: https://numpy.org/
