# 📊 Tabela: PCLOGCONTROLEFISCAL

### Estrutura de Colunas e Restrições

             Tabela       Coluna  Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCONTROLEFISCAL       CODLOC   NUMBER(9,0)                                           código do log    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGCONTROLEFISCAL    CODFILIAL   VARCHAR2(2)                                        código de filial            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL         DATA          DATE                           data da execução do recalculo            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL        OPCAO  VARCHAR2(20)    opção de recalculo - estoque / historico / piscofins            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL      CODFUNC   NUMBER(8,0)                                   código do funcionário            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL    DTINICIAL          DATE                                             data incial            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL      DTFINAL          DATE                                              data final            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL      MAQUINA VARCHAR2(100)                                       maquina utilizada            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL     TERMINAL  VARCHAR2(50)                                      terminal utilizado            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL       OSUSER  VARCHAR2(30)                          usuario do sistema operacional            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL CODIGOORIGEM  NUMBER(10,0)                                           Código Origem            OPERACIONAL                        NaN
PCLOGCONTROLEFISCAL  OBSERVACOES          CLOB serão gravados todos os produtos que forem recalculados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*