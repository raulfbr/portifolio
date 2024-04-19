# Projeto 01

Este foi o primeiro projeto que realizei 100% sem ajuda de qualquer professor ou vídeo resposta. Foi 100% realizado com pesquisas na internet e inteligência artificial. (Leia a conclusão, onde aponto as habilidades aprendidas/reforçadas)


Recebi o seguinte case via e-mail (realizei algumas alterações para não ficar 100% igual e omiti o nome de quem/onde recebi):


## Resolva o seguinte case:

No mundo corporativo, dados são fundamentais para embasar decisões estratégicas. As pesquisas de opinião emergem como valiosas fontes desses dados. Para conduzi-las de forma eficaz, é essencial contar com indivíduos dispostos a compartilhar suas perspectivas.

Empresas denominadas "Painéis" desempenham um papel crucial nesse contexto. Elas estabelecem uma ponte (preservando o anonimato) entre sua comunidade de participantes, conhecidos como Painelistas, e grandes corporações em busca de insights.

Este exercício se concentra em dados simulados de uma empresa de Painel. A organização mantém um grupo de Painelistas (arquivo `Painelista.csv`) que estão motivados a participar de pesquisas de opinião em troca de compensações financeiras.

As respostas dos Painelistas são coletadas através das Pesquisas (arquivo `Pesquisa.csv`), com duas pesquisas já registradas para este exercício.
O relacionamento entre os Painelistas e as Pesquisas é documentado no arquivo `Painelista_Pesquisa.csv`. As contribuições de cada Painelista para cada pesquisa são armazenadas em `Resposta.csv`.
As pesquisas são compostas por Questões, e as alternativas de resposta estão listadas em `OpcoesDeRespostas.csv`.
Um diagrama que ilustra as interconexões entre esses arquivos pode ser encontrado abaixo para uma compreensão visual do processo.

<p align="center">
  <img src="https://github.com/raulfbr/portifolio/blob/main/projeto01/data/DiagramaRelacional.png?raw=true" alt="DiagramRelacional" width="50%">
</p>


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

## Metodologia

De início foi necessário realizar a juntar de todoas as tabelas conforme diagrama relacional, após foi utilizado a metodologia CRISP-DM, de forma interativa.

### Tecnologias Utilizadas

- Linguagens de Programação: [Python]
- Frameworks e Bibliotecas: [Pandas]
- Ferramentas: [KNIME]

## Estrutura do Projeto

- **data/**: Conjuntos de tabelas/dados utilizados no projeto.
- **notebooks/**: Notebooks Jupyter com o código e insigths.
- 
## Resultados

Todos os insigths então dentro do código Python.

## Conclusões Pessoais

1. Aprofundei-me na função `merge` do Python, conduzindo estudos para aplicá-la na junção de tabelas relacionais.
2. Compreendi a importância e eficácia do uso do método `astype` durante operações de merge para garantir a consistência dos dados.
3. Aprimorei minhas habilidades em manipulação de datas, utilizando o `pd.to_datetime` para tratamento adequado de informações temporais.
4. Apliquei técnicas para transformar respostas, tanto únicas quanto múltiplas, em linhas separadas para melhor análise e organização dos dados.
5. Inicialmente, subestimei o tempo necessário para a conclusão do projeto. Portantoa reforcei o aprendizado de que é essencial estabelecer tanto um **prazo otimista** quanto um **pessimista** ao iniciar qualquer projeto. Isso ajuda a antecipar possíveis obstáculos e manter a transparência com o cliente ao longo do processo.


## Como Contribuir

Instruções para contribuição, incluindo como configurar o ambiente de desenvolvimento, executar o projeto localmente e os passos para submissão de novas funcionalidades ou correções.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).
