# 📊 Tabela: PCREINFR9000

### Estrutura de Colunas e Restrições

      Tabela                Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR9000                    ID   NUMBER(8,0)                                   Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR9000               GRUPOID   NUMBER(8,0)                             Grupo identificador            OPERACIONAL                        NaN
PCREINFR9000                   MES   NUMBER(8,0)                               Mês de referência            OPERACIONAL                        NaN
PCREINFR9000                   ANO   NUMBER(8,0)                               Ano de referência            OPERACIONAL                        NaN
PCREINFR9000                EVENTO   VARCHAR2(6)                                          Evento            OPERACIONAL                        NaN
PCREINFR9000 DTSOLICITACAOEXCLUSAO          DATE                 Data de solicitação de exclusão            OPERACIONAL                        NaN
PCREINFR9000            DTEXCLUSAO          DATE                                Data de exclusão            OPERACIONAL                        NaN
PCREINFR9000                RECIBO VARCHAR2(150)                                Numero do recibo            OPERACIONAL                        NaN
PCREINFR9000           IDREGEVENTO   NUMBER(8,0)                          Id do evento períodico            OPERACIONAL                        NaN
PCREINFR9000    RECUPERACAO_RECIBO  VARCHAR2(10) Informaç.ão se o recibo foi obtido por consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*