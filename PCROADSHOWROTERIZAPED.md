# 📊 Tabela: PCROADSHOWROTERIZAPED

### Estrutura de Colunas e Restrições

               Tabela         Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROADSHOWROTERIZAPED     IDROMANEIO NUMBER(10,0) Identificador do Romaneio Gerado para RoadShow            OPERACIONAL                        NaN
PCROADSHOWROTERIZAPED         NUMPED NUMBER(10,0)                    Número do Pedido Reterizado            OPERACIONAL                        NaN
PCROADSHOWROTERIZAPED NUMPEDROADSHOW VARCHAR2(20)           Número do Pedido + Código do Cliente            OPERACIONAL                        NaN
PCROADSHOWROTERIZAPED        POSICAO  VARCHAR2(1)               Posição do Pedido na Roterização            OPERACIONAL                        NaN
PCROADSHOWROTERIZAPED          DTMOV         DATE                           Data da Movimentação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*