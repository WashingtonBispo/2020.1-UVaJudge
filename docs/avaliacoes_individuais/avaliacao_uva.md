# **Avaliação do site UVa Online Judge**

## 1 Introdução

<p align="justify"> &emsp;&emsp; Baseado no que foi definido no planejamento será feita uma análise do site UVa. Seguiremos do seguinte modo: primeiro será feita uma análise da usabilidade baseada em metas de usabilidade, segundo iremos responder as perguntas definidas como objetivo da avaliação e, por fim, terminaremos com as avaliações heurísticas.</p>

<p align="justify"> &emsp;&emsp; Pelo fato do UVa ter sido escolhido para o projeto final, efetuaremos uma análise utilizando vários métodos.</p>

## 2 Metas de Usabilidade

### 2.1 Usabilidade do UVa

<p align="justify"> &emsp;&emsp; De acordo com Jakob Nielsen (1993), existem 6 metas de usabilidade, elas são eficácia, eficiência, segurança, utilidade, aprendizagem e memorização. Segue abaixo uma avaliação baseada nessas metas de usabilidade.</p>

1. Eficácia: o sistema garante que os usuários acessem um ótimo banco de questões, além de prover acesso à questões de competições passadas.
2. Eficiência: o sistema possui muitas complicações. Os problemas são separados em volumes, o que é muito ineficiente, visto que para saber se uma questão é sobre grafos é necessário acessá-la. Mesmo problema com o acesso às competições passadas.
3. Segurança: não existem erros de usuário que possam prejudicar muito a usabilidade. Todas as questões não possuem limites de envio, logo, errar uma questão não atrapalha em nada na usabilidade. Quanto ao login e senhas, o UVa não dispõe de proteção de 2 etapas, o que é compreensível já que o site não armazena nenhum conteúdo que precise de sigilo.
4. Utilidade: o sistema consegue apresentar ferramentas de alta eficácia, falhando apenas na eficiência.
5. Aprendizagem: o sistema apresenta muitos recursos úteis, mas é difícil se guiar pelo banco de questões devido a ausência de tags e classificações.
6. Memorização: não existem barreiras que dificultem voltar a usar o sistema até porque recebe poucas atualizações.


## 3 Objetivos da avaliação
<p align="justify"> &emsp;&emsp; Os objetivos da avaliação serão expostos por meio de um conjunto de perguntas. Essas que servirão de guia para entender melhor a avaliação e o próprio UVa em si. Segue abaixo os objetivos e suas respostas.</p>

1. De que maneira o sistema separa os problemas? Separa por meio de eventos, livros e volumes.
2. Existe uma classificação de problemas por categorias? Não.
3. Como são disponibilizados as competições? È possível acessá-las separadamente, mas para ler e fazer as questões é necessário acessar os volumes. Isso dificulta muito a usabilidade visto que não existe sistema de busca no site.
4. O usuário consegue acessar e praticar por meio de competições passados? Como dito na questão anterior, é possível. Vale ressaltar que, quando se trata de competições de grande renome, o acesso à elas é muito bom, ainda com o problema de inexistência de uma ferramenta de busca.
5. O usuário entende o que os volumes significam? Nenhum volume é classificado e são separados por números. Não existe legenda, logo, para saber sobre do que se trata aquele volume de questões é preciso lê-las.
6. Qual alternativa é mais eficiente: categorias ou volumes? Categorias costumam dizer por si só sobre o que é uma questão. Mesmo adicionando uma legenda aos volumes ainda seria uma barreira a mais que o usuário precisaria passar apenas para ver o contexto da questão. O fato é que o sistema atual é pior do que ambas as alternativas citadas acima.

## 4 Avaliações heurísticas

### 4.1 Status do sistema

```
Verificação:          O site informa ao usuário a situação atual do sistema?
Grau de severidade:   Simples.
Local:                Submissões.
Contexto:             Usuário submete resposta para alguma questão.
Causa:                Usuário precisa acessar diferentes abas para ver resultado da submissão.
Efeito sobre usuário: Barreira desnecessária para atividade essencial, além de desconforto.
Efeito sobre tarefa:  Nenhum.
Correção possível:    Mostrar resposta na mesma aba da questão.
```

### 4.2 Compatibilidade do sistema com o mundo real

```
Verificação:          A linguagem do site é acessível?
Grau de severidade:   Grave.
Local:                uHunt.
Contexto:             Uhunt é uma ferramenta de apoio ao UVa. É usado para manter informações do usuário e recomendar questões.
Causa:                Linguagem totalmente desorganizada, excesso de informações, poluição visual pelo excesso de texto.
Efeito sobre usuário: Confusão.
Efeito sobre tarefa:  Nenhum.
Correção possível:    Remodelar completamente a maneira como os dados são apresentados. Apresentar apenas o essencial.
```
### 4.3 Controle do usuário e liberdade

```
Verificação:          O usuário se sente no controle do sistema? O sistema se comporta como esperado?
Grau de severidade:   Sem importância.
Local:                Estatísticas do site.
Contexto:             Não há nenhuma estatística do site disponível.
Causa:                Nenhum dado disponível.
Efeito sobre usuário: Descaso, uma aba inútil está sendo disponibilizada.
Efeito sobre tarefa:  Falta de informação.
Correção possível:    Fornecer informação sobre as estatísticas do site.
```
### 4.4 Consistência e padrões

```
Verificação:          Existe um padrão nas telas do site? Este padrão é seguido em todos os lugares possíveis?
Grau de severidade:   Grave.
Local:                uHunt.
Contexto:             Site possui interface que destoa com a interface do UVa, mesmo que tenham sido feitos para se relacionarem.
Causa:                Mudança de interface.
Efeito sobre usuário: Confusão.
Efeito sobre tarefa:  Ineficiente.
Correção possível:    É imprescindivel que a interface do UVa mantenha coerência em todas as suas ferramentas.
```

### 4.5 Prevenção de erros

```
Verificação:          Caso o usuário acesse alguma região defeituosa do sistema ou algum link quebrado, a mensagem de erro é clara? O sistema auxilia o usuário caso alguma funcionalidade não funciona como deveria?
Grau de severidade:   Nulo.
Local                 Nenhum.
Contexto:             Não foi identificado nenhuma região defeituosa no sistema.
Causa:                Os erros comuns ocorrem em questões, o site é feito pensando na possibilidade desse erro.
Efeito sobre usuário: Nenhum.
Efeito sobre tarefa:  Nenhum.
Correção possível:    Nenhuma.
```
### 4.6 Reconhecimento ao invés de lembrança

```
Verificação:          O usuário não deve precisar lembrar uma informação que estava em uma página acessada anteriormente no mesmo site.
Grau de severidade:   Simples.
Local:                Submissões.
Contexto:             Usuário submeteu resposta à uma questão, usuário não tem acesso à sua submissão.
Causa:                Não disponibilizar visualização do código.
Efeito sobre usuário: Dificuldade em criar um banco de soluções e em ver histórico de erros.
Efeito sobre tarefa:  Nenhum.
Correção possível:    Disponibilizar visualização do código submetido.
```

### 4.7 Flexibilidade e eficiência de uso

```
Verificação:          Existe algum tipo de personalização para atender usuários de perfis diferentes? Existem atalhos para agilizar a utilização do site por usuários mais experientes?
Grau de severidade:   Grave.
Local:                UVa (Geral).
Contexto:             UVa parte do princípio que usuário já participa de ambientes de competição.
Causa:                Assumir perfil único de usuário.
Efeito sobre usuário: Afasta usuários que não participam de ambientes de competição.
Efeito sobre tarefa:  Exclusão.
Correção possível:    Apresentar um guia básico descrevendo como funciona o mundo das maratonas de programação.
```
### 4.8 Estética e design minimalista

```
Verificação:          A organização do site é boa? As informações mais importantes são facilmente acessíveis?
Grau de severidade:   Grave.
Local:                Banco de questões.
Contexto:             Um site que foca em resolução de questões deve, no mínimo, fornecer boas ferramentas para filtrar e pesquisar questões.
Causa:                Sem ferramentas de busca.
Efeito sobre usuário: Completa perda de eficiência.
Efeito sobre tarefa:  Inexistente, funcionalidade não implementada.
Correção possível:    Fornecer boas ferramentas de busca.
```

### 4.9 Ajudar usuários a reconhecer, diagnosticar e corrigir erros

```
Verificação:          O uDebug fornece poder de reconhecer, diagnosticar e corrigir ao usuário?
Grau de severidade:   Grave.
Local:                uDebug.
Contexto:             uDebug é uma ferramenta de auxílio disponibilizada pelo.
UVa para ajudar o usuário a lidar com erros nas questões
Causa:                Informações erradas no uDebug, qualquer um pode adicionar novas informações.
Efeito sobre usuário: Confusão e desinformação.
Efeito sobre tarefa:  Nenhum.
Correção possível:    Filtrar melhor contribuições de novas informações.
```
### 4.10 Ajuda e documentação

```
Verificação:          Caso o usuário tenha alguma dúvida ou dificuldade em utilizar o sistema, é fornecido algum tipo de ajuda ou suporte? O usuário consegue tirar suas dúvidas sem sair do site?
Grau de severidade:   Catastrófico.
Local:                UVa (nenhuma ferramenta disponível).
Contexto:             UVa não fornece nenhum suporte dentro do site.
Causa:                Falta de suporte.
Efeito sobre usuário: Usuário fica perdido caso ocorra algum problema.
Efeito sobre tarefa:  Impossível de ser completada.
Correção possível:    Fornecer um fórum para tirar dúvidas, um fórum aberto fomentaria mais discussões e novas soluções.
```


# Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|08/09/2020|1.0|Primeira versão da avaliação em latex|Sérgio Cipriano|
|15/09/2020|1.1|Criação do documento na versão markdown|Washington Bispo|
|15/09/2020|2.0|Adaptação do material de latex para markdown|Sérgio Cipriano|
