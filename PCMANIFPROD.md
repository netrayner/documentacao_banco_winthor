# 📊 Tabela: PCMANIFPROD

### Estrutura de Colunas e Restrições

     Tabela           Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFPROD         NUMMANIF  NUMBER(8,0)               Código de produto incluido em uma Manifestação.            OPERACIONAL                        NaN
PCMANIFPROD           NUMSEQ  NUMBER(2,0) Número da Manifestação à qual a seleção de produtos pertence.            OPERACIONAL                        NaN
PCMANIFPROD          CODPROD  NUMBER(6,0)                          Número de sequencia da Manifestação.            OPERACIONAL                        NaN
PCMANIFPROD      QTRECLAMADA NUMBER(20,6)  Indica a quantidade reclamada/avaria informada pelo cliente.            OPERACIONAL                        NaN
PCMANIFPROD          NUMNOTA NUMBER(10,0)                                                Numero da Nota            OPERACIONAL                        NaN
PCMANIFPROD     CODMOTORISTA  NUMBER(8,0)                                           Código do Motorista            OPERACIONAL                        NaN
PCMANIFPROD           CODRCA  NUMBER(4,0)                                                 Código do Rca            OPERACIONAL                        NaN
PCMANIFPROD CODTRANSPORTADOR  NUMBER(6,0)                                       Código do Transportador            OPERACIONAL                        NaN
PCMANIFPROD      CODAJUDANTE  NUMBER(8,0)                             Identifica o ajudate do motorista            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*