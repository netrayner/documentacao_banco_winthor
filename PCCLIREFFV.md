# 📊 Tabela: PCCLIREFFV

### Estrutura de Colunas e Restrições

    Tabela           Coluna   Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIREFFV        IMPORTADO    NUMBER(1,0)           Flag de importação do pedido            OPERACIONAL                        NaN
PCCLIREFFV           CGCCLI   VARCHAR2(18)                     cgc/Cpf do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIREFFV           CODREF    NUMBER(2,0) sequencial para referencia por cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIREFFV           CODCLI    NUMBER(6,0)                      Codigo do cliente            OPERACIONAL                        NaN
PCCLIREFFV         EMPREFER   VARCHAR2(40)                     nome da referencia            OPERACIONAL                        NaN
PCCLIREFFV         TELREFER   VARCHAR2(13)                 Telefone da referencia            OPERACIONAL                        NaN
PCCLIREFFV     CONTATOREFER   VARCHAR2(40)                  Contato da referencia            OPERACIONAL                        NaN
PCCLIREFFV     LIMCREDREFER   NUMBER(14,2)                      Limite de credito            OPERACIONAL                        NaN
PCCLIREFFV  DTCADASTROREFER           DATE         Data de cadastro da referencia            OPERACIONAL                        NaN
PCCLIREFFV   DTULTCOMPREFER           DATE                  Data da ultima compra            OPERACIONAL                        NaN
PCCLIREFFV   VLULTCOMPREFER   NUMBER(14,2)                 Valor da ultima compra            OPERACIONAL                        NaN
PCCLIREFFV              OBS   VARCHAR2(80)                             Observação            OPERACIONAL                        NaN
PCCLIREFFV DTMAIORCOMPREFER           DATE                   Data da maior compra            OPERACIONAL                        NaN
PCCLIREFFV VLMAIORCOMPREFER   NUMBER(14,2)                  Valor da maior compra            OPERACIONAL                        NaN
PCCLIREFFV      CODCOBREFER    VARCHAR2(4)                     Codigo de cobrança            OPERACIONAL                        NaN
PCCLIREFFV    OBSERVACAO_PC VARCHAR2(4000)         Mensagem de retorno da package            OPERACIONAL                        NaN
PCCLIREFFV       DTINCLUSAO           DATE Data de inclusão do registro na tabela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*