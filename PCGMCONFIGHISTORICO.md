# 📊 Tabela: PCGMCONFIGHISTORICO

### Estrutura de Colunas e Restrições

             Tabela                Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMCONFIGHISTORICO                CODIGO NUMBER(10,0)             Código sequêncial da relação com as parametrizações    CHAVE PRIMÁRIA (PK)                        NaN
PCGMCONFIGHISTORICO          CODPARAMMETA NUMBER(10,0)   código da parametrização que ira utilizar os dados histórivos CHAVE ESTRANGEIRA (FK)              PCGMPARAMMETA
PCGMCONFIGHISTORICO CODPARAMMETAHISTORICO NUMBER(10,0) código da parametrização que será utilizada como dado histórico            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*