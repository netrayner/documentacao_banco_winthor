# 📊 Tabela: PCMETANESTLE

### Estrutura de Colunas e Restrições

      Tabela            Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETANESTLE           CODUSUR  NUMBER(4,0)                                  Indica o código do vendedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETANESTLE         CODFILIAL  VARCHAR2(2)                                    Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETANESTLE              DATA         DATE                         Indica a data da meta a ser cumprida.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETANESTLE       QTCOBERTURA  NUMBER(6,0)            Indica a quantidade prevista de clientes cobertos.            OPERACIONAL                        NaN
PCMETANESTLE     QTPOSITIVACAO  NUMBER(6,0)         Indica a quantidade prevista de clientes positivados.            OPERACIONAL                        NaN
PCMETANESTLE      QTPROSPECCAO  NUMBER(6,0)    Indica a quantidade prevista prospecção de novos clientes.            OPERACIONAL                        NaN
PCMETANESTLE QTPROSPECCAOFINAL  NUMBER(6,0)                   Indica o objetivo de clientes a prospectar.            OPERACIONAL                        NaN
PCMETANESTLE    VLMETAMIXPILAR NUMBER(12,2) Valor de meta para os produtos pertencentes a linha mix pilar            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*