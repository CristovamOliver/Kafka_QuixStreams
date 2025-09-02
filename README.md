# Weather Streaming com Kafka e Quix Streams


Este projeto demonstra a produção, consumo e transformação de um streaming de dados meteorológicos usando Apache Kafka e a biblioteca Quix Streams.
Ele coleta dados da API de clima, ("https://api.open-meteo.com/v1/forecast")  envia para um tópico Kafka, processa os dados em diferentes unidades de temperatura e, por fim, consome os resultados.


*  Instale as dependências:
     pip install -r requirements.txt

1 - Send_to_Kafka (gera os dados de clima)

2 - Read_from_Kafka (lê e imprime os dados)

3 - Kafka_processor (converte as temperaturas)

