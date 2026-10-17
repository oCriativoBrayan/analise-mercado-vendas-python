# Análise de Mercado e Vendas com Python

## Objetivo
Analisar dados de vendas de um mercado, pelo período de 3 meses, para identificar padrões, avaliar o desempenho comercial e gerar informações que apoiem a tomada de decisões.

## Tecnologias
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- OpenPyXL

## Etapas do projeto
1. Importação dos dados.
2. Limpeza e tratamento.
3. Transformação e organização.
4. Análise exploratória.
5. Visualização dos resultados.
6. Identificação de indicadores e oportunidades de melhoria (fase decriação)

## Como executar

Clone o repositório:

```bash
git clone https://github.com/oCriativoBrayan/analise-mercado-vendas-python.git
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Abra o projeto no Jupyter Notebook e execute as células.

## Validações com claude

Claude trouxe lógica, eu implementei. Claude ficou responsável por avaliar meu código e mostrar caminhos possíveis para ajuste.


<img width="941" height="411" alt="image" src="https://github.com/user-attachments/assets/1f39d1cd-2fbc-43d9-a0f7-3c01e0c7fed9" />


## Resultados:

#### Análise 2: TOP 10 Produtos com MENOR margem

Claramente os produtos com margem negativa, consequentemente prejuizo para o mercado são Picanha com mais 20mil NEGATIVO, Alcatra e Mussarela. Logo, será necessário responder a algumas perguntas antes da tomada de decisão:

Existe possibilidade de negociação de preços com fornecedor?

Qual estratégia de vendas utilizada? e se pode ser mudada, ou, excluida?

Quem controla precificação desses itens?


<img width="1182" height="466" alt="image" src="https://github.com/user-attachments/assets/5c23b6de-4d88-4b6e-9a1c-22fc38d5dce7" />

#### Análise 2: Setor com maior e menor quantidade vendida

Hortifruti teve mais 5mil vendas, em comparação com os produtos da mercearia que tiveram pouco mais de 1mil vendas, não se pode chegar a um decisão somente com esses dados, porém, claramente perfil de consumo dos clientes está focado no hortifruti. Logo, um análise mais aprofundada nesta área, podemos melhorar lucratividade, negociando preços e prazos com os fornecedores.


<img width="1092" height="452" alt="image" src="https://github.com/user-attachments/assets/66e53551-e938-45a4-a560-08d404c56a8e" />


#### Análise 3: Maior faturamento por categoria

Hortifruti conforme análise acima se destacou, juntamente com frios e açougue. Hortifruti com quase 140mil em faturamento, considerando margem de lucro, sem sombra de dúvidas "galinha dos ovos de ouro" do mercado. Já frios e açougue demandam atenção com faturamento proximo de 100mil, um erro no preço, pode causa grandes prejuizos, consumindo o lucro da operação e comprometendo saúde financeira da empresa.


<img width="967" height="597" alt="image" src="https://github.com/user-attachments/assets/b33dbc2a-d39e-4d31-9081-bb72952b7657" />


#### Análise 4: Margem por categoria

Açougue é categoria que mais chama atenção, com seu lucro negativo, agora um ponto, bebidas tem lucratividade muito boa. O que aponta para um possivel estratégia, perde no açogue x ganha na bebida, ainda sim, precisa verificar possibilidade de melhoria da margem, pelo menos deixando positiva.


<img width="898" height="506" alt="image" src="https://github.com/user-attachments/assets/9d2dbde5-6558-40af-918e-559ddac8d213" />

#### Análise 5: Margem por nome produto

Hortifruti e bebidas, permanecem com melhor rentabilidade, já picanha, alcatra e queijo mussarela,mostra que será necessário, reanálida dos fornecedores, buscando melhores preços.


<img width="1000" height="626" alt="image" src="https://github.com/user-attachments/assets/3f2d9b23-1def-4b69-ac29-f8a5a14b4c14" />
