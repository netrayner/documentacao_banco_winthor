# 📊 Tabela: PCLOGVALEITEM

### Estrutura de Colunas e Restrições

       Tabela      Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGVALEITEM      NUMPED NUMBER(10,0)          Número do Pedido da devolução.            OPERACIONAL                        NaN
PCLOGVALEITEM     CODPROD  NUMBER(6,0)                      Código do produto.            OPERACIONAL                        NaN
PCLOGVALEITEM QTDEVOLVIDA NUMBER(20,6) Quantidade devolvida do item no pedido.            OPERACIONAL                        NaN
PCLOGVALEITEM         OBS VARCHAR2(75)                Observação da devolução.            OPERACIONAL                        NaN
PCLOGVALEITEM      PVENDA NUMBER(18,6)                 Preço de Venda do item.            OPERACIONAL                        NaN
PCLOGVALEITEM        DATA         DATE                      Data da devolução.            OPERACIONAL                        NaN
PCLOGVALEITEM     USUARIO VARCHAR2(80)       Usuário que realizou a devolução.            OPERACIONAL                        NaN
PCLOGVALEITEM   CODFILIAL  VARCHAR2(2)             Código da filial do pedido.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*