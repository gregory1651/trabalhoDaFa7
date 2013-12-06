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
_[Descreva os padrões e procedimentos que devem ser seguidos no projeto. Crie subseções se achar necessário, para organizá-los melhor.]_



5. Treinamento e Recursos
=========================
_[Descreva as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de CM especificadas.]_



6. Auditorias de Configuração
=============================
_[Descreva o cronograma das auditorias de configuração e o que será verificado. Informe também como serão reportados os problemas encontrados e onde sera feito o acompanhamento dos itens corretivos.]_
