_# VERSÃO DE TRABALHO #_
=====

# Políticas de Segurança de Utilização SICC

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:0 orderedList:1 -->

1. [Sessão de utilização](#sesso-de-utilizao)
2. [Credenciais de acesso](#credenciais-de-acesso)
3. [Nome de utilizador](#nome-de-utilizador)
4. [Passwords](#passwords)
5. [Bloqueios de conta](#bloqueios-de-conta)
6. [Perfis](#perfis)
	1. [Relacionamento de perfis](#relacionamento-de-perfis)
	2. [Gestão de permissões](#gesto-de-permisses)
		1. [Menu Parametrização](#menu-parametrizao)
7. [Processos](#processos)
	1. [Alteração de Password](#alterao-de-password)
	2. [Pedido de criação de conta de utilizador](#pedido-de-criao-de-conta-de-utilizador)
8. [Sub-processos](#sub-processos)
	1. [Verifica formulário "Alterar Password"](#verifica-formulrio-alterar-password)
9. [Plano de Implementação](#plano-de-implementao)

<!-- /TOC -->

Neste capítulo encontram-se os requisitos aplicáveis à utilização do sistema por utilizadores locais, com o intuito de prevenir eventuais situações de risco para segurança das diversas partes interessadas no SICC e/ou para os dados nele contidos, quer sejam situações provocadas voluntária ou involunta
riamente por utilizadores legítimos ou ilegítimos, humanos ou virtuais. Além da identificação e definição dos requisitos, são indicadas as dependências entre elas bem como o período da sua aplicação.

### Sessão de utilização

Em cada posto de trabalho o sistema permite uma sessão de trabalho de cada vez, sendo que esta pode ser não autenticada (sem _login_) ou autenticada (com _login_).

-   Sessão não autenticada:

| # | Requisito | Descrição | Dependências | Início | Fim |
|---|---|----|----|----|----|
| 1.1 | Duração | Inicia-se após a abertura da janela do sistema ou após o logoff e termina com o início de uma sessão autenticada ou com o fecho da janela do sistema | n.d. | n.d. | n.d. |
| 1.2 | Funcionalidades sem autenticação | Restrição total a leitura/escrita de dados/informações confidenciais, nomeadamente: i) pedido de autenticação de utilizador (_login_), ii) seleção da data de trabalho e ano de utilizador, iii) pedido de alteração da password, iv) fecho da aplicação | n.d. | n.d. | n.d. |


-   Sessão autenticada:

| # | Requisito | Descrição | Dependências | Início | Fim |
|---|---|---|---|---|---|
| 1.3 | Duração | Inicia-se após a autenticação no sistema (_login_) e termina com o _logoff_ ou com o fecho da janela do sistema | n.d. | n.d. | n.d. |
| 1.4 | Duração máxima da sessão sem atividade | O utilizador pode permanecer ligado durante 15min sem interagir com aplicação | n.d. | n.d. | n.d. |
| 1.5 | Duração máxima da sessão com atividade | O utilizador pode permanecer ligado durante 600min (10h) desde que não seja detetada inatividade | n.d. | n.d. | n.d. |
| 1.6 | Funcionalidades com autenticação | Leitura e escrita de dados confidenciais, associadas ao seu perfil de utilização | n.d. | n.d. | n.d. |

### Credenciais de acesso

O acesso autenticado ao sistema requer sempre a introdução e validação prévia do conjunto singular "nome de utilizador & password". Este conjunto deve ser do conhecimento único do utilizador, sendo por isso recomendadas as seguintes boas práticas:

-   Limitação total do acesso de terceiros às credenciais de acesso ou a dados/informação que permitam a descoberta das credenciais de acesso;
-   Não registar em locais acessíveis a terceiros (ex.: cadernos, Post-Its®/notas aderentes, agendas);
-   Não registar o registo em sistemas de informação (ex.: ficheiros de texto, email, word, excel, telemóvel);
-   Não divulgar oralmente a password em âmbito profissional ou extraprofissional.

### Nome de utilizador

O nome de utilizador é singular e intransmissível no SICC.

| # | Requisito | Descrição | Dependências | Início | Fim |
|---|---|---|---|---|---|
| 3.1 | Criação do gestor local | A criação é feita pela equipa central do SICC | n.d. | n.d. | n.d. |
| 3.2 | Criação do utilizador local | A criação é feita pelo gestor local do SICC | n.d. | n.d. | n.d. |
| 3.3 | Composição | O nome de utilizador é formado com base no nome legal completo do utilizador e compõe-se apenas por letras maiúsculas | n.d. | n.d. | n.d. |
| 3.4 | Comprimento mínimo | Tem pelo menos 6 carateres | n.d. | n.d. | n.d. |
| 3.5 | Comprimento máximo | Tem no máximo 30 carateres | n.d. | n.d. | n.d. |
| 3.6 | Período de validade | O período de validade é variável e deve coincidente com a data de início e de fim de necessidade de acesso ao SICC | n.d. | n.d. | n.d. |

### Passwords

A password está associada a um único nome de utilizador, no entanto pode ser repetida no sistema.

| # | Requisito | Descrição | Dependências | Início | Fim |
| --- | --- | --- | --- | --- |--- |
| 4.1 | Criação inicial | A primeira password é definida manualmente pelo gestor local do sistema | n.d. | n.d. | n.d. |
| 4.2 | Reutilização | Tem de ser diferente das últimas 5 passwords definidas | n.d. | n.d. | n.d. |
| 4.3 | Validade máxima | n.d. | n.d. | n.d. | n.d. |
| 4.4 | Validade mínima | Se a nova password for definida manualmente tem a duração mínima de 24h mas se for definida automaticamente, não tem duração mínima e pode ser alterada imediatamente. | n.d. | n.d. | n.d. |
| 4.5 | Comprimento | Tem de conter, pelo menos, 8 caracteres | n.d. | n.d. | n.d. |
| 4.6 | Complexidade | Tem de conter, pelo menos, 2 dos 4 tipos de carateres diferentes: i) letras maiúsculas ii) letras minúsculas iii) números iv) símbolos (ex.: !, #, %) | n.d. | n.d. | n.d. |

### Bloqueios de conta

| # | Requisito | Descrição | Dependências | Início | Fim |
|---|---|---|---|---|---|
| 5.1 | Bloqueio por autenticações falhadas | Após 5 tentativas consecutivas de autenticação falhadas, a conta de utilizador é bloqueada automaticamente | n.d. | n.d. | n.d. |
| 5.2 | Duração do bloqueio por autenticações falhadas | A conta é desbloqueada automaticamente após 30minutos | n.d. | n.d. | n.d. |
| 5.3 | Duração entre tentativas falhadas | Após cada tentativa de autenticação falhada, o utilizador terá de aguardar 5 segundos até poder efetuar nova tentativa | n.d. | n.d. | n.d. |
| 5.4 | Bloqueio por ausência prolongada | Após 365 dias do último login no sistema, a conta é bloqueada automaticamente | n.d. | n.d. | n.d. |
| 5.5 | Duração do bloqueio por ausência prolongada | A conta é bloqueada até ser concluído o processo de desbloqueio | 5.4 | n.d. | n.d. |

### Perfis

JC: identificar e descrever cada perfil
JC: Propôr ao Luís que a gestão dos perfis de users fique do lado das entidades e do nosso lado fique a gestão dos perfis de gestores. Adicionalmente, criar um report que nos permita listar os users por entidade com as repetivas permissões


#### Relacionamento de perfis

JC: colocar diagrama com relacionamento(hierarquia) entre perfis

#### Gestão de permissões

JC: elaborar diagrama de ecrãs do SICC(mapa da aplicação)?? Ex: Capítulo Interface Gráfica

##### Menu Parametrização

| Caminho                                            | Administrador   | Gestor local | Utilizador local |
|----------------------------------------------------| --------------- | ------------ |------------------|
| Parametrização> Instituição> Recolha                                 | ------------ | ---------------- |
| Parametrização> Instituição> Exercícios                              | ------------ | ---------------- |
| Parametrização> Instituição> Configurações                           | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Códigos Postais> Recolha          | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Códigos Postais> Listagens        | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Bancos> Recolha                   | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Bancos> Listagens                 | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Fatores de Aglutinação> Recolha   | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Fatores de Aglutinação> Listagens | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Tipos de Entidade> Recolha        | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Tipos de Entidade> Listagens      | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Instituições Bancárias> Recolha   | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Instituições Bancárias> Listagens | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> Responsáveis                      | ------------ | ---------------- |
| Parametrização> Tabelas Genéricas> R.O.C.                            | ------------ | ---------------- |

Legenda:
-   **L** - Permite leitura de informação;
-   **G** - Permite gravação de informação;
-   **E** - Permite consulta, introdução e eliminação de informação;

### Processos

#### Alteração de Password

![Alteração de Password](assets/alteracao_de_password.svg)

#### Pedido de criação de conta de utilizador

### Sub-processos

#### Verifica formulário "Alterar Password"
![]()

### Plano de Implementação
