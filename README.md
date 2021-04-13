# Ciência e Visualização de Dados - Primeira Entrega

# Projeto `Falhas de Diagnóstico Médico e os Impactos no Sistema Único de Saúde Brasileiro`
# Project `Medical Diagnostic Failures and the Impacts on the Brazilian Unified Health System`

# Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação [*Ciência e Visualização de Dados em Saúde*](https://github.com/datasci4health/home), oferecida no primeiro semestre de 2021, na Unicamp.

### Equipe

> |Nome  | RA | Especialização|
> |--|--|--|
> | Gleyson Roberto do Nascimento | 043801  | Elétrica|
> | Negli René Gallardo Alvarado  | 234066  | Saúde|
> | Rafael Vinícius da Silveira  | 137382  | Física|
> | Sérgio Sevileanu  | 941095  | Elétrica|


# Descrição Resumida do Projeto
~~~ 
As falhas de diagnóstico médico são responsáveis, num primeiro momento, por consequências aos indivíduos que foram vitimadas por estas falhas, todavia, até onde se estendem essas consequências? 
Neste contexto, o projeto busca compreender melhor quais são os impactos que as falhas trazem ao Sistema Único de Saúde, se é possível mitigar os resultados negativos e auxiliar na predição de casos de falha de diagnóstico através do Aprendizado de Máquina.
A principal motivação da equipe neste projeto científico é contribuir para um melhor atendimento aos pacientes, que são os principais afetados, auxiliar os profissionais médicos alertando-os sobre a possibilidade de falha de diagnóstico e, por fim, auxiliar no uso mais racional de recursos, evitando as custas causadas pelas falhas de diagnóstico.
~~~
### Vídeo de apresentação da proposta do projeto
[![Projeto Saúde](https://github.com/grnbatera/Data4health/blob/main/Mídias/thumb.JPG)](https://www.youtube.com/watch?v=AYZ8yBdD8Ds)


# Perguntas de Pesquisa
~~~ 
1) Qual é a extensão do impacto causado pelas falhas de dignóstico médico dentro do Sistema Único de Saúde do Brasil?
2) Uma vez conhecida esta extensão, é possível propor um método de predição de casos de falha de diagnóstico em Machine/Deep Learning?
3) Sendo possível essa predição, esse método de fato seria útil, de fácil acesso e amigável para os profissionais do SUS?
~~~ 

# Bases de Dados
> Neste primeiro momento, as bases elencadas são:
> |Base de Dados  | Fonte | Descrição|
> |--|--|--|
> | [Sistema de Informações Hospitalares do SUS - SIHSUS](https://bigdata-metadados.icict.fiocruz.br/dataset/sistema-de-informacoes-hospitalares-do-sus-sihsus/resource/ae85ac54-6734-43b8-a820-6129a854e1ff) | Fiocruz  | Dados do Sistema de Informações Hospitalares do SUS (SIHSUS) reunidos pela Plataforma de Ciência de Dados aplicada à Saúde (PCDaS)|
> | [Cadastro Nacional de Estabelecimentos de Saúde - CNES](https://bigdata-metadados.icict.fiocruz.br/dataset/cadastro-nacional-de-estabelecimentos-de-saude-cnes/resource/7bcf4f68-f2e9-4e06-87b5-229358702efc)  | Fiocruz  | Dados do Cadastro Nacional de Estabelecimentos de Saúde (CNES) reunidos pela Plataforma de Ciência de Dados aplicada à Saúde (PCDaS)|
> | [Classificação Estatística Internacional de Doenças e Problemas Relacionados à Saúde - CID-10](http://www2.datasus.gov.br/cid10/V2008/cid10.htm)  | DataSUS  | CID - 10 em Língua Portuguesa e colaborativa com a OMS|
> | [Estatísticas Sociais - IBGE](https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html)  | IBGE  | Dados referentes ao padrão de vida da população brasileira|

# Metodologia
~~~ 
Através da metodologia CRISP-DM, os dados coletados serão reunidos, analisados, limpos, minerados (nestas etapas, haverá a ênfase na análise estatística) e, após isso, através de aprendizado de máquina, se for possível, será criado um modelo de predição de falhas de diagnóstico médico e por fim este modelo será analisado e, se for validado, pode ser implementado como auxílio para profissionais de saúde do SUS.
~~~ 

# Ferramentas
~~~ 
Para este projeto será utilizado um Notebook em  Google Colaboratory e Linguagem de Programação Python 3.0. Por sua vez, dentro da linguagem serão utilizadas as seguintes Bibliotecas: Numpy (para a análise numérica/estatística), Pandas (para manipulação dos dados), MatPlotLib/Seaborn (para visualização dos dados), Keras/Scikit Learn/TensorFlow (para aprendizado de máquina).
~~~ 

# Cronograma
> Proposta de cronograma:
> |Atividade  | Descrição | Tempo estimado|
> |--|--|--|
> | Business Understand | Busca da melhor metodologia para encontrarmos as respostas das perguntas de pesquisa  | 12/04 a 16/04 (1 semana)|
> | Data Understanding  | Busca e avaliação dos dados necessários para a pesquisa   | 19/04 a 23/04 (1 semana)|
> | Data Preparation  | Limpeza, uniformização, normalização e adequação da base de dados final de trabalho  | 26/04 a 07/05 (2 semanas)|
> | Data Mining  | Mineração dos dados através de análises estatísticas  | 10/05 a 19/05 (1.5 semana)|
> | Modeling  | Modelamento de predição de falha de diagnóstico médico através de aprendizado de máquina  | 20/05 a 28/05 (1.5 semana)|
> | Evaluation | Avaliação do modelo de predição de falha de diagnóstico médico  | 31/05 a 04/06 (1 semana)|
> | Deployment | Avaliação de metodolgias para implementação no SUS  | 07/06 a 11/06 (1 semana)|
> | Relatório Final | Confecção do Relatório Final  | 14/06 a 23/06 (1.5 semana)|
> | Apresentação de Projeto | Apresentação do Projeto Final da Disciplina | 24/06 e 29/06|
