# 📊 Tabela: PCPRESTACAOCONTA

### Estrutura de Colunas e Restrições

          Tabela                 Coluna  Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRESTACAOCONTA      NUMPRESTACAOCONTA  NUMBER(10,0)                                Código Chave Primária da Prestação    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTACAOCONTA     TIPOPRESTACAOCONTA   VARCHAR2(1)                                 Tipo de Conta(V=viagem, A=avulsa)            OPERACIONAL                        NaN
PCPRESTACAOCONTA              CODFILIAL   VARCHAR2(2)                                     Chave Extrangeira para filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCPRESTACAOCONTA DTINICIOPRESTACAOCONTA          DATE                                          Data início da Prestação            OPERACIONAL                        NaN
PCPRESTACAOCONTA    DTFIMPRESTACAOCONTA          DATE                                           Data Final da Prestação            OPERACIONAL                        NaN
PCPRESTACAOCONTA                PROJETO  VARCHAR2(50)                                              Descrição do Projeto            OPERACIONAL                        NaN
PCPRESTACAOCONTA        TIPOSOLICITANTE   VARCHAR2(1) Tipo de Solicitante (F=funcionário, M=Motorista, V=Vendedor(RCA))            OPERACIONAL                        NaN
PCPRESTACAOCONTA         CODSOLICITANTE   NUMBER(8,0)                                             Código do Solicitante            OPERACIONAL                        NaN
PCPRESTACAOCONTA   MOTIVOPRESTACAOCONTA VARCHAR2(150)                                  Descrição do Motivo da Prestação            OPERACIONAL                        NaN
PCPRESTACAOCONTA   STATUSPRESTACAOCONTA   VARCHAR2(2)                                      Status da Prestação de Conta            OPERACIONAL                        NaN
PCPRESTACAOCONTA        DTHORAAPROVACAO          DATE                                    Data de aprovação da Prestação            OPERACIONAL                        NaN
PCPRESTACAOCONTA          DTSOLICITACAO          DATE                                  Data de solicitação da Prestação            OPERACIONAL                        NaN
PCPRESTACAOCONTA      BLOQUEIOFORAPRAZO   VARCHAR2(1)                                            Bloqueio Fora do prazo            OPERACIONAL                        NaN
PCPRESTACAOCONTA     CODUSUARIOINCLUSAO   NUMBER(8,0)                                     Código do usuário de inclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*