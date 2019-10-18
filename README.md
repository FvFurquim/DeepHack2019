#  DeepHack2019
Projeto sobre ciência de dados para o Hackfest DeepHack2019 sediado pelo USPCodeLab em parceria com NuBank e Tribunal de Contas Estadual de São Paulo (TCE-SP).


# FAUSTOP

## Visão Geral
O Facilitador Auxiliar de Usuários Sobre o Tópico ODS de Produção (FAUSTOP) é um projeto que auxilia na identificação dos Objetivos de Desenvolvimento Sustentável (ODS), da Agenda 2030 da ONU, a partir de dados do TCE-SP.

 * O projeto é focado no **Objetivo 12** da ODS: Assegurar padrões de produção e de consumo sustentáveis.
 * O projeto foi feito na linguagem de programação Python 3.
 * A implementação do site foi realizada em HTML, CSS e Java Script.


# Metodologia
   1. Aplicamos o método de **Data Envelopment Analysis**(DEA) para medir a eficiência dos municípios de São Paulo.
   2. Para o tratamento e a análise de dados, utilizamos o pacote pandas e o módulo pyDEA.
   3. Os dados do TCE-SP foram cruzados com o IDH e o PIB de cada município (dados disponibilizados pelo IBGE).
   4. Assumimos a cidade com maior eficiência como modelo e analisamos o padrão em seus resultados.
   5. Por fim, verificou-se em quais aspectos os municípios poderiam realizar mudanças para aumentar sua eficiência.

## Análise de Dados

### Escolha de Variáveis
Em relação à base de dados disponibilizada pelo TCE-SP, julgamos pertinentes considerar para a análise: as receitas, despesas, perguntas e respostas relacionadas ao Objetivo 12 da ODS dos municípios (IEGM). Além disso, para complementar a análise, os dados sobre o PIB e o IDH de cada cidade foram considerados.

### Data Envelopment Analysis (DEA)
como funciona o dea e o pydea

Selecionamos como input para pyDEA, o IDH e a receita do município dividindo-o pelo PIB do Estado. Para output, selecionamos a relação entre perguntas respondidas positivamente (P), negativamente(N) e as neutras (X) através da fórmula: (2 * P + X) / N. 

### Resultados
Após a análise dos dados, a cidade com maior grau de eficiência --Santos-- foi escolhida como modelo. As respostas da cidade modelo e das demais cidades foram comparadas. Ao final, as perguntas com maiores índices de discrepâncias são apresentadas como tópicos a serem levados em maior consideração.


## Como Usar o FAUSTOP?
O FAUSTOP ainda não está disponível para acesso na Internet. Para acessá-lo, execute o código de HTML na pasta deepHacksite (link abaixo).
 
  Pasta contendo os arquivos essenciais, ou seja, contendo tudo que compõe o site: [deepHacksite Arquivos Essenciais] (https://github.com/FvFurquim/DeepHack2019/tree/master/deepHacksite/public_html)
 
 Obs: O site não está completamente funcional. Por mais que as análises foram feitas, nada foi colocado em um banco de dados. Portanto, o site é apenas um protótipo para mostrar como as informações seriam disponibilizadas.

## Integrantes do Projeto
   * Caio Rodrigues
   * Felipe Furquim
   * Stefany Nohama

