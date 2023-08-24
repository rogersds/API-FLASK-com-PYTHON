# API-FLASK-com-PYTHON
- Flask API de Análise de Vendas
Esta é uma aplicação simples construída com Flask para analisar dados de vendas a partir de um arquivo Excel.
 Ela oferece endpoints para fornecer informações sobre o faturamento geral e os produtos vendidos.

# Endpoints
 GET Faz a Requisição de dados 

- GET /
Este endpoint retorna o faturamento total das vendas.

- GET /vendas/produtos
Este endpoint retorna um dicionário com o faturamento total agrupado por produto.

- GET /vendas/produtos/{produto}
Este endpoint retorna o faturamento associado a um produto específico. Se o produto não existir nos dados, uma mensagem apropriada será retornada.
