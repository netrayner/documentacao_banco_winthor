# 📊 Tabela: PCFORNECSOFITVIEW

### Estrutura de Colunas e Restrições

           Tabela             Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORNECSOFITVIEW CODFORNECSOFITVIEW       NUMBER Código do vínculo entre o tipo e fornecedor Sofitview    CHAVE PRIMÁRIA (PK)                        NaN
PCFORNECSOFITVIEW          CODFORNEC  NUMBER(6,0)                                  Código do Fornecedor            OPERACIONAL                        NaN
PCFORNECSOFITVIEW    CODTIPOFORNECSV       NUMBER             Descrição do Tipo de Fornecedor Softiview CHAVE ESTRANGEIRA (FK)      PCTIPOFORNECSOFITVIEW
PCFORNECSOFITVIEW         DTULTALTER         DATE                              Data da última alteração            OPERACIONAL                        NaN
PCFORNECSOFITVIEW             STATUS  VARCHAR2(1)                 Status do registro - Ativo ou Inativo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*