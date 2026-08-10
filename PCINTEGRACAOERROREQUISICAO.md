# 📊 Tabela: PCINTEGRACAOERROREQUISICAO

### Estrutura de Colunas e Restrições

                    Tabela                 Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOERROREQUISICAO                     ID NUMBER(10,0)                  Chave primária da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOERROREQUISICAO LAYOUTERROTRANSFORMADO         CLOB Armazena layout de erro para transformação            OPERACIONAL                        NaN
PCINTEGRACAOERROREQUISICAO             IDROTAERRO NUMBER(10,0)              Armazena o id da rota de erro CHAVE ESTRANGEIRA (FK)    PCINTEGRACAOROTASERVICO
PCINTEGRACAOERROREQUISICAO             IDROTAEXEC NUMBER(10,0)        Armazenado o id da rota de execução CHAVE ESTRANGEIRA (FK)    PCINTEGRACAOROTASERVICO
PCINTEGRACAOERROREQUISICAO             HTTPSTATUS  NUMBER(5,0)                     Armazena o HTTP Status            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*