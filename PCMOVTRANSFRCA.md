# 📊 Tabela: PCMOVTRANSFRCA

### Estrutura de Colunas e Restrições

        Tabela          Coluna  Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVTRANSFRCA    CODRCAORIGEM   NUMBER(4,0)                                                       Código do RCA de origem    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVTRANSFRCA   CODRCADESTINO   NUMBER(4,0)                                                      Código do RCA de destino    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVTRANSFRCA DTTRANSFERENCIA          DATE                                                         Data da transferência    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVTRANSFRCA          CODCLI   NUMBER(6,0)                                                             Código do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVTRANSFRCA       CODROTINA   NUMBER(6,0)                                                 Código da rtoina que realizou            OPERACIONAL                        NaN
PCMOVTRANSFRCA         CODFUNC   NUMBER(8,0)                                            Código do funcionário que realizou            OPERACIONAL                        NaN
PCMOVTRANSFRCA      OBSERVACAO VARCHAR2(300)                                                                    Observação            OPERACIONAL                        NaN
PCMOVTRANSFRCA          COLUNA  VARCHAR2(30)                                Coluna de origem do RCA no cadastro de cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVTRANSFRCA       DTRETORNO          DATE Indica a data que será feito o retorno automático da transferência de cliente            OPERACIONAL                        NaN
PCMOVTRANSFRCA  EFETUOURETORNO   VARCHAR2(1)                        Indica se foi feito o retorno automático dos registros            OPERACIONAL                        NaN
PCMOVTRANSFRCA  DTCANCELTRANSF          DATE                Data que houve o cancelamento da transferência pela rotina 328            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*