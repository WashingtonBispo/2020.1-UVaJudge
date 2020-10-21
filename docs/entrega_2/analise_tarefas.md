# Análise de tarefas

## 1. Contextualização

<p align="justify"> &emsp;&emsp; Utilizaremos a análise de tarefas para entender melhor como o usuário utiliza o UVa online judge. Nosso objetivo é responder 4 perguntas: qual o trabalho dos usuários? Como eles o realizam? É possível realizar sem problemas? Porquê efetuam esses trabalhos?</p>

## 2. Objetivos e métodos de análise escolhido

<p align="justify"> &emsp;&emsp; A análise terá como foco elaborar um possível redesign do UVa atual. Assim sendo, faremos uma análise para cada persona definida, de modo que os cenários fiquem melhor elaborados e adequados com a visão definida nas personas. Usaremos um conjunto variado de modelos para entendermos melhor sobre cada modelo como também obter uma quantidade maior de informações.</p>

## 3. Análise Hierárquica de Tarefas

### 3.1 Descrição

<p align="justify"> &emsp;&emsp; A análise hierárquica de tarefas foi desenvolvida com o objetivo de entender as competências envolvidas nas tarefas do usuário, avaliando objetivos de alto nível dos usuários e decompodo-os em subobjetivos.</p>

### 3.2 Personas primárias

#### 3.2.1 Maria lee Oliveira

<p align="justify"> &emsp;&emsp; A primeira persona primária que analisaremos será a Maria lee Oliveira, 33 anos, professora que almeja chegar no mundial com seu time de estudantes.</p>

<p align="center">
  <img src="../../assets/analise_tarefas/Maria_Lee_Oliveira.jpeg">
</p>

| Objetivos | Problemas e recomendações |
|-|-|
| Acessar seção de problemas | **Ação:** selecionar na barra lateral "Browse problems". **Plano:** acessar os arquivos de questões do mundial ICPC. |
| Acessar ICPC World Finals | **Ação:** selecionar no campo de arquivos exibido a pasta do ICPC. **Plano:** solucionar questões do último ICPC. |
| Abrir arquivo de questões do último contest disponível(2018) | **Ação:** abertura do arquivo do ICPC 2018. **Feedback:** falha, arquivo vazio. **Recomendação:** importar questões do ICPC 2018 para o UVa. |
| Abrir questões do contest | **Ação:** Acessar questões do próximo contest que não possua a falha anterior, até correção ser feita. **Plano:** submeter código com a resposta. |
| Exibir casos de teste das questões | **Feedback:** apresentar informações específicas da questão selecionada. |
| Exibir texto entrada das questões | **Feedback:** exibir texto com as informações de entrada(input) da questão. |
| Exibir saídas esperadas para cada problema | **Feedback:** exibir como será o padrão de resposta. |
| Submeter resposta | **Ação:** submeter solução criada. **Plano:** obter accepted(resposta correta). **Input:** arquivo da linguagem utilizada na solução do problema. |
| Verificar resposta | **Feedback:** retornará ACC caso tenha obtido êxito, as demais siglas são relacionadas a todas as possíveis falhas possíveis. |

#### 3.2.2 Matheus Henrique Bastos

<p align="justify"> &emsp;&emsp; A segunda persona primária que analisaremos será o Matheus Henrique Bastos, 20 anos, granduando em engenharia de computação que almeja se tornar um competidor melhor.</p>

<p align="center">
  <img src="../../assets/analise_tarefas/Matheus_Henrique_Bastos.jpeg">
</p>

