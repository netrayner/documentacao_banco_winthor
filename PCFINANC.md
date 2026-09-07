# 📊 Tabela: PCFINANC

### Estrutura de Colunas e Restrições

  Tabela                       Coluna   Tipo/Tamanho                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINANC                         DATA           DATE                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC                     SALDOBCO   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                      SALDOLP   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                      SALDOCR   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                  SALDOESTFIN   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                 SALDOESTREAL   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                      SALDOCP   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                    SALDOREAL   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                     SALDOFIN   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                    VENDAREAL   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                    RECEBREAL   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                      CMVREAL   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                    SALDOCHDV   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                     SALDODIN   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                    SALDOAPLI   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                   RECEBREAL2   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                   RECEBREAL3   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                   RECEBREAL4   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                       AUXTMP    NUMBER(6,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                  VLVENDAPREV   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                   MARGEMPREV    NUMBER(8,4)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                    CODFILIAL    VARCHAR2(2)                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC                    DTGERACAO           DATE                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                      SALDOCX   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                    SALDOVALE   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC            SALDOEMPRESTATIVO   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC          SALDOEMPRESTPASSIVO   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                  SALDOCTRANS   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                   SALDOCRFOR   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC             SALDOINVESTATIVO   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC           SALDOINVESTPASSIVO   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC               SALDOADIANTFOR   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                 SALDOCREDCLI   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC            SALDOTITULOVENDOR   NUMBER(16,2)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                    CODROTINA    NUMBER(4,0)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                      CODFUNC    NUMBER(8,0)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC                SALDOCPMANUAL   NUMBER(16,2)                                Indica o saldo de contas a pagar manual.             OPERACIONAL                        NaN
PCFINANC           SALDOESTCONSIGVEND   NUMBER(16,2)                                  Saldo do estoque consignado de vendas.             OPERACIONAL                        NaN
PCFINANC                   SALDOREAL2   NUMBER(16,2)      Saldo real considerando saldo pendente conta a receber fornecedor.             OPERACIONAL                        NaN
PCFINANC                SALDOCPOUTROS   NUMBER(16,2)                    Saldo contas a pagar referente a outros fornecedores.            OPERACIONAL                        NaN
PCFINANC       LISTAFILIAISBANCOCAIXA VARCHAR2(4000) Lista das filiais vinculadas ao caixa / banco cadastradas na rotiina 524    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC PARMULTIFILIALCAIXABANCO3882    VARCHAR2(1)                       Status do parametro 3882 multifiliais caixa/banco.    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC   SALDOESTOQUECONSUMOINTERNO   NUMBER(16,2)                                      Saldo do estoque do consumo interno            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*