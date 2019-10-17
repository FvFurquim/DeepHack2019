# DeepHack2019
Projeto sobre ciência de dados para o Hackfest DeepHack2019 sediado pelo USPCodeLab em parceria com NuBank e Tribunal de Contas Estadual de São Paulo (TCE-SP).

# FAUSTOP

## Visão Geral
O Facilitador Auxiliar de Usuários Sobre o Tópico ODS de Produção (FAUSTOP) é um projeto que auxilia na identificação dos Objetivos de Desenvolvimento Sustentável (ODS), da Agenda 2030 da ONU, a partir de dados do TCE-SP.

 * O projeto é focado no **Objetivo 12** da ODS: Assegurar padrões de produção e de consumo sustentáveis.
 * O projeto foi feito na linguagem de programação Python 3.
 * A implemetação do site foi realizada em HTML, CSS e JavaScript.


## Analise de Dados
   1. Aplicamos o método de **Data Envelopment Analysis**(DEA) para medir a eficiencia dos municipios de São Pualo.
   2. Para o tratamento e a analise de dados, utilizamos o pacote pandas e o módulo pyDEA.
   3. Os dados do TCE-SP foram cruzados com o IDH de cada município (dados disponibilizados pelo IBGE).
   4. Assumimos a cidade com maior eficiencia como modelo e analisamos o padrão em seus resultados.
   5. Por fim, Verificou-se em quais aspectos os municipios poderiam realizar mudanças para aumentar sua eficiencia.


## Como Usar o FAUSTOP?
 * O FAUSTOP ainda não está disponível para acesso na Internet, para acessá-lo rode o código de HTML na pasta deepHacksite.
 
 Obs: O site não está completamente funcional. Por mais que as análises foram feitas, nada foi colocado em um banco de dados. Portanto, o site é apenas um protótipo para mostrar como as informações seriam disponibilizadas.
 

## Integrantes do Projeto
   * Caio Rodrigues
   * Felipe Furquim
   * Stefany Nohama
