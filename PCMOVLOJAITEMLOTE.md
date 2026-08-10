# 📊 Tabela: PCMOVLOJAITEMLOTE

### Estrutura de Colunas e Restrições

           Tabela            Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVLOJAITEMLOTE        CODMOVLOJA   NUMBER(6,0)                               Código sequencial    CHAVE PRIMÁRIA (PK)              PCMOVLOJAITEM
PCMOVLOJAITEMLOTE           CODPROD   NUMBER(6,0)                               Código do produto    CHAVE PRIMÁRIA (PK)              PCMOVLOJAITEM
PCMOVLOJAITEMLOTE            NUMSEQ  NUMBER(20,0)                   Número sequência de inclusão.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVLOJAITEMLOTE      QTLANCAMENTO  NUMBER(22,6)                        Quantidade do lançamento            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE   QTFRENTELOJAANT  NUMBER(22,6)  Quantidade anterior da loja antes da alteração            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE QTFRENTELOJAATUAL  NUMBER(22,6)                   Quantidade atualizada da loja            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE            MOTIVO VARCHAR2(200)      Motivo de alteração da quantidade aplicada            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE         CODFUNCAD   NUMBER(8,0)               Código do funcionário de cadastro            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE        DTCADASTRO          DATE                                Data de cadastro            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE     NUMTRANSVENDA  NUMBER(10,0)                                Número da venda.            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE           NUMLOTE  VARCHAR2(15)                                  Número do lote            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE        DTVALIDADE          DATE                        Data de validade do lote            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE      DTFABRICACAO          DATE                      Data de fabricação do lote            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE      QTREGISTRADA  NUMBER(22,6)      Quantidade registrada da primeira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE     QTREGISTRADA2  NUMBER(22,6)       Quantidade registrada da segunda contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE     QTREGISTRADA3  NUMBER(22,6)      Quantidade registrada da terceira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE      CODFUNCCONT1   NUMBER(8,0)      Código do funcionario da primeira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE      CODFUNCCONT2   NUMBER(8,0)       Código do funcionario da segunda contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE      CODFUNCCONT3   NUMBER(8,0)      Código do funcionario da terceira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE         DATACONT1          DATE                       Data da primeira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE         DATACONT2          DATE                        Data da segunda contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE         DATACONT3          DATE                       Data da terceira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE         CANCELADO   VARCHAR2(1)                     Verificar se está cancelado            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE          QTCANCEL  NUMBER(22,6)                            Quantidade Cancelada            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE       CODAUXILIAR  NUMBER(20,0)                                   Cód. Auxiliar            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE       QTDEVOLVIDA  NUMBER(22,6)                 Quantidade devolvida ao estoque            OPERACIONAL                        NaN
PCMOVLOJAITEMLOTE      CODAGREGACAO  VARCHAR2(20) Responsavel por armazenar o código de agregação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*