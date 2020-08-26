# SERVERLESS FRAMEWORK WITH AWS LAYERS.
- Injeção de camadas em realtime.
- Exemplo utilizado: moment, localizado em uma pasta independente da lambda.

# Function
- hello
- setup: dentro do yml definimos que a layer esta localizada dentro da pasta: "layers". Além disso, definimos o runtime do node compativel.

# Run
- sls invoke local -f hello