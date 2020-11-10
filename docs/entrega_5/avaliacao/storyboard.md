# Storyboard

## 1. Introdução

<p align="justify"> &emsp;&emsp; Baseado no que foi definido no planejamento da avaliação do storyboard será feita uma avaliação do documento <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_4/storyboard/">storyboard</a>. Seguiremos do seguinte modo: primeiro, será feita uma análise da usabilidade baseada em metas de usabilidade, segundo, iremos responder as perguntas definidas como objetivo da avaliação e, por fim, terminaremos com as avaliações heurísticas.</p>

## 2. Metas de Usabilidade

### 2.1 Avaliação

<p align="justify"> &emsp;&emsp; De acordo com Jakob Nielsen (1993), existem 6 metas de usabilidade, elas são eficácia, eficiência, segurança, utilidade, aprendizagem e memorização. Segue abaixo uma avaliação baseada nessas metas de usabilidade.</p>

1. Eficácia: No storyboard <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_4/storyboard/#31-buscando-uma-questao-especifica-no-banco-de-questoes">Buscando uma questão específica no banco de questões</a>, é possível observar que o usário possui dificuldade em filtrar o banco de questões disponível no UVa. Devido essa falta de eficácia o usuário opta por mudar de juiz online;
2. Eficiência: No storyboard <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_4/storyboard/#33-como-o-udebug-te-auxilia-na-correcao-da-sua-solucao">Como o UDebug te auxilia na correção da sua solução</a>, é apresentado como o uDebug é eficiente em auxiliar o usuário a debugar seu código;
3. Segurança: Em nenhum storyboard foi abordado segurança;
4. Utilidade: Como mostrado no storyboard <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_4/storyboard/#31-buscando-uma-questao-especifica-no-banco-de-questoes">Buscando uma questão específica no banco de questões</a>, o UVa não fornece um sistema de busca que é extremamente necessário para o usuário;
5. Aprendizagem: No storyboard <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_4/storyboard/#32-motivacoes-para-utilizar-o-uva">Motivações para utilizar o UVa</a> mostra de forma sutil essa meta;
6. Memorização: Em nenhum storyboard foi abordado memorização;

### 2.2 Relato dos resultados

<p align="justify"> &emsp;&emsp; Os storyboards ainda não abordam todas as metas de usabilidade. Por mais que não seja obrigatório, caso abordássemos todas, o conjunto de storyboards ofereceria uma quantidade enriquecedora de informações. Dito isso, é preciso abordar segurança, memorização e aprendizagem (essa que já foi abordada, mas apenas de forma sutil).</p>

## 3. Objetivos da avaliação

<p align="justify"> &emsp;&emsp; Durante o planejamento foram feitas perguntas para definir os objetivos da avaliação. Nesta seção não será subdividido avaliação e relato dos resultados, pois esses estão muito conectados dentro das respostas. Segue abaixo essas respostas obtidas durante nossa avaliação.</p>

1. Os erros diagnosticados nos storyboards foram também identificados nos testes-piloto? Não, o teste-piloto foi feito utilizando protótipos de papel. Como os erros diagnosticados foram corrigidos no protótipo, os erros não se repetiram.
2. As atividades dos usuários foram devidamente identificadas na avaliação? Sim, os usuários efetuaram atividades semelhantes ao fluxo de tarefas apresentado nos storyboards.
3. Os objetivos das personas são refletidos nos storyboards? Sim, todos os objetivos aparecem nos storyboards. É importante ressaltar que os storyboards foram criados visando as personas, logo, era essencial refletir os objetivos das personas nesses storyboards.
4. Os participantes do teste-piloto conseguem se identificar com alguma história contada nos storyboards? Sim, o problema de filtragem no banco de questões mostrou-se recorrente e o mesmo ocorreu com o uso do uDebug para auxiliar na solução de questões.
5. As personas executam atividades presentes storyboards? Sim, as atividades das personas estão conectadas tanto com a análise de tarefas quanto no storyboard. Assim, caso deseje entender melhor sobre as personas, elas estão bem apresentadas em todos esses documentos. Ao estudar todos eles é possível entender completamente tudo relacionado à persona estudada.

## 4. Avaliações heurísticas

### Status do sistema

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

```
Verificação:          O site informa ao usuário a situação atual do sistema?
Grau de severidade:   Simples.
Local:                Submissões.
Contexto:             Usuário submete resposta para alguma questão e recebe TLE (tempo limite excedido).
Causa:                Quando o problema não apresenta informações sobre o tempo limite, o usuário não tem como inferir o que deve ser feito.
Efeito sobre usuário: Confusão.
Efeito sobre tarefa:  Dificuldade desnecessária.
Correção possível:    Sempre apresentar o tempo limite dentro do cabeçalho da questão.
```

### Controle do usuário e liberdade

```
Verificação:          O usuário se sente no controle do sistema? O sistema se comporta como esperado?
Grau de severidade:   Relevante.
Local:                Buscador de questões.
Contexto:             Não há nenhuma ferramenta de busca avançada disponível no site.
Causa:                Falta de ferramenta de busca.
Efeito sobre usuário: Descaso, usuário não consegue acessar o conteúdo fornecido no site com eficiência.
Efeito sobre tarefa:  Falta de informação.
Correção possível:    Criar ferramenta de busca.
```

### Reconhecimento ao invés de lembrança

```
Verificação:          uDebug exibe casos de teste corretamente?
Grau de severidade:   Grave.
Local:                uDebug.
Contexto:             Alguns casos de errados presentes no uDebug.
Causa:                Qualquer um pode adicionar novos casos de teste.
Efeito sobre usuário: Indignação, usuário se sente enganado pelo teste apresentado.
Efeito sobre tarefa:  Aumento de submissões com WA, TLE, e PE.
Correção possível:    Restringir com mais rigidez à submissão de casos de teste exemplos.
```

### Flexibilidade e eficiência de uso

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

### Ajudar usuários a reconhecer, diagnosticar e corrigir erros

```
Verificação:          O uDebug fornece poder de reconhecer, diagnosticar e corrigir ao usuário?
Grau de severidade:   Grave.
Local:                uDebug.
Contexto:             uDebug é uma ferramenta de auxílio disponibilizada pelo UVa para ajudar o usuário a lidar com erros nas questões.
Causa:                Informações erradas no uDebug, qualquer um pode adicionar novas informações.
Efeito sobre usuário: Confusão e desinformação.
Efeito sobre tarefa:  Nenhum.
Correção possível:    Filtrar melhor contribuições de novas informações.
```

### 4.1 Relato dos resultados

<p align="justify"> &emsp;&emsp; Nessa avaliação o objetivo era catalogar quantos e quais erros eram possíveis de averiguar pelo storyboard. Como demonstrado, foram catalogados erros semelhantes aos encontrados na <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_1/avaliacoes_individuais/avaliacao_uva/">primeira avaliação do UVa</a> e, além disso, também foi possível discutir melhor sobre outros erros, como o erro mais visto até agora de ausência de ferramentas de busca.</p>

<p align="justify"> &emsp;&emsp; Por fim, é importante notar que, além de ajudar na documentação e diagnóstico de erros, os storyboards também apresentam comportamentos do usuário que ainda não haviam sido documentados. Exemplo disso é no storyboard <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_4/storyboard/#31-buscando-uma-questao-especifica-no-banco-de-questoes">Buscando uma questão específica no banco de questões</a>, que é visível assim que ocorrer um descaso do sistema com o usuário, esse poderá optar por abandonar o sistema em questão e optar pelos concorrentes.</p>

## 5. Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|09/11/2020|1.0|Criação da versão inicial do documento com os tópicos 1, 2, 3 e 4|Sérgio Cipriano|
|10/11/2020|1.1|Análises heurísticas efetuadas|Sérgio Cipriano|
|10/11/2020|1.1|Fundindo os documentos de avaliação e relato de resultados em um só|Sérgio Cipriano|
