# 📊 Tabela: PCDATACHEQ

### Estrutura de Colunas e Restrições

    Tabela          Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDATACHEQ          CGCENT VARCHAR2(18) Campo utilizado para informar o CPF/CNPJ do cliente.    CHAVE PRIMÁRIA (PK)                        NaN
PCDATACHEQ        NUMBANCO  NUMBER(4,0)                            Indica o número do banco.    CHAVE PRIMÁRIA (PK)                        NaN
PCDATACHEQ      NUMAGENCIA  NUMBER(4,0)                          Indica o número da agência.    CHAVE PRIMÁRIA (PK)                        NaN
PCDATACHEQ    QTOCORRENCIA  NUMBER(3,0)                  Indica a quantidade de ocorrências.            OPERACIONAL                        NaN
PCDATACHEQ DTULTOCORRENCIA         DATE                   Indica a data da última ocorrência            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*