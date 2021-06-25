# Ciência e Visualização de Dados - Terceira Entrega

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

Neste projeto, através de dados externos, foram criadas as bases raw, que foram pré-processados, criando as bases intermediárias, que por sua vez foram transformadas e enriquecidas, formando as bases de dados finais (processed) para data mining.

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

Todo o projeto foi elaborado em noteooks do Google Colaboratory, através da Linguagem Python 3.7, num processo em 4 etapas: 

1) *Pré-Processamento do Big Data*: Através do notebook [Projeto_Final_Big_Data](https://github.com/grnbatera/Data4health/blob/main/notebook/Projeto_Final_Big_Data.ipynb), houve a manipulação do arquivo raw para a retirada de varáveis sem descrição no dicionário de variáveis e com índice de NaN maior que 75%, além de criar um subset com todas as cidades dos estados de São Paulo, Bahia, Paraná, Pará e Goiás;
2) *Processamento dos arquivos dos Estados*: Através dos notebooks [SP](https://github.com/grnbatera/Data4health/blob/main/notebook/SP.ipynb), [BA](https://github.com/grnbatera/Data4health/blob/main/notebook/BA.ipynb), [PR](https://github.com/grnbatera/Data4health/blob/main/notebook/PR.ipynb), [PA](https://github.com/grnbatera/Data4health/blob/main/notebook/PA.ipynb) E [GO](https://github.com/grnbatera/Data4health/blob/main/notebook/GO.ipynb) foram processados os arquivos dos estados de São Paulo, Bahia, Paraná, Pará e Goiás, respectivamente, na busca de um retrato das regiões do país. Através destes notebooks, os arquivos foram processados e foram analisadas as características estatísticas, correlações, p-valor e análise gráfica por scatter plots, box plots e q-q plots;
3) *Análise Estatístca das Falhas de Diagnóstico*: Através do notebook [Análise_das_Falhas_de_Diagnóstico](https://github.com/grnbatera/Data4health/blob/main/notebook/An%C3%A1lise_das_Falhas_de_Diagn%C3%B3stico.ipynb), foi realizada uma análise de caracterização estatística do objeto de estudo desse projeto, que são as falhas de diagnóstico médico. 
4) *Aprendizagem de Máquina*: Para esta etapa, os notebooks do Google Colab correspondem a criação de um classificador para as classes 0 (diagnóstico equivocado) e 1 (falha de diagnóstico), assim, os resultados podem ser vistos para  [SP](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_SP.ipynb), [BA](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_BA.ipynb), [PR](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_PR.ipynb), [PA](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_PA.ipynb) E [GO](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_GO.ipynb).


## `src`

Como o projeto foi todo realizado em notebook do Google Colaboratory , não houve a necessidade de código fonte fora dos notebooks, todavia, nesta pasta existe a documentação acerca do [Google Colab](https://github.com/grnbatera/Data4health/tree/main/src).

## `assets`

Na pasta assets encontram-se as figuras referenciadas neste projeto, a apresentação do projeto em PDF, os dicionários de varáveis dos bancos external, raw, interim e  processed e um dicionário das categorias e subcategorias do CID-10.


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
> A principal motivação da equipe neste projeto científico é contribuir para um melhor atendimento aos pacientes, que são os principais afetados, auxiliar os profissionais médicos alertando-os sobre a possibilidade de falha de diagnóstico e, por fim, auxiliar no uso mais racional de recursos, evitando as custas causadas pelas falhas de diagnóstico.
> 
> Considerando-se que não há disponibilidade de trabalhos relativos ao gerenciamento das falhas de diagnóstico no SUS, utilizar o aprendizado de máquina para criar um classificador que auxilie na predição deste tipo de falha, que ajude a compreender as features que levam a este tipo de diagnóstico e, além disso, ter um registro mais científico deste processo através da metodologia CRISP-DM seria uma boa solução neste contexto.
>     
>Após a análise, o projeto esbarrou em dificuldades técnicas proporcionadas pelo fato dos dados disponíveis se tratarem de big data, assim, como este tipo de dado demanda abordagem específica e a expertise do grupo neste tipo de dado ainda é limitada, optou-se pela divisão da base de dados e consideramos para estudos os Estados de São Paulo, Bahia, Paraná, Pará e Goiás, representando as 5 regiões do Brasil, assim, encontramos resultados parciais e podemos concluir para este cenário que:
>
>1) Através de análise exploratória/estatítistica: as falhas de diagnóstico e os diagnósticos equivocados são de fato exceções e ocorrem mais para homens brancos e pardos (quando há declaração de raça) e o tempo médio de internação geralmente dobra quando há falha de diagnóstico e esta leva ao óbito do(a) paciente.  Em termos de óbito, as falhas de diagnóstico tem menor representatividade que os diagnósticos equivocados;
>
>2) Análise de aprendizagem de máquina: a princípio, os diagnósticos foram colocados em 3 classes: diagnóstico equivocado (0), falha de diagnóstico (1) e diagnóstico correto (2), contudo, através dos modelos de machine learning do scikit-learn, todos os resultados de classificação foram enviesados para a classe diagnóstico correto, uma vez que esta representa a grande maioria, desta forma, para evitar esse enviesamento, reduziu-se apenas para as classes 0 e 1, desta forma, foi possível encontrar um classificador eficiente por Gradient Boosting, mas que devido a redução de classes, basicamente ele nos ajudou a compreender melhor a importância das features para os tipos de diganóstico. 


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

# Vídeos do Projeto

