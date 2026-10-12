# 🍊 Análise dos preços da laranja na região de Limeira

Dashboard desenvolvido em **Power BI** para analisar dez anos de dados sobre os preços da caixa de **40,8 kg de laranja lima**, cultivada na região de **Limeira, São Paulo**, com base nas informações disponibilizadas pelo **CEPEA**.

## Objetivo

Explorar a evolução histórica dos preços, comparar médias mensais e anuais e identificar períodos de preços mais altos e mais baixos, oferecendo informações que podem apoiar decisões de compra e venda.

## Tecnologias utilizadas

- **Power BI:** tratamento dos dados e construção do dashboard.
- **Arquivo XLS:** formato utilizado para exportar e importar a base.

## Fonte dos dados

Os dados foram obtidos no portal do **Centro de Estudos Avançados em Economia Aplicada (CEPEA)**.

- **Portal:** https://www.cepea.org.br/
- **Produto analisado:** laranja lima.
- **Região:** Limeira, São Paulo.
- **Unidade de cotação:** caixa de 40,8 kg.
- **Período:** dez anos de registros históricos.

## Metodologia

### 1. Coleta e importação

Os registros de preços foram exportados do portal do CEPEA para um arquivo XLS e importados no Power BI.

### 2. Tratamento das datas

A base apresentava ano, mês e dia em colunas separadas. Essas informações foram reunidas em uma única coluna de data, permitindo organizar os registros cronologicamente e realizar as análises temporais.

### 3. Construção das análises

O dashboard reúne:

| Visualização | Finalidade |
|---|---|
| Preços por dia | Acompanhar as oscilações ao longo da série histórica |
| Média de preços por mês | Comparar os meses, considerando os registros dos diferentes anos |
| Média de preços por ano | Comparar os níveis médios de preços entre os anos |
| Tabela de consulta | Consultar o preço registrado em uma data específica |

### 4. Organização visual

O painel foi organizado para facilitar a leitura e a consulta das informações, com uma identidade visual relacionada à citricultura e uma hierarquia clara entre títulos, gráficos e tabela.

## Principais resultados

A comparação das médias mensais indicou que:

- **Os meses do meio do ano apresentaram preços mais baixos**, indicando períodos historicamente mais favoráveis à compra.
- **Os meses do fim e do início do ano apresentaram preços mais altos**, indicando períodos historicamente mais favoráveis à venda, considerando o preço recebido.
- A análise diária permitiu identificar o **maior pico de preço da série histórica**.

Essas conclusões descrevem o comportamento observado na base analisada. Não representam uma previsão nem garantem que o mesmo padrão se repita nos próximos anos.

## Limitações da análise

- A comparação utiliza os preços registrados na fonte, sem ajuste pela inflação.
- As médias mensais resumem observações de diferentes anos e podem ocultar variações entre eles.
- Preços mais altos não significam necessariamente maior rentabilidade, pois a análise não considera custos de produção, transporte, armazenamento ou perdas.
- Os resultados se referem ao produto, à região e ao período analisados.

## Como visualizar

1. Baixe o arquivo `.pbix` disponível neste repositório.
2. Abra o arquivo no **Power BI Desktop**.
3. Explore os gráficos e a tabela de preços.

Para atualizar os dados, pode ser necessário ajustar o caminho do arquivo XLS nas configurações da fonte de dados.

## Aprendizados

Este projeto permitiu praticar:

- Importação e tratamento de dados no Power BI.
- Preparação de datas para análises temporais.
- Análise descritiva de séries históricas.
- Comparação de médias mensais e anuais.
- Visualização de dados e comunicação de resultados.

## Autor

**João Pedro Ramiro**  
Estudante de Ciência de Dados na FATEC de Adamantina.

- [LinkedIn](https://www.linkedin.com/in/joaopedroramiro/)
- [GitHub](https://github.com/joaopedroramiro321-source)
