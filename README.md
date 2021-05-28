# Ciência e Visualização de Dados - Segunda Entrega

# Projeto `Falhas de Diagnóstico Médico e os Impactos no Sistema Único de Saúde Brasileiro`
# Project `Medical Diagnostic Failures and the Impacts on the Brazilian Unified Health System`

Estrutura [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) do Projeto:

~~~
├── README.md          <- Apresentação do Projeto `Falhas de Diagnóstico Médico e os Impactos no Sistema Único de Saúde Brasileiro`
│
├── data
│   ├── external       <- Dados da Plataforma de Ciência de Dados aplicada à Saúde (PCDaS)
│   ├── interim        <- Dados intermediários, e.g., resultado de transformação
│   ├── processed      <- Dados finais usados para a modelagem
│   └── raw            <- Dados originais sem modificações
│
├── notebooks          <- Notebooks do Google Colabooratory
│
├── src                <- fonte em linguagem de programação em Python 3.7
│   └── README.md      <- instruções básicas de instalação/execução
│
└── assets             <- Mídias usadas no projeto
~~~

## `data`

Neste projeto, atraés de dados externos, foram crandas as bases raw, que foram pré-processados, criando as bases intermmedárias, que po sua vez foram tansformados e enriquecidos, formando a ase de dados final para data mining.

