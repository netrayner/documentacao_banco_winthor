# 📊 Tabela: PCPEDIDADOSVEICULOS

### Estrutura de Colunas e Restrições

             Tabela         Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIDADOSVEICULOS         NUMPED NUMBER(10,0)               Número do pedido            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS        CODPROD  NUMBER(6,0)              Código do produto            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS         NUMSEQ NUMBER(20,0) Número da sequencia do produto            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS         CHASSI VARCHAR2(17)              Chassi do Veículo            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS         CODCOR  NUMBER(4,0)                  Código da Cor            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS        DESCCOR VARCHAR2(40)               Descrição da Cor            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS       POTMOTOR VARCHAR2(10)                 Potência Motor            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS    CILINDRADAS  VARCHAR2(4)           Cilindradas do Motor            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS    PESOLIQUIDO NUMBER(18,4)                   Peso Liquido            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS      PESOBRUTO NUMBER(18,4)                     Peso Bruto            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS          SERIE  VARCHAR2(9)                          Série            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS  TPCOMBUSTIVEL  VARCHAR2(2)            Tipo de Comnustível            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS       NUMMOTOR VARCHAR2(21)                Número do Motor            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS            CMT NUMBER(18,4)    Capacidade Maxima de Tração            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS  DISTANCIAEIXO NUMBER(18,4)          Distância entre eixos            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS         ANOMOD  NUMBER(4,0)                     Ano Modelo            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS         ANOFAB  NUMBER(4,0)                 Ano Fabricação            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS      TPPINTURA  NUMBER(1,0)                Tipo de Pintura            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS      TPVEICULO  VARCHAR2(2)                Tipo de veículo            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS ESPECIEVEICULO  VARCHAR2(1)                Espécie veículo            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS            VIN  VARCHAR2(1)          VIN(chassi) remarcado            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS    CONDVEICULO  VARCHAR2(1)               Condição Veículo            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS      CODMODELO VARCHAR2(10)            Código Marca Modelo            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS CODCORDENATRAM  NUMBER(2,0)            Código cor Denatram            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS        LOTACAO  NUMBER(3,0)                        Lotação            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS    TPRESTRICAO  NUMBER(1,0)              Tipo de restrição            OPERACIONAL                        NaN
PCPEDIDADOSVEICULOS     TPOPERACAO  NUMBER(1,0)               Tipo da Operação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*