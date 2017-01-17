![img_spms.png](Ficheiros_de_suporte/Logos/logotipo_SICC_262x140.png)

# Reposição de Pagamentos e Cobranças

``Os direitos de autor deste trabalho pertencem à SPMS e a informação nele contida é confidencial.``

``Este trabalho não pode ser reproduzido ou divulgado, na íntegra ou em parte, a terceiros nem utilizado para outros fins que não aqueles para que foi fornecido sem a autorização escrita prévia ou, se alguma parte do mesmo for fornecida por virtude de um contrato com terceiros, segundo autorização expressa de acordo com esse contrato. Todos os outros direitos e marcas são reconhecidos.``

``As cópias impressas não assinadas representam versões não controladas. ``

---

# Índice

1. [Introdução](#introducao)
2. [Reposição Abatida aos Pagamentos](#rap)
3. [Reposição Não Abatida nos Pagamentos](#rnap)
4. [Resumo](#resumo)


<a name="introducao"></a>
# 1. Introdução

A reposição de pagamentos e cobranças dividem-se em RAP/RNAP, no sistema SICC e surge sempre que é detetado um pagamento/cobrança indevido do organismo, a um fornecedor/ cliente e é finalizada quando efetivado o pagamento/ recebimento.
Sempre que seja detetado um pagamento / recebimento indevido, deverá proceder à emissão de uma guia de reposição. Esta pode ser:

- Reposição Abatida aos Pagamentos (RAP), quando existe uma alteração a um pagamento já efetuado e são considerados contabilisticamente como Notas de Crédito ( NC);
- Reposição Não Abatida aos Pagamentos (RNAP) quando existe uma alteração a uma cobrança já efetuada e são consideradas contabilisticamente como CC;

<a name="rap"></a>
# 2. Reposição Abatida aos Pagamentos

![img_1.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_1.png)


As reposições abatidas nos pagamentos são todas as importâncias que abatem aos pagamentos realizados, libertando as dotações correspondentes, e têm as seguintes características comuns:
A existência de uma reposição abatida pressupõe que houve um pagamento excessivo em relação a uma determinada aquisição, cuja regularização é efetuada, no respetivo ano financeiro, através da correção da dotação utilizada e do respetivo saldo disponível, aumentando-o. Decorre deste entendimento que a reposição abatida aos pagamentos não seja tida como uma receita orçamental.

![img_2.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_2.png)

**Legenda:**
1. Esta corresponde a um documento (nota de crédito ou similar) emitida por um fornecedor, que tem associado o compromisso que deu origem ao pagamento indevido e que reflete o respetivo crédito;
2. O fornecedor paga guia de reposição e alerta Contabilidade para essa ocorrência;
3. Este movimento é efetuado através da conta 2529* e a respetiva classificação orçamental que deu origem ao pagamento indevido sendo debitado por contrapartida da compensação da partida em aberto da guia de reposição;
4. A conta de disponibilidades será debitada por contrapartida da compensação da liquidação da RAP;
5. Movimentar a conta de compromissos por contrapartida da conta de cabimentos.


Estas operações abatem aos pagamentos realizados, libertando as dotações correspondentes. Trata-se da situação que ocorre com as entregas de fundos relativas a pagamentos em excesso ou indevidos, ocorridos no ano em curso.

Desta forma, no menu:
![img_3.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_3.png)

Este mesmo registo de reposição pagamento poderá ser efetuado por uma das seguintes contas: 3*,4*,6* ou 7*.

![img_4.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_4.png)

![img_5.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_5.png)

Desta forma e para a despesa, o sistema SICC, identifica os documentos quando se efetuar o CE (automaticamente), no entanto demonstram-se os respetivos lançamentos:

![img_6.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_6.png)

NC – O processo de lançamento de uma Reposição de pagamento, é bastante similar a uma Nota de crédito convencional. Desta forma, todas as contas 2* (exceto a 25*) são movimentadas a débito, por contrapartida das contas 3*, 4*, 5*, 6*, 7*.

**Movimentação Contabilística: Lançar Nota de Crédito (doc. NC)**

![img_7.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_7.png)

CE – Na altura do lançamento do CE, a informação é proveniente do criado anteriormente na NC, sendo que a conta 2*passa a crédito e a conta 2529* a débito, com o classificador e económico e chave orçamental associado à conta 3*, 4*, 5*, 6*, 7* gerado anteriormente.

![img_8.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_8.png)

**Movimentação Contabilística: Liquidação da RAP (doc. CE)**

![img_9.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_9.png)

Finda a etapa, deve o utilizador confirmar a criação do CE e passar para o nível seguinte:

![img_10.png](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_10.png)

AP - Neste passo, pode-se efetuar a confirmação sem associar a fatura, pelo facto de se tratar de uma Reposição abatida aos pagamentos. Desta forma, todos os lançamentos aqui demonstrados, são provenientes da CE. Este movimento não é refletido na contabilidade. O valor deste documento será negativo.

![img_11](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_11.png)

![img_12](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_12.png)

![img_13](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_13.png)

:warning: __Se se tratar de uma transferência bancária, é necessário acrescentar o movimento contabilístico da conta 111 (caixa) a débito por contrapartida da rubrica financeira gerada pelas contas 3; 4; 5; 6; 7.__

![img_14](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_14.png)

:warning:__Se o Documento for transferência Bancária na AP, o sistema irá acrescentar registo da 111* a Crédito pela conta 112* ou 113* de acordo com a seleção efetuada na conta bancária da AP.__

PG – No Pagamento, os movimentos criados na AP são replicados nesta etapa de criação.

![img_15](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_15.png)

O utilizador acede aos movimentos contabilísticos, sendo que para o efeito, tem novamente de pressionar o botão de “Confirme”.

![img_16](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_16.png)

**Movimentação Contabilística: Registo da entrada de Pagamento da RAP (doc. AP/PG)**

![img_17](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_17.png)

Na mesma altura e no AP, ao gerar contabilidade, o sistema, associado ao número do CP ou P2, irá realizar as seguintes regularizações.

**Movimentação Contabilística no NC (RAP ou NC “normal”) ao gerar contabilidade**

![img_18](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_18.png)

![img_19](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_19.png)

<a name="rnap"></a>
# 3. Reposição Não Abatida nos Pagamentos

![img_20](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_20.png)
As reposições não abatidas nos pagamentos abrangem as receitas provenientes das entradas de fundos em resultado de cobranças orçamentais indevidos.

![img_21](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_21.png)

**Legenda:**
1. A contabilidade analisa a cobrança indevida;
2. Este documento será registado debitando a conta do cliente por contrapartida da conta 3*; 4*; 5*; 6*;7* com introdução da respetiva classificação orçamental. Após registada a CC/RNAP, a mesma é enviada ao cliente;
3. Cliente efetua o pagamento para regularizar a cobrança indevida;
4. O programa de liquidação da receita permitirá selecionar a RNAP em aberto que se pretende transferir para a conta 2519*.

Desta forma, no menu:

![img_22](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_22.png)

Um novo ecrã surge com uma *checkbox* que permite ao utilizador, definir se trata de um CC ou uma RNAP. Este mesmo registo de reposição pagamento, igualmente à RAP, poderá ser efetuado por uma das seguintes contas: 3*,4*,6* ou 7* a débito, por contrapartida de uma 2* (expeto 25*).
Assim, e para efeitos de manual de  utilizador, demonstramos o processo de contabilização abaixo da RNAP.
Deve o utilizador escolher a entidade, bem como atribuir um número de documento com o respetivo valor. Tratando-se de uma RNAP, a *checkbox* tem de estar ativa.

![img_23](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_23.png)

![img_24](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_24.png)

Desta forma e para a receita, o sistema SICC, identifica os documentos quando se efetuar o CC (automaticamente).

![img_25](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_25.png)

CC – O processo de lançamento de uma Reposição de pagamento, é bastante similar a um crédito a clientes convencional. Desta forma, todas as contas 2* (exceto a 2529*) são movimentadas a débito, por contrapartida das contas 3*, 4*, 5*, 6*, 7*.

**Movimentação Contabilística: Registar RNAP (doc. CC)**

![img_26](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_26.png)

DE – Na altura do lançamento do DE, a informação é proveniente do criado anteriormente no CC, sendo que a conta 2* passa a crédito e a conta 2519* a débito, com o classificador económico associado à conta 3*, 4*, 5*, 6*, 7* gerado anteriormente no CC.

![img_27](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_27.png)

![img_28](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_28.png)

**Movimentação Contabilística: Liquidação da Receita (doc. DE)**

![img_29](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_29.png)

Finda a etapa, deve o utilizador confirmar a criação do CC e passar para o nível seguinte:
GR - Neste passo, pode-se efetuar a confirmação sem associar a fatura, pelo facto de se tratar de uma Reposição não abatida nos pagamentos. Desta forma, todos os lançamentos aqui demonstrados, são provenientes do CC.

![img_30](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_30.png)

![img_31](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_31.png)

![img_32](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_32.png)

**Movimentação Contabilística: Registo da entrada de Pagamento da RNAP (doc. GR/CO)**

![img_33](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_33.png)

![img_34](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_34.png)

No valor de caixa (folha de caixa) estes valores serão positivos, dado que as contas 1 são registadas a crédito e não a débito.
![img_35](Ficheiros_de_suporte/Reposicao_Pagamentos_Cobrancas/img_35.png)

<a name="resumo"></a>
# 4. Resumo

As RAP e RNAP são reposições de pagamentos e cobranças respetivamente. São tratadas contabilisticamente de forma diferente das notas de crédito (NC e CC) antes do Pagamento e da Cobrança.

Os seus registos contabilísticos resumem-se a:

### **RAP:**

|Registo contabilístico|Débito|Crédito|
|:---------------------|:-----|:------|
|Lançar Nota de Crédito (NC/RAP)|3*; 4*; 5*; 6*; 7*|22*/26*|
|Liquidação da RAP (CE)|2529*|22*/26*|
|Registo da entrada de Pagamento da RAP (AP/PG)|1*|2529*|
|Movimentação Contabilística no NC (Rap ou NC “normal”) ao gerar contabilidade|02700000|02600000|
|Movimentação Contabilística no NC (Rap ou NC “normal”) ao gerar contabilidade|02600000|02300000|

### **RNAP:**

|Registo contabilístico|Débito|Crédito|
|:---------------------|:-----|:------|
|Registar RNAP (CC)|3*; 4*; 5*; 6*; 7*|22*/26*|
|Liquidação da Receita (DE)|2519*|22*/26*|
|Registo da entrada de Pagamento da RNAP (GR/CO)|1*|2519*|