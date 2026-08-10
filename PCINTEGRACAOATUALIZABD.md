# 📊 Tabela: PCINTEGRACAOATUALIZABD

### Estrutura de Colunas e Restrições

                Tabela                  Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOATUALIZABD        DATAHORAEXECUCAO         DATE                           Data e hora da execução            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD                      ID NUMBER(10,0)                              Coluna sequencial ID    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOATUALIZABD               MATRICULA  NUMBER(8,0)         Matricula do usuário que fez a integração            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD                 MAQUINA VARCHAR2(50)                     Hostname que fez a integração            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD                      IP VARCHAR2(60)                  HostAddress que fez a integração            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD                    JSON         CLOB                         JSON que fez a integração            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD                  OPCOES VARCHAR2(50) Tabela e coluna que foram alteradas na integração            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD QTDREGISTROSATUALIZADOS  NUMBER(8,0)                    Quantidade de linhas alteradas            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD  QTDREGISTROSANTERIORES  NUMBER(8,0) Quantidade de linhas solicitadas a para alteração            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD                NOVADATA         DATE                    Data que foi alterada os dados            OPERACIONAL                        NaN
PCINTEGRACAOATUALIZABD            VERSAOROTINA VARCHAR2(60)        Nome e versão da rotina que fez o registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*