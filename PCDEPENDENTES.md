# 📊 Tabela: PCDEPENDENTES

### Estrutura de Colunas e Restrições

       Tabela               Coluna  Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEPENDENTES            CODFORNEC   NUMBER(6,0)       Código do fornecedor            OPERACIONAL                        NaN
PCDEPENDENTES        CODDEPENDENTE   NUMBER(6,0)       Código do dependente    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPENDENTES                  CPF  VARCHAR2(11) Número de Inscrição no CPF            OPERACIONAL                        NaN
PCDEPENDENTES                 NOME VARCHAR2(200)         Nome do dependente            OPERACIONAL                        NaN
PCDEPENDENTES   RELACAODEPENDENCIA   NUMBER(6,0)     Relação de dependência            OPERACIONAL                        NaN
PCDEPENDENTES DESCRICAODEPENDENCIA  VARCHAR2(30)   Descrição da dependência            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*