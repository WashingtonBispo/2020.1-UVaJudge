# Análise de tarefas

## 1. Contextualização

<p align="justify"> &emsp;&emsp; Utilizaremos a análise de tarefas para entender melhor como o usuário utiliza o UVa online judge. Nosso objetivo é responder 4 perguntas: qual o trabalho dos usuários? Como eles o realizam? É possível realizar sem problemas? Porquê efetuam esses trabalhos?</p>

## 2. Objetivos e método de análise escolhido

<p align="justify"> &emsp;&emsp; A análise terá como foco elaborar um possível redesign do UVa atual. Assim sendo, faremos uma análise para cada persona definida, de modo que os cenários fiquem melhor elaborados e adequados com a visão definida nas personas. Usaremos o modelo de análise de hierárquica de tarefas, o que nos permitirá criar modelos mais complexos baseados nos objetivos de cada persona.</p>

## 3. Análises de tarefas das personas

### 3.1 Personas primárias

#### 3.1.1 Maria lee Oliveira

<p align="justify"> &emsp;&emsp; A primeira persona primária que analisaremos será a Maria lee Oliveira, 33 anos, professora que almeja chegar no mundial com seu time de estudantes.</p>

<p align="center">
  <img src="../../assets/analise_tarefas/Maria_Lee_Oliveira.jpeg">
</p>

| Objetivos | Problemas e recomendações |
|---------|--------------------|
| Acessar seção de problemas | **Ação:** selecionar na barra lateral "Browse problems". **Plano:** acessar os arquivos de questões do mundial ICPC. |
| Acessar ICPC World Finals | **Ação:** selecionar no campo de arquivos exibido a pasta do ICPC. **Plano:** solucionar questões do último ICPC. |
| Abrir arquivo de questões do último contest disponível(2018) | **Ação:** abertura do arquivo do ICPC 2018. **Feedback:** falha, arquivo vazio. **Recomendação:** importar questões do ICPC 2018 para o UVa. |
| Abrir questões do contest | **Ação:** Acessar questões do próximo contest que não possua a falha anterior, até correção ser feita. **Plano:** submeter código com a resposta. |
| Exibir casos de teste das questões | **Feedback:** apresentar informações específicas da questão selecionada. |
| Exibir texto entrada das questões | **Feedback:** exibir texto com as informações de entrada(input) da questão. |
| Exibir saídas esperadas para cada problema | **Feedback:** exibir como será o padrão de resposta. |
| Submeter resposta | **Ação:** submeter solução criada. **Plano:** obter accepted(resposta correta). **Input:** arquivo da linguagem utilizada na solução do problema. |
| Verificar resposta | **Feedback:** retornará ACC caso tenha obtido êxito, as demais siglas são relacionadas a todas as possíveis falhas possíveis. |

#### 3.1.2 Matheus Henrique Bastos

<p align="justify"> &emsp;&emsp; A segunda persona primária que analisaremos será o Matheus Henrique Bastos, 20 anos, granduando em engenharia de computação que almeja se tornar um competidor melhor.</p>

<p align="center">
  <img src="../../assets/analise_tarefas/Matheus_Henrique_Bastos.jpeg">
</p>

| Objetivos | Problemas e recomendações |
| ----------| ------------------------- |
| Acessar seção de problemas | **Ação:** selecionar na barra lateral "Browse problems". **Plano:** buscar questões por categoria. |
| Buscar questões nos bancos de volumes | **Ação:** usar ferramenta de busca customizada do UVa. **Feedback:** enorme quantidade de resultados não relacionados(a ferramenta usa a API de busca do google de forma indevida, acessando o buscador diretamente, o que exibe tudo relacionado a palavra "uva"). **Recomendação:** nesse caso, a solução é realizar uma busca manual. Para solucionar esse problema é necessário criar uma busca customizada interna. |
| Submeter resposta | **Ação:** submeter solução criada. **Plano:** obter accepted(resposta correta). **Input:** arquivo da linguagem utilizada na solução do problema. |
| Verificar resposta | **Feedback:** retornará ACC caso tenha obtido êxito, as demais siglas são relacionadas a todas as possíveis falhas possíveis. |
| Solicitar auxilio do professor | **Ação:** caso ocorra falha na submissão (resposta que não seja ACC), pode ser requisitada a ajuda de algum professor de programação. |
| Olhar editorial | **Ação:** caso ocorra falha na submissão (resposta que não seja ACC), pode se ler o editorial que explica a questão. |
| Refazer com o auxílio do uDebug | **Ação:** caso ocorra falha na submissão (resposta que não seja ACC), ainda é possível testar novas entradas usando o uDebug. |

### 3.2 Personas secundárias

#### 3.2.1 Juliana Figo Sabugueiro

<p align="justify"> &emsp;&emsp; Nossa primeira análise de persona secundária envolverá a Juliana Figo Sabugueiro, 17 anos, estudante do ensino médio que almeja resolver questões fáceis do UVa para aprender a programar.</p>

<p align="center">
  <img src="../../assets/analise_tarefas/Juliana_Figo_Sabugueiro.jpeg">
</p>

| Objetivos | Problemas e recomendações |
|---------|--------------------|
| Acessar seção de problemas | **Ação:** seleciona na barra lateral "Browse problems". **Plano:** buscar questões por categoria. |
| Ordenar problemas pela ordem de dificuldade | **Problema:** só é possível fazer isso nas questões da sessão dos livros CP. **Recomendação:** realizar estudo seguindo os livros CP. |
| Acessar problemas para iniciantes | **Ação:** acessar seção de introdução dos CPs. |
| Submeter resposta | **Ação:** submeter solução criada. **Plano:** obter accepted(resposta correta). **Input:** arquivo da linguagem utilizada na solução do problema. |
| Verificar resposta | **Feedback:** retornará ACC caso tenha obtido êxito, as demais siglas são relacionadas a todas as possíveis falhas possíveis. **Ação:** se obter resposta certa, partir para a próxima questão e solucioná-la. |

## 4. Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|08/09/2020|1.0|Primeira versão da análise de tarefas|Sérgio Cipriano|
|08/09/2020|1.1|Análise de tarefas da persona Maria lee Oliveira|Sérgio Cipriano|
|08/09/2020|1.2|Análise de tarefas da persona Matheus Henrique Bastos|Sérgio Cipriano|
|08/09/2020|1.3|Análise de tarefas da persona Juliana Figo Sabugueiro|Sérgio Cipriano|
|08/09/2020|1.4|Adicionando tabela de objetivos para cada persona|Sérgio Cipriano e Washington Bispo|
