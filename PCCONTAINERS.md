# 📊 Tabela: PCCONTAINERS

### Estrutura de Colunas e Restrições

      Tabela             Coluna  Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTAINERS IDCONTROLEEMBARQUE  VARCHAR2(20)                         Identificação do controle de embarque.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTAINERS        IDCONTAINER  VARCHAR2(20)                                     Identificação do container    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTAINERS    DTPREVDEVOLUCAO          DATE                                Data de previsão para devolução            OPERACIONAL                        NaN
PCCONTAINERS        DTDEVOLUCAO          DATE                                                 Data devolução            OPERACIONAL                        NaN
PCCONTAINERS             LACRES VARCHAR2(300) Descrição dos números que identificam os lacres dos containers            OPERACIONAL                        NaN
PCCONTAINERS      TIPOCONTAINER VARCHAR2(200)                    Descrição para definir o tipo do container.            OPERACIONAL                        NaN
PCCONTAINERS          DTCHEGADA          DATE                                  Data de chegada do container.            OPERACIONAL                        NaN
PCCONTAINERS       DIASCARENCIA   NUMBER(6,0)                                               Dias de carência            OPERACIONAL                        NaN
PCCONTAINERS           VLDIARIA  NUMBER(12,4)                                                Valor da diária            OPERACIONAL                        NaN
PCCONTAINERS          VLCOTACAO  NUMBER(12,4)                                       Valor unitário da moeda             OPERACIONAL                        NaN
PCCONTAINERS         DTCADASTRO          DATE                                 Data de cadastro do containers            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*