**Vídeo da Proposta** | **Vídeo da Apresentação Final**
----- | -----
[![Projeto Saúde](https://github.com/grnbatera/Data4health/blob/main/assets/thumb.jpg)](https://www.youtube.com/watch?v=AYZ8yBdD8Ds) | [![Projeto Saúde 2](https://github.com/grnbatera/Data4health/blob/main/assets/thumb2.jpg)](https://youtu.be/V8YKLD1h4J0)

# Slides do Projeto

## Slides da Proposta
[Proposta](https://github.com/grnbatera/Data4health/blob/main/assets/Apresenta%C3%A7%C3%A3o_Proposta.pdf)

## Slides da Apresentação Final
[Apresentação Final](https://github.com/grnbatera/Data4health/blob/main/assets/Apresenta%C3%A7%C3%A3o_Final.pdf)

# Introdução e Referenciais de Teóricos
> Contextualização do projeto:
> 
>As falhas de diagnóstico médico são responsáveis, num primeiro momento, por consequências aos indivíduos que foram vitimadas por estas falhas, todavia, até onde se estendem essas consequências? 
>
>Neste contexto, o projeto busca compreender melhor quais são os impactos que as falhas trazem ao Sistema Único de Saúde, se é possível mitigar os resultados negativos e auxiliar na predição de casos de falha de diagnóstico através do Aprendizado de Máquina.
>
> Caracterização do problema:
>
>De forma geral, sabe-se que ocorrem eventuais falhas de diagnóstico durante os atendimentos no SUS, contudo, não há uma caracterização mais científica a este respeito, assim sendo, este projeto busca preeencher em algum grau esta lacuna.
>
> Motivação:
> 
> A principal motivação da equipe neste projeto científico é contribuir para um melhor atendimento aos pacientes, que são os principais afetados, auxiliar os profissionais médicos alertando-os sobre a possibilidade de falha de diagnóstico e, por fim, auxiliar no uso mais racional de recursos, evitando as custas causadas pelas falhas de diagnóstico.
>
> Relevância:
> 
>Considerando-se a possibilidade de redução de perdas humanas, perdas financeiras e a falta de dados científicos brasileiros no tema, acreditamos que o projeto seja relevante.
>
> Trabalhos relacionados:
> 
>Para o SUS não foram encontrados trabalhos relacionados, desta forma, foram tomados por base os seguintes trabalhos:
>
>[1]	Singh H, Schiff GD, Graber ML, Onakpoya I, Thompson MJ. The global burden of diagnostic errors in primary care. BMJ Qual Saf. 2017; 26(6):484-94.
>
>[2]	Care CoDEiH, Services BoHC, Medicine Io, The National Academies of Sciences Eg, and Medicine. Improving Diagnosis in Health Care. 2015.
>
>[3]	Kassirer JP. Our stubborn quest for diagnostic certainty. A cause of excessive testing. N Engl J Med. 1989; 320(22):1489-91.
>
> Indicação da análise proposta:
> 
>Seguindo a metodologia do CRISP-DM, duas análises principais ocorreram, a análise exploratória/estatística na etapa de Data Mining e a análise por aprendizagem de máquina, na etapa de Modeling.
>
> Indicação dos resultados alcançados
> 
> Através de análise exploratória/estatítistica: as falhas de diagnóstico e os diagnósticos equivocados são de fato exceções e ocorrem mais para homens brancos e pardos (quando há declaração de raça) e o tempo médio de internação geralmente dobra quando há falha de diagnóstico e esta leva ao óbito do(a) paciente.  Em termos de óbito, as falhas de diagnóstico tem menor representatividade que os diagnósticos equivocados;
> 
> Análise de aprendizagem de máquina: a princípio, os diagnósticos foram colocados em 3 classes: diagnóstico equivocado (0), falha de diagnóstico (1) e diagnóstico correto (2), contudo, através dos modelos de machine learning do scikit-learn, todos os resultados de classificação foram enviesados para a classe diagnóstico correto, uma vez que esta representa a grande maioria, desta forma, para evitar esse enviesamento, reduziu-se apenas para as classes 0 e 1, desta forma, foi possível encontrar um classificador eficiente por Gradient Boosting, mas que devido a redução de classes, basicamente ele nos ajudou a compreender melhor a importância das features para os tipos de diganóstico.
>


# Perguntas de Pesquisa

> 1) Qual é a extensão do impacto causado pelas falhas de dignóstico médico dentro do Sistema Único de Saúde do Brasil?
> 2) Uma vez conhecida esta extensão, é possível propor um método de predição de casos de falha de diagnóstico em Machine/Deep Learning?
> 3) Sendo possível essa predição, esse método de fato seria útil, de fácil acesso e amigável para os profissionais do SUS?

# Objetivos do Projeto:
>
>Este projeto possui por objetivo compreender melhor quais são os impactos que as falhas trazem ao Sistema Único de Saúde, se é possível mitigar os resultados negativos e auxiliar na predição de casos de falha de diagnóstico através do Aprendizado de Máquina.
>
 
# Metodologia
 
> Através da metodologia CRISP-DM, os dados coletados serão reunidos, analisados, limpos, minerados (nestas etapas, haverá a ênfase na análise estatística) e, após isso, através de aprendizado de máquina, se for possível, será criado um modelo de predição de falhas de diagnóstico médico e por fim este modelo será analisado e, se for validado, pode ser implementado como auxílio para profissionais de saúde do SUS.


## Bases de Dados e Evolução

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
> O banco do SIHSUS é o principal utilizado no projeto e trata-se das informações repassadas pelos hospitais que atendem pelo SUS, ele possui 240 variáveis, de forma que havia uma infinidade de informações que poderíamos separar nas seguintes categorias: informações de região, informações administrativas, informações financeiras, informações estatíticas (IBGE) e, por fim, informações sobre o atendimento e dados anomizados dos pacientes. O fato mais marcante e que trouxe problemas significativos e atraso em entrega é o tamanho do banco (240 variáveis e mais de 10 milhões de linhas) sendo necessária uma logística mais sofisticada para lidar com os dados, além disso, infelizmente é um banco onde muitas pessoas podem inserir dados, desta forma, a possibilidade de erro sistemático é muito grande, assim foram encontradas muitas variáveis com pouca informação, problemas de tipologia dos dados, duplicidade de variáveis e até mesmo variáveis sem definição no próprio dicionário. As variáveis de foco de estudo deste projeto são as que possuem CID-10 definido, a saber: v48 (CID-10 do Diagnóstico Principal), v49 (CID-10 do Diagnóstico Secundário), v82 (CID-10 do Diagnóstico Feito por Socorrista), v104 (CID-10 do Diagnóstico Primário de Causa da Morte) e v105 (CID-10 do Diagnóstico Final de Causa da Morte). 
> * Quais as transformações e tratamentos (e.g., dados faltantes e limpeza) feitos?
> De maneira simplificada, como o maior problema foi o tamanho do banco, considerando as limitações técnicas do grupo e os recursos computacionais disponíveis no Google Colab, a primeira mudança adotada foi separar os dados de forma que um Estado de cada região do Brasl fosse contemplado, assim, houve o split para São Paulo, Bahia, Paraná, Pará e Goiás e a partir daí seria feita uma análise considerando um retrato regional. A seguir, foram analisados os dados únicos de cada variável e houve um tratamento colocando-os como categorias numéricas, para facilitar o tratamento pelo Python, foram retiradas as variáveis sem definição formal no dicionário de variáveis e com missing superior a 75% e o corte (5-95)% para retirada de outliers (excetuando-se as variáveis foco de estudo). Onde havia missing ou zeros de categoria, foram substituídos pela string 'vazio' e criando então uma categoria específica. No caso específico das variáveis de estudo, apenas v48 consta em todas as observações, v49 aparece em menos de 20% das observações e v82, v104 e v105 são bem pouco expressivos, de forma que eliminar os missings ou imputar valores seria uma prática complicada, assim, a opção foi categorizar e verificar a influência da categoria 'vazio'.   
> * Apresente aqui uma Análise Exploratória (inicial) sobre esta base.
> Considerando as variáveis foco de estudo, tivemos o seguinte cenário preliminar:
> * Missing para as variáveis de interesse:

Matriz de Missing | Total de Missing
----- | -----
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/spmissing1.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/spmissing2.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/bamissing1.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/bamissing2.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/prmissing1.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/prmissing2.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/pamissing1.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/pamissing2.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/gomissing1.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/gomissing2.png)

> * Scatterplots: Nos links, temos os scatterplots de [São Paulo](https://colab.research.google.com/drive/11QUzieVMyBbsbAaUuPuxQGYpQ7E7WLgo#scrollTo=wXE5zeL6SQ3Z&line=4&uniqifier=1), [Bahia](https://colab.research.google.com/drive/1QUllaWfJqJJtX0uoI0sG9Bk6yuN8UEqq#scrollTo=wXE5zeL6SQ3Z&line=1&uniqifier=1), [Paraná](https://colab.research.google.com/drive/1Zwbb-r1J8za-85WLUjj7PP19BI8McT6s#scrollTo=wXE5zeL6SQ3Z&line=1&uniqifier=1), [Pará](https://colab.research.google.com/drive/1fBKX7jXjrNBEQ8buTe2UydNJEAPHPz2e#scrollTo=wXE5zeL6SQ3Z&line=5&uniqifier=1), [Goiás](https://colab.research.google.com/drive/1_gEofDZiDsGX6L0BTPhjxAiPu68_nLdE#scrollTo=wXE5zeL6SQ3Z&line=3&uniqifier=1)
> * Boxplots: Nos links, temos os boxplots de [São Paulo](https://colab.research.google.com/drive/11QUzieVMyBbsbAaUuPuxQGYpQ7E7WLgo#scrollTo=0PaExDnuf8S4&line=1&uniqifier=1), [Bahia](https://colab.research.google.com/drive/1QUllaWfJqJJtX0uoI0sG9Bk6yuN8UEqq#scrollTo=MsB8VwCPgU2C&line=4&uniqifier=1), [Paraná](https://colab.research.google.com/drive/1Zwbb-r1J8za-85WLUjj7PP19BI8McT6s#scrollTo=0PaExDnuf8S4&line=4&uniqifier=1), [Pará](https://colab.research.google.com/drive/1fBKX7jXjrNBEQ8buTe2UydNJEAPHPz2e#scrollTo=bcMF1w-1f3BW&line=5&uniqifier=1), [Goiás](https://colab.research.google.com/drive/1_gEofDZiDsGX6L0BTPhjxAiPu68_nLdE#scrollTo=KHm7kc7zdyZX&line=1&uniqifier=1) 
> * Q-Q plots: Nos links, temos os Q-Q plots de [São Paulo](https://colab.research.google.com/drive/11QUzieVMyBbsbAaUuPuxQGYpQ7E7WLgo#scrollTo=Qtw3A4I9fIAR&line=4&uniqifier=1), [Bahia](https://colab.research.google.com/drive/1QUllaWfJqJJtX0uoI0sG9Bk6yuN8UEqq#scrollTo=Ktcpy5QtfNoY&line=4&uniqifier=1), [Paraná](https://colab.research.google.com/drive/1Zwbb-r1J8za-85WLUjj7PP19BI8McT6s#scrollTo=Qtw3A4I9fIAR&line=3&uniqifier=1), [Pará](https://colab.research.google.com/drive/1fBKX7jXjrNBEQ8buTe2UydNJEAPHPz2e#scrollTo=Y1bR0DAJexeS&line=4&uniqifier=1), [Goiás](https://colab.research.google.com/drive/1_gEofDZiDsGX6L0BTPhjxAiPu68_nLdE#scrollTo=4fjZ6Mw7Jfrq&line=3&uniqifier=1) 
> * Heatmap de Correlação para as varáveis de interesse: Nos links, temos os heatmaps de correlaçãoo para as varáveis v48, v49, v82, v104 e v105 de [São Paulo](https://colab.research.google.com/drive/11QUzieVMyBbsbAaUuPuxQGYpQ7E7WLgo#scrollTo=jg7VfXftOTBf&line=1&uniqifier=1), [Bahia](https://colab.research.google.com/drive/1QUllaWfJqJJtX0uoI0sG9Bk6yuN8UEqq#scrollTo=jg7VfXftOTBf&line=2&uniqifier=1), [Paraná](https://colab.research.google.com/drive/1Zwbb-r1J8za-85WLUjj7PP19BI8McT6s#scrollTo=jg7VfXftOTBf&line=1&uniqifier=1), [Pará](https://colab.research.google.com/drive/1fBKX7jXjrNBEQ8buTe2UydNJEAPHPz2e#scrollTo=jg7VfXftOTBf&line=2&uniqifier=1), [Goiás](https://colab.research.google.com/drive/1_gEofDZiDsGX6L0BTPhjxAiPu68_nLdE#scrollTo=jg7VfXftOTBf&line=2&uniqifier=1) 

> Com base nesta análise preliminar foi possível constatar que embora as variáveis de foco de estudo tivessem grande diferença com relação a presença de dados, houve a correlação de algumas delas com outras variáveis do banco de forma que é possível um estudo mais aprofundado para verificar se de fato essas correlações se verificam, uma vez que graficamente não foi possível corroborar, já que as variáveis categóricas precisam de uma melhor análise com regressão logística e o fato de ser Big Data complicou um tanto fazer scatterplots considerando este tipo de regressão com os recursos computacionais disponíveis. 

> |Base de Dados  | Fonte | Descrição|
> |--|--|--| 
> | [Classificação Estatística Internacional de Doenças e Problemas Relacionados à Saúde - CID-10](http://www2.datasus.gov.br/cid10/V2008/cid10.htm)  | DataSUS  | CID - 10 em Língua Portuguesa e colaborativa com a OMS|

> De forma geral, o banco de dados do CID-10 é mais um dicionário que um banco de dados propriamente, de forma, que após a análise constatamos nosso equívoco em elencar este dicionário como uma base de dados. Todavia, através dele foi possível compreender a lógica de funcionamento do CID-10. A hierarquia é composta por Capítulo > Grupo > Categoria > Subcategoria, assim, o diagnóstico final seria uma subcategoria. Um exemplo simples seria: subcategoria A010 (febre tifóide), categoria A01 (febres tifóides e paratifóides), grupo A00 a A09 (doenças infecciosas intestinais), Capítulo I (A00 a	B99 - Algumas doenças infecciosas e parasitárias). Este conhecimento foi fundamental para fazer uma limitação no que seria uma possível falha de diagnóstico e a limitação escolhida foi a subcategoria, uma vez que ela engloba uma possibilidade de 10 doenças distintas mas com sintomas semelhantes, passíveis de equívoco, logo, a possível falha estaria num segundo diagnóstico com categoria distinta da primeira, sinalizando que o profissional deveria fazer uma investigação mais profunda antes de fechar o diagnóstico primário. 

### Integração entre Bases e Análise Exploratória

> De uma forma geral, após a integração da base de dados do SIHSUS com o dicionário de CID-10 por left join nas variáveis v48, v49, v82, v104 e v105 e aplicando as definições de diagnóstico correto, diagnóstico equivocado e falha de diagnóstico, foi possível consolidar o seguinte resultado: 

Gráficos Estatísticos | Gráficos Estatísticos
----- | -----
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/g1.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/g2.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/g3.png) | 


> Além disso, existem mais métricas calculadas para [São Paulo](https://colab.research.google.com/drive/1nhI7yKvV7cVWu3cgeNyo7dWTQleq1j5m#scrollTo=RUXNeQjmh8jV&line=14&uniqifier=1), [Bahia](https://colab.research.google.com/drive/1nhI7yKvV7cVWu3cgeNyo7dWTQleq1j5m#scrollTo=kZ3reexd7knR&line=5&uniqifier=1), [Paraná](https://colab.research.google.com/drive/1nhI7yKvV7cVWu3cgeNyo7dWTQleq1j5m#scrollTo=gfMr3RrlBk7L&line=9&uniqifier=1), [Pará](https://colab.research.google.com/drive/1nhI7yKvV7cVWu3cgeNyo7dWTQleq1j5m#scrollTo=6szGzNcUFR8y&line=11&uniqifier=1), [Goiás](https://colab.research.google.com/drive/1nhI7yKvV7cVWu3cgeNyo7dWTQleq1j5m#scrollTo=6szGzNcUFR8y&line=11&uniqifier=1) 
 
>Após a análise de resultados, foi percepitível que a grande maioria dos atendimentos notificados representam diagnósticos corretos, salvo o fato de que eventualmente poderiam ter existir erros na inserção de dados nos bancos. Os casos onde ocorreu diagnóstico equivocado, isto é, um diagnóstico dentro de uma mesma categoria de CID-10 do diagnóstico possuem ordem de grandeza geralmente menor que as falhas de diagnóstico, sendo, portanto, casos menos comuns. Além disso, temos o seguinte cenário:
>
>**Quando houve óbito, os CIDs mais frequentes nos equívocos e falhas foram**:
>
>* Em SP: a) Equívocos: A419 (Septicemia não especificada), J189 (Pneumonia não especificada), b) Falhas: Z851 (História pessoal de neoplasia maligna de traquéia, brônquio e pulmão), Z854 (História pessoal de neoplasia maligna de órgãos genitais);
>* Em BA: a) Equívocos: I64 (Acidente vascular cerebral, não especificado como hemorrágico ou isquêmico), A419 (Septicemia não especificada),  b) Falhas: Z851 (História pessoal de neoplasia maligna de traquéia, brônquio e pulmão), Z852 (História pessoal de neoplasia maligna de outros órgãos respiratórios e intratorácicos);
>* Em PR: a) Equívocos:  A419 (Septicemia não especificada), I64 (Acidente vascular cerebral, não especificado como hemorrágico ou isquêmico), b) Falhas: Z851 (História pessoal de neoplasia maligna de traquéia, brônquio e pulmão), Z914 (História pessoal de trauma psicológico não classificado em outra parte);
>* Em PA: a) Equívocos:  I64 (Acidente vascular cerebral, não especificado como hemorrágico ou isquêmico), A419 (Septicemia não especificada),  b) Falhas: Y349 (Fatos ou eventos não especificados e intenção não determinada - local não especificado), Y849 (Reação anormal em paciente ou complicação tardia, causadas por procedimento médico, não especificado, sem menção de acidente durante o procedimento);
>* Em GO: a) Equívocos:  J189 (Pneumonia não especificada), I64 (Acidente vascular cerebral, não especificado como hemorrágico ou isquêmico),  b) Falhas: Y211 (Afogamento e submersão, intenção não determinada - habitação coletiva), Y356 (Intervenção legal envolvendo o uso de outros meios especificados);
>
>**Quando não houve óbito, os CIDs mais frequentes nos equívocos e falhas foram**:
>
>* Em SP: a) Equívocos: G09 (Seqüelas de doenças inflamatórias do sistema nervoso central), G821 (Paraplegia espástica), b) Falhas: Z962 (Presença de implante otológicos e audiológicos), Z970 (Presença de olho artificial);
>* Em BA: a) Equívocos: X939 (Agressão por meio de disparo de arma de fogo de mão - local não especificado), V209 (Motociclista traumatizado em colisão com um pedestre ou um animal - motociclista não especificado traumatizado em um acidente de trânsito),  b) Falhas: Z889 (História pessoal de alergia a drogas, medicamentos e substâncias biológicas não especificadas), Z916 (História pessoal de outros traumas físicos);
>* Em PR: a) Equívocos:  W999 (Exposição a outros fatores ambientais artificiais e aos não especificados - local não especificado), W199 (Queda sem especificação - local não especificado) , b) Falhas: Z915 (História pessoal de auto agressão), Z931 (Gastrostomia); 
>* Em PA: a) Equívocos:  W999 (Exposição a outros fatores ambientais artificiais e aos não especificados - local não especificado), H431 (Hemorragia do humor vítreo) , b) Falhas: Z574 (Exposição ocupacional a agentes tóxicos na agricultura), Z599 (Circunstâncias não especificadas econômicas ou de habitação); 
>* Em GO: a) Equívocos:  W189 (Outras quedas no mesmo nível - local não especificado), V299 (Motociclista [qualquer] traumatizado em um acidente de trânsito não especificado) , b) Falhas: Z722 (Uso de droga), Z811 (História familiar de abuso de álcool).
>
>Além disso, pelos dados, ficou evidente que a regionalização dos diagnósticos em si seria inevitável, já que os comportamentos de CID-10 variam bastante conforme o estado. Todavia, alguns outros comportamentos atendem a um certo padrão, por exemplo:
>
>As falhas de diagnóstico e os diagnósticos equivocados ocorrem mais para homens brancos e pardos (quando há declaração de raça) e o tempo médio de internação geralmente dobra quando há falha de diagnóstico e esta leva ao óbito do(a) paciente.  Em termos de óbito, as falhas de diagnóstico tem menor representatividade que os diagnósticos equivocados.  
>

# Análises Realizadas
>Seguindo a metodologia CRISP-DM, foram seguidas as seguintes etapas de análise:
>
>*Business Understand*: nesta etapa, foi cosiderada a metodologia para chegarmos a variável v258, ou seja, Análise de Falha de Diagnóstco, onde foi possível elaborar que  seria definido como **diagnóstico equivocado** aquele em que houve mais de um diagnóstico de CID-10, contudo, eles fazem parte da mesma categoria de CID-10, de forma que é plausível o equívoco dada a semelhança de sintomas entre os CID-10 e seria definido como **falha de diagnóstico** aquele em que houve mais de um diagnóstico de CID-10, contudo, eles fazem parte de categorias de CID10 distintas, de forma que embora possam existir sintomas semelhantes entre os CID-10, caberia ao profissional uma análise mais aprofundada antes do diagnóstico. A maior dificuldade enfrentada pelo grupo nesta etapa foi establecer um critério válido uma vez que embora seja intuitivo, em termos de CID-10, não há definições mais formais para este tipo de situação, contudo, ao atribuir o Grupo de CID-10, tornou o objetivo plausível;
>
>*Data Understanding*: nesta etapa ficou estabelecido que as bases de dados: [Sistema de Informações Hospitalares do SUS - SIHSUS](https://bigdata-metadados.icict.fiocruz.br/dataset/sistema-de-informacoes-hospitalares-do-sus-sihsus/resource/ae85ac54-6734-43b8-a820-6129a854e1ff), [Classificação Estatística Internacional de Doenças e Problemas Relacionados à Saúde - CID-10](http://www2.datasus.gov.br/cid10/V2008/cid10.htm), [Cadastro Nacional de Estabelecimentos de Saúde - CNES](https://bigdata-metadados.icict.fiocruz.br/dataset/cadastro-nacional-de-estabelecimentos-de-saude-cnes/resource/7bcf4f68-f2e9-4e06-87b5-229358702efc) e [Estatísticas Sociais - IBGE](https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html) seriam elencadas na busca de correlações que levariam a uma compreensão do que ocorreria coma a variável dependente  Análise de Falha de Diagnóstco (v258). Como as bases de dados eram públicas, sem restrições de divulgação e já anomizadas, seriam ideias para a realização do nosso objetivo. Nesta etapa, a maior dificuldade foi elencar possíveis features que pudessem de fato explicar o que ocorria no SUS, todavia, o ambiente hospitalar possuía documentação suficiente e ainda que fosse um retrato de uma parcela do SUS, seria suficiente para uma prova de conceito;
>
>*Data Preparation*: nesta etapa começamos de fato a trabalhar com os bancos de dados e fomos colocados frente a um novo desafio: trabalhar com Big Data. Nossa falta de experiência com este tipo de dados foi responsável pela primeira grande dificuldade do projeto, que poderia inclusive nos fazer mudar radicalmente de objetivo, contudo, assumimos as consequências de nossa escolha e seguimos o projeto com algumas modificações: ao invés de analisar o SUS como um todo, pegar os maiores Estados das Regiões do Brasil, tentando manter um retrato do SUS no Brasil, mas com um significativa redução do consumo de recursos computacionais. Além disso, as bases [Cadastro Nacional de Estabelecimentos de Saúde - CNES](https://bigdata-metadados.icict.fiocruz.br/dataset/cadastro-nacional-de-estabelecimentos-de-saude-cnes/resource/7bcf4f68-f2e9-4e06-87b5-229358702efc) e [Estatísticas Sociais - IBGE](https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html) foram descartadas sem que houvesse uma análise prévia, já que eram bases mais secundárias que só ajudariam a inserir features para melhorar a análise, mas cujo custo computacional seria bastante grande. Uma vez tomadas as decisões, era preciso lidar com os recursos computacionais do Google Colab e isto nos levou à computação paralela através da biblioteca Dask. Com o auxílio do Dask Dataframe fizemos então a manipulação dos arquivos raw para a retirada de varáveis sem descrição no dicionário de variáveis e com índice de NaN maior que 75%, além de criar um subset com todas as cidades dos Estados de São Paulo, Bahia, Paraná, Pará e Goiás, regularizar os tipos existentes em cada variável, fazer a deduplicação e, por fim, categorizar as variáveis uma vez que no universo de centenas de milhares de observações, os valores se comportavam de forma categórica;
>
>*Data Mining*: nesta etapa, foram realizadas as análises estatísticas do banco, contudo, mesmo utilizando o Dask Dataframe, para que houvesse o cálculo dos parâmetros estatísticos, gráficos de scatterplot, histogrmas, boxplots, q-q plots e  heatmaps de correlação era necessário o uso do dask.Dataframe.compute() e isto significava um uso de recursos computacional toda vez que era necessário fazer o cálculo, assim, para evitar esse tipo de situação, o Dask Dataframe computado era convertido em arquivo pickle, de forma que qualquer variável do Google Colab pode ser baixado em formato pickle e depois reinserido no código sem o uso intenso de recurso computacional. Este método estava longe de ser o ideal, era uma computação pseudo-paralela que conseguimos inferir com nossa pouca experiência em paralelismo, de forma que todo o processo foi bastante custoso e levou a notebooks rodando por mais de 36 horas, dado o tamanho dos dados, e levou ao atraso da entrega 02, mas foi possível a realização das análises e principalmente ao fazer as correlações por Spearman da variável v258, que representa a variável dependente deste projeto, é possível verificar que poucas variáveis possuem correlação posivita e negativa maior que 0.3, de forma que a maioria das variáveis estão fracamente correlacionadas ou não correlacionadas com a variável dependente, conforme mostra a figura:

Heatmap de correlação para v258 |
----- |
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/v258a.png)

>
>Código de computação do Dask Dataframe e dumping em arquivo pickle:

~~~python
import dask
from dask import dataframe
import pickle
from google.colab import files

full = dask.Dataframe(full, npartitions = 245).compute()

with open('full.pkl','wb') as f:
  pickle.dump(relacoes,f,pickle.HIGHEST_PROTOCOL)
files.download('full.pkl')
~~~

>*Modeling*: na etapa seguinte, foi realizado o aprendizado de máquina em busca de um modelo onde pudéssemos compreender melhor a influência das features na variável dependente, todavia, o problema do Big Data ainda persistia, assim, não era possível manter os cálculos dos modelos de Machine Learning no mesmo sistema da etapa de *Data Mining*, era preciso evoluir e essa evolução aconteceu graças aos Laboratórios 05 e 06 da disciplina, onde fomos apresentados ao CUDA e ao uso da GPU. Desta forma, conseguimos chegar ao [!RAPIDS](https://colab.research.google.com/drive/1rY7Ln6rEE1pOlfSHCYOVaqt8OvDO35J0#forceEdit=true&offline=true&sandboxMode=true) e com ele foi possível alterar o kernel do Google Colab de forma que era possível forçar o uso da GPU e, também, otimizar os processos via CUDA. Além disso, foi possível melhorar o uso do paralelismo através do Dask CUDA Dataframe (Dask_cuDF), ter um controle melhor do uso da RAM através do garbage collect e a biblioteca Scikit-Learn é bastante otimizada para o uso com CUDA e computação paralela, de forma que temos, o código de exemplo:

~~~python
import gc
import dask
from dask_ml.model_selection import train_test_split

t1 = dask.Dataframe(full, npartitions = 245)
xtreino, xteste, ytreino, yteste = train_test_split((t1.iloc[:,0:191]),(t1.iloc[:,191:]), test_size = 0.3,random_state=66,shuffle=True)
n=gc.collect()

import sklearn
from sklearn.ensemble import GradientBoostingClassifier
import joblib
from joblib import parallel_backend

model = GradientBoostingClassifier(n_estimators=100)
with parallel_backend('dask'):
  model.fit(xtreino,ytreino)
n=gc.collect()  
~~~
>
>Embora tenha ocorrido muita evolução em termos computacionais, com um uso mais racional dos recursos computacionais e notebooks com Big Data sendo rodados em 4 a 5h oras, muito diferente das 36h anteriores, ainda assim havia uma limitação no próprio banco de dados, isto é, a variável dependente possuía 3 categorias: diagnóstico equivocado (0), falha de diagnóstico (1) e diagnóstico correto (2), contudo, como a maioria dos dados era diagnóstico correto (2), ocorria enviesamento dos modelos de classificador por machine learning para o diagnóstico correto (2). Desta forma, optamos por retirar esta categoria e utilizarmos apenas [0,1], com esta configuração houve um melhor desempenho dos modelos de machine learning e houve um destaque do classificador por Gradient Boosting.
>
>*Evaluation*: embora o classificador por Gradient Boosting tenha sido o melhor nas avaliações com dados de treino (70%) e dados de teste (30%), com boa acurácia, boa sensisbilidade e boa especificidade, como foi necessária a retirada da categoria  diagnóstico correto (2), não é possível dizer que o modelo atende a proposta de classificar todas as categorias, assim, ele serviu para que tivéssemos a noção da importância das features no diagnóstico equivocado e na falha de diagnóstico. Acreditamos que Deep Learning possa ter um melhor desempenho, contudo, bibliotecas como o Tensorflow e o Pytorch que poderiam implementar uma DNN simples, não se adequaram bem no ambiente RAPIDS com computação paralela no Google Colab. O Scikit-Learn possui o MPL e poderia fazer uma rede neural, todavia, como ainda não temos uma boa noção da melhor arquitetura de uma DNN para este tipo de dado, de forma que não nos sentimos confortáveis para ir para um Deep Learning layer por layer;
>
>*Deployment*: como o modelo de machine learning encontrado não atende todas as classificações, não foi possível criar um sistema que pudesse auxiliar plenamente no diagnóstico médico no ambiente do SUS, todavia, é possível a passagem da aprendizagem de que diagnósticos equivocados levam mais a óbito, sendo uma boa prática uma melhor análise antes do fechamento de diagnóstico, além disso, pelas features do classificador foi possível perceber que existem 3 categorias que mais influenciam: o hospital e seu tipo (existem hospitais com maior incidência), informações técnicas (doenças com mais incidência, tempo de internação) e informação do paciente (condição sócio-econômica).
>  

# Ferramentas

> Para este projeto foram utilizados Notebooks em  Google Colaboratory com GPU, com kernel implementada por RAPIDS e computação paralela na Linguagem de Programação Python 3.7. Por sua vez, dentro da linguagem foram utilizadas as seguintes Bibliotecas: Numpy (para a análise numérica/estatística), Dask e Pandas (para manipulação dos dados), MatPlotLib/Seaborn (para visualização dos dados), Scikit Learn/Dask-ML (para aprendizado de máquina), CUDA para processos em GPU e Garbage Collect para manutenção do uso da RAM.
> 
# Resultados
>
> Em termos estatísticos, os resultados econtrados foram:
> 
>**Quando houve óbito, os CIDs mais frequentes nos equívocos e falhas foram**:
>
>* Em SP: a) Equívocos: A419 (Septicemia não especificada), J189 (Pneumonia não especificada), b) Falhas: Z851 (História pessoal de neoplasia maligna de traquéia, brônquio e pulmão), Z854 (História pessoal de neoplasia maligna de órgãos genitais);
>* Em BA: a) Equívocos: I64 (Acidente vascular cerebral, não especificado como hemorrágico ou isquêmico), A419 (Septicemia não especificada),  b) Falhas: Z851 (História pessoal de neoplasia maligna de traquéia, brônquio e pulmão), Z852 (História pessoal de neoplasia maligna de outros órgãos respiratórios e intratorácicos);
>* Em PR: a) Equívocos:  A419 (Septicemia não especificada), I64 (Acidente vascular cerebral, não especificado como hemorrágico ou isquêmico), b) Falhas: Z851 (História pessoal de neoplasia maligna de traquéia, brônquio e pulmão), Z914 (História pessoal de trauma psicológico não classificado em outra parte);
>* Em PA: a) Equívocos:  I64 (Acidente vascular cerebral, não especificado como hemorrágico ou isquêmico), A419 (Septicemia não especificada),  b) Falhas: Y349 (Fatos ou eventos não especificados e intenção não determinada - local não especificado), Y849 (Reação anormal em paciente ou complicação tardia, causadas por procedimento médico, não especificado, sem menção de acidente durante o procedimento);
>* Em GO: a) Equívocos:  J189 (Pneumonia não especificada), I64 (Acidente vascular cerebral, não especificado como hemorrágico ou isquêmico),  b) Falhas: Y211 (Afogamento e submersão, intenção não determinada - habitação coletiva), Y356 (Intervenção legal envolvendo o uso de outros meios especificados);
>
>**Quando não houve óbito, os CIDs mais frequentes nos equívocos e falhas foram**:
>
>* Em SP: a) Equívocos: G09 (Seqüelas de doenças inflamatórias do sistema nervoso central), G821 (Paraplegia espástica), b) Falhas: Z962 (Presença de implante otológicos e audiológicos), Z970 (Presença de olho artificial);
>* Em BA: a) Equívocos: X939 (Agressão por meio de disparo de arma de fogo de mão - local não especificado), V209 (Motociclista traumatizado em colisão com um pedestre ou um animal - motociclista não especificado traumatizado em um acidente de trânsito),  b) Falhas: Z889 (História pessoal de alergia a drogas, medicamentos e substâncias biológicas não especificadas), Z916 (História pessoal de outros traumas físicos);
>* Em PR: a) Equívocos:  W999 (Exposição a outros fatores ambientais artificiais e aos não especificados - local não especificado), W199 (Queda sem especificação - local não especificado) , b) Falhas: Z915 (História pessoal de auto agressão), Z931 (Gastrostomia); 
>* Em PA: a) Equívocos:  W999 (Exposição a outros fatores ambientais artificiais e aos não especificados - local não especificado), H431 (Hemorragia do humor vítreo) , b) Falhas: Z574 (Exposição ocupacional a agentes tóxicos na agricultura), Z599 (Circunstâncias não especificadas econômicas ou de habitação); 
>* Em GO: a) Equívocos:  W189 (Outras quedas no mesmo nível - local não especificado), V299 (Motociclista [qualquer] traumatizado em um acidente de trânsito não especificado) , b) Falhas: Z722 (Uso de droga), Z811 (História familiar de abuso de álcool).
>
>Além disso, pelos dados, ficou evidente que a regionalização dos diagnósticos em si seria inevitável, já que os comportamentos de CID-10 variam bastante conforme o estado. Todavia, alguns outros comportamentos atendem a um certo padrão, por exemplo:
>
>As falhas de diagnóstico e os diagnósticos equivocados ocorrem mais para homens brancos e pardos (quando há declaração de raça) e o tempo médio de internação geralmente dobra quando há falha de diagnóstico e esta leva ao óbito do(a) paciente.  Em termos de óbito, as falhas de diagnóstico tem menor representatividade que os diagnósticos equivocados.  

>Em termos de Aprendizado de Máquina, o classificador por Gradient Boosting foi o que obteve melhor acurácia, especificidade e sensibilidade, de forma que os resultados enontrados são os seguintes:

Matriz de Confusão - Dados de Treino | Matriz de Confusão - Dados de Teste
----- | -----
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/01sp.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/02sp.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/01ba.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/02ba.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/01pr.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/02pr.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/01pa.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/02pa.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/01go.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/02go.png)

Curva ROC | Curva ROC
----- | -----
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/03sp.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/03ba.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/03pr.png) | ![Gráfico 02](https://github.com/grnbatera/Data4health/blob/main/assets/03pa.png)
![Gráfico 01](https://github.com/grnbatera/Data4health/blob/main/assets/03go.png) | 


Estado |	Acurácia |	Sensibilidade |	Especificidade |	RMSE
----- | ----- | ----- | ----- | -----
SP - treino |	0.9578083117 |	0.67 |	0.99 |	0.0421916883
SP - teste |	0.9566485054 |	0.68 |	0.99 |	0.04335149463
BA - treino |	0.9884554281 |	0.84 |	1.00 |	0.01154457193
BA - teste |	0.9808565866 |	0.74 |	0.99 |	0.01914341337
PR - treino |	0.9922745802 |	0.79 |	1.00 |	0.007725419767
PR - teste |	0.9837473573 |	0.61 |	0.99 |	0.01625264271
PA - treino |	0.9999006162 |	0.99 |	1.00 |	9.94E-05
PA - teste |	0.9947856315 |	0.70 |	1.00 |	0.005214368482
GO - treino |	0.9895330439 |	0.91 |	0.99 |	0.01046695606
GO - teste |	0.9813058036 |	0.84 |	0.99 |	0.01869419643

Importância |	Variável |	Descrição
----- | ----- | -----
1 |	v69 |	Definição de óbito
2	| v51	| Definição do motivo de saída/permanência
3 |	v48 |	Código do diagnóstico principal (CID10)
4 |	v5	 | Número da AIH
5 |	v100 |	Código CNES do hospital
6 |	v7	| Definição do número da AIH
7 |	v117 |	Sequencial da AIH na remessa
8 |	v68 |	Indica óbito
9 |	v79 |	Definição do número de filhos do paciente
10 |	v249 |	Dias de permanência

>O resultado para os demais modelos de machine learning utilizados para a análise podem ser vistos em  [SP](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_SP.ipynb), [BA](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_BA.ipynb), [PR](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_PR.ipynb), [PA](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_PA.ipynb) E [GO](https://github.com/grnbatera/Data4health/blob/main/notebook/ML_GO.ipynb).
>
# Discussão
>A) *Resultados Estatísticos*: Os principais resultados demonstram que as falhas de diagnóstico e os diagnósticos equivocados realmente são exceções e ocorrem mais para homens brancos e pardos (quando há declaração de raça), fato decorrente de fatores sócio-econômicos, uma vez que esse grupo tem maior acesso aos hospitais; o tempo médio de internação geralmente dobra quando há falha de diagnóstico e esta leva ao óbito do(a) paciente; em termos de óbito, as falhas de diagnóstico tem menor representatividade que os diagnósticos equivocados; no geral, neoplasias são as doenças com maior incidência de falhas de diagnóstico. Por fim, no banco de dados há falta de dados de diagnósticos secundários a partir de 2015;
>
>B) *Resultados da Aprendizagem de Máquina*: Através do modelo de Gradient Boosting foi possível criar um classificador para analisar a importância das features que levam a uma falha de diagnóstico ou diagnóstico equivocado, contudo, devido ao enviesamento ocorrido quando a classe "diagnóstico correto" estava presente, não foi possível elaborar um classificador funcional para predizer as 3 classes de diagnóstico. Com relação as features, basicamente existem 3 categorias importantes: a primeira tem relação com o hospital, alguns possuem maiores índices de falha/equívoco que outros; a segunda com as condições técnicas (diagnóstico principal, tempo de internação, óbito) e a terceira com as condições sócio-econômicas do paciente (quantidade de filhos);
>
# Conclusão
>
>Neste projeto, foi possível concluir que:
>
>1) De forma geral, as falhas e equívocos de diagnóstico são sim exceções, contudo, há uma grande divergência com relação ao real valor, uma vez que o banco de dados do SIHSUS é mantido e modificado por muitos usuários e com diferentes realidades, sujeito a erros sistemáticos, além disso, não há dados de diagnósticos secundários a partir de 2015 em todo o banco, o que prejudica a transparência do processo;
>
>2) Em termos humanos, os diagnósticos equivocados levam mais ao óbito, fato que não era exatamente esperado, já que o diagnóstico dado era próximo do real, assim, uma investigação mais detalhada no hospital é justificada;
>
>3) Em termos econômicos, as falhas de diagnóstico geralmente dobram o tempo de internação e, além disso, possuem maiores custos médios por internação, causando maior impacto ao sistema.
>

# Respostas para as perguntas de pesquisa
>
> 1) Qual é a extensão do impacto causado pelas falhas de dignóstico médico dentro do Sistema Único de Saúde do Brasil?
>
> R - Com base nos dados obtidos, as falhas de diagnóstico, juntamente com os diagnósticos equivocados representam, de fato, exceções, sendo predominantes os diagnósticos corretos, todavia, diagnósticos equivocados levam mais a óbito, tendo um maior impacto em termos humanísticos e a falha de diagnóstico geralmente dobra o tempo de internação e, também, leva a maiores valores médios de internação, tendo um maior impacto econômico, ao menos para os Estados de São Paulo, Bahia, Paraná, Pará e Goiás. Todavia, cabe o disclaimer que a base da dos do SIHSUS, utilizada para responder a esta pergunta possui um grande número de usuários inserindo dados, de forma que há possibilidade bem grande de erro sistemático nestas inserções de dados, além disso, os dados são referentes apenas ao sistema hospitalar, o que representa uma parcela, mas não a totalidade das unidades de atendimento do SUS e o último fator é que desde 2015 não há mais inserção de dados de diagnósticos secundários no banco do SIHSUS, o que pode causar distorções da realidade.
>  
> 2) Uma vez conhecida esta extensão, é possível propor um método de predição de casos de falha de diagnóstico em Machine/Deep Learning?
>
> R - Para esta pesquisa, foi possível criar um método de predição de duas das três categorias possíveis de diagnóstico, sendo, portanto, possível verificar a influência das features neste modelo que classifica diagnóstico equivocado e falha de diagnóstico, contudo, não foi possível fazer um modelo em deep learning que pudesse corresponder a totalidade das classes de diagnóstico médico devido a inexperiência do grupo com relação a DNN no ambiente RAPIDS com computação paralela.
> 
> 3) Sendo possível essa predição, esse método de fato seria útil, de fácil acesso e amigável para os profissionais do SUS?
> 
> R - Infelizmente, para esta pesquisa não foi possível estabelecer uma metodologia totalmente útil para o auxílio no diagnóstico médico por parte dos profissionais do SUS, todavia, houve algum aprendizado com relação aos diagnósticos equivocados e seria justificado para estes casos uma ánalise maior no ambiente hospitalar até o fechamento do diagnóstico.
> 
# Trabalhos Futuros
>
>São possibilidades de trabalhos futuros:
>
>1) Análise dos diagnósticos médicos através do uso do Deep Learning para Big Data: desta forma talvez fosse viável um classificador funcional para as 3 classes de diagnóstico e que poderia ser implementado no SUS para o auxílio de diagnóstico;
>
>2) O SIHSUS é uma base que representa apenas os hospitais, de forma que há uma gama muito grande de unidades de atendimento não contempladas, assim, se houver a possibilidade da inclusão de mais databases com outros tipos de unidades, o modelo teria um retrato mais fiel do sistema;
>
>3) Ter acesso à algumas features como exames pedidos e resultados obtidos poderiam tornar o modelo mais completo e confiável.
>
# Referências Bibliográficas
>
>[1] Martinez, F.; Contreras, L. "CRISP-DM Twenty Years Later: From Data Mining Processes to Data Science Trajectories". IEEE Transactions on Knowledge and Data Engineering, 2020;

>[2] Singh, H; Onakpoya, I. "The global burden of diagnostic errors in primary care". BMJ Qual Saf, 2017.

>[3] Daniel, J. "Data Science with Python and Dask". 1st Edition, Manning Publisher, 2019;

>[4] https://rapids.ai/index.html <acesso em 01/06/2021>.

