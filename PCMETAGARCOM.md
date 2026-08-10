# 📊 Tabela: PCMETAGARCOM

### Estrutura de Colunas e Restrições

      Tabela                  Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAGARCOM               MATRICULA  NUMBER(8,0)                        Matricula do garçom    CHAVE PRIMÁRIA (PK)                     PCEMPR
PCMETAGARCOM                    DATA         DATE                       Data da movimentação    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAGARCOM             VLVENDAPREV NUMBER(22,6)             Valor da venda prevista / meta            OPERACIONAL                        NaN
PCMETAGARCOM                 VLVENDA NUMBER(22,6)                   Valor de venda realizada            OPERACIONAL                        NaN
PCMETAGARCOM             VLDEVOLUCAO NUMBER(22,6)                         Valor da devolução            OPERACIONAL                        NaN
PCMETAGARCOM          VLVENDALIQUIDA NUMBER(22,6)                     Valor de venda líquida            OPERACIONAL                        NaN
PCMETAGARCOM        PRCVENDAATINGIDO NUMBER(18,6)  Percentual da venda atigindo sobre a meta            OPERACIONAL                        NaN
PCMETAGARCOM           QTCLIENTEPREV NUMBER(10,0)      Quantidade de cliente prevista / meta            OPERACIONAL                        NaN
PCMETAGARCOM               QTCLIENTE NUMBER(10,0)            Quantidade de cliente realizado            OPERACIONAL                        NaN
PCMETAGARCOM      PRCCLIENTEATINGIDO NUMBER(18,6) Percentual de cliente atigido sobre a meta            OPERACIONAL                        NaN
PCMETAGARCOM               QTMIXPREV NUMBER(10,0)    Quatnidade de mix de produto mix / meta            OPERACIONAL                        NaN
PCMETAGARCOM                   QTMIX NUMBER(10,0)    Quantidade de miex de produto realizado            OPERACIONAL                        NaN
PCMETAGARCOM          PRCMIXATINGIDO NUMBER(18,6)  Percentual de mix de produto sobre a meta            OPERACIONAL                        NaN
PCMETAGARCOM           VLTAXASERVICO NUMBER(22,6)                   Valor da taxa do serviço            OPERACIONAL                        NaN
PCMETAGARCOM PERCCOMISSAOGARCOMGERAL NUMBER(18,6)     Percentual de comissão do garçom geral            OPERACIONAL                        NaN
PCMETAGARCOM   VLTAXASERVICOCOMISSAO NUMBER(22,6)                    Valor de comissão geral            OPERACIONAL                        NaN
PCMETAGARCOM  PERCCOMISSAOGARCOMCASA NUMBER(18,6) Percentual de comissão do garçom pela casa            OPERACIONAL                        NaN
PCMETAGARCOM       VLTAXASERVICOCASA NUMBER(22,6)                     Valor da comissão casa            OPERACIONAL                        NaN
PCMETAGARCOM              DTCADASTRO         DATE                           Data de cadastro            OPERACIONAL                        NaN
PCMETAGARCOM              DTALTERADO         DATE                          Data de alteração            OPERACIONAL                        NaN
PCMETAGARCOM           CODUSUARIOINC  NUMBER(8,0)              Código do usuário de inclusão            OPERACIONAL                        NaN
PCMETAGARCOM           CODUSUARIOALT  NUMBER(8,0)             Código de usuário de alteração            OPERACIONAL                        NaN
PCMETAGARCOM              DTAPURACAO         DATE                           Data de apuração            OPERACIONAL                        NaN
PCMETAGARCOM           CODUSUARIOAPU  NUMBER(8,0)       Código do usuário que fez a apuração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*