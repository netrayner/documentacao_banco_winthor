# 📊 Tabela: PCPEDIDOLOGPARAMETROS

### Estrutura de Colunas e Restrições

               Tabela        Coluna  Tipo/Tamanho      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIDOLOGPARAMETROS      IDORIGEM  NUMBER(20,0) Identificador da tabela.    CHAVE PRIMÁRIA (PK)         PCPEDIDOPARAMETROS
PCPEDIDOLOGPARAMETROS NOMEPARAMETRO VARCHAR2(200)       Nome do parâmetro.    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIDOLOGPARAMETROS         VALOR  VARCHAR2(50)      Valor do parâmetro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*