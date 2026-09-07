# 📊 Tabela: PCADIANTFUNC

### Estrutura de Colunas e Restrições

      Tabela             Coluna  Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCADIANTFUNC    NUMADIANTAMENTO  NUMBER(10,0)                          Código chave primária de Adiantamento    CHAVE PRIMÁRIA (PK)                        NaN
PCADIANTFUNC   TIPOADIANTAMENTO   VARCHAR2(1)                       Tipo de Adiantamento(V=viagem, A=avulso)            OPERACIONAL                        NaN
PCADIANTFUNC          CODFILIAL   VARCHAR2(2)                                               Código da Filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCADIANTFUNC      DTSOLICITACAO          DATE                            Data da solicitação de Adiantamento            OPERACIONAL                        NaN
PCADIANTFUNC     DTINICIOVIAGEM          DATE                                       Data da início da viagem            OPERACIONAL                        NaN
PCADIANTFUNC        DTFIMVIAGEM          DATE                                          Data do fim da viagem            OPERACIONAL                        NaN
PCADIANTFUNC            PROJETO  VARCHAR2(50)                                           Descrição do projeto            OPERACIONAL                        NaN
PCADIANTFUNC    TIPOSOLICITANTE   VARCHAR2(1) Tipo Solicitante (F=funcionário, M=Motorista, V=Vendedor(RCA))            OPERACIONAL                        NaN
PCADIANTFUNC     CODSOLICITANTE   NUMBER(8,0)                                          Código do solicitatne            OPERACIONAL                        NaN
PCADIANTFUNC  VALORADIANTAMENTO  NUMBER(12,2)                                          Valor do Adiantamento            OPERACIONAL                        NaN
PCADIANTFUNC MOTIVOADIANTAMENTO VARCHAR2(150)                               Descrição de motivo adiantamento            OPERACIONAL                        NaN
PCADIANTFUNC STATUSADIANTAMENTO   VARCHAR2(1)                                         Status do adiantamento            OPERACIONAL                        NaN
PCADIANTFUNC   OBSADIANTAMENTO1 VARCHAR2(150)                                   Observação primero aprovador            OPERACIONAL                        NaN
PCADIANTFUNC   OBSADIANTAMENTO2 VARCHAR2(150)                                   Observação segundo aprovador            OPERACIONAL                        NaN
PCADIANTFUNC      CODAPROVADOR1   NUMBER(8,0)                                      Código primeiro aprovador            OPERACIONAL                        NaN
PCADIANTFUNC      CODAPROVADOR2   NUMBER(8,0)                                       Código segundo aprovador            OPERACIONAL                        NaN
PCADIANTFUNC   STATUSAPROVADOR1   VARCHAR2(1)                                      Status primeiro aprovador            OPERACIONAL                        NaN
PCADIANTFUNC   STATUSAPROVADOR2   VARCHAR2(1)                                       Status segundo aprovador            OPERACIONAL                        NaN
PCADIANTFUNC    DTHORAAPROVACAO          DATE                                                 Data aprovação            OPERACIONAL                        NaN
PCADIANTFUNC  NUMPRESTACAOCONTA  NUMBER(10,0)                         Chave extrangeira para Prestação Conta CHAVE ESTRANGEIRA (FK)           PCPRESTACAOCONTA

---
*Documentação gerada automaticamente.*