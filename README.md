|**REGRAS DE NEGÓCIO IMPLEMENTADAS NO SISTEMA**|
|-------------------------------------------------------------------------------------|

## Minha seção {#my-section}

|**RN001**| 
|-------------------------------------------------------------------------------------|

Todos os campos deverão ser exibidos com máscara correspondente aos dados. 
**[Histórias relacionadas #49 #50 #57 #58 #95 #99 #102 #109 #106 #107 #116 #28]**

|**RN002**| 
|-------------------------------------------------------------------------------------|

Os dados exibidos no relatório deverão ser recuperados da funcionalidade [**'Incluir Permissão'**](#54), [**'Editar Permissão'**](#55).  **[Histórias relacionadas #55 #57 #58 #183 #184]**


|**RN003**| 
|-------------------------------------------------------------------------------------|

O campo **'Funcionalidade'** deverá exibir a lista de funcionalidades cadastradas no sistema, utilizando-se da funcionalidade [**'Incluir Funcionalidade'**](#94) [**'Editar Funcionalidade'**](#96). **[Histórias relacionadas #183]**

|**RN004**| 
|-------------------------------------------------------------------------------------|

As colunas do resultado da pesquisa, deverão exibir a opção de ordenação, que permite ordenar os dados em ordem crescente ou decrescente ao clicar no título. Por padrão o resultado deverá ser exibido do mais recente para o mais antigo. **[Histórias relacionadas #49 #58 #95 #106 #99 #102 #109 #116]**

|**RN005**| 
|-------------------------------------------------------------------------------------|

Após realizar a pesquisa o sistema deverá exibir a quantidade de registros localizados, sendo 10 registros por página para visualizar os demais registros caso existam, será necessário navegar pela opção de paginação. **[Histórias relacionadas #49 #58 #102 #109 #116]**

|**RN006**| 
|-------------------------------------------------------------------------------------|

O campo **Programa**, deverá recuperar e exibir a lista de programas cadastrados no sistema, utilizando-se da funcionalidade [**'Incluir Programa'**](#46) e [**'Editar Programa'**](#47) **[Histórias relacionadas #94 #96 #109 #58 #102 #106 #116 #183 ]**

|**RN007**| 
|-------------------------------------------------------------------------------------|

Os dados exibidos no resultado da pesquisa deverão ser recuperados da funcionalidade [**'Incluir Funcionalidade'**](#94) e [**'Editar Funcionalidade'**](#96). **[Histórias relacionadas #102]**

|**RN008**| 
|-------------------------------------------------------------------------------------|

O campo deverá exibir a opção **Todos**, que ao ser marcada exibe o resultado da pesquisa relacionado a todos os itens da lista.

|**RN009**| 
|-------------------------------------------------------------------------------------|

Os campos **'UF'** e **'Município'** deverão exibir as informações conforme abaixo: **[Histórias relacionadas #46 #49 #98 #109 #100 #106 #116 #117 #121 #28]**

**UF**
 - Todas

 - Todas as UF’s do Brasil

**Município**

 - Todos

 - Todos os Municípios referente as UF's

Os campos deverão ser relacionados conforme a seleção da **UF**. 

Ao selecionar uma **UF** o campo **Município** deverá exibir os municípios relacionados a UF selecionada.

Ao Selecionar Todas as **UF's** o campo **Município** deverá exibir todos os munícipios relacionados as UF's exibidas no campo **UF**.

Permitir selecionar uma ou todas as opções dos campos.

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_uf/tb_municipio


|**RN010**| 
|-------------------------------------------------------------------------------------|

O campo **Ano** deverá exibir as opções para seleção: **[Histórias relacionadas #46 #49]**

- 2023 à 2030 

|**RN011**| 
|-------------------------------------------------------------------------------------|

O campo **Área Relacionada ao Negócio** deverá exibir as opções: **[Histórias relacionadas #46 #49]**

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_area_negocio


|**RN012**| 
|-------------------------------------------------------------------------------------|

O campo **Público-alvo** deverá exibir as opções: **[Histórias relacionadas #46 #49]**


- Urbano

- Rural

|**RN013**| 
|-------------------------------------------------------------------------------------|

O campo **Ciclo** deverá exibir as opções: **[Histórias relacionadas #46 #49 #103]**

- 1 Ano a 10 anos

|**RN014**| 
|-------------------------------------------------------------------------------------|

As opções **'Excluir'** e **'Editar'** serão exibidas habilitadas somente quando não houver nenhum usuário vinculado  ao programa em referência. **[Histórias relacionadas #47 #48 #49 #104]**

|**RN015**| 
|-------------------------------------------------------------------------------------|

As opções **'Excluir'** e **'Editar'** serão exibidas habilitadas somente quando não houver nenhum perfil vinculado  a permissão ou grupo de permissão em referência. **[Histórias relacionadas #55 #56 #104 #185]**

|**RN016**| 
|-------------------------------------------------------------------------------------|

O campo **Esfera** deverá exibir as opções: **[Histórias relacionadas #46 #106 #107]**

- Federal

- Distrital

- Estadual

- Municipal

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_esfera_publica/rl_ente_federa_esfera_programa

              

|**RN017**| 
|-------------------------------------------------------------------------------------|

O campo **Meta PNE** deverá exibir as opções: **[Histórias relacionadas #103 #104]**

- Meta 01 até Meta 20

|**RN018**| 
|-------------------------------------------------------------------------------------|

Todos os campos serão de preenchimento obrigatório. **[Histórias relacionadas #46 #47 #54 #55 #28 #117 #119 #121]**

Caso o usuário deixe de preencher um dos campos, o sistema deverá exibir mensagem de alerta no topo da tela **[[MSGE004](https://gitlabbuilder.mec.gov.br/doc-sis/documentacao-pigp/-/issues/29)]** e marcar o campo na cor vermelha com a mensagem de indicação abaixo do campo . **[[MSGE005](https://gitlabbuilder.mec.gov.br/doc-sis/documentacao-pigp/-/issues/29)]**

|**RN019**| 
|-------------------------------------------------------------------------------------|

O sistema deverá permitir ao usuário acionar a opção **'Avançar'** sem que seja selecionado nenhum dos campos. **[Histórias relacionadas #103]**

|**RN020**| 
|-------------------------------------------------------------------------------------|

O campo **Fases do Programa** deverá exibir as opções: **[Histórias relacionadas #104]**

- Diagnóstico

- Planejamento

- Adesão

- Análise

- Repasse Financeiro

- Prestação de Contas

- Acompanhamento

- Gestão Escolar

- Execução Financeira


**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_fase/rl_fase_programa

|**RN021**| 
|-------------------------------------------------------------------------------------|

O campo **Eixo Estratégico** deverá exibir as opções: **[Histórias relacionadas #104]**

- Eixo 1 Resultados

- Eixo 2 Intervenção Direta

- Eixo 3 Intervenção Parcial ou Direta

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_eixo_estrat/rl_eixo_estrat_programa

|**RN022**| 
|-------------------------------------------------------------------------------------|

O campo **Dimensão** deverá exibir as opções: **[Histórias relacionadas #104]**

- Gestão Educacional - Estadual

- Formação de Profissionais da Educação - Estadual

- Práticas Pedagógicas e Avaliação - Estadual

- Infraestrutura Física e recursos pedagógicos - Estadual


**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_area_indicador_gestao/rl_dmso_indicador_programa


|**RN023**| 
|-------------------------------------------------------------------------------------|

O campo **Meio para Financiamento** deverá exibir as opções: **[Histórias relacionadas #104]**

- Custeio

- Capital

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_meio_financiamento

|**RN024**| 
|-------------------------------------------------------------------------------------|

O campo **Orçamento** deverá exibir as opções: **[Histórias relacionadas #104]**

- Empenho

- Pagamento

- Orçamento de Investimento

- Orçamento Custeio

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_tipo_orcamento_programa

|**RN025**| 
|-------------------------------------------------------------------------------------|

O campo **Indicador PNE** deverá exibir as opções: **[Histórias relacionadas #104]**

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_indicador_pne

|**RN026**| 
|-------------------------------------------------------------------------------------|

O campo **Tipo de População** deverá exibir as opções: **[Histórias relacionadas #104]**
 
- Quilombola

- Ribeirinhos

- Pescadores Artesanais

- Extrativistas

- Agricultores Familiares

- Assentados de Reforma Agrária

- Indígenas

- Caiçaras

- Outros

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_tipo_populacao


|**RN027**| 
|-------------------------------------------------------------------------------------|

Os campos Esfera, UF e Município deverão ser relacionados conforme abaixo:

- Quando a seleção no campo **Esfera** for igual a **Federal**, os campos UF e Município , deverão exibir todas as opções da lista.
Sendo o campo Município dependente do campo UF que deverá exibir os Município relaciodos as UF's.

- Quando a seleção no campo **Esfera** for igual a **Estadual**, o campo UF deverá exibir todas as opções da lista e o campo Município exibir todos Município  relacionados as UF's selecionadas.

- Quando a seleção no campo **Esfera** for igual a **Município**, os campos UF e Município, deverão exibir todas as opções da lista.


|**RN028**| 
|-------------------------------------------------------------------------------------|

O campo **Modalidade de Ensino** deverá exibir as opções: **[Histórias relacionadas #104]**

- Educação Infantil

- Ensino Médio

- Educação Especial

- Educação Profissional

- Ensino Fundamental

- EJA

- Educação Especial Classes especiais e exclusivas 

- Alunos em tempo integral

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_modalidade_ensn


|**RN029**| 
|-------------------------------------------------------------------------------------|

O campo **Etapas de Ensino** deverá exibir as opções: **[Histórias relacionadas #104]**

- Creche

- Pré-escola

- Ensino Médio

- Ensino Fundamental

- Concomitante

- Integrado Regular

- Integrado EJA

- Subsequente

- Normal Magistério

- Projovem Urbano

- RC Fundamental, Médio e Concomitante

- Anos Iniciais


**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_etapa_ensn

|**RN030**| 
|-------------------------------------------------------------------------------------|

O campo **Infraestrutura** deverá exibir as opções: **[Histórias relacionadas #104]**

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_infra

|**RN031**| 
|-------------------------------------------------------------------------------------|

O campo **Desdobramento** deverá exibir as opções: **[Histórias relacionadas #104]**

- Urbana

- Rural

- Parcial

- Integral

- Diurno

- Noturno

- Atendimento Educacional Especializado (AEE)

- Atividade Complementar

- Classe Hospitalar

- Unidade de Atendimento Socioeducativo

- Unidade Prisional

- Educação para Povos Ciganos e Situação de Intinerância 


**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_desd

|**RN032**| 
|-------------------------------------------------------------------------------------|

O campo **Recurso** deverá exibir as opções: **[Histórias relacionadas #104]**

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_recurso_financeiro

|**RN033**| 
|-------------------------------------------------------------------------------------|

Quando a opção selecionada no campo **Tipo de População** for igual a **Outros**, o sistema deverá habilitar campo de texto para que o usuário informe obrigatóriamente os demais tipos de população. 

|**RN034**| 
|-------------------------------------------------------------------------------------|



|**RN035**| 
|-------------------------------------------------------------------------------------|

O campo **Modalidade de Ensino** e **Etapas de Ensino** deverão ser relacionados conforme abaixo: **[Histórias relacionadas]**

- Quando a opção selecionada for **‘Todos’** o campo **‘Etapas de Ensino’** deverá exibir todas as opções:

  - Creche

  - Pré-escola

  - Ensino Fundamental

  - Ensino Médio

  - Anos Iniciais

  - Anos Finais

  - Concomitante

  - Integrado Regular

  - Integrado EJA

  - Subsequente

  - Normal Magistério

  - Projovem Urbano

  - RC Fundamental, Médio e Concomitante

- Quando a opção selecionada for **‘Educação Infantil’** o campo ‘**Etapas de Ensino’** deverá exibir as opções:

  - Todos 

  - Creche

  - Pré-escola

- Quando a opção selecionada for **‘Ensino Médio’** o campo **‘Etapas de Ensino’** deverá exibir a opção:

  - Ensino Médio

- Quando a opção selecionada for **‘Ensino Especial’** o campo **‘Etapas de Ensino’** deverá exibir as opções:

  - Todos

  - Ensino Fundamental

  - Ensino Médio

- Quando a opção selecionada for **‘Educação Profissional’** o campo **‘Etapas de Ensino’** deverá exibir as opções:

  - Todos

  - Concomitante

  - Integrado Regular

  - Integrado EJA

  - Subsequente

  - Normal Magistério

  - Projovem Urbano

  - RC Fundamental, Médio e Concomitante

- Quando a opção selecionada for **‘Ensino Fundamental’** o campo **‘Etapas de Ensino’** deverá exibir as opções:

  - Todos

  - Anos Iniciais

  - Anos Finais

- Quando a opção selecionada for **‘EJA’** ou **‘Educação Especial Classes especiais e exclusivas’** o campo **‘Etapas de Ensino’** deverá exibir as opções:

  - Todos

  - Ensino Fundamental

  - Ensino Médio

- Quando a opção selecionada for **‘Alunos em tempo integral’** o campo **‘Etapas de Ensino’** deverá exibir as opções:

  - Todos

  - Creche

  - Pré-escola

  - Ensino Fundamental

  - Ensino Médio

|**RN036**| 
|-------------------------------------------------------------------------------------|

Os dados das **Solicitações de Acesso** deverão ser recuperadas do módulo **Gerenciar Acesso**>>**Meus Programas**>>**Solicitar Acesso**.  **[Histórias relacionadas #106 #107]**

|**RN037**| 
|-------------------------------------------------------------------------------------|

Os dados do usuário deverão ser recuperados do módulo **Manter usuário** >> opção **Incluir Usuário** e do módulo **Meus Programas** >> opção **Solicitar Acesso**. **[Histórias relacionadas #107]**

|**RN038**| 
|-------------------------------------------------------------------------------------|

As opções **'Excluir'** e **'Editar'** serão exibidas habilitadas somente quando não houver nenhuma permissão vinculado a funcionalidade em referência. **[Histórias relacionadas #97 ]** 

|**RN039**| 
|-------------------------------------------------------------------------------------|

Os dados exibidos no resultado da pesquisa deverão ser recuperados da funcionalidade [**'Incluir Perfil'**](#98) e [**'Editar Perfil'**](#100).

|**RN040**| 
|-------------------------------------------------------------------------------------|

As opções **'Excluir'** e **'Editar'** serão exibidas habilitadas somente quando não houver nenhum usuário vinculado ao perfil em referência. **[Histórias relacionadas #99 #109 #100 #101]** 

|**RN041**| 
|-------------------------------------------------------------------------------------|

Ao selecionar o **'Programa'** o sistema deverá exibir a tela **‘Vincular Funcionalidade’** com a lista de funcionalidades e permissões cadastradas para aquele programa.  **[Histórias relacionadas #98 #100]**

|**RN042**| 
|-------------------------------------------------------------------------------------|

O sistema deverá realizar o vínculo/desvínculo do perfil de acordo com a seleção do usuário por funcionalidade e permissão. **[Histórias relacionadas #98 #100]**

|**RN043**| 
|-------------------------------------------------------------------------------------|

Os campos da opção **'Editar'** serão exibidos habilitados somente quando não houver nenhum usuário vinculado ao perfil em referência. Caso haja usuários vinculados, o sistema deverá permitir edição apenas do 'vincular/desvincular' funcionalidade. **[Histórias relacionadas]**


|**RN044**| 
|-------------------------------------------------------------------------------------|

O campo **Unidade Orçamentária** deverá exibir as opções: **[Histórias relacionadas #46 #121 #28]**

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_unidade_orcamentaria


|**RN045**| 
|-------------------------------------------------------------------------------------|
 
O campo deverá exibir a lista de perfis relacionada ao programa selecionado pelo usuário, utilizando-se da funcionalidade manter perfil. **[Histórias relacionadas #107 #116 #122 #124]**


|**RN046**| 
|-------------------------------------------------------------------------------------|

O campo deverá exibir a opção Todos e permitir ao usuário selecionar uma ou mais opções da lista.

|**RN047**| 
|-------------------------------------------------------------------------------------|

O sistema deverá verificar se o nome indicado já encontra-se cadastrado, caso positivo sinalizar ao usuário e não permitir a inclusão. **[[MSGA002](https://gitlabbuilder.mec.gov.br/doc-sis/documentacao-pigp/-/issues/29)]**  **[Histórias relacionadas #54 #46 #172 #183]**

|**RN048**| 
|-------------------------------------------------------------------------------------|

Quando o usuário selecionar  como campos complementares os campos Meta PNE e Indicador PNE os campos deverão ser relacionados:

Ao selecionar no campo Meta PNE a opção Meta 1
O campo Indicador PNE deverá exibir as opções:

|**RN049**| 
|-------------------------------------------------------------------------------------|

O campo **'Funcionalidade'** deverá recuperar e exibir para seleção a lista de funcionalidades cadastradas no sistema. utilizando-se da opção **Incluir Funcionalidade** **[Histórias relacionadas #57 #58]**

|**RN050**| 
|-------------------------------------------------------------------------------------|

O campo **'Perfil'** deverá recuperar e exibir para seleção a lista de perfis cadastrados no sistema, utilizando-se da funcionalidade 'Manter Perfil'. **[Histórias relacionadas #106]**

|**RN051**| 
|-------------------------------------------------------------------------------------|

O campo **'Status'** deverá exibir as opções: **[Histórias relacionadas #116]**

- Ativo

- Inativo

|**RN052**| 
|-------------------------------------------------------------------------------------|

O campo **'Cargo'** e **'Função'**  deverão exibir a lista de cargos e funções existentes no MEC. **[Histórias relacionadas #106 #116 #28]**

**Banco:** DBPIGP

**table_schema:** autmec

**table_name:** tb_usua

**column_name:** co_seq_cargo

|**RN053**| 
|-------------------------------------------------------------------------------------|

Os dados exibidos no resultado da pesquisa deverão ser recuperados da funcionalidade [**'Incluir Usuário'**](#117), [**'Editar Usuário'**](#119) e [**'Solicitar Acesso'**](#28) **[Histórias relacionadas #116 #158 ]**


|**RN054**| 
|-------------------------------------------------------------------------------------|

Os campos com a chave de pesquisa **CPF**, deverá ser recuperado e validado de acordo com a base da Receita Federal. **[Histórias relacionadas #117 #28 ]**


|**RN055**| 
|-------------------------------------------------------------------------------------|

Dado recuperado da base da Receita Federal de acordo com o **CPF** informado, desabilitada a alteração. **[Histórias relacionadas #117 #119]**

|**RN056**| 
|-------------------------------------------------------------------------------------|

O campo com dados recuperados da Receita Federal não poderão ser editados. **[Histórias relacionadas #117]**

|**RN057**| 
|-------------------------------------------------------------------------------------|

O campo **‘CPF'** deverá receber somente números, ao inserir o dados o sistema deverá verificar se é um dado válido. **[Histórias relacionadas #117 #28]**

|**RN058**| 
|-------------------------------------------------------------------------------------|

O campo **‘Nome ’** deverá ser autocomplete, a partir do 3° caractere o sistema deverá exibir a lista, possibilitando ao usuário a seleção de um dos nomes relacionados. **[Histórias relacionadas #116]**


|**RN059**| 
|-------------------------------------------------------------------------------------|




|**RN060**| 
|-------------------------------------------------------------------------------------|


O campo **Gênero** deverá exibir as opções: **[Histórias relacionadas #117 #28]**

- Feminino

- Masculino

- Não Especificado

| **RN061** |
|-----------|


O campo **‘CEP'** deverá receber somente números, ao inserir o dados o sistema deverá verificar se é um dado válido. **[Histórias relacionadas #117]**


| **RN062** |
|-----------|

Os campos de pesquisa **CEP**, deverá ser recuperado e validado de acordo com a base de dados do SERPRO. **[Histórias relacionadas #117 #28]**


|**RN063**| 
|-------------------------------------------------------------------------------------|

Dado recuperado da base do SERPRO de acordo com o **CEP** informado. **[Histórias relacionadas #117]**

|**RN0064**| 
|-------------------------------------------------------------------------------------|

O campo **Órgão/Instituição** deverá exibir as opções: **[Histórias relacionadas #117 #121 #28]**

- A definir


|**RN065**| 
|-------------------------------------------------------------------------------------|



|**RN066**| 
|-------------------------------------------------------------------------------------|

O campo **Unidade Gestora** deverá exibir as opções: **[Histórias relacionadas  #121 #28]**

- A definir

|**RN067**| 
|-------------------------------------------------------------------------------------|

O campo **Cargo Eletivo** deverá exibir as opções: **[Histórias relacionadas  #121 #28]**

- Sim

- Não

|**RN068**| 
|-------------------------------------------------------------------------------------|

Os campos menu, submmenu e aba deverão capturar e exibir os dados utilizando-se da funcionalidade [Manter Menu](#105), caso não exista o dado cadastrado no menu, a lista deverá vir com hífen (-) na coluna  referente.

|**RN069**| 
|-------------------------------------------------------------------------------------|

O sistema deverá validar se o "Programa" e "Perfil" selecionados para o usuário já existem, caso a seleção seja de uma informação já existente o sistema deverá alertar o usuário e impedir o cadastro.


|**RN070**| 
|-------------------------------------------------------------------------------------|

Caso o usuário não tenha conta no Acesso.gov.br o mesmo deverá criá-lo para acessar o sistema PIGP.


|**RN071**| 
|-------------------------------------------------------------------------------------|

Ao selecionar a opção "Manter-me conectado" o sistema deverá manter salva as informações de login do usuário.


| **RN072** |
|-----------|

As opções **'Excluir'** e **'Editar'** serão exibidas habilitadas somente quando o usuário não tiver acessos a programas  cadastrados.  **[Histórias relacionadas #120]**

| **RN073** |
|-----------|

O sistema deverá exibir campo de imagem com uma imagem padrão e possibilitar ao usuário selecionar uma imagem em formato jpg. da sua preferência.  **[Histórias relacionadas #158 #161 #162 ]**

| **RN074** |
|-----------|

Os campos de **Data Início da Função** e **Data Fim da Função** serão habilitados somente quando a opção selecionada no campo **Cargo Eletivo** for igual a **Sim**.  **[Histórias relacionadas #162]**


| **RN075** |
|-----------|

Caso o usuário esteja acessando o sistema através do ambiente interno do MEC, o sistema deverá trazer o campo usuário preenchido. **[Histórias relacionadas #160]**


| **RN076** |
|-----------|

A exclusão deverá ser apenas lógica na base de dados. **[Histórias relacionadas #97]**


| **RN077** |
|-----------|

Caso o usuário selecione o ícone de status, a permissão do usuária deverá ser alterada para posição contrária a que está "ativa para inativa" ou "inativa para ativa" o sistema deverá armazenar o status e retirar o acesso do programa e perfil do usuário.    


| **RN078** |
|-----------|

Ao realizar o cadastro o sistema inseri uma linha na lista de Programas Cadastrados com o status "ativo" e ícone que sinaliza este status [indicação verde].


| **RN079** |
|-----------|

Toda a ação de inclusão, alteração e exclusão no sistema em todas as funcionalidades, deverão ser armazenadas para fins de log de auditoria. Deve ser identificado o usuário que realizou a transação, data/hora (timestamp) e o tipo da transação realizada.
**[Histórias relacionadas #170]**

| **RN080** |
|-----------|

A exibição de informações da **ação realizada** em [**'Visualizar Log de Auditoria'**](#170), deverá exibir:

- Todos os campos obrigatórios da funcionalidade quando for ação de inclusão ou exclusão.
- Todos os campos alterados na funcionalidade quando for ação de alteração.
**[Histórias relacionadas #170]**


| **RN081** |
|-----------|

No filtro de pesquisa o sistema não deverá permitir ao usuário realizar a pesquisa sem que tenha preenchido pelo menos um dos parametros exibidos.

| **RN082** |
|-----------|

Ao selecionar a opção voltar, o sistema deverá retornar para a tela de pesquisa, com a consulta realizada mantida no resultado.  **[Histórias relacionadas  #47 #95  #96 #97 #100 #101 #118 #119 #123 #124 #155 #156 #170 #170 #185]**

| **RN083** |
|-----------|

Exibir a lista de opções em ordem alfabética. **[Histórias relacionadas #171 #175 #176 #177 #178 #183]**

| **RN084** |
|-----------|

Exibir a lista de opções em ordem crescente

| **RN085** |
|-----------|

A opção deverá exibir a lista de programas cadastrados na Plataforma que tenham funcionalidades cadastradas no módulo Funcionalidade. 

O campo deverá ser múltipla seleção, onde o usuário poderá selecionar uma ou mais opções da lista.

**[Histórias relacionadas #171 #174 #176 #177 #178]**


| **RN086** |
|-----------|

As opções Expandir o Detalhamento do Menu e Visualizar Arvore do Menu serão exibidas somente após o programa possuir pelo menos um menu cadastrado. **[Histórias relacionadas #171]**

| **RN087** |
|-----------|

A opção ordenar, permite ao usuário definir a posição em que o menu será exibido, o sistema deverá permitir a ordenação apenas de menus do mesmo tipo. **[Histórias relacionadas #171]**

O ícone deverá ser exibido desabilitado caso não tenha mais de um menu com o mesmo tipo.


| **RN088** |
|-----------|

O campo Vísivel deverá exibir as opções Sim ou Não, sendo SIm para que o módulo cadastrado esteja vísivel no sistema para todos os perfis selecionados e a opção Não o módulo cadastrado ainda não estará visivel para os usuários. **[Histórias relacionadas #172 #173 #115 #174]**


| **RN089** |
|-----------|

O campo Acesso rápido deverá exibir as opções Sim ou Não, sendo sim para que o módulo cadastrado seja exibido na opção de acesso rápido e a opção Não, o módulo não será exibido no acesso rápido. **[Histórias relacionadas #172 #173 #115 #174]**

| **RN090** |
|-----------|

A opção excluir deverá ser exibida habilitada somente para o menor menu ( hierarquicamente) cadastrado.  O usuário só poderá realizar a exclusão do menor menu para o maior. **[Histórias relacionadas #171]**

| **RN091** |
|-----------|

Os dados exibidos no relatório deverão ser recuperados da funcionalidade  [**'Incluir Grupo de Permissão'**](#183) e [**'Editar Grupo de Permissão'**](#184). **[Histórias relacionadas  #183 #184]**



| **RN092** |
|-----------|

A lista deve conter 8 (oito) ou mais permissões selecionados para a criação de um grupo de permissão, caso contrário deverá ser exibida mensagem de alerta para o usuário. [**[[MSGE018](#29)]]. **[Histórias relacionadas  #183 #184]**


| **RN093** |
|-----------|

O nome exibido deverá ser a junção dos campos [nome da permissão] + [programa selecionado]. **[Histórias relacionadas  #183, #184 e #148]**



| **RN094** |
|-----------|

Ao selecionar a opção [+] o sistema inclui na lista de permissões o nome da funcionalidade e sua(s) respectiva(s) permissão(ões) vinculada(s). **[Histórias relacionadas  #183, #184]**

| **RN095** |
|-----------|

Ao selecionar a opção [-] o sistema retira na lista de permissões o nome da funcionalidade e sua(s) respectiva(s) permissão(ões) vinculada(s). **[Histórias relacionadas  #183, #184]**


| **RN096** |
|-----------|

O sistema exibe a lista de funcionalidades de acordo com o programa selecionado. **[Histórias relacionadas  #183, #184]**

| **RN097** |
|-----------|

A lista de permissões deve vir abaixo do nome da funcionalidade selecionada. **[Histórias relacionadas  #183, #184]**


| **RN098** |
|-----------|

Vincular funcionalidade será exibido quando o usuário selecionar somente o campo **'Programa'**. **[Histórias relacionadas  #148]**


| **RN099** |
|-----------|

Vincular Grupo de Permissão será exibido na funcionalidade quando o usuário selecionar o campo **'Programa'** + **'Grupo de Permissão'**. **[Histórias relacionadas  #148]**


| **RN0100** |
|-----------|

Caso o usuário selecione 8 ou mais permissões para vinculo ao perfil, o sistema deve exibir mensagem para criar um Grupo de Permissão, se o usuário selecionar **'sim'** o sistema deve direciona-lo para a tela **'[Incluir Grupo de Permissão' #183]**, caso o usuário selecione **'não'** o sistema permanece na tela  **'[Incluir Perfil' #98]**
 [Histórias relacionadas  #148]**


| **RN0101** |
|-----------|


O sistema deverá validar as permissões selecionadas, caso já exista cadastrado um grupo de permissão com as mesmas permissões selecionadas, o sistema deverá informar o usuário e impedir o cadastro do grupo de permissões. **[Histórias relacionadas  #183, #184]**



| **RN0102** |
|-----------|


Caso o grupo de permissão esteja vinculado à um perfil, o sistema deverá permitir apenas a inclusão de novas permissões no grupo, não será possível retirar as permissões já selecionadas para este grupo.  **[Histórias relacionadas  #184]**

| **RN0103** |
|-----------|

O sistema deverá exibir a lista de programas conforme a Esfera, UF e Município indicada pelo usuário. **[Histórias relacionadas  #098]**

| **RN0104** |
|-----------|

O campo status deverá exibir as opções. **[Histórias relacionadas  #106]**

- Pendente de Aprovação
- Aprovado
- recusado
- Todos

[Texto do link](#my-section)

| **RN0105** |
|-----------|

A opção Abrir solicitação será exibida somente quando o usuário tiver perfil de administrador e quando a solicitação estiver com status **Pendente de Aprovação**. #106]**


