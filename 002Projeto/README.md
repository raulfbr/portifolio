# Projeto 002: Análise de Risco de Inadimplência em Fintech 📉

## Desafio
Investigar fatores de risco associados à inadimplência em empréstimos pessoais utilizando dados de clientes de uma fintech. 🔎

## Ferramentas
Python (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Sklearn`, `Stasmodels`, `time`, `tqdm`, `Sci-Py`)  🐍

## Metodologia
CRISP-DM 🔁

## Destaques
- **Information Value (IV)**: Avaliação do poder preditivo das variáveis em relação à variável target. 🎯
- **Análise Exploratória de Dados (EDA)**: Compreensão do perfil dos clientes e da distribuição da inadimplência. 
- **Visualização de Dados**: Utilização de gráficos para identificar padrões e tendências nas variáveis. 
- **Insights de Negócio**: Identificação de fatores de risco e sugestões de medidas para mitigar a inadimplência.

## Aprendizados (reforçar)
- **Técnicas de EDA**: Análise descritiva.
- **Visualização de Dados com Seaborn**: pairplot, countplot.
- **Cálculo de Information Value**: Implementação de função personalizada para calcular o IV. 
- **Interpretação de Resultados**: Tradução de insights analíticos em ações práticas para o negócio.
- *_Machine Learning_*
>    - Regressão Linear (Linear Regression)
>    - Regressão Logísca (Logistic Regression)
>    - Random Forest (Random Forest)
>    - Gradient Boosting 
>    - Redes Neurais (Neural Network)

## Observação
O projeto demonstra habilidades em análise de risco e ações para serem executadas para mitigar a inadimplência.


---

## - **Perguntas para serem respondidas**🚨
1. Qual é o perfil dos clientes em relação à inadimplência com base nas variáveis individuais?
2. Quais variáveis têm correlação linear e alto Information Value (IV) com a inadimplência?
3. Quais fatores influenciam diretamente a inadimplência, considerando causalidade entre as variáveis?
4. Quais medidas a fintech deve adotar para minimizar a inadimplência com base nos fatores de risco identificados?
-  Todas as respostam estão dentro do Notebooks, segue resumo:

## Principais Insights 💡
- **Saldo de Conta Corrente**: Clientes com baixo saldo em conta corrente apresentam maior risco de inadimplência. 📉
- **Duração do Empréstimo**: Empréstimos de maior duração estão associados a taxas de inadimplência mais elevadas. 
- **Sexo**: Homens demonstram uma taxa de inadimplência significativamente maior do que mulheres.
- **Escolaridade e Tipo de Moradia**: Influenciam o risco de inadimplência, mas com menor poder preditivo.

## Recomendações 📋
- Segmentar clientes com base no saldo da conta corrente e na duração do empréstimo. 
- Oferecer soluções personalizadas para clientes de alto risco, como limites de crédito mais baixos ou prazos de pagamento mais curtos. 
- Implementar sistemas de alerta para identificar sinais de potencial inadimplência. 
- Investir em educação financeira para conscientizar os clientes sobre a importância da gestão financeira responsável. 

## Como Contribuir

Para contribuir:
1. Configure seu ambiente de desenvolvimento.
2. Clone o repositório e execute localmente.
3. Crie um branch, implemente e faça um pull request com uma descrição clara de suas alterações.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).
