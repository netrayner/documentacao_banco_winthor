# 📊 Tabela: PCFATOGERADOR

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFATOGERADOR CODFATOGERADOR  NUMBER(8,0)                              Indica o código do fato gerador    CHAVE PRIMÁRIA (PK)                        NaN
PCFATOGERADOR      DESCRICAO VARCHAR2(60)                           Indica o descrição do fato gerador            OPERACIONAL                        NaN
PCFATOGERADOR SQLFATOGERADOR         CLOB Indica o SQL do fato gerador responsável pela regra contábil            OPERACIONAL                        NaN
PCFATOGERADOR TIPOLANCAMENTO  VARCHAR2(2)                Indica o tipo do fato gerador da movimentação            OPERACIONAL                        NaN
PCFATOGERADOR     OBSERVACAO         CLOB                         Indica a observação do fato gerador.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*