| Objetivos | Problemas e recomendações |
|-|-|
| Acessar seção de problemas | **Ação:** selecionar na barra lateral "Browse problems". **Plano:** buscar questões por categoria. |
| Buscar questões nos bancos de volumes | **Ação:** usar ferramenta de busca customizada do UVa. **Feedback:** enorme quantidade de resultados não relacionados(a ferramenta usa a API de busca do google de forma indevida, acessando o buscador diretamente, o que exibe tudo relacionado a palavra "uva"). **Recomendação:** nesse caso, a solução é realizar uma busca manual. Para solucionar esse problema é necessário criar uma busca customizada interna. |
| Submeter resposta | **Ação:** submeter solução criada. **Plano:** obter accepted(resposta correta). **Input:** arquivo da linguagem utilizada na solução do problema. |
| Verificar resposta | **Feedback:** retornará ACC caso tenha obtido êxito, as demais siglas são relacionadas a todas as possíveis falhas possíveis. |
| Solicitar auxilio do professor | **Ação:** caso ocorra falha na submissão (resposta que não seja ACC), pode ser requisitada a ajuda de algum professor de programação. |
| Olhar editorial | **Ação:** caso ocorra falha na submissão (resposta que não seja ACC), pode se ler o editorial que explica a questão. |
| Refazer com o auxílio do uDebug | **Ação:** caso ocorra falha na submissão (resposta que não seja ACC), ainda é possível testar novas entradas usando o uDebug. |

### 3.3 Personas secundárias

#### 3.3.1 Juliana Figo Sabugueiro

<p align="justify"> &emsp;&emsp; Nossa primeira análise de persona secundária envolverá a Juliana Figo Sabugueiro, 17 anos, estudante do ensino médio que almeja resolver questões fáceis do UVa para aprender a programar.</p>

<p align="center">
  <img src="../../assets/analise_tarefas/Juliana_Figo_Sabugueiro.jpeg">
</p>

| Objetivos | Problemas e recomendações |
|-|-|
| Acessar seção de problemas | **Ação:** seleciona na barra lateral "Browse problems". **Plano:** buscar questões por categoria. |
| Ordenar problemas pela ordem de dificuldade | **Problema:** só é possível fazer isso nas questões da sessão dos livros CP. **Recomendação:** realizar estudo seguindo os livros CP. |
| Acessar problemas para iniciantes | **Ação:** acessar seção de introdução dos CPs. |
| Submeter resposta | **Ação:** submeter solução criada. **Plano:** obter accepted(resposta correta). **Input:** arquivo da linguagem utilizada na solução do problema. |
| Verificar resposta | **Feedback:** retornará ACC caso tenha obtido êxito, as demais siglas são relacionadas a todas as possíveis falhas possíveis. **Ação:** se obter resposta certa, partir para a próxima questão e solucioná-la. |

## 4. Análise GOMS

### 4.1 Descrição

<p align="justify"> &emsp;&emsp; O método Goms tem o objetivo de analisar o desempenho de usuários realizando tarefas dentro de um sistema computacional. Sua análise é dividida em objetivos, operadores, métodos e regras de seleção. Existem vários modelos dentre a família GOMS, iremos trabalhar somente com o CMN-GOMS, pois o modelo KLM não responde nossos objetivos descritos na contextualização e o modelo CPM-GOMS pela seguinte citação:</p>

```
Em geral, o CPM-GOMS assume que o usuário é extremamente experiente e executa
as tarefas tão rápido quanto a arquitetura MHP permite. Isso significa que o 
usuário sabe exatamente onde procurar visualmente um determinado item de 
informação, e que não há atividades cognitivas substanciais associadas à
seleção de métodos ou decisões complexas. Portanto, os modelos CPM-GOMS devem
ser utilizados apenas para tarefas nas quais a seleção do método se baseia
em dicas óbvias do ambiente ou envolve decisões triviais (John, 2003).
```

<p align="justify"> &emsp;&emsp; A usabilidade atual do UVa envolve decisões não triviais quanto sua navegação, além de não apresentar uma organização visual boa o suficiente para se fazer um percurso cognitivo baseado apenas em características visuais. Com tudo isso explicado, segue nossa análise baseada no modelo CMN-GOMS.</p>

### 4.2 Análise CMN-GOMS

