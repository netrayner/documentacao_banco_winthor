# 📊 Tabela: PCCOMISSAOREGIAO

### Estrutura de Colunas e Restrições

          Tabela          Coluna Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSAOREGIAO        CODFAIXA  NUMBER(8,0)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAOREGIAO       NUMREGIAO  NUMBER(4,0)                                                         NaN            OPERACIONAL                        NaN
PCCOMISSAOREGIAO      PERDESCINI NUMBER(12,6)                                                         NaN            OPERACIONAL                        NaN
PCCOMISSAOREGIAO      PERDESCFIM NUMBER(12,6)                                                         NaN            OPERACIONAL                        NaN
PCCOMISSAOREGIAO          PERCOM  NUMBER(8,4)                                                         NaN            OPERACIONAL                        NaN
PCCOMISSAOREGIAO            TIPO  VARCHAR2(2)                                                         NaN            OPERACIONAL                        NaN
PCCOMISSAOREGIAO         CODEPTO  NUMBER(6,0)                                                         NaN            OPERACIONAL                        NaN
PCCOMISSAOREGIAO          CODSEC  NUMBER(6,0)                                                         NaN            OPERACIONAL                        NaN
PCCOMISSAOREGIAO         CODPROD  NUMBER(6,0)                                                         NaN            OPERACIONAL                        NaN
PCCOMISSAOREGIAO       CODFILIAL  VARCHAR2(2)            Código da filial na qual a comissão será válida.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO        DTINICIO         DATE                                 Data do início de vigência.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO           DTFIM         DATE                                  Data do final de vigência.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO    TIPOVENDEDOR  VARCHAR2(1) Informa se a comissão é diferenciada pelo tipo de vendedor.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO       PERCOMEXT  NUMBER(8,4)                                  % de comissão RCA externo.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO       PERCOMINT  NUMBER(8,4)                                  % de comissão RCA interno.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO      DTCADASTRO         DATE                 Data que o registro foi inserido na tabela.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO CODFUNCCADASTRO  NUMBER(8,0)           Código do funcionário que cadastrou a informação.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO        DTULTALT         DATE             Data da última vez que o registro foi alterado.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO   CODFUNCULTALT  NUMBER(8,0)      Código do funcionário que realizou a última alteração.            OPERACIONAL                        NaN
PCCOMISSAOREGIAO    CODLINHAPROD  NUMBER(6,0)                                             Código da Linha            OPERACIONAL                        NaN
PCCOMISSAOREGIAO      DTMXSALTER         DATE                                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*