## Projeto 01: Análise de Dados de Pesquisas de Opinião 📊

**Desafio:** Analisar dados simulados de uma empresa de pesquisa de opinião para obter insights sobre o perfil dos participantes e suas respostas.

**Ferramentas:** Python (Pandas), KNIME (No-Code)

**Metodologia:** CRISP-DM

**Destaques:**

* **Junção de Dados:** Consolidação de cinco conjuntos de dados em uma única tabela com informações completas sobre os participantes e suas respostas.
* **Análise Demográfica:** Cálculo da média e desvio padrão da idade dos participantes, análise da distribuição por sexo, região e renda.
* **Análise de Comportamento:** Avaliação do uso do Pix para diferentes finalidades, segmentado por sexo e outras características.
* **Insights Gerados:**  Identificação de padrões e tendências para auxiliar na tomada de decisões estratégicas da empresa de pesquisa. 

**Aprendizados:**

* **Manipulação de Dados com Pandas:**  Aprofundamento no uso da função `merge` e métodos como `astype` e `pd.to_datetime`.
* **Transformação de Dados:**  Conversão de respostas em linhas separadas para facilitar a análise.
* **Gestão de Tempo e Projetos:**  Importância de estabelecer prazos realistas e manter comunicação transparente com o cliente. 
* **Exploração de Novas Ferramentas:**  Utilização do KNIME para análise de dados sem código.

**Repositório:** https://github.com/raulfbr/portifolio/tree/main/projeto01

**Observação:** O projeto demonstra habilidades em manipulação de dados, análise exploratória, estatística descritiva e geração de insights.



---


# Case recebido:

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

## Como Contribuir

Para contribuir:
1. Configure seu ambiente de desenvolvimento.
2. Clone o repositório e execute localmente.
3. Crie um branch, implemente e faça um pull request com uma descrição clara de suas alterações.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).
