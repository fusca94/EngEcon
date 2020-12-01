# Engenharia Econômica



## 1. Matemática Financeira - Introdução



### Juros

Ponderar:

- Risco de crédito

- Inflação

- Custo de oportunidade

- Remuneração (rendimentos em aplicações)

 

Fatores de produção de remuneração:

- Trabalho > Salário

- Tecnologia > Royalties

* **Capital > Juro**
* Capacidade empresarial > Lucro
* Terra > Aluguel

 

Valor Futuro = Valor Presente + Juros

 

### Juros Simples 

VF = VP(1 + i*n)

Taxas Equivalentes > dois VP's aplicados no mesmo período resultam no mesmo VF



### Juros Compostos

VF = VP(1+i)^n^

Taxas Equivalentes > i~m~ = (1+i~a~)^1/12^ - 1



## 2. Taxas de Mercado



### Percentual de Depósito Interbancário

DI %ano -> DI %dia -> Taxa base dia -> Taxa base ano

* 1ª Etapa:

  i~d~ = (1+i~a~)^(1/252)^ - 1  Obs.: 252 pois são considerados apenas dias úteis

* 2ª Etapa:

  Taxa dia = %DI * i~d~

* 3ª Etapa:

  Taxa ano = (1+ Taxa dia)^252^ - 1

Ex.: DI 9% a.a.. calcular o equivalente de 105%

i~d~ = (1+0,09)^(1/252)^ - 1 = 0,0003423 = 0,003423%

Taxa dia = 105% *  0,0003423 = 0,0003592 = 0,03591%

Taxa ano = (1+0,0003423)^252^ - 1 = 0,09471 = **9,471%**

Caso fosse feito apenas 105% * 0,09 = 9,45, <u>que está errado<u>



### Indexador Spread

1 + Taxa final = [(1 + indexador) * (1 + spread)]^período^



### TJLP - Taxa de Juros de Longo Prazo

Cálculo BNDES

* TJLP > 6,00% a.a.:

  Fator de Capitalização(FC) = [(1+TJLP/100)/(1+6%)]^n/360^

  Juros = SD * FC * {[1+((s+6)/100)]^n/360^ - 1}, s é o spread

* TJLP =< 6,00% a.a.:

  FC = 1

  J = SD * {[1 + (s+TJLP)/100]^n/360^ - 1}

SF = SD*FC + J

### Taxa Nominal e Real

Taxa Nominal segue a inflação e Taxa Real é o ganho sem a inflação.

1 + Real = (1 + tx nominal)/(1 + inflação)

