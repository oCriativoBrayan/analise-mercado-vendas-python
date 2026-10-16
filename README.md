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

Claramente os produtos com margem negativa, consequentemente prejuizo para o mercado são Picanha, Alcatra e Mussarela. Logo, será necessário responder a algumas perguntas antes da tomada de decisão:
Existe possibilidade de negociação de preços com fornecedor?
Qual estratégia de vendas utilizada? e se pode ser mudada, ou, excluida?
Quem controla precificação desses itens?


<img width="1094" height="485" alt="image" src="https://github.com/user-attachments/assets/ee2fb726-f510-45eb-af86-8624250a435d" />

#### Análise 2: Setor com maior e menor quantidade vendida

Hortifruti teve quase 10mil vendas, em comparação com os produtos da mercearia que tiveram pouco menos de 2mil vendas, não se pode chegar a um decisão somente com esses dados, porém, claramente perfil de consumo dos clientes está focado no hortifruti. Logo, um análise mais aprofundada nesta área, podemos melhorar lucratividade, negociando preços e prazos com os fornecedores.


<img width="965" height="486" alt="image" src="https://github.com/user-attachments/assets/0b210705-6c2f-4088-a0bb-60ce1f6c57df" />


#### Análise 3: Maior faturamento por categoria

Hortifruti conforme análise acima se destacou, juntamente com frios e açougue.   Hortifruti com quase 200mil em faturamento, considerando margem de lucro, sem sombra de dúvidas "galinha dos ovos de ouro" do mercado. Já frios e açougue demandam atenção com faturamento proximo de 150mil, erro no preço, pode causa grandes prejuizos, consumindo lucro da operação, comprometendo saúde financeira da empresa.


<img width="1014" height="637" alt="image" src="https://github.com/user-attachments/assets/0a0661e0-5276-49cc-8a3b-b6b9e691adc5" />


#### Análise 4: Margem de lucro por categoria  - MEDIA

Açougue é categoria que mais chama atenção, com seu lucro negativo, agora um ponto, bebidas tem lucratividade muito boa. O que aponta para um possivel estratégia, perde no açogue x ganha na bebida, ainda sim, precisa verificar possibilidade de melhoria da margem, pelo menos deixando positiva.


<img width="958" height="613" alt="image" src="https://github.com/user-attachments/assets/e893caf9-31da-4770-b2b9-2e05b6d7b1e1" />

#### Análise 5: Margem de lucro por categoria  - SOMA

Hortifruti e bebidas, permanecem com melhor rentabilidade, mercearia mostra um valor proximo de 10, isso mostra que será necessário, reanálida dos fornecedores, busncando melhores preços.


<img width="969" height="615" alt="image" src="https://github.com/user-attachments/assets/9e1dc480-a545-46e9-b37c-fd4d8924d910" />
