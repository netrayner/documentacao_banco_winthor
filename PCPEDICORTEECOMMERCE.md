# 📊 Tabela: PCPEDICORTEECOMMERCE

### Estrutura de Colunas e Restrições

              Tabela         Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDICORTEECOMMERCE             ID NUMBER(10,0)                        Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICORTEECOMMERCE         NUMPED NUMBER(10,0)                      Número do pedido no winthor            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE      NUMPEDWEB NUMBER(10,0)                   Número do pedido no e-commerce            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE      CODFILIAL  VARCHAR2(2)                      Código da filial no winthor            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE        CODPROD  NUMBER(6,0)                                Código do produto            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE           TIPO  VARCHAR2(1)          Tipo de alteração no pedido (I, A ou E)            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE             QT NUMBER(18,6)                     Quantidade do item do pedido            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE         PVENDA NUMBER(18,6)                           Preço de venda do item            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE PVENDAORIGINAL NUMBER(18,6)      Preço de venda original, antes da alteração            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE    DTALTERACAO         DATE                                Data da alteração            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE       SITUACAO  VARCHAR2(1) Situação (S/N), enviado para o e-commerce ou não            OPERACIONAL                        NaN
PCPEDICORTEECOMMERCE        CAPTURA  VARCHAR2(2)                  Indica se registro é de captura            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*