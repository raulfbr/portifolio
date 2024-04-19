# Projeto 01

Este foi o primeiro projeto que realizei 100% sem ajuda de qualquer professor ou vídeo resposta. Foi 100% realizado com pesquisas na internet e inteligência artificial. (Leia a conclusão, onde aponto as habilidades aprendidas/reforçadas)


- Recebi o seguinte case via e-mail (realizei algumas alterações para não ficar 100% igual e omiti o nome de quem/onde recebi):
- Os dados são fictícios

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

- Segue minha considerações:
  

# Desenvolvimento do projeto:

## Metodologia

Inicialmente, foi essencial unir todas as tabelas de acordo com o diagrama relacional. Posteriormente, adotei a metodologia CRISP-DM de maneira interativa para orientar o processo.

### Tecnologias Utilizadas

- Linguagens de Programação: [Python]
- Frameworks e Bibliotecas: [Pandas]
- Ferramentas: [KNIME]

## Estrutura do Projeto

- **data/**: Conjuntos de tabelas/dados utilizados no projeto.
- **notebooks/**: Notebooks Jupyter com o código e insigths.
- 
## Resultados

- Todos os insights estão diretamente no código Python.
- Embora não fosse um requisito incial, de forma proativa, desenvolvi insights com base nas respostas às perguntas levantadas, baseada em dados.

## Conclusões Pessoais

1. Aprofundei-me na função `merge` do Python, realizando estudos para aplicá-la eficientemente na junção de tabelas relacionais.
2. Reconheci a importância e eficácia do método `astype` durante as operações de merge, assegurando a consistência e integridade dos dados.
3. Aprimorei minhas habilidades em manipulação de datas, utilizando o `pd.to_datetime` para um tratamento mais preciso de informações temporais.
4. Implementei técnicas para converter respostas, sejam elas únicas ou múltiplas, em linhas separadas, visando aprimorar a análise e organização dos dados.
5. Inicialmente, subestimei o tempo requerido para concluir o projeto. Reforcei a importância de estabelecer prazos tanto otimistas quanto pessimistas ao iniciar qualquer projeto, permitindo antecipar desafios e manter uma comunicação transparente com o cliente durante todo o processo.

- Adorei o desafio de conduzir um projeto completamente independente, sem orientações prévias e sem garantias de estar no caminho certo (que simula situações da vida real). Aproveitei essa oportunidade para explorar e aprender a utilizar a ferramenta KNIME, conhecida por sua abordagem NoCode. O arquivo `knwf` está disponível na pasta "notebooks".

## Como Contribuir

Para contribuir:
1. Configure seu ambiente de desenvolvimento.
2. Clone o repositório e execute localmente.
3. Crie um branch, implemente e faça um pull request com uma descrição clara de suas alterações.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).