Os dados external não possuem restrição de divulgação, considerando que estão anonimizados e possuem acesso direto pela Fioruz BigData, assim, estão disponíveis nos links abaixo e possuem este [Dicionário de Variáveis](https://github.com/grnbatera/Data4health/blob/main/assets/Dicion%C3%A1rio%20de%20Vari%C3%A1veis%20Banco%20Original.csv): 

## Bases de Dados External:
> Nesta etapa, as bases efetivamente utilizadas foram:
> |Base de Dados  | Fonte | Descrição|
> |--|--|--|
> | [Sistema de Informações Hospitalares do SUS - SIHSUS](https://bigdata-metadados.icict.fiocruz.br/dataset/sistema-de-informacoes-hospitalares-do-sus-sihsus/resource/ae85ac54-6734-43b8-a820-6129a854e1ff) | Fiocruz  | Dados do Sistema de Informações Hospitalares do SUS (SIHSUS) reunidos pela Plataforma de Ciência de Dados aplicada à Saúde (PCDaS)|
> | [Classificação Estatística Internacional de Doenças e Problemas Relacionados à Saúde - CID-10](http://www2.datasus.gov.br/cid10/V2008/cid10.htm)  | DataSUS  | CID - 10 em Língua Portuguesa |

Os dados raw, interim e processed estão disponíveis nos links abaixo e possuem este [Dicionário de Variáveis](https://github.com/grnbatera/Data4health/blob/main/assets/Dicion%C3%A1rio%20de%20Vari%C3%A1veis.csv): 

## Bases de Dados Raw:
> Nesta etapa, as bases inciais são:
> |Base de Dados  | Descrição|
> |--|--|
> | [Dados Raw de SP](https://drive.google.com/file/d/1Hdzz218LvSzz_reDjndKZ2a6r_M_zKl-/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado de São Paulo sem a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Raw de BA](https://drive.google.com/file/d/1LcqDxhUAIwVEsMEcrfAAQGjoQvCD8qGn/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado da Bahia sem a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Raw de PR](https://drive.google.com/file/d/19zx0YYD10ddYYGGk5BOwKcvLSlyE0DcQ/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado do Paraná sem a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Raw de PA](https://drive.google.com/file/d/1vffaXC_qag8_dwf49xDPL7CctAxZ6_x-/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado do Pará sem a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Raw de GO](https://drive.google.com/file/d/16g9O_wwsowh5V6CHNRWxnpA1rQtxZX7G/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado de Goiás sem a limpeza, categorização, transformação e criação das variáveis para a análise|

## Bases de Dados Interim:
> Nesta etapa, as bases unificadas prontas para o processamento são:
> |Base de Dados  | Descrição|
> |--|--|
> | [Dados Intermediários de SP](https://drive.google.com/file/d/12itifDFEuwrKdrrc20eSw7tJKyTuY88X/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado de São Paulo prontos para a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Intermediários de BA](https://drive.google.com/file/d/1tx0J9RSm3U0tfFeiSVdpTW2C9duK3wB2/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado da Bahia prontos para a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Intermediários de PR](https://drive.google.com/file/d/1Fmsoqlhvw873n7XcdOKisk1k24FCMfpI/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado do Paraná prontos para a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Intermediários de PA](https://drive.google.com/file/d/1q1UitWVVzPCPI-nv-ElSPSi4Ny7SR1aR/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado do Pará prontos para a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Intermediários de GO](https://drive.google.com/file/d/1dHD5IEemZ_Dd8kysf9j1jHPKZJG-38vC/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado de Goiás prontos para a limpeza, categorização, transformação e criação das variáveis para a análise|

## Bases de Dados Processed:
> Nesta etapa, as bases finais são:
> |Base de Dados  | Descrição|
> |--|--|
> | [Dados Processados de SP](https://drive.google.com/file/d/12itifDFEuwrKdrrc20eSw7tJKyTuY88X/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado de São Paulo finalizado após a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Processados de BA](https://drive.google.com/file/d/1tx0J9RSm3U0tfFeiSVdpTW2C9duK3wB2/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado da Bahia finalizado após a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Processados de PR](https://drive.google.com/file/d/1Fmsoqlhvw873n7XcdOKisk1k24FCMfpI/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado do Paraná finalizado após a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Processados de PA](https://drive.google.com/file/d/1q1UitWVVzPCPI-nv-ElSPSi4Ny7SR1aR/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado do Pará finalizado após a limpeza, categorização, transformação e criação das variáveis para a análise|
> | [Dados Processados de GO](https://drive.google.com/file/d/1dHD5IEemZ_Dd8kysf9j1jHPKZJG-38vC/view?usp=sharing) |  Dados sobre o Sistema de Internação Hositalar (SHI) do Estado de Goiás finalizado após a limpeza, categorização, transformação e criação das variáveis para a análise|


## `notebooks`

Todo o projeto foi elaborado em noteooks do Google Colaboratory, através da Linguagem Python 3.7, num processo em 3 etapas: 

1) *Pré-Processamento do Big Data*: Através do notebook [Projeto_Final_Big_Data](https://github.com/grnbatera/Data4health/blob/main/notebook/Projeto_Final_Big_Data.ipynb), houve a manipulação do arquivo raw para a retirada de varáveis se descrição no dicionário de variáveis e com índice de NaN maior que 75%, além de criar um subset com todas as cidades dos estados de São Paulo, Bahia, Paraná, Pará e Goiás;
2) *Processamento dos arquivos dos Estados*: Através dos notebooks [SP](https://github.com/grnbatera/Data4health/blob/main/notebook/SP.ipynb), [BA](https://github.com/grnbatera/Data4health/blob/main/notebook/BA.ipynb), [PR](https://github.com/grnbatera/Data4health/blob/main/notebook/PR.ipynb), [PA](https://github.com/grnbatera/Data4health/blob/main/notebook/PA.ipynb) E [GO](https://github.com/grnbatera/Data4health/blob/main/notebook/GO.ipynb) foram processados os arquivos dos estados de São Paulo, Bahia, Paraná, Pará e Goiás, respectivamente, na busca de um retrato das regiões do país. Através destes notebooks, os arquivos fooram processados e foram analisadas as características estatísticas, correlações, p-valor e análise gráfica por scatter plots, box plots e q-q pplots;
3) *Análise Estatístca das Falhas de Diagnóstico*: Por fim, através do notebook [Análise_das_Falhas_de_Diagnóstico](https://github.com/grnbatera/Data4health/blob/main/notebook/An%C3%A1lise_das_Falhas_de_Diagn%C3%B3stico.ipynb), foi realizada uma análise de caracterização estatística do objeto de estudo desse projeto, que são as falhas de diagnóstico médico. 


## `src`

Como o projeto foi todo realzado em notebook do Google Colaboratory , não houve a necessidade de código fonte fora dos notebooks, todava, nesta pasta existe a documentação acerca do [Google Colab](https://github.com/grnbatera/Data4health/tree/main/src).

## `assets`

Na pasta assets encontram-se as figuras referenciadas neste projeto, a apresentação do projeto em PDF, os dicionários de varáveis dos bancos external, raw, interim e  processed e umm dicionário das categorias e subcategorias do CID-10.


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

> As falhas de diagnóstico médico são responsáveis, num primeiro momento, por consequências aos indivíduos que foram vitimadas por estas falhas, todavia, até onde se estendem essas consequências? 
> Neste contexto, o projeto busca compreender melhor quais são os impactos que as falhas trazem ao Sistema Único de Saúde, se é possível mitigar os resultados negativos e auxiliar na predição de casos de falha de diagnóstico através do Aprendizado de Máquina.
> 
> A principal motivação da equipe neste projeto científico é contribuir para um melhor atendimento aos pacientes, que são os principais afetados, auxiliar os profissionais médicos alertando-os sobre a possibilidade de falha de diagnóstico e, por fim, auxiliar no uso mais racional de recursos, evitando as custas causadas pelas falhas de > diagnóstico.

# Definições e Disclaimer:

> Algumas definições iniciais e um disclaimer se fazem necessários:
> 
> Como a base de dados principal utlizada é a do SIHSUS, os dados são referentes exclusivamente aos atendimentos hospitlares realizados pelo SUS durante os anos de 2008 a 2018; 
> 
> Será definido como **diagnóstico correto** aquele em que houve apenas um diagnóstico de CID-10, sem alterações durante o período de internação até a alta/óbito do paciente;
> 
> Será definido como **diagnóstico equivocado** aquele em que houve mais de um diagnóstico de CID-10, contudo, eles fazem parte da mesma categoria de CID-10, de forma que é plausível o equívoco dada a semelhança de sintomas entre os CID-10;
> 
> Será definido como **falha de diagnóstico** aquele em que houve mais de um diagnóstico de CID-10, contudo, eles fazem parte de categorias de CID10 distintas, de forma que embora possam existir sintomas semelhantes entre os CID-10, caberia ao profissional uma análise mais aprofundada antes do diagnóstico.
> 
> **Disclaimer**: Considerando a natureza do banco de dados do SIHSUS, isto é, um Big Data em que inúmeros funcionários do Sistema Único de Saúde possuem acesso e inserem os dados de forma manual em realdades e condições bastante distintas, existe a séria possibildade de erro sistemático, desta forma, a acurácia deste trabalho deve ser considerada com ressalvas.

### Vídeo de apresentação da proposta do projeto
[![Projeto Saúde](https://github.com/grnbatera/Data4health/blob/main/assets/thumb.jpg)](https://www.youtube.com/watch?v=AYZ8yBdD8Ds)


# Perguntas de Pesquisa

> 1) Qual é a extensão do impacto causado pelas falhas de dignóstico médico dentro do Sistema Único de Saúde do Brasil?
> 2) Uma vez conhecida esta extensão, é possível propor um método de predição de casos de falha de diagnóstico em Machine/Deep Learning?
> 3) Sendo possível essa predição, esse método de fato seria útil, de fácil acesso e amigável para os profissionais do SUS?
 

# Bases de Dados

### Bases Estudadas mas Não Adotadas

> |Base de Dados  | Fonte | Descrição|
> |--|--|--|
> | [Cadastro Nacional de Estabelecimentos de Saúde - CNES](https://bigdata-metadados.icict.fiocruz.br/dataset/cadastro-nacional-de-estabelecimentos-de-saude-cnes/resource/7bcf4f68-f2e9-4e06-87b5-229358702efc)  | Fiocruz  | Dados do Cadastro Nacional de Estabelecimentos de Saúde (CNES) reunidos pela Plataforma de Ciência de Dados aplicada à Saúde (PCDaS)|
> | [Estatísticas Sociais - IBGE](https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html)  | IBGE  | Dados referentes ao padrão de vida da população brasileira|
> 

> De forma geral, o uso das duas bases acima mencionadas não foi possível pelo fato do Big Data existente nas bases principais tornar inviável o merge/join/union no ambiente do Google Colab, ao menos para o nível de conhecimento técnico que o grupo possui para o gerenciamento de Big Data em Python com os recursos computacionais oferecdos pelo Colab, assim, dada a inviabilidade, os bancos foram descartados sem que houvesse análise.

### Bases Estudadas Adotadas
> |Base de Dados  | Fonte | Descrição|
> |--|--|--|
> | [Sistema de Informações Hospitalares do SUS - SIHSUS](https://bigdata-metadados.icict.fiocruz.br/dataset/sistema-de-informacoes-hospitalares-do-sus-sihsus/resource/ae85ac54-6734-43b8-a820-6129a854e1ff) | Fiocruz  | Dados do Sistema de Informações Hospitalares do SUS (SIHSUS) reunidos pela Plataforma de Ciência de Dados aplicada à Saúde (PCDaS)|
> 
> * Qual o esquema/dicionário desse banco?
> O banco possui este [Esquemático](https://colab.research.google.com/drive/11QUzieVMyBbsbAaUuPuxQGYpQ7E7WLgo#scrollTo=OQuRCjbjag4X&line=1&uniqifier=1) e este [Dicionário de Variáveis](https://github.com/grnbatera/Data4health/blob/main/assets/Dicion%C3%A1rio%20de%20Vari%C3%A1veis.csv). 
> * O que descobriu sobre esse banco?
> O banco do SIHSUS é o principal utilizado no projeto e trata-se das informações repassadas pelos hospitais que atendem pelo SUS, ele possui 240 variáveis, de forma que havia uma infinidade de informações que poderíamos separar nas seguintes categorias: informações de região, informações administrativas, informações financeiras, informações estatíticas (IBGE) e, por fim, informações sobre o atendimento e dados anomizados dos pacientes. O fato mais marcante e que trouxe problemas significativos e atraso em entrega é o tamanho do banco (240 variáveis e mais de 10 milhões de linhas) sendo necessária uma logística mais sofisticada para lidar com os dados, além disso, infelizmente é um banco onde muitas pessoas podem inserir dados, desta forma, a possibilidade de erro sistemático é muito grande, assim foram encontrados muitas variáveis com pouca informação, problemas de tpo de dados, duplicidade de variáveis e até mesmo variáveis sem definição no próprio dicionário. As variáveis de foco de estudo deste projeto são as que possuem CID-10 definido, a saber: v48 (CID-10 do Diagnóstico Principal), v49 (CID-10 do Diagnóstico Secundário), v82 (CID-10 do Diagnóstico Feito por Socorrista), v104 (CID-10 do Diagnóstico Primário de Causa da Morte) e v105 (CID-10 do Diagnóstico Final de Causa da Morte). 
> * Quais as transformações e tratamentos (e.g., dados faltantes e limpeza) feitos?
> De maneira simplificada, como o maior problema foi o tamanho do banco, considerando as limitações técnicas do grupo e os recursos computacionais disponíveis no Google Colab, a primeira mudança adotada foi separar os dados de forma que um Estado de cada região do Brasl fosse contemplado, assim, houve o split para São Paulo, Bahia, Paraná, Pará e Goiás e a partir daí seria feita uma análise considerando um retrato regional. A seguir, foram analisados os dadoos únicos de cada variável e houve um tratamento colocando-os como categorias numéricas, para facilitar o tratamento pelo Python, foram retiradas as variáveis sem definição formal no dicionário de variáveis e com missing superior a 75% e o corte (5-95)% para retirada de outliers (excetuando-se as variáveis foco de estudo). Onde havia missing ou zeros de categoria, foram substituídos pela string 'vazio' e criando então uma categoria específica. No caso específico das variáveis de estudo, apenas v48 consta em todas as observações, v49 aparece em menos de 20% das observações e v82, v104 e v105 são bem pouco expressivos, de forma que eliminar os missings ou imputar valores seria uma prática complicada, assim, a opção foi categorizar e verificar a influência da categoria 'vazio'.   
> * Apresente aqui uma Análise Exploratória (inicial) sobre esta base.
> Considerando as variáveis foco de estudo, tivemo o seguinte cenário:
> 




----- | -----
![Gráfico 01](https://github.com/grnbatera/IT305G/blob/main/Mídias/g01.png) | ![Gráfico 02](https://github.com/grnbatera/IT305G/blob/main/Mídias/g02.png)
![Gráfico 03](https://github.com/grnbatera/IT305G/blob/main/Mídias/g03.png) | ![Gráfico 04](https://github.com/grnbatera/IT305G/blob/main/Mídias/g04.png)
![Gráfico 05](https://github.com/grnbatera/IT305G/blob/main/Mídias/g05.png) | ![Gráfico 06](https://github.com/grnbatera/IT305G/blob/main/Mídias/g06.png)
![Gráfico 07](https://github.com/grnbatera/IT305G/blob/main/Mídias/g07.png) | ![Gráfico 08](https://github.com/grnbatera/IT305G/blob/main/Mídias/g08.png)
![Gráfico 09](https://github.com/grnbatera/IT305G/blob/main/Mídias/g09.png) | ![Gráfico 10](https://github.com/grnbatera/IT305G/blob/main/Mídias/g10.png)


> |Base de Dados  | Fonte | Descrição|
> |--|--|--|
> | [Classificação Estatística Internacional de Doenças e Problemas Relacionados à Saúde - CID-10](http://www2.datasus.gov.br/cid10/V2008/cid10.htm)  | DataSUS  | CID - 10 em Língua Portuguesa e colaborativa com a OMS|
> 
> Faça uma descrição sobre o que concluiu sobre esta base. Sugere-se que respondam perguntas ou forneçam informações indicadas a seguir:
> * Qual o esquema/dicionário desse banco?
> O banco possui 240 variáveis e mais de 10 milhões de linhas, considerando aproximadamente 1 milhão para cada ano estudado (2008 a 2018). Este é o seu [dicionário]( 
> * O que descobriu sobre esse banco?
> * Quais as transformações e tratamentos (e.g., dados faltantes e limpeza) feitos?
> * Apresente aqui uma Análise Exploratória (inicial) sobre esta base.
> 
> |Base de Dados  | Fonte | Descrição|
> |--|--|--|
> | [Classificação Estatística Internacional de Doenças e Problemas Relacionados à Saúde - CID-10](http://www2.datasus.gov.br/cid10/V2008/cid10.htm)  | DataSUS  | CID - 10 em Língua Portuguesa e colaborativa com a OMS|

# Metodologia
 
> Através da metodologia CRISP-DM, os dados coletados serão reunidos, analisados, limpos, minerados (nestas etapas, haverá a ênfase na análise estatística) e, após isso, através de aprendizado de máquina, se for possível, será criado um modelo de predição de falhas de diagnóstico médico e por fim este modelo será analisado e, se for validado, pode ser implementado como auxílio para profissionais de saúde do SUS.
 

# Ferramentas

> Para este projeto será utilizado um Notebook em  Google Colaboratory e Linguagem de Programação Python 3.0. Por sua vez, dentro da linguagem serão utilizadas as seguintes Bibliotecas: Numpy (para a análise numérica/estatística), Pandas (para manipulação dos dados), MatPlotLib/Seaborn (para visualização dos dados), Keras/Scikit Learn/TensorFlow (para aprendizado de máquina).
> 

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
