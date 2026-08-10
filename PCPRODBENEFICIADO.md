# 📊 Tabela: PCPRODBENEFICIADO

### Estrutura de Colunas e Restrições

           Tabela       Coluna Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODBENEFICIADO       NUMPED NUMBER(10,0)                                           Número do pedido de beneficiamento    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODBENEFICIADO      CODPROD  NUMBER(6,0)                                                Código do Produto Beneficiado    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODBENEFICIADO           QT NUMBER(14,8)                                           Quantidade de produto beneficiado             OPERACIONAL                        NaN
PCPRODBENEFICIADO        PUNIT NUMBER(18,6)                                        Preço unitário do produto beneficiado            OPERACIONAL                        NaN
PCPRODBENEFICIADO   QTENTREGUE NUMBER(14,8)                                 Quantidade entregue de produtos beneficiados            OPERACIONAL                        NaN
PCPRODBENEFICIADO CODESTRUTURA  NUMBER(6,0) Campo para armazenar a fórmula que foi utlizada para na sugestão de insumos.            OPERACIONAL                        NaN
PCPRODBENEFICIADO      QTPERDA NUMBER(14,8)                                  Quantidade de perda do produto  beneficiado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*