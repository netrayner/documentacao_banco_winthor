# 📊 Tabela: PCIMPORTACAOSSCC

### Estrutura de Colunas e Restrições

          Tabela               Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCIMPORTACAOSSCC             NUMBONUS   NUMBER(6,0)                                        Número Bônus            OPERACIONAL                        NaN
PCIMPORTACAOSSCC                NUMNF  NUMBER(10,0)                                           Número NF            OPERACIONAL                        NaN
PCIMPORTACAOSSCC                SERIE   VARCHAR2(5)                                            Série NF            OPERACIONAL                        NaN
PCIMPORTACAOSSCC         CNPJ_EMISSOR  VARCHAR2(18)                                     Cnpj emissor NF            OPERACIONAL                        NaN
PCIMPORTACAOSSCC      DATA_IMPORTACAO          DATE              Data de importação do arquivo xml sscc            OPERACIONAL                        NaN
PCIMPORTACAOSSCC              ARQUIVO  VARCHAR2(60)   Nome do arquivo de importação do arquivo xml sscc            OPERACIONAL                        NaN
PCIMPORTACAOSSCC       ID_GRUPO_CAIXA  VARCHAR2(14)                      ID do grupo de caixa importado            OPERACIONAL                        NaN
PCIMPORTACAOSSCC             ID_CAIXA  VARCHAR2(20)                               ID da caixa importada            OPERACIONAL                        NaN
PCIMPORTACAOSSCC            CONFERIDO   VARCHAR2(1)           Identificador se a caixa já foi conferida            OPERACIONAL                        NaN
PCIMPORTACAOSSCC   USUARIO_IMPORTACAO   NUMBER(4,0)                      Usuário que importou o arquivo            OPERACIONAL                        NaN
PCIMPORTACAOSSCC USUARIO_CANCELAMENTO   NUMBER(4,0)   Usuário que realizou o cancelamento da importação            OPERACIONAL                        NaN
PCIMPORTACAOSSCC    DATA_CANCELAMENTO          DATE              Data em que foi cancelada a importação            OPERACIONAL                        NaN
PCIMPORTACAOSSCC                  OBS VARCHAR2(200) Observação da divergência encontrada na conferência            OPERACIONAL                        NaN
PCIMPORTACAOSSCC       COD_MOTIVO_DIV   NUMBER(4,0)                     Código de motivo da divergência            OPERACIONAL                        NaN
PCIMPORTACAOSSCC            SEQ_CAIXA   NUMBER(4,0)                                  Sequência da caixa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*