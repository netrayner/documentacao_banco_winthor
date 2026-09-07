# 📊 Tabela: PCCOMPOSICAOPRODBENEFIC

### Estrutura de Colunas e Restrições

                 Tabela          Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPOSICAOPRODBENEFIC       CODFILIAL  VARCHAR2(2)                Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAOPRODBENEFIC         CODPROD  NUMBER(6,0)   Código do Produto beneficiado    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAOPRODBENEFIC       CODINSUMO  NUMBER(6,0)                Código do Insumo    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAOPRODBENEFIC              QT NUMBER(14,8)                      Quantidade            OPERACIONAL                        NaN
PCCOMPOSICAOPRODBENEFIC           PUNIT NUMBER(18,6)        Valor unitário do insumo            OPERACIONAL                        NaN
PCCOMPOSICAOPRODBENEFIC     NUMTRANSENT NUMBER(10,0) Número da transação de entrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAOPRODBENEFIC      DTCADASTRO         DATE                   Data cadastro            OPERACIONAL                        NaN
PCCOMPOSICAOPRODBENEFIC CODFUNCCADASTRO  NUMBER(8,0)                  Código usuário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*