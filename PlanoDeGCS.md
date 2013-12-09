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
|   09/12/2013       |    1.1      | Alteração do Documento | Gabriel Nobre |
|   09/12/2013       |    1.2      | Alteração do Documento |C. Augusto Magalhaes |


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
|SVN| Subversion |
|CR|Change Request |



1.4 Referências
---------------

•	Template de Plano de Gerenciamento de Configuração, 1987-2001, IBM.<br>
•	Plano de Gerenciamento do Projeto Remoção 


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

|Ferramenta          |Descrição               |Versão          |
|--------------------|------------------------|---------------|
| TortoiseSVN        |  Ferramenta gráfica para gerenciamento no sistema de controle de versão|1.7.11 |
| Subersion          |  Sistema de Controle de Versão|1.7.8 |




3. O Programa de Gerenciamento de Configuração
==============================================

3.1 Identificação da Configuração
---------------------------------
### 3.1.1 Métodos de Identificação
----------------------------------

####Configurações de Software

|Dado                |Regras                                                                |
|----------------------|------------------------------------------------------------------  |
|Tipo                  |Deve ser citado o tipo, ou seja, a finalidade do software.          |
|Ferramenta            |Deve ser citado o nome do software.                                 |
|Versão                |Deve ser citada a versão do software.                               |
|Configuração Software |Deve ser citado:<br>- o nome do software.<br>- a versão do software.|

####Configurações de Hardware

|Dado                  |Regras                                                                            |
|----------------------|--------------------------------------------------------------------              |
|Quantidade            |A quantidade deve ser citada com o seguinte padrão: “000”.                        |
|Ambiente              |Deve ser citado o nome do software.                                               |
|Configuração Hardware |Deve ser citado: <br> - o clock do processador. <br> - a capacidade da memória ram. <br> - a capacidade do HD. <br> - o ip utilizado.                                                                  |
|Software Instalados   |- Nome e versão dos softwares instalados.                                         |

####Artefatos

|Artefato              |Regras                                                              |
|----------------------|--------------------------------------------------------------------------------------|
|• Plano do Projeto <br>                                                                                                 • Plano de Gerência de Configuração <br>                                                                                • Plano de Testes <br>                                                                                                  • Plano de Implantação <br>                                                                                             • Diagrama de Classes <br>                                                                                              • Diagrama de Casos de Uso <br>                                                                                         • Especificação de Caso de Uso <br>                                                                                     • Cenários de Testes <br>                                                                                               • Casos de Testes <br>                                                                                                  • Sumário de Testes <br> |                                                                                                                   Os artefatos devem seguir o seguinte padrão de identificação: <br>                                                     - Sigla do módulo: “AA”. <br>                                                                                           - Sigla do artefato : “AAA”. <br>                                                                                       - Número da versão da entrega: “v1.0”. <br>                                                                             - Data da emtrega: “dd/mm/yy". <br> <br>                                                                                   Regra de versionamento dos artefatos: <br>                                                                           - À cada correção no artefato deverá ser acrescido mais 1 ao número após o ponto decimal. |

####Software do Sistema

As versões do sistema devem ser geradas com o seguinte padrão: <br> •	Versão: “0” <br> •	Release: “00” <br> •	Build: “000” <br> •	Exemplo: “1.25.131”


### 3.1.2 Itens de Configuração

| Item (ou Tipo de Item)                 |Responsável na equipe	               | Inclusão em Baseline          |
|----------------------------------------|-------------------------------------|-------------------------------|
|Planos                                  |Gerente de Projetos                  |Logo após a aprovação do cliente, bem como o sponsor, dependendo do plano referido.|
|Documentações de Requisitos e Testes    |Líder Técnico e Analista de Testes   |Logo após a aprovação do cliente, bem como o sponsor, dependendo do plano referido.|
|Código-Fonte                            |Gerente de Projetos e Líder Técnico  |Ao fim da iteração, após a verificação e validação por parte dos responsáveis pela qualidade no software.|


### 3.1.3 Baselines do Projeto

À cada nova baseline, a identificação da mesma deverá seguir o seguinte padrão: <br>                                    • Baseline de Documentos: "DOC_V_ <versão>" <br>                                                                        • Baseline de Código Fonte: "FONTE_V_ <versão>" <br>                                                                    • Baseline de Releases: "RELEASE_V_ <versão>"

À seguir o momento em que as baselines devem ser geradas:

|Baseline              |Responsável                         |Item                                                      |
|----------------------|------------------------------------|----------------------------------------------------------|
|Planejamento          |Gerente de Projetos                 |- Plano do Projeto <br>                                                                                                 - Plano de Gerência de Configuração <br>                                                                                - Plano de Testes <br>                                                                                                  - Plano de Implantação
|Requisitos            |Analista de Requisitos              |- Diagrama de Classes                                                                                                   - Diagrama de Casos de Uso                                                                                              - Especificações de Casos de Uso
|Desenvolvimento       |Líder Técnico                       |- Código-Fonte
|Testes                |Líder Técnico / Analista de Testes  |- Cenários de Testes                                                                                                    - Casos de Testes                                                                                                       - Sumário de Testes
|Entrega de Release    |Gerente de Projetos                 |- Release do Software do Sistema


### 3.1.4 Estrutura do Repositório de Versões

|Item / Arquivo        |Diretótio                                                           |
|----------------------|-----------------------------------------------------------------------------------------|
|• Plano do Projeto <br>                                                                                                • Plano de Gerência de Configuração <br>                                                                                • Plano de Testes <br>                                                                                                  • Plano de Implantação  <br>                 |C:\ > Sistemas > Nome do projeto > Planos
|• Diagrama de Classes <br>                                                                                              • Diagrama de Casos de Uso <br>                                                                                         • Código-Fonte                              |C:\ > Sistemas > Nome do projeto > Módulo > Doc. Requisitos        |
|• Cenários de Testes <br>                                                                                              • Casos de Testes <br>                                                                                                  • Sumário de Testes <br>                     |C:\ > Sistemas > Nome do projeto > Módulo > Doc. Testes            |
|• Entrega de Release                        |C:\ > Sistemas > Nome do projeto > Releases                        |

3.2 Controle de Configuração e Mudança
--------------------------------------

### 3.2.1 Processamento e Aprovação de Solicitações de Mudança

A.	As mudanças, bem como etapas das mesmas devem ser registradas através da ferramenta Redmine. <br>                   
B.	Podem solicitar mudanças:
* **Clientes / Usuários**
* **Diretoria**
* **Gerente de Projeto**
* **Analistas de Requisitos**
* **Analistas de Testes**
* **Desenvolvedores**
* **Equipe de Suporte**

C.	As mudanças deverão seguir o fluxo à seguir:
* **Aberta**: status inicial da solicitação de mudança.
*	**Análise**: etapa onde é analisado o impacto e viabilidade da mudança. Há dois resultados possíveis da análise:
* **Aprovada**: a solitação de mudança é encaminhada para a fase de execução.
* **Reprovada**: a solicitação de mudança é arquivada, com as devidas justificativas.
* **Em Execução**: nessa etapa é desenvolvida as documentações necessárias referentes a requisitos, dependendo da solicitação, e logo após a mudança é codificada.
* **Testes**: são criadas as documentações de testes, bem como executados, registrados e analisados os testes necessários.
* **Retornada**: após os testes, a tarefa deve retornar para a etapa de execução devido a ter sido encontrado bugs, e haver a necessidade de corrigí-los.
* **Concluída**: a mudança foi realizada, testada e aprovada. Portanto, resta apenas registrar devidamente a conclusão da mesma, para que seja planejada a release na qual será disponibilizada essa mudança realizada. 


### 3.2.2 Comitê de Controle de Mudança (CCB)

|Dado                |Regras                                                                                     |
|-------------------------|--------------------------------------------------------------------------------------|
|Gerente de Projetos      |- Conduzir a reunião. <br>                                                                                              - Registrar as decisões tomadas na reunião. <br>                                                                        - Atualizar o status  da solicitação de mudanças, conforme decidido em reunião. <br>                                    - Avaliar a viabilidade e impacto da mudança.                                         |
|Analista de Requisitos   |- Avaliar a viabilidade e impacto da mudança.                                         |
|Líder Técnico            |- Será a opinião mais forte na avaliação sobre a viabilidade e impacto da mudança.    |
|Analista de Testes       |- Avaliar a viabilidade e impacto da mudança. <br>                                                                      - Analisar se a mudança é testável. Deve ser citado o nome do software.               |


4. Padrões e Procedimentos
==========================
Nessa parte de padrões e procedimentos serão citados os padrões utilizados no projeto escolhido pela equipe.

Identificação: PRJ SADES 029 – sistemaRemoção<br>
Nome do projeto: sistemaRemocao<br>
Caminho repositório:
http://srvapp.jfce.jus.br/desenvolvimento/documentacaosades/projetos/PRJ SADES 029 - sistemaRemoção

Abaixo segue o padrão para identificar os documentos e artefatos:<br>
I18N - Tabela de Internacionalização;
MAN – Manual;
DOC - Documento não classificado;
MAD - Modelo de Análise e Projeto;
MRT - Matriz de Ratreabilidade de Requisitos;
TSTD - Projeto de Testes;
REQ - Especificação de Requisitos de Software;
MBD - Esquema do Banco de Dados.










5. Treinamento e Recursos
=========================
|      Treinamento          |                Objetivo               |      Publico Alvo     |
|---------------------------|---------------------------------------|-----------------------|
|      Repositório(SVN)     | Capacitar o pessoal para o uso do SVN<br> acessando o repositorio de uma maquina cliente<br> incluir e excluir novos itens e os comandos principais do repositorio | Toda equipe envolvida no desenvolvimento.|


6. Auditorias de Configuração
=============================
A função de auditoria de configuração geralmente ocorre quando a release deve ser criada e tem o objetivo de assegurar que a baseline contem todos os artefatos necessarios. Suas atividades são: auditoria funcional e auditoria física.
Audutoria Física: tem o objetivo de identificar se a release está completa em relação ao que foi acordado em cláusulas no contrato, os passos são: identificar a baseline a ser implentada(pode ser apenas um nome mas também pode ser uma lista completa de todos os componentes), confirmar que todos os artefatos necessarios conforme especificado no caso de desenvolvimento estão presente  na baseline.
Auditoria Funcional: A auditoria funcional verifica se uma baseline atende os requisitos estabelecidos e também abrange a revisão dos planos, dados, metodologia e resultados dos testes, assegurando que a release cumpre corretamente o que foi especifiado. Os passos são: preparar relatório que lista cada requisito estabelecido para a baseline, confirmar que cada requisito passou por um ou mais testes e que o resultado de todos esses testes doi aprovado e gerar uma lista das CR's estabelecidas para essa baseline, confirmando que cada CR foi fechada.

