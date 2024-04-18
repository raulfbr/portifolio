# Nome do Projeto

## Resolva o seguinte case:

No mundo corporativo, dados são fundamentais para embasar decisões estratégicas. As pesquisas de opinião emergem como valiosas fontes desses dados. Para conduzi-las de forma eficaz, é essencial contar com indivíduos dispostos a compartilhar suas perspectivas.

Empresas denominadas "Painéis" desempenham um papel crucial nesse contexto. Elas estabelecem uma ponte (preservando o anonimato) entre sua comunidade de participantes, conhecidos como Painelistas, e grandes corporações em busca de insights.

Este exercício se concentra em dados simulados de uma empresa de Painel. A organização mantém um grupo de Painelistas (arquivo Painelista.csv) que estão motivados a participar de pesquisas de opinião em troca de compensações financeiras.

As respostas dos Painelistas são coletadas através das Pesquisas (arquivo Pesquisa.csv), com duas pesquisas já registradas para este exercício.
O relacionamento entre os Painelistas e as Pesquisas é documentado no arquivo Painelista_Pesquisa.csv. As contribuições de cada Painelista para cada pesquisa são armazenadas em Resposta.csv.
As pesquisas são compostas por Questões, e as alternativas de resposta estão listadas em OpcoesDeRespostas.csv.
Um diagrama que ilustra as interconexões entre esses arquivos pode ser encontrado abaixo para uma compreensão visual do processo.


![DiagramRelacional]([https://github.com/acenelio/assets/raw/main/sds1/web1.png](https://github.com/raulfbr/portifolio/blob/main/projeto01/data/DiagramaRelacional.png?raw=true))




### 1. Junção dos Conjuntos de Dados
Realize a junção dos cinco conjuntos de dados e crie uma única tabela que inclua todas as respostas dos 600 Painelistas nas duas pesquisas. Esta tabela deve conter 5551 linhas (uma para cada resposta) e 14 colunas. Um exemplo com 23 linhas dessa tabela pode ser encontrado no arquivo `Modelo01.csv`.

### 2. Análise de Dados
Utilize os dados no formato que preferir para responder às seguintes questões:

   **a.** Qual é a média e o desvio padrão de idade dos 600 Painelistas? Pode ser necessário fazer algumas aproximações para responder a esta questão, e a sua metodologia de aproximação será avaliada.

   **b.** Qual é a porcentagem de Painelistas que têm filho(s) e são do sexo feminino?

   **c.** Qual é a porcentagem de Painelistas da região SUL que têm uma renda mensal de até R$ 2.999?

   **d.** Qual é a porcentagem dos 600 Painelistas que utilizam o Pix para cada uma das finalidades pesquisadas?

   **e.** Qual é a porcentagem de Painelistas que utilizam o Pix para [Transferir dinheiro para amigos e familiares] OU [Pagar compras em lojas online] e são do sexo masculino?

Mais do que as respostas finais, o foco está na implementação das suas soluções em Python. Portanto, é crucial enviar o arquivo ipynb com o código desenvolvido para chegar às respostas.

Qualquer ferramenta open-source poderá ser utilizada, porém a preferência é:
- Utilizar somente Pandas para soluções em Python

## Descrição

Breve descrição do projeto, apresentando o contexto, o problema abordado e a solução proposta.

## Objetivos

- **Objetivo Principal**: Descrição do objetivo principal do projeto.
- **Objetivos Secundários**: Lista de objetivos secundários ou metas a serem alcançadas.

## Metodologia

Explicação detalhada dos métodos, técnicas e ferramentas utilizados no desenvolvimento do projeto.

### Tecnologias Utilizadas

- Linguagens de Programação: [Linguagem(s) utilizada(s)]
- Frameworks e Bibliotecas: [Frameworks e bibliotecas utilizadas]
- Ferramentas: [Outras ferramentas ou plataformas utilizadas]

## Estrutura do Projeto

- **data/**: Conjuntos de dados utilizados no projeto.
- **notebooks/**: Notebooks Jupyter ou outros formatos com o código, análises e visualizações.
- **src/**: Scripts com funções e classes reutilizáveis.
- **models/**: Modelos de Machine Learning ou Deep Learning treinados.
- **reports/**: Relatórios gerados a partir das análises.

## Resultados

Apresentação dos resultados obtidos, incluindo métricas, gráficos e insights relevantes.

## Conclusões

Conclusões finais sobre o projeto, destacando os principais aprendizados, limitações e possíveis trabalhos futuros.

## Como Contribuir

Instruções para contribuição, incluindo como configurar o ambiente de desenvolvimento, executar o projeto localmente e os passos para submissão de novas funcionalidades ou correções.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).
