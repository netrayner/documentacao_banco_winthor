# 📊 Tabela: PCMETAOSCOMODC

### Estrutura de Colunas e Restrições

        Tabela         Coluna  Tipo/Tamanho                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAOSCOMODC        NUMMETA   NUMBER(8,0)                                                                     Campo para armazenar o código da meta    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAOSCOMODC       TIPOMETA   NUMBER(1,0)                                                                       Campo para armazenar o tipo da meta    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAOSCOMODC      DESCRICAO  VARCHAR2(40)                                                                 Campo para armazenar a descrição da meta.            OPERACIONAL                        NaN
PCMETAOSCOMODC      CODFILIAL   VARCHAR2(2)                                       Campo para armazenar o código da filial em que a meta será validada            OPERACIONAL                        NaN
PCMETAOSCOMODC       DTINICIO          DATE                                                            Campo para armazenar a data de inicio da meta.            OPERACIONAL                        NaN
PCMETAOSCOMODC          DTFIM          DATE                                                                  Campo para armazenar a data fim da meta.            OPERACIONAL                        NaN
PCMETAOSCOMODC            OBS VARCHAR2(200)                                                              Campo para armazenar as observações da meta.            OPERACIONAL                        NaN
PCMETAOSCOMODC       DTCANCEL          DATE                                                      Campo para armazenar a data do cancelamento da meta.            OPERACIONAL                        NaN
PCMETAOSCOMODC TODASCONDICOES   VARCHAR2(1) Campo para armazenar se para na apuração da meta o participante deve alcançar todos os critérios da meta.            OPERACIONAL                        NaN
PCMETAOSCOMODC       TODOSRCA   VARCHAR2(1)                                                 Campo para armazenar se todos os RCAs participam da meta.            OPERACIONAL                        NaN
PCMETAOSCOMODC      TODOSFUNC   VARCHAR2(1)                                         Campo para armazenar se todos os funcionários participam da meta.            OPERACIONAL                        NaN
PCMETAOSCOMODC       TODOSSUP   VARCHAR2(1)                                         Campo para armazenar se todos os supervisores participam da meta.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*