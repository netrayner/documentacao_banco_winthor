# 📊 Tabela: PCNVEIMPORTACAO

### Estrutura de Colunas e Restrições

         Tabela     Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNVEIMPORTACAO     CODNVE VARCHAR2(20)                 Código NVE    CHAVE PRIMÁRIA (PK)                      PCNCM
PCNVEIMPORTACAO   CODNIVEL VARCHAR2(10)               Nível do NVE            OPERACIONAL                        NaN
PCNVEIMPORTACAO    UNIDADE VARCHAR2(10)   Unidade de medida do NVE            OPERACIONAL                        NaN
PCNVEIMPORTACAO DTCADASTRO         DATE            Data do Vinculo            OPERACIONAL                        NaN
PCNVEIMPORTACAO CODUSUARIO  NUMBER(8,0) Código do usuário Cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*