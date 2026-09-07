# 📊 Tabela: PCDESCONTOC

### Estrutura de Colunas e Restrições

     Tabela              Coluna  Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCONTOC              CODIGO  NUMBER(10,0)                                                       Indica o código da campanha de desconto.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTOC           DESCRICAO  VARCHAR2(40)                                                    Indica a descrição da campanha de desconto.            OPERACIONAL                        NaN
PCDESCONTOC            DTINICIO          DATE                                   Indica a data de início de vigência da campanha de desconto.            OPERACIONAL                        NaN
PCDESCONTOC               DTFIM          DATE                            Indica a data final Data final de vigência da campanha de desconto.            OPERACIONAL                        NaN
PCDESCONTOC      TIPOPATROCINIO   VARCHAR2(1)                                                       Indica o tipo de patrocínio da campanha.            OPERACIONAL                        NaN
PCDESCONTOC        TIPOCAMPANHA   VARCHAR2(3)                                                                     Indica o tipo de campanha.            OPERACIONAL                        NaN
PCDESCONTOC        TIPODESCONTO   VARCHAR2(1)                                                                     Indica o tipo de desconto.            OPERACIONAL                        NaN
PCDESCONTOC UTILIZACODPRODPRINC   VARCHAR2(1)                                                      Indica se considera famílias de produtos.            OPERACIONAL                        NaN
PCDESCONTOC  UTILIZACODCLIPRINC   VARCHAR2(1)                                                         Indica se considera redes de clientes.            OPERACIONAL                        NaN
PCDESCONTOC         METODOLOGIA VARCHAR2(400)                                                              Indica o metodologia da campamha.            OPERACIONAL                        NaN
PCDESCONTOC              SYNCFV   VARCHAR2(1)                                                                                            NaN            OPERACIONAL                        NaN
PCDESCONTOC       NAODEBITCCRCA   VARCHAR2(1)             Indica se conceder a política de desconto não irá debitar do conta corrente do RCA            OPERACIONAL                        NaN
PCDESCONTOC     CREDITAPOLITICA   VARCHAR2(2) Indica se irá creditar no conta corrente do RCA o valor da diferença do desconto não concedido            OPERACIONAL                        NaN
PCDESCONTOC       COMBOCONTINUO   VARCHAR2(2)                         Identificador se a campanha de desconto faz parte do processo de combo            OPERACIONAL                        NaN
PCDESCONTOC           CODFILIAL   VARCHAR2(2)                                                     Código da Filial para Cadastro da Campanha            OPERACIONAL                        NaN
PCDESCONTOC      ALTERARPTABELA   VARCHAR2(1)                                                            Define se campanha altera o PTABELA            OPERACIONAL                        NaN
PCDESCONTOC          PERCFORNEC  NUMBER(10,4)                                                            Percentual custeado pelo fornecedor            OPERACIONAL                        NaN
PCDESCONTOC            NUMVERBA   NUMBER(8,0)                                                             Nr. da verba atribuída a campanha.            OPERACIONAL                        NaN
PCDESCONTOC      PERCCUSTFORNEC  NUMBER(12,4)                                                           Percentual custeado pelo fornecedor.            OPERACIONAL                        NaN
PCDESCONTOC          DTMXSALTER          DATE                                                                                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*