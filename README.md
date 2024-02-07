# IA900
Repo destinado aos projetos 

Passo a passo criando modelo
 
1- ACESSE:
https://learn.microsoft.com/pt-br/azure/machine-learning/tutorial-first-experiment-automated-ml?view=azureml-api-2
2-Navegue ate DADOS na barra lateral esquerda.Preencha os campos obrigatórios, escolha Tabular e clique em criar
3-Em Fonte de dados clique em 'De arquivos da WEB' utilize a URL do videoe avance. até terminar o modelo.

Após seguir os passos  acima clique em pontos de extremidade e crie um ponto, utilizando o seu modelo ja criado selecione o o que tenha  TAG melhor
siga os passos da ferramenta ate conseguir a saida em JSON dos pontos como esta abaixo

{
  "input_data": {
    "columns": [
      "day",
      "mnth",
      "year",
      "season",
      "holiday",
      "weekday",
      "workingday",
      "weathersit",
      "temp",
      "atemp",
      "hum",
      "windspeed"
    ],
    "index": [],
    "data": []
  }
}
