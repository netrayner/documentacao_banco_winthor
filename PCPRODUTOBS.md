# 📊 Tabela: PCPRODUTOBS

### Estrutura de Colunas e Restrições

     Tabela  Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTOBS   IDOBS  NUMBER(8,0)  Código sequencial.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOBS CODPROD  NUMBER(6,0)  Código do produto.            OPERACIONAL                        NaN
PCPRODUTOBS TIPOOBS  VARCHAR2(2) Tipo da observação.            OPERACIONAL                        NaN
PCPRODUTOBS   TEXTO         CLOB         Observação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*