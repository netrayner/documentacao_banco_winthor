# 📊 Tabela: PCLOGFISCAL

### Estrutura de Colunas e Restrições

     Tabela       Coluna   Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGFISCAL         DATA           DATE                                Data de alteração            OPERACIONAL                        NaN
PCLOGFISCAL     REGISTRO    VARCHAR2(7) Registro de identificação da movimentação fiscal            OPERACIONAL                        NaN
PCLOGFISCAL       CODIGO   NUMBER(10,0)            Código de identificação do lançamento            OPERACIONAL                        NaN
PCLOGFISCAL    VALORALFA VARCHAR2(2000)                                       Valor novo            OPERACIONAL                        NaN
PCLOGFISCAL VALORALFAANT VARCHAR2(2000)                                   Valor anterior            OPERACIONAL                        NaN
PCLOGFISCAL       TABELA   VARCHAR2(30)                                   Nome da Tabela            OPERACIONAL                        NaN
PCLOGFISCAL       COLUNA   VARCHAR2(30)                                   Nome da Coluna            OPERACIONAL                        NaN
PCLOGFISCAL       DTSPED           DATE                          Data de geração do Sped            OPERACIONAL                        NaN
PCLOGFISCAL    CODFILIAL    VARCHAR2(2)                     Código da Filial da Operação            OPERACIONAL                        NaN
PCLOGFISCAL          OBS   VARCHAR2(30)                                Observação do Log            OPERACIONAL                        NaN
PCLOGFISCAL     DTMOVANT           DATE             Data de movimentação anterior ao log            OPERACIONAL                        NaN
PCLOGFISCAL    DTINICIAL           DATE               Data inicial da descrição anterior            OPERACIONAL                        NaN
PCLOGFISCAL      DTFINAL           DATE                 Data final da descrição anterior            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*