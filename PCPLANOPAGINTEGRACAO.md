# 📊 Tabela: PCPLANOPAGINTEGRACAO

### Estrutura de Colunas e Restrições

              Tabela          Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPLANOPAGINTEGRACAO              ID NUMBER(10,0)   Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPLANOPAGINTEGRACAO CODIGOECOMMERCE NUMBER(10,0)        Código do ecommerce            OPERACIONAL                        NaN
PCPLANOPAGINTEGRACAO   CODIGOWINTHOR NUMBER(10,0)          Código no winthor CHAVE ESTRANGEIRA (FK)                    PCPLPAG
PCPLANOPAGINTEGRACAO        FILIALID NUMBER(10,0) Código da filial ecommerce CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE

---
*Documentação gerada automaticamente.*