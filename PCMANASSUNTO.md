# 📊 Tabela: PCMANASSUNTO

### Estrutura de Colunas e Restrições

      Tabela             Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANASSUNTO         CODASSUNTO  NUMBER(6,0)                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMANASSUNTO            ASSUNTO VARCHAR2(30)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO           CODSETOR  NUMBER(6,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO             PRAZO1  NUMBER(6,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO             PRAZO2  NUMBER(6,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO             PRAZO3  NUMBER(6,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO           CODFUNC1  NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO           CODFUNC2  NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO           CODFUNC3  NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO           CODFUNC4  NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO             PRAZO4  NUMBER(6,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO              COPIA  VARCHAR2(1)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO         PRAZOSETOR  NUMBER(6,0)                                                    NaN            OPERACIONAL                        NaN
PCMANASSUNTO CODOPERCOMUNICACAO  NUMBER(8,0)                        Indica o operador comunicação.             OPERACIONAL                        NaN
PCMANASSUNTO              ATIVO  VARCHAR2(1)               Indica se o registro esta ativo/inativo.            OPERACIONAL                        NaN
PCMANASSUNTO         GERAAGENDA  VARCHAR2(1) Gera Agenda automaticamente ao gerar uma manifestação.            OPERACIONAL                        NaN
PCMANASSUNTO            INTERNO  VARCHAR2(1)                                  Manifestação Interna.            OPERACIONAL                        NaN
PCMANASSUNTO         OBRIGAQTDE  VARCHAR2(1)                                      Obriga Quantidade            OPERACIONAL                        NaN
PCMANASSUNTO         DTMXSALTER         DATE                                                    NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*