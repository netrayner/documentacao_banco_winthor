# 📊 Tabela: PCAUDITORIAI

### Estrutura de Colunas e Restrições

      Tabela       Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUDITORIAI      CODPROD  NUMBER(6,0)                Indica o código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCAUDITORIAI NUMAUDITORIA  NUMBER(8,0)  Indica o número da auditoria por veículo.    CHAVE PRIMÁRIA (PK)                PCAUDITORIA
PCAUDITORIAI    QTVEICULO NUMBER(18,4) Indica a quantidade do produto no veículo.            OPERACIONAL                        NaN
PCAUDITORIAI       QTCONF NUMBER(20,6)  Indica a quantidade conferida do produto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*