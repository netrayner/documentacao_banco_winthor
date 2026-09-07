# 📊 Tabela: PCINVENTENDERECOIVOLUME

### Estrutura de Colunas e Restrições

                 Tabela      Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINVENTENDERECOIVOLUME    INVENTOS  NUMBER(8,0) Ordem de serviço do inventário.            OPERACIONAL                        NaN
PCINVENTENDERECOIVOLUME CODENDERECO  NUMBER(8,0)             Código do endereço.            OPERACIONAL                        NaN
PCINVENTENDERECOIVOLUME     CODPROD  NUMBER(8,0)              Código do produto.            OPERACIONAL                        NaN
PCINVENTENDERECOIVOLUME     NUMLOTE VARCHAR2(15)                 Número do lote.            OPERACIONAL                        NaN
PCINVENTENDERECOIVOLUME    CONTAGEM  NUMBER(2,0)                 Contagem da OS.            OPERACIONAL                        NaN
PCINVENTENDERECOIVOLUME  DTVALIDADE         DATE            Validade do produto.            OPERACIONAL                        NaN
PCINVENTENDERECOIVOLUME   SEQUENCIA  NUMBER(6,0)          Sequencia do checkout.            OPERACIONAL                        NaN
PCINVENTENDERECOIVOLUME          QT NUMBER(18,6)           Quantidade informada.            OPERACIONAL                        NaN
PCINVENTENDERECOIVOLUME  CONFIRMADO      CHAR(1)               Confirmado na OS.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*