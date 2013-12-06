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
|   05/12/2013       |    1.0      |   Criação do Documento |Daniel Gregory |
|_&lt;dd/mm/aaaa&gt;_|_&lt;1.1&gt;_|_&lt;Outra versão&gt;_  |_&lt;autor&gt;_|



1. Introdução
==============
O Plano de Gerenciamento de Configuração descreve todas as atividades do Gerenciamento de Controle de Configuração e Mudança que serão executadas durante o ciclo de vida do produto. Suas atividades envolvem identificar a configuração do software, manter sua integridade durante o projeto e controlar sistematicamente as mudanças do projeto de Remoção.



1.1 Finalidade
---------------
Este documento tem por objetivo principal descrever a organização, nomenclatura e regras para o versionamento do projeto Remoção, criando um padrão a ser seguido por toda equipe garantindo maior controle do projeto.

1.2 Escopo
----------
Este documento detalha toda a infra-estrutura utilizada durante o desenvolvimento do projeto Remoção sendo destinado a todos os participantes do desenvolvimento deste projeto.

1.3 Definições, Acrônimos e Abreviações
---------------------------------------

|Termo               |                  Significado                         |
|--------------------|------------------------------------------------------|
|--------------------|------------------------------------------------------|
|--------------------|------------------------------------------------------|


1.4 Referências
---------------

_[Esta subseção apresenta uma lista completa de todos os documentos mencionados no Plano de Gerenciamento de Configuração. Identifique os documentos por título, número de relatório (se aplicável), data e organização responsável pela publicação. Especifique as fontes a partir das quais as referências podem ser obtidas. Essas informações podem ser fornecidas por um anexo ou outro documento.]_

1.5 Visão Geral
---------------
As proximas seções deste documento estão organizados da seguinte forma:<br>


|Seção    |                  Titulo                         |                  Descrição                         |
|---------|------------------------------------------------------|------------------------------------------------------|
|2|Gerenciamento de Configuração de Software|Nesta seção são informados as responsalibidades de cada individio da equipe e as ferramentos utilizadas na gerência de configuração no projeto |
|3|O Programa de Gerenciamento de Configuração|Demonstra os padrões de nomenclatura, numeração, marcação diretórios que devem ser seguidos ao gerenciar as baselines e artefatos do projeto|
|4|Padrões e Procedimentos| São abordades os detalhes sobre padrões e procedimentos a serem seguidos.|
|5|Treinamento e Recursos|Descreve as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de Gerenciamento de configurações especificadas|
|6|Auditorias de Configuração|Descreve o cronograma das auditorias de configuração e o que será verificado|

2. Gerenciamento de Configuração de Software
============================================

2.1 Organização, Responsabilidades e Interfaces
------------------------------------------------
|Papeis|Equipe|Responsabilidade|
|---------|------------------------------------------------------|------------------------------------------------------|
|Gerente de Configuração|Sergio Rodrigues| Acompanhar as alterações dos itens de configurações de um determinado projeto |
|Gestor de ferramentas de Gerência de configuração|Paulo Igo |Manutenção da infraestrutura necessária para o bom funcionamento da Gerência de configuração no conjunto dos projetos da organização, ou no contexto do projeto, se for o caso |
|Gestor de Configuração de Software| Augusto Magalhães |Responsável por aprovar e gerenciar as atividades relativas a Gerência de Configuração de Software, coordenar a equipe de Gerência de Configuração de Software. coordenar o trabalho de integração de sistemas |
|Desenvolvedor| Gabriel <br> Nobre Chagas Lima |Seguir os padrões e procedimentos definidos no Plano de Gerência de Configuração |

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
_[Descreva os padrões e procedimentos que devem ser seguidos no projeto. Crie subseções se achar necessário, para organizá-los melhor.]_



5. Treinamento e Recursos
=========================
_[Descreva as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de CM especificadas.]_



6. Auditorias de Configuração
=============================
_[Descreva o cronograma das auditorias de configuração e o que será verificado. Informe também como serão reportados os problemas encontrados e onde sera feito o acompanhamento dos itens corretivos.]_
