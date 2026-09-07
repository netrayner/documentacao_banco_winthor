# 📊 Tabela: PCMOVENDPENDCONFLOTE

### Estrutura de Colunas e Restrições

              Tabela            Coluna Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVENDPENDCONFLOTE         CODFILIAL  VARCHAR2(2)                                                Filial daoperação.            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE             NUMOS NUMBER(10,0)                                                 Ordem de serviço.            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE           CODPROD  NUMBER(6,0)                                                Código do produto.            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE           NUMLOTE VARCHAR2(15)                                                   Número do lote.            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE                QT NUMBER(20,8)                                               Quantidade do lote.            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE           CODOPER  VARCHAR2(2)                                                   CODIGO OPERAÇÃO            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE            TIPOOS  NUMBER(4,0)                                                        TIPO DA OS            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE           QTPECAS NUMBER(20,8)                  Quantidade de peças informada para peso variável            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE            QTORIG NUMBER(20,8)                                               Quantidade original            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE       CODENDERECO NUMBER(10,0)                                                Código do Endereço            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE        DESDOBRADO      CHAR(1)                                                     Desdobramento            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE INDUCAOFINALIZADA      CHAR(1)               Indentifica se a indução de lote já está finalizada            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE             DTVAL         DATE Data de validade usada para produtos que controlam validade na PK            OPERACIONAL                        NaN
PCMOVENDPENDCONFLOTE         DTENTRADA         DATE                                     Data de entrada dos endereços            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*