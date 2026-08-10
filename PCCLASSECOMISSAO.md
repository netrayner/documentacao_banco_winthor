# 📊 Tabela: PCCLASSECOMISSAO

### Estrutura de Colunas e Restrições

          Tabela        Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLASSECOMISSAO IDENTIFICADOR  VARCHAR2(2)                      Identificador da Classe.     CHAVE PRIMÁRIA (PK)                        NaN
PCCLASSECOMISSAO       PCOMINT  NUMBER(6,2) Percentual de Comissão para Vendedor Interno.             OPERACIONAL                        NaN
PCCLASSECOMISSAO       PCOMEXT  NUMBER(6,2) Percentual de Comissão para Vendedor Externo.             OPERACIONAL                        NaN
PCCLASSECOMISSAO       PCOMREP  NUMBER(6,2)    Percentual de Comissão para Representante.             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*