# 📊 Tabela: PCHIST

### Estrutura de Colunas e Restrições

Tabela     Coluna Tipo/Tamanho                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHIST    CODHIST  NUMBER(4,0)                                                                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCHIST  HISTORICO VARCHAR2(40)                                                                                                  NaN            OPERACIONAL                        NaN
PCHIST       TIPO  VARCHAR2(1)                                                                                                  NaN            OPERACIONAL                        NaN
PCHIST    EXPORTA  VARCHAR2(1) Indica se os clientes bloqueados com este histórico serão ou não exportados para o força de vendas.             OPERACIONAL                        NaN
PCHIST DTMXSALTER         DATE                                                                                                  NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*