# 📊 Tabela: PCBANCOSVINCULADOS

### Estrutura de Colunas e Restrições

            Tabela          Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBANCOSVINCULADOS          NUMSEQ  NUMBER(8,0)                 Número de sequencia dos registros.    CHAVE PRIMÁRIA (PK)                        NaN
PCBANCOSVINCULADOS        CODBANCO  NUMBER(4,0) Código do banco "Principal" cadastrado na PCBANCO.            OPERACIONAL                        NaN
PCBANCOSVINCULADOS CODBANCODESTINO  NUMBER(4,0) Código do banco "Vinculado" cadastrado na PCBANCO.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*