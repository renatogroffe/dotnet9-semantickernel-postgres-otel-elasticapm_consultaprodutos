# dotnet9-semantickernel-postgres-otel-elasticapm_consultaprodutos
Exemplo em .NET 9 de Console Application que faz uso do projeto Semantic Kernel, com integração com soluções de IA como Azure Open AI e Ollama na consulta de informações de produtos em uma base PostgreSQL. Inclui Docker Compose para criação do ambiente de testes com os dados + monitoramento com Elastic APM e OpenTelemetry.

---

## Resultados da Telemetria

Trace gerado:

![Trace gerado](img/otel-elasticapm-01.png)

O mesmo trace com a consulta à base de dados:

![Trace gerado - consulta à base](img/otel-elasticapm-02.png)

E exibindo o detalhamento do consumo de tokens (em testes com o Azure OpenAI):

![Trace gerado - consumo de tokens](img/otel-elasticapm-03.png)