<p align="justify"> &emsp;&emsp; Nesse modelo há uma hierarquia estrita de objetivos, os operadores são executados estritamente em ordem sequencial, e os métodos são representados numa notação semelhante à um pseudocódigo, que inclui submétodos e condicionais. Tal como na análise hierárquica de tarefas, serão feitas análises para cada uma das personas.</p>

<p align="justify"> &emsp;&emsp; Na nossa análise usaremos os seguintes termos:</p>

```
Goal    : Objetivo do usuário utilizando o sistema.
OP      : Ações concretas que o UVa oferece ao usuário.
METHOD  : Sequência de subobjetivos e operadores para atingir um objetivo.
SEL.RULE: Regras pré-definidas sobre o estado do sistema.
contest : Termo utilizado pelo UVa para competições.
```

<p align="justify"> &emsp;&emsp; Segue abaixo uma análise baseada no objetivo de cada persona:</p>

**Maria lee Oliveira**: Chegar no mundial de programação competitiva com seu time

```
Goal 0: Separar tópicos e questões de estudo
  Goal 1: Escolher contest
    METHOD 1: Definir contest utilizado para iniciar treinamento
    (SEL.RULE: peferência do usuário)
      OP: Levar cursor até menu "BROWSE PROBLEMS"
      OP: Selecionar ACM-ICPC World Finals
      OP: Escolher um dos contests disponíveis
  Goal 2: Auxiliar estudantes na resolução do contest
    METHOD 1: Processo que será feito fora do site
  GOAL 3: Separar tópico de estudo
    METHOD 1: Definir tópico para estudo do CP3
    (SEL.RULE: tópicos serão separados levando em consideração as listas de exercício do livro CP3)
      OP: Levar cursor até menu "BROWSE PROBLEMS"
      OP: Selecionar "Competitive Programming 3: The New Lower Bound of Programming Contests (Steven & Felix Halim)"
      OP: Escolher um dentre os 7 tópicos disponíveis
  Goal 4: Auxiliar estudantes na resolução do CP3
    METHOD 1: Processo que será feito fora do site
```

**Matheus Henrique Bastos**: Melhorar suas habilidades de programação

```
Goal 0: Separar tópicos e questões de estudo
  GOAL 3: Separar tópico de estudo
    METHOD 1: Definir tópico para estudo do CP3
    (SEL.RULE: tópicos serão separados levando em consideração as listas de exercício do livro CP3)
      OP: Levar cursor até menu "BROWSE PROBLEMS"
      OP: Selecionar "Competitive Programming 3: The New Lower Bound of Programming Contests (Steven & Felix Halim)"
      OP: Escolher um dentre os 7 tópicos disponíveis
  Goal 4: Auxiliar estudantes na resolução do CP3
    METHOD 1: Processo que será feito fora do site
```

**Juliana Figo Sabugueiro**: Aprender a programar

<p align="justify"> &emsp;&emsp; Para atingir seu objetivo, Juliana pode seguir o mesmo caminho trilhado por Matheus. Como o UVa não fornece um sistema de organização de questões baseado em nível de dificuldade, o melhor caminho para um iniciante é seguir pelas questões do CP3, que são organizadas por dificuldade.</p>

## 4. Bibliografia

<p align="justify"> &emsp;&emsp; BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador, Editora Elsevier, Rio de Janeiro, 2010.1</p>

## 5. Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|08/09/2020|1.0|Primeira versão da análise de tarefas|Sérgio Cipriano|
|03/10/2020|1.1|Análise de tarefas da persona Maria lee Oliveira|Sérgio Cipriano|
|03/10/2020|1.2|Análise de tarefas da persona Matheus Henrique Bastos|Sérgio Cipriano|
|03/10/2020|1.3|Análise de tarefas da persona Juliana Figo Sabugueiro|Sérgio Cipriano|
|03/10/2020|1.4|Adicionando tabela de objetivos para cada persona|Sérgio Cipriano e Washington Bispo|
|04/10/2020|1.5|Correção formatação|Sérgio Cipriano|
|17/10/2020|2.0|Criação de análise de tarefas por CMN-GOMS|Sérgio Cipriano|
