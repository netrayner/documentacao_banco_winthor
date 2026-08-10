# 📊 Tabela: PCESTRUTURABENEFIC

### Estrutura de Colunas e Restrições

            Tabela          Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTRUTURABENEFIC    CODPRODBENEF  NUMBER(6,0)                   Código do Produto beneficiado    CHAVE PRIMÁRIA (PK)                        NaN
PCESTRUTURABENEFIC   CODPRODINSUMO  NUMBER(6,0)                                Código do Insumo    CHAVE PRIMÁRIA (PK)                        NaN
PCESTRUTURABENEFIC              QT NUMBER(14,8)                                      Quantidade            OPERACIONAL                        NaN
PCESTRUTURABENEFIC      DTCADASTRO         DATE                                Data do Cadastro            OPERACIONAL                        NaN
PCESTRUTURABENEFIC CODFUNCCADASTRO  NUMBER(8,0)                         Código usuário cadastro            OPERACIONAL                        NaN
PCESTRUTURABENEFIC      DTULTALTER         DATE                           Data última alteração            OPERACIONAL                        NaN
PCESTRUTURABENEFIC CODFUNCULTALTER  NUMBER(8,0)                 Código usuário última alteração            OPERACIONAL                        NaN
PCESTRUTURABENEFIC    CODESTRUTURA  NUMBER(6,0)      Campo para armazenar código da  estrutura.    CHAVE PRIMÁRIA (PK)                        NaN
PCESTRUTURABENEFIC       DESCRICAO VARCHAR2(40) Campo para armazenar a descrição da  estrutura.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*