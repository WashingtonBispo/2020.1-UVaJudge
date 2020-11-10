# Análise de tarefas

## 1. Introdução

<p align="justify"> &emsp;&emsp; Baseado no que foi definido no planejamento da avaliação da análise de tarefas, será feita uma avaliação do documento <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_2/analise_tarefas/">análise de tarefas</a>. Seguiremos do seguinte modo: primeiro, será feita uma análise da usabilidade baseada em metas de usabilidade, segundo, iremos responder as perguntas definidas como objetivo da avaliação e, por fim, terminaremos com as avaliações heurísticas.</p>

## 2. Metas de Usabilidade

### 2.1 Avaliação

<p align="justify"> &emsp;&emsp; De acordo com Jakob Nielsen (1993), existem 6 metas de usabilidade, elas são eficácia, eficiência, segurança, utilidade, aprendizagem e memorização. Segue abaixo uma avaliação baseada nessas metas de usabilidade.</p>

1. Eficácia: No caminho de tarefas das personas, foi observado que elas possuem uma dificuldade geral em 
encontrar alguma questão especifíca no banco de questões.
2. Eficiência:  O site possui uma barra de pesquisa que não é eficiente, além disso, ele possui o Udebug para
ajudar o usuário a encontrar um caso de teste que falha.
3. Segurança: Não é possível ter acesso ao código que foi enviado.
4. Utilidade: O site não possui uma boa maneira de se encontrar pelos problemas, a barra de procura disponível é ineficiente e apresenta resultados indesejados.
5. Aprendizagem: Não há nenhum tipo de auxilio à novos usuários na plataforma.
6. Memorização: O usuário consegue se lembrar como as tarefas são feita após um tempo sem usar o sistema.

### 2.2 Relato dos resultados

<p align="justify"> &emsp;&emsp; As análises de tarefas mostram-se boas para catalogar as metas de usabilidade. Ademais, são ótimas para se entender melhor sobre as personas, isso porque, na análise de tarefas é mostrado como cada persona atua para atingir os seus objetivos.</p>

## 3. Objetivos da avaliação

<p align="justify"> &emsp;&emsp; Durante o planejamento foram feitas perguntas para definir os objetivos da avaliação. Segue abaixo as respostas obtidas durante nossa avaliação.</p>

1. Os erros diagnosticados na análise de tarefas foram também identificados nos testes-piloto? Não.
2. As atividades dos usuários foram devidamente identificadas na avaliação? Sim.
3. Os objetivos das personas estão fiéis ao nosso perfil de usuário e aos dados coletados nas entrevitas e avaliações?  Sim, as personas definem bem quais são nossos possíveis usuários.
4. O erro encontrado na <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_2/analise_tarefas/#321-maria-lee-oliveira">análise de tarefas da Maria lee Oliveira</a> foi relatado durante o teste-piloto? Não, Maria Lee encontrou o banco de questões que estava buscando.

## 4. Avaliações heurísticas

### Status do sistema

```
Verificação: Qual boa é disponibilidade do sistema?, seus links são funcionais?          
Grau de severidade: Grave
Local: Geral               
Contexto: Ocasionalmente, o site fica fora do ar. Alguns links estão quebrados.          
Causa: Atualizações, falta de organização.               
Efeito sobre usuário: Frustração.
Efeito sobre tarefa: Faz com que a tarefa não possa ser cumprida.
Correção possível: Informar sobre atualizações, melhorar o tempo que demora pro 
site se recuperar, consertar os links quebrados.    
```

### Compatibilidade do sistema com o mundo real

```
Verificação: A estrutura do site é algo compatível com
o mundo real?      
Grau de severidade: Simples   
Local: Geral               
Contexto: O site não apresenta uma estrutura intuitiva.            
Causa: O modelo que o site foi criado não foi planejado
para que fosse ser usado por leigos               
Efeito sobre usuário: No inicio deixa os usuários confusos
Efeito sobre tarefa: Dificuldade inicial. 
Correção possível: Criar uma página que explica o site.   
```

### Controle do usuário e liberdade

```
Verificação: O nível de liberdade do usuário é o adequado?          
Grau de severidade: Simples.  
Local: Banco de problemas.               
Contexto: O site é muito amplo, tornando muito difícil encontrar as 
carecteristicas dos problema.             
Causa: A estrutura do site faz com que seja dificl para o usuário encontrar 
problemas do seu nível.               
Efeito sobre usuário: O usuário pode se sentir perdido no site.
Efeito sobre tarefa: Dificuldade em iniciar a tarefa.  
Correção possível: Organizar e classificar o banco de problemas.
```

### Consistência e padrões

```
Verificação: Os itens são agrupados logicamente e os padrões de formatação são
seguidos consistentemente em todas as telas da interface?         
Grau de severidade: Cosmético
Local: Tela do problema               
Contexto: O usuário não consegue retornar ao banco em que aquele
problema se encontra             
Causa: Não há link para retornar ao banco de problemas               
Efeito sobre usuário: Desorientação
Efeito sobre tarefa: Nenhuma 
Correção possível: Criar um hiperlink que leva o usuário ao
banco de questões.   
```

### Prevenção de erros

```
Verificação: O site consegue ajudar o usuário a se prevenir dos erros?          
Grau de severidade: grave   
Local: Submissão              
Contexto: Caso o usuário envie uma extensão inválida o arquivo quebra o site.            
Causa: O sistema não checa se o formato do arquivo enviado é válido.               
Efeito sobre usuário: O usuário acha que enviou o documento correto
mas o site quebra, deixando ele confuso.
Efeito sobre tarefa: Dificulta a realização, pode causa a desistência.  
Correção possível: Checar previamente se é um arquivo válido.   
```

### Reconhecimento ao invés de lembrança

```
Verificação: O usuário consegue se familiarizar de forma eficiente?         
Grau de severidade: grave.
Local: Geral.                
Contexto: Alguns caminhos e opções do site são dificeís de serem
relembrados.            
Causa: Caminhos muito especifícos.               
Efeito sobre usuário: Confusão e frustração.
Efeito sobre tarefa: Pode fazer o usuário desistir da tarefa. 
Correção possível: Facilitar alguns acessos do site.   
```

### Flexibilidade e eficiência de uso

```
Verificação: O site consegue se adequar ao nível do usuário?        
Grau de severidade: Catastrófico  
Local: Geral               
Contexto: Não há maneira de um novo usuário se adequar ao site            
Causa: O site não se adequa baseado na habilidade do usuário                
Efeito sobre usuário: Desmotivação
Efeito sobre tarefa:  Desistência
Correção possível: Criar um caminho para novos usuários  
```

### Estética e design minimalista

```
Verificação: Há unidades de informação desnecessárias?           
Grau de severidade: Cosméticos   
Local: Geral               
Contexto: É possível notar pelo site um conjunto de locais com informações demais
tais como a tela inicial que possue muitas informações.            
Causa: Excesso de informação.               
Efeito sobre usuário: Distração, confusão e desorientação
Efeito sobre tarefa: Dificuldade em realizar elas. 
Correção possível: Diminuir a quantidade de informações. 
```

### Ajudar usuários a reconhecer, diagnosticar e corrigir erros

```
Verificação: Quando encontrado um erro, o usuário consegue se recuperar
facilmente.         
Grau de severidade: severo  
Local: Submissão               
Contexto: A página de submissão pode levar a um lugar sem volta            
Causa: Quando enviado uma arquivo incompatível a página quebra
e não permite voltar à página de submissão.              
Efeito sobre usuário: Confusão, desorientação.
Efeito sobre tarefa: Aumentar a dificuldade da tarefa, confusão
pois o usuário não sabe que enviou errado.
Correção possível: Utilizar um método que permita voltar às páginas 
anteriores, checar se o arquivo é compatível.  
```

### Ajuda e documentação

```
Verificação: A aplicação auxilia caso o usuário precise de ajuda?         
Grau de severidade: Simples  
Local: Contato               
Contexto: O site não oferece mais de uma maneira de contactar alguma ajuda.            
Causa: Não há interesse em oferecer mais canais de diálogo.               
Efeito sobre usuário: Desamparo.
Efeito sobre tarefa: Desistência. 
Correção possível: Colocar mais maneiras de falar com eles.
```

### Relato dos resultados

<p align="justify"> &emsp;&emsp; Nessa avaliação o objetivo era catalogar quantos e quais erros eram possíveis de averiguar pelo storyboard. Como demonstrado, foram catalogados erros semelhantes aos encontrados na <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge/entrega_1/avaliacoes_individuais/avaliacao_uva/">primeira avaliação do UVa</a> tal como ocorreu no relato dos resultados do storyboard.</p>

<p align="justify"> &emsp;&emsp; Entretanto, diferente do que ocorreu na avaliação do storyboard, nessa avaliação foi possível catalogar erros de todas as 10 heurísticas. Assim, é possível chegar a dois entendimentos: (i) As análises de tarefas agregam dados essenciais no reconhecimento de erros do UVa, (ii) e esse resultado valida a visão de adicionar novos storyboards (visão essa que foi abordada <a href="https://interacao-humano-computador.github.io/2020.1-UVaJudge//entrega_5/avaliacao/storyboard/#22-relato-dos-resultados">aqui</a>)</p>

## 5. Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|09/11/2020|1.0|Criação da versão inicial do documento com os tópicos 1, 2, 3 e 4|Sérgio Cipriano|
|09/11/2020|1.1|Preenchimento da avaliação heuristica|Washington Bispo|
|10/11/2020|1.2|Modificado os tópicos 2.1 e 3|Washington Bispo|
|10/11/2020|1.3|Fundindo os documentos de avaliação e relato de resultados em um só|Sérgio Cipriano|