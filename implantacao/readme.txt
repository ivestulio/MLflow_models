O mlflow serve o modelo como um serviço em uma requisição HTTP, web service 

# Para servir o modelo na porta 2345:

   mlflow models serve --model-uri runs:/[id_modelo]/[log_modelo] -p 2345

[id_modelo] : identificador do modelo, o id da saída do print, ou o que aparece na ui 
[log_modelo]: log do modelo que criamos quando registramos o modelo: modelonb (mlflow.sklearn.log_model(naive_bayes, 'modelonb')
-p : porta 

# Para consumir o modelo: usar: consumindo_modelo.ipynb


