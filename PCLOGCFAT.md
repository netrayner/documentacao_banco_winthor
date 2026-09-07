# 📊 Tabela: PCLOGCFAT

### Estrutura de Colunas e Restrições

   Tabela        Coluna   Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCFAT      ENTIDADE    VARCHAR2(1)                    Entidade            OPERACIONAL                        NaN
PCLOGCFAT IDENTIFICADOR   NUMBER(22,0)               Identificador            OPERACIONAL                        NaN
PCLOGCFAT          TIPO    VARCHAR2(1)                        Tipo            OPERACIONAL                        NaN
PCLOGCFAT      MENSAGEM           CLOB                    Mensagem            OPERACIONAL                        NaN
PCLOGCFAT          DATA           DATE                        Data            OPERACIONAL                        NaN
PCLOGCFAT        NUMCAR    NUMBER(8,0)      Número do Carregamento            OPERACIONAL                        NaN
PCLOGCFAT        NUMPED   NUMBER(10,0)            Número do Pedido            OPERACIONAL                        NaN
PCLOGCFAT    OBSERVAÇÃO VARCHAR2(4000)       Observações do Evento            OPERACIONAL                        NaN
PCLOGCFAT     MATRICULA    NUMBER(8,0)        Matrícula do Usuário            OPERACIONAL                        NaN
PCLOGCFAT NUMTRANSVENDA   NUMBER(10,0)   Numero Transação de Venda            OPERACIONAL                        NaN
PCLOGCFAT   NUMTRANSENT   NUMBER(10,0) Numero Transação de Entrada            OPERACIONAL                        NaN
PCLOGCFAT      DETALHES           CLOB          Detalhes do Evento            OPERACIONAL                        NaN
PCLOGCFAT    OBSERVACAO VARCHAR2(4000)       Observações do Evento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*