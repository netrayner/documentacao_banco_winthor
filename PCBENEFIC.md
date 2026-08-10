# 📊 Tabela: PCBENEFIC

### Estrutura de Colunas e Restrições

   Tabela          Coluna Tipo/Tamanho                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFIC          NUMPED NUMBER(10,0)                                                                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFIC       CODFILIAL  VARCHAR2(2)                                                                                                    NaN            OPERACIONAL                        NaN
PCBENEFIC            DATA         DATE                                                                                                    NaN            OPERACIONAL                        NaN
PCBENEFIC        CODCONTA NUMBER(10,0)                                                                                                    NaN            OPERACIONAL                        NaN
PCBENEFIC       HISTORICO VARCHAR2(40)                                                                                                    NaN            OPERACIONAL                        NaN
PCBENEFIC       CODFORNEC  NUMBER(6,0)                                                                                                    NaN            OPERACIONAL                        NaN
PCBENEFIC           DTFAT         DATE                                      Indica a data e hora do Faturamento do Pedido de Beneficiamento.             OPERACIONAL                        NaN
PCBENEFIC      CODFUNCFAT  NUMBER(8,0)                    Matrícula do Funcionário responsável pelo Faturamento do Pedido de Beneficiamento.             OPERACIONAL                        NaN
PCBENEFIC          PRAZO1  NUMBER(4,0) Campo para armazenar o prazo de pagamento para geração do contas a pagar na entrade de beneficiamento             OPERACIONAL                        NaN
PCBENEFIC CODFILIALTRANSF  VARCHAR2(2)                                             Filial para transferência do estoque do produto de origem.            OPERACIONAL                        NaN
PCBENEFIC        TIPOLANC  VARCHAR2(2)                                                                                     Tipo de lançamento            OPERACIONAL                        NaN
PCBENEFIC          STATUS  VARCHAR2(1)                                                                               Status Aberto ou Fechado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*