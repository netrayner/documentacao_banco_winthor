# 📊 Tabela: PCMOVBLOQUEIO

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVBLOQUEIO   NUMTRANSACAO NUMBER(10,0)                                                                         Código de identificação do registro na tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVBLOQUEIO          DTMOV         DATE                                                                      Data que o registro foi criado no banco de dados.            OPERACIONAL                        NaN
PCMOVBLOQUEIO  IDENTIFICADOR NUMBER(10,0)                              Número da transação de entrada, saída ou bônus usado para movimentar o estoque bloqueado.            OPERACIONAL                        NaN
PCMOVBLOQUEIO      CODFILIAL  VARCHAR2(2)                                                       Código da filial usada para movimentar o estoque na tabela PCEST    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVBLOQUEIO        CODPROD  NUMBER(6,0)                                                     Código da produto usado para movimentar o estoque na tabela PCEST.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVBLOQUEIO         NUMSEQ NUMBER(20,0)                                                        Número sequencial do registro usado na movimentação do estoque.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVBLOQUEIO        CODOPER  VARCHAR2(2) Operação do registro. Exemplo: 'E' para entrada manual, 'S' para saída manual, 'EM' para entrada de mercadoria, etc...    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVBLOQUEIO           QTDE NUMBER(22,8)                                                                       Quantidade movimentar o estoque na tabela PCEST.            OPERACIONAL                        NaN
PCMOVBLOQUEIO         MOTIVO  NUMBER(4,0)                                                           Motivo do bloqueio informado pelo usuário em algumas rotinas            OPERACIONAL                        NaN
PCMOVBLOQUEIO    CODFUNCLANC  NUMBER(8,0)                                                                    Código do usuário que fez o lançamento do bloqueio.            OPERACIONAL                        NaN
PCMOVBLOQUEIO     ROTINALANC VARCHAR2(48)                                                                     Código da rotina que fez o lançamento do bloqueio.            OPERACIONAL                        NaN
PCMOVBLOQUEIO        NUMLOTE VARCHAR2(15)                                                                                 Número do lote do produto movimentado.            OPERACIONAL                        NaN
PCMOVBLOQUEIO    CODDEPOSITO  NUMBER(6,0)                                                                              Código do depósito usado na movimentação.            OPERACIONAL                        NaN
PCMOVBLOQUEIO      DTESTORNO         DATE                                                    Data do estorno da operação de bloqueio do estoque na tabela PCEST.            OPERACIONAL                        NaN
PCMOVBLOQUEIO CODFUNCESTORNO  NUMBER(8,0)                                                                         Código do funcionário que estornou o bloqueio.            OPERACIONAL                        NaN
PCMOVBLOQUEIO  ROTINAESTORNO VARCHAR2(48)                                                                      Código da rotina que fez o estorno do lançamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*