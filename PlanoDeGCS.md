<Nome do Projeto>
=================
Plano de Gerenciamento de Configuração
======================================
Versão &lt;1.0&gt;
------------------

_[Observação: O template a seguir é fornecido para uso com o Rational Unified Process (RUP).  O texto exibido entre colchetes e em itálico foi incluído para orientar o autor e deve ser excluído antes da publicação do documento._

_Este documento utiliza a formatação da linguagem [Markdown] (http://daringfireball.net/projects/markdown/). Você pode encontrar um guia de referência rápido [aqui] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).]_

Histórico de Versões
--------------------

|Data                |Versão       |Descrição               |Autor          |
|--------------------|-------------|------------------------|---------------|
|_&lt;dd/mm/aaaa&gt;_|_&lt;1.0&gt;_|_&lt;Versão inicial&gt;_|_&lt;autor&gt;_|
|_&lt;dd/mm/aaaa&gt;_|_&lt;1.1&gt;_|_&lt;Outra versão&gt;_  |_&lt;autor&gt;_|



1. Introdução
==============

_[A introdução do Plano de Gerenciamento de Configuração  oferece uma visão geral de todo o documento. 
Ela inclui a finalidade, o escopo, as definições, os acrônimos, as abreviações, as referências e uma visão geral deste
Plano de Gerenciamento de Configuração.]_

1.1 Finalidade
---------------
_[Especifique a finalidade deste Plano de Gerenciamento de Configuração.]_

1.2 Escopo
----------
_[Uma breve descrição do escopo deste Plano de Gerenciamento de Configuração; o modelo ao qual ele está associado e tudo o que é afetado ou influenciado por este documento.]_

1.3 Definições, Acrônimos e Abreviações
---------------------------------------
_[Esta subseção apresenta as definições de todos os termos, acrônimos e abreviações necessários para a correta interpretação do Plano de Gerenciamento de Configuração.  Essas informações podem ser fornecidas mediante referência ao Glossário do projeto.]_

1.4 Referências
---------------
_[Esta subseção apresenta uma lista completa de todos os documentos mencionados no Plano de Gerenciamento de Configuração. Identifique os documentos por título, número de relatório (se aplicável), data e organização responsável pela publicação. Especifique as fontes a partir das quais as referências podem ser obtidas. Essas informações podem ser fornecidas por um anexo ou outro documento.]_

1.5 Visão Geral
---------------
_[Esta subseção descreve o conteúdo restante do Plano de Gerenciamento de Configuração e explica como o documento está organizado.]_



2. Gerenciamento de Configuração de Software
============================================

2.1 Organização, Responsabilidades e Interfaces
------------------------------------------------
_[Descreva quem será o responsável pela execução das diversas atividades de Gerenciamento de Configuração (CM) descritas no Processo de CM.]_

2.2 Ferramentas, Ambiente e Infra-estrutura
-------------------------------------------
_[Descreva o ambiente de computação e as ferramentas de software a serem utilizadas para desempenhar as funções de CM em todo o ciclo de vida do projeto ou produto._
_Descreva as ferramentas e os procedimentos necessários utilizados para o controle de versão dos itens de configuração gerados no ciclo de vida do projeto ou produto._
_As questões envolvidas na configuração do ambiente de CM incluem:_
* _tamanho previsto dos dados do produto_
* _distribuição da equipe do produto_
* _localização física dos servidores e clientes]_
 


3. O Programa de Gerenciamento de Configuração
==============================================

3.1 Identificação da Configuração
---------------------------------
### 3.1.1 Métodos de Identificação
----------------------------------
_[Descreva como os artefatos do projeto ou produto devem ser nomeados, marcados e numerados. O esquema de identificação deve abranger o hardware, o software do sistema, os produtos de terceiros (COTS) e todos os artefatos de desenvolvimento de aplicativos listados na estrutura de diretórios do produto; por exemplo, planos, modelos, componentes, software de teste, resultados e dados, executáveis e assim por diante.]_

### 3.1.2 Itens de Configuração
_[Relacionar os artefatos ou grupos de artefatos, separando por tipo, modulo ou subsistema, responsável ou momento em que deverão ser incluídos em baselines._
* _“Inclusão em Baseline” em branco significa que o grupo de artefatos não participará de baseline. Pode ser expresso como uma data ou identificador de uma baseline, fase ou ponto de controle_
* _“Responsável”: indicar nominalmente, sempre que possível]_

| Item (ou Tipo de Item)                 | Responsável na equipe	     | Inclusão em Baseline |
|----------------------------------------|-----------------------------|----------------------|
|_&lt;grupo de itens de configuração&gt;_|_&lt;nome do responsável&gt;_|_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|


### 3.1.3 Baselines do Projeto

_[As baselines funcionam como um padrão oficial no qual os trabalhos subseqüentes são baseados. Somente mudanças autorizadas podem ser efetuadas nas baselines._
_Descreva em que pontos do ciclo de vida do projeto ou produto as baselines devem ser estabelecidas. As baselines mais comuns devem ser definidas ao final de cada uma das fases de Iniciação, Elaboração, Construção e Transição. Elas também podem ser geradas no final de iterações ocorridas dentro das várias fases ou com freqüência ainda maior._
_Descreva quem autoriza uma baseline e o que ela contém.]_

### 3.1.4 Estrutura do Repositório de Versões
_[Descreva a organização de diretórios do seu repositório e que itens/arquivos devem ser armazenados em cada diretório.]_

3.2 Controle de Configuração e Mudança
--------------------------------------

### 3.2.1 Processamento e Aprovação de Solicitações de Mudança
_[Descreva o processo pelo qual os problemas e as mudanças são submetidos, revisados e dispostos. Inclua como funciona a transição de estados de uma solicitação de mudança]_

### 3.2.2 Comitê de Controle de Mudança (CCB)
_[Descreva a participação e os procedimentos para processar solicitações e aprovações de mudança a serem seguidos pelo CCB. Informe quem são os membros do CCB e suas responsabilidades.]_



4. Padrões e Procedimentos
==========================
Gerencia de configuração é um processo que cada vez mais vem chamando atenção de quem está no ramo chamado TI, tudo isso visando competitividade, qualidade, produtividade e menutenibilidade, para se conseguir tudo isso é importante ter um entendimento sobre padrões bem definido, saber quando é necessario usar padrão A ou B e identificar quais ferramentas suportam quais padrões.
Padrões são independentes de feramentas, algumas ferramentas suportam padrões explicitamente e outras menos diretamente, como por exemplo de algumas ferramentas que não suportam branching e merging tão bem quantos outras, essa praticas não são executadas sem apoio de ferramentas.
Existem diversos padrões a serem seguidos dependendo de como cada necessidade se encaixa com determinado padrão até mesmo padrões que se aplicados em conjunto com outros trabalharam de forma mais eficiente por isso é importante ter um alto conhecimento quando se aplica-los, existem vários padrões que são eles, mainline, active development line, private workspace, repository, private system build, integration build entre outros, alguns destes seram especificados iniciando pelo mainline: 

Mainline:  
O padrão mainline mostra como gerenciar a codeline para minimizar esforços com integração que branching e merging requerem se não usamos branchs, perdemos a isolação que ele oferece e cada membro da equipe precisa disputar a aquisição do artefato para realizarem suas tarefas e aquele que consegue o artefato, seqüestra-o para realizar suas mudanças enquanto os demais candidatos a adquirí-lo esperam na fila. 
Por outro lado, se usamos branchs aumentamos o desenvolvimento concorrente entre os membros da equipe, mas em muitos casos, os códigos precisam trabalhar juntos de qualquer forma e precisamos alocar recursos para integrar a mudanças paralelas, a razão para trabalhar com uma mainline é para ter uma codeline central que seja base para subbranches e para acomodar seus merges. 
A mainline para um projeto geralmente inicia com o código base do release anterior, ou se estamos iniciando um novo projeto, temos somente uma codeline que é a própria mainline, trabalhar com uma mainline não significa "não fazer branch", significa que todas as atividades desenvolvidas sobre os artefatos são refletidas sempre sobre uma simples codeline em um determinado momento.

Active development line: 
Oactive development line ajuda a balancear estabilidade e progresso no desenvolvimento do produto sobre a mainline. Digamos que o padrão Mainline precisa do padrão Active Development Line para ser executado de forma completa ou eficiente. 
Para aumentar a performance de um desenvolvimento em equipe desejamos aumentar a quantidade de membros da equipe trabalhando na suas atividades de forma concorrente e também aumentar a comunicação entre esses membros para diminuir conflitos entre as suas atividades, essa comunicação é implementada através dos pontos de sincronização onde os trabalhos de todos os membros serão integrados e suas dependências serão gerenciadas para evitar deadlock e blocking.
Deadlocks são causados por dependências múltiplas e blocks ocorrem quando alguém reserva um artefato para editá-lo e passa muito tempo para liberá-lo para as outras pessoas, quando alguém check-in uma mudança para a mainline, esta pessoa pode causar atrasos a toda a equipe a sua mudança impacta o trabalho dos demais. Então seria necessário antes de executar o check-in testar as mudanças com a última versão dos artefatos da mainline para observar qualquer incompatibilidade.

Repository:
Este padrão mostra como construir uma área de trabalho local facilmente e com a configuração necessária. Quando vamos realizar uma mudança sobre o sistema precisamos de uma área onde possamos acomodar as corretas versões dos arquivos do sistema para realizar a mudança, e testa-la de forma isolada, queremos obter os elementos da área de trabalho facilmente tal que possamos confiantemente criar um ambiente que permita-nos fazer nosso trabalho com a versão correta do software, por exemplo, quando vamos corrigir um erro de uma versão anterior do software. A criação manual de uma área de trabalho gasta muito tempo. E podem levar a erros de configuração por não pegarem a versão correta de um componente. Dessa forma, precisamos de um mecanismo simples e repetível para criar uma área de trabalho. Poderíamos criar áreas de trabalho que contivessem artefatos de alguma versão identificável do produto, como artefatos de uma determinada release, por exemplo. O mecanismo poderia também facilitar a necessidade de atualização da área de trabalho quando uma nova release fosse criada. 

Private System Build:
No padrão Private System Build cada membro da equipe pode trabalhar de forma isolada das mudanças realizadas pelos demais mas esses trabalhos precisam ser sincronizados em um determinado momento para compor o sistema de forma íntegra, para isso é necessário realizar builds locais no sistema consistentemente e incluindo as novas mudanças e este padrão explica como podemos verificar se as mudanças sendo desenvolvidas nas áreas de trabalhos estão consistentes com a atual configuração da codeline, antes de publicá-las.
Em uma equipe de desenvolvimento com política liberal de codelines, mudanças acontecem muito rapidamente. O código existente é mudado, novos módulos são adicionados a codeline, e as dependências podem mudar.O único verdadeiro teste para avaliar a compatibilidade das mudanças é através da realização de builds centralizados da área de trabalho de integração que acomoda todas as mudanças de todos os membros da equipe. Os builds privados eliminam alguns possíveis erros sobre as mudanças realizadas na área de trabalho, mas não garantem que apareçam erros no builds noturnos quando todas as mudanças são integradas.










5. Treinamento e Recursos
=========================
|      Treinamento          |                Objetivo               |      Publico Alvo     |
|---------------------------|---------------------------------------|-----------------------|
|      Repositório(SVN)     | Capacitar o pessoal para o uso do SVN<br> acessando o repositorio de uma maquina cliente<br> incluir e excluir novos itens e os comandos principais do repositorio | Toda equipe envolvida no desenvolvimento.|


6. Auditorias de Configuração
=============================
A função de auditoria de configuração geralmente ocorre quando a release deve ser criada. Suas atividades são: auditoria funcional e auditoria física.<br>
Audutoria Física: tem o objetivo de identificar se a release está completa em relação ao que foi acordado em cláusulas no contrato, os passos são: identificar a baseline a ser implentada(pode ser apenas um nome mas também pode ser uma lista completa de todos os componentes), confirmar que todos os artefatos necessarios conforme ezspecificado no caso de desenvolvimento estçai presente  na baseline.<br>
Auditoria Funcional: A auditoria funcional verifica se uma baseline atende os requisitos estabelecidos e também abrange a revisão dos planos, dados, metodologia e resultados dos testes, assegurando que a release cumpre corretamente o que foi especifiado. Os passos são: preparar relatório que lista cada requisito estabelecido para a baseline, confirmar que cada requisito passou por um ou mais testes e que o resultado de todos esses testes doi aprovado e gerar uma lista das CR's estabelecidas para essa baseline, confirmando que cada CR foi fechada.<br>
Caso algo de errado seja encontrado na auditoria é necessário seguir alguns passos com por exemplo:<br>
Analisar e identificar o que deve ser feito para a correção, pode ser que nesta ação seja necessário entrevistas com alguns membros da equipe para que todos ajude a encontrar o que ocasionou o problema.<br>
Caso encontre-se artefatos ausentes o que geralmente se faz é criar uma CR ou uma tarefa que fará o artefato que esteja faltando.<br>
Caso haja alguma CR para ser resolvida ela pode ser testada para ver se está tudo correto ou  adiada para alguma baseline posterior.


