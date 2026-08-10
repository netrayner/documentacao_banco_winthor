# 📊 Tabela: PCBIONEXOPDCC

### Estrutura de Colunas e Restrições

       Tabela                 Coluna   Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBIONEXOPDCC                 ID_PDC   NUMBER(10,0)                   Número da cotação    CHAVE PRIMÁRIA (PK)                        NaN
PCBIONEXOPDCC             TITULO_PDC  VARCHAR2(100)                   Título da cotação            OPERACIONAL                        NaN
PCBIONEXOPDCC        DATA_VENCIMENTO           DATE                  Data de vencimento            OPERACIONAL                        NaN
PCBIONEXOPDCC        HORA_VENCIMENTO           DATE                  hora de vencimento            OPERACIONAL                        NaN
PCBIONEXOPDCC          NOME_HOSPITAL  VARCHAR2(100)                     Nome do cliente            OPERACIONAL                        NaN
PCBIONEXOPDCC          CNPJ_HOSPITAL   VARCHAR2(20)                     CNPJ do cliente            OPERACIONAL                        NaN
PCBIONEXOPDCC                CONTATO  VARCHAR2(100)                  Contato do cliente            OPERACIONAL                        NaN
PCBIONEXOPDCC     ID_FORMA_PAGAMENTO   NUMBER(10,0)        Código da forma de pagamento            OPERACIONAL                        NaN
PCBIONEXOPDCC        FORMA_PAGAMENTO  VARCHAR2(100)     Descrição da forma de pagamento            OPERACIONAL                        NaN
PCBIONEXOPDCC             OBSERVACAO VARCHAR2(4000)               Observação da cotação            OPERACIONAL                        NaN
PCBIONEXOPDCC                  TERMO  VARCHAR2(200)                    Termo da cotação            OPERACIONAL                        NaN
PCBIONEXOPDCC        TERMO_CONDICOES VARCHAR2(4000)       Condições do termo da cotação            OPERACIONAL                        NaN
PCBIONEXOPDCC       ENDERECO_ENTREGA  VARCHAR2(150)                 Endereço de entrega            OPERACIONAL                        NaN
PCBIONEXOPDCC FATURAMENTO_MINIMO_ENV   NUMBER(12,6)         Valor do faturamento mínimo            OPERACIONAL                        NaN
PCBIONEXOPDCC      PRAZO_ENTREGA_ENV    NUMBER(3,0)                    Prazo de entrega            OPERACIONAL                        NaN
PCBIONEXOPDCC  VALIDADE_PROPOSTA_ENV           DATE        Data de validade da proposta            OPERACIONAL                        NaN
PCBIONEXOPDCC ID_FORMA_PAGAMENTO_ENV   NUMBER(10,0) Identificação da forma de pagamento            OPERACIONAL                        NaN
PCBIONEXOPDCC              FRETE_ENV    VARCHAR2(3)                               Frete            OPERACIONAL                        NaN
PCBIONEXOPDCC        OBSERVACOES_ENV VARCHAR2(3000)              Observações da cotação            OPERACIONAL                        NaN
PCBIONEXOPDCC             MSGULT_ENV VARCHAR2(4000)             Última mensagem enviava            OPERACIONAL                        NaN
PCBIONEXOPDCC              CODFILIAL    VARCHAR2(2)                    Código da filial            OPERACIONAL                        NaN
PCBIONEXOPDCC           DTIMPORTACAO           DATE                  Data de importação            OPERACIONAL                        NaN
PCBIONEXOPDCC          DTCONFIRMACAO           DATE                 Data de confirmação            OPERACIONAL                        NaN
PCBIONEXOPDCC                 CODCLI    NUMBER(6,0)                   Código do cliente            OPERACIONAL                        NaN
PCBIONEXOPDCC                CODUSUR    NUMBER(4,0)                   Código do usuário            OPERACIONAL                        NaN
PCBIONEXOPDCC                     UF    VARCHAR2(2)                  Unidade Federativa            OPERACIONAL                        NaN
PCBIONEXOPDCC                 NUMPED   NUMBER(10,0)                    Número do pedido            OPERACIONAL                        NaN
PCBIONEXOPDCC              NUMPEDRCA   NUMBER(10,0)         Número do pedido da cotação            OPERACIONAL                        NaN
PCBIONEXOPDCC                 STATUS    VARCHAR2(1)                    Status do pedido            OPERACIONAL                        NaN
PCBIONEXOPDCC              DTENTREGA           DATE                     Data de entrega            OPERACIONAL                        NaN
PCBIONEXOPDCC            OBSENTREGA1   VARCHAR2(75)               Observação de entrega            OPERACIONAL                        NaN
PCBIONEXOPDCC            OBSENTREGA2   VARCHAR2(75)               Observação de entrega            OPERACIONAL                        NaN
PCBIONEXOPDCC            OBSENTREGA3   VARCHAR2(75)               Observação de entrega            OPERACIONAL                        NaN
PCBIONEXOPDCC            OBSENTREGA4   VARCHAR2(75)               Observação de entrega            OPERACIONAL                        NaN
PCBIONEXOPDCC     DATACANCELRESPOSTA           DATE Cancelamento de resposta de cotação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*