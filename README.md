# Previsão de Demanda  
Notebook com a EDA do dataset [Rossmann Store](https://www.kaggle.com/competitions/rossmann-store-sales/data?select=train.csv) e também aplicação da biblioteca 'Prophet' (antiga fbprophet).  

## Objetivo  
Realizar a previsão de faturamento pros próximos 30 dias de uma das lojas presentes no dataset.  

## Observações  
- Nesta base estão presentes 1.115 filiais de uma loja e para o desenvolvimento do estudo foi escolhida a 'Loja 1'
- A 'Prophet' é boa para ser utilizada em períodos sazonais - não lineares. Desta forma possui a sensibilidade para encarar datas comemorativas e feriados como picos de vendas específicos, não necessariamente entendo como uma tendência para previsões futuras
- Esta biblioteca necessita de um tratamento específico para realizar a previsão e, por isso, é importante renomear as colunas antes do uso da biblioteca. Parte do tratamento é feito dentro de uma função e no que diz respeito as datas comemorativas foi feito a parte
