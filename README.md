# KafkaWeather
Producer and consumer interacting with weather API

The jupyter notebook creates a function to query a weather data API (OpenWeather API) for the current weather data in Minneapolis, Minnesota. A variable can be set for the duration between API queries. When the notebook is run, the weather API will be queried, a Kafka producer will publish the weather data, and a Kafka consumer will read and print select fields of the data.

The weather data updates every 5 - 10 minutes. Therefore, the query time was set to 10 minutes, but only three queries were made.
