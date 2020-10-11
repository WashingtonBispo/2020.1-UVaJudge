# Guia de Estilo

## 1. Introdução

<p align="justify"> &emsp;&emsp; Trata-se de um registro das principais decisões de design tomadas, de forma que elas não se percam, isto é, sejam efetivamente incorporadas no produto final. </p>

### 1.1 Objetivo do guia de estilo

<p align="justify"> &emsp;&emsp;  Guias de estilo servem de ferramenta de comunicação entre os membros da equipe de design e também com a equipe de desenvolvimento. É importante que as decisões de design possam ser facilmente consultadas e reutilizadas nas discussões sobre extensões ou versões futuras do produto.</p>
<p align="justify"> &emsp;&emsp; O site avaliado UVa online judge não possui um guia de estilo público, sendo assim, criaremos um já com as novas decisões de melhorias para o sistema em questão.</p>

### 1.2 Organização e conteúdo do guia de estilo

<p align="justify"> &emsp;&emsp; A organização do guia de estilo será baseada na estrutura que Marcus(1992) e Mayhem(1999) recomendam.</p>

### 1.3 Público-alvo do guia de estilo

<p align="justify"> &emsp;&emsp; O público alvo é própria equipe que está propondo uma reformulação da aplicação para aplicar em um protótipo. A equipe vigente durante a criação desse guia de estilo é Sérgio Cipriano, Washington Bispo e Paulo Batista.</p>

### 1.4 Como manter o guia 

<p align="justify"> &emsp;&emsp; Aplicaremos a teoria estudada na disciplina Interação Humano Computador a fim de propor um protótipo condizente com os conceitos aprendidos. Futuras alterações no novo protótipo do UVa deverão seguir o estilo definido aqui.</p>

## 2. Resultados de análise 

### 2.1 Descrição do ambiente de trabalho do usuário

<p align="justify"> &emsp;&emsp; Na tela inicial, no centro da página o usuário encontra uma notícia sobre
a nova plataforma que está sendo desenvolvida. À direita ele encontra um livro recomendado e um aviso sobre os próximos contests. À esquerda ele encontra o local de login e abaixo dele se encontra as principais funcionalidades do site, tais como: submeter questão, minhas submissões, procurar problemas e etc. E na parte mais baixo do site podemos encontrar uma nota de agradecimento pelo suporte e outra recomendação de livro</p>

## 3. Elementos de interface

### 3.1 Disposição espacial e grid 

<p align="justify"> &emsp;&emsp; A disposição está atual muita confusa. Na aba esquerda da home está linkado janelas que nem existem mais, exemplo disso é a aba de estatísticas do site que ao ser selecionada o usuário é redirecionado à uma janela vazia. Além disso, vários links e emails que são apresentados na home já estão defasados e não recebem nenhuma atualização.</p>


<p align="justify"> &emsp;&emsp; Home atual do site:</p>
<img  src="https://cdn.discordapp.com/attachments/752587900377628756/764931238208864266/UVa_home.png" class="center">

<p align="justify"> &emsp;&emsp; Exemplo de aba vazia:</p>
<img  src="https://media.discordapp.net/attachments/752587900377628756/764935725358907422/UVa_link_vazio.png?width=1173&height=660" class="center">

<p align="justify"> &emsp;&emsp; Esses problemas são causados por um excesso de informações datadas ou não trabalhadas. Desse modo, para corrigir essas falhas, será resuzido a quantidade de informações apresentando apenas os pontos principais e funcionais. Algumas dessas janelas vazias possuem ideias interessantes, mas falham em aplicar essa ideia no conteúdo visto que estão vazias.</p>
<p align="justify"> &emsp;&emsp; A janela principal(Home) não acrescenta nenhuma informação relavante. Assim, iremos dividir o UVa em 4 janelas principais: login, cadastro, problemas e notícias. A aba login será a nova aba principal, mas mesmo sem fazer login, todas as demais abas estarão disponíveis. A aba de notícias irá conter o feed de notícias que aparecia na atual Home e a aba problemas será uma reformulação da aba Browse problems.</p>
<p align="justify"> &emsp;&emsp; Segue abaixo os grids que criamos para cada janela.</p>

### 3.2 Janelas 

<p align="justify"> &emsp;&emsp; </p>

### 3.3 Tipografia 

<p align="justify"> &emsp;&emsp; São utilizados duas fontes principais no website que mudam de cores dependendo do contexto:</p>

* **Verdana** <br>
<img  src="https://www.prepressure.com/images/fonts_sample_verdana.png" class="left">

* **Trebuchet MS** <br>
<img  src="https://cdn.discordapp.com/attachments/752587900377628756/764935808309788682/unknown.png" class="left">

### 3.4 Símbolos não tipográficos 

<p align="justify"> &emsp;&emsp; Os símbolos não tipográficos foram os seguintes:</p>
<img align = "left" src="https://cdn.discordapp.com/attachments/752587900377628756/764936749079068672/unknown.png">
<img align = "left" src="https://cdn.discordapp.com/attachments/752587900377628756/764938204091908116/unknown.png"> <br><br><br>

### 3.5 Cores

<p align="justify"> &emsp;&emsp; 
#c31756<br>
#ffffff<br>
#aaaabb<br>
#0f0f6f<br>
#337ab7<br>
</p>

## 4. Elementos de interação 

### 4.1 Estilos de interação

<p align="justify"> &emsp;&emsp; </p>

### 4.2 Seleção de um estilo

<p align="justify"> &emsp;&emsp; </p>

### 4.3 Aceleradores (teclas de atalho)

<p align="justify"> &emsp;&emsp; </p>

## 5. Elementos de ação 

### 5.1 Preenchimento de campos 

<p align="justify"> &emsp;&emsp; Além do login e do cadastro, é necessário preencher campos nas submissões dos problemas. Segue foto expositiva:</p>
<img  src="https://cdn.discordapp.com/attachments/752587900377628756/764950446359707658/unknown.png">

### 5.2 Seleção

<p align="justify"> &emsp;&emsp; Basta escolher a linguagem de programação e enviar o código para solucionar o problema. Também é possível selecionar o arquivo com o código.</p>

### 5.3. Ativação

<p align="justify"> &emsp;&emsp; Depois basta clicar em "enviar". O código será submetido e corrigido.</p>
    
## 6. Vocabulário e padrões

### 6.1 Terminologia 

* Contests: É o nome adequado para as competições
* 

### 6.2 Tipos de tela (para tarefas comuns)

No UVa, todas as páginas possuem como padrão uma barra lateral à esquerda.
<img src="../../assets/uva/Lateral_Esquerda_Uva.png">


### 6.3 Sequências de diálogos (e.g., para feedback ou confirmação de uma operação)

<p align="justify"> &emsp;&emsp; O site não cria sequência de diálogo, de forma que a única maneira de ver o feedback de uma submissão é indo até a aba "My submissions". Além disso caso haja algum erro na submissão (como o envio de uma imagem por engano) o site redireciona para uma aba de erro como mostrado na parte 5.3 desse documento.</p>

## 7. Referência

* BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana, **Interação Humano-Computador**, Rio de Janeiro: Elsevier, 2011.

## 8. Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|11/10/2020|1.0| Criação do documento |Sérgio Cipriano e Washington Bispo|