# Desafio BootCamp Santander 2023:

## Explorando IA GEnerativa em um Pipeline de ETL com Python

---

### Contexto

Recentemente houve um pedido de recuperação judicial da empresa Hotmilhas ([Clique para ler a notícia](https://valor.globo.com/empresas/noticia/2023/08/31/indenizaes-contra-123milhas-e-hotmilhas-tambm-dependem-da-recuperao-judicial.ghtml)), neste caso saiu uma lista com 7 arquivos com dados dos Credores e a partir desses arquivos contruí o seguinte Pipeline:

### Pipeline

1 - Juntar os 7 arquivos .xlsx em um único;

2 - Transformar a coluna 'Valor' no tipo numérico (float);

3 - Escrever o valor total de débitos presentes nesses arquivos;

4 - Usar a API da OpenAI para gerar uma mensagem motivacional para os credores (fazer 200 mensagens e depois simplificar para não pesar o código e a geração de tokens)

5 - Adicionar a mensagem ao arquivo;

6 - Salvar dados em .xlsx
