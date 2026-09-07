# 📊 Tabela: PCNCM

### Estrutura de Colunas e Restrições

Tabela                    Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
 PCNCM                    CODNCM  VARCHAR2(15)                            Código NCM.            OPERACIONAL                        NaN
 PCNCM                 DESCRICAO VARCHAR2(500)                         Descrição NCM.            OPERACIONAL                        NaN
 PCNCM                  CAPITULO   NUMBER(2,0)                          Capítulo NCM.            OPERACIONAL                        NaN
 PCNCM                     CODEX   NUMBER(4,0)                     Código de exceção.            OPERACIONAL                        NaN
 PCNCM                DTINCLUSAO          DATE                      Data da Inclusão.            OPERACIONAL                        NaN
 PCNCM                DTEXCLUSAO          DATE                      Data da Exclusão.            OPERACIONAL                        NaN
 PCNCM           CODUSURINCLUSAO   NUMBER(8,0) Código do Usuário que Cadastrou o NCM.            OPERACIONAL                        NaN
 PCNCM           CODUSUREXCLUSAO   NUMBER(8,0)  Código do Usuário que Inativou o NCM.            OPERACIONAL                        NaN
 PCNCM                  CODNCMEX  VARCHAR2(20)                 Código NCM de exceção.    CHAVE PRIMÁRIA (PK)                        NaN
 PCNCM                 DTALTERC5  TIMESTAMP(6)                      Data de alteração            OPERACIONAL                        NaN
 PCNCM OBRIGARECEITUARIOAGRICOLA   VARCHAR2(1)           Obrigar receituario agricola            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*