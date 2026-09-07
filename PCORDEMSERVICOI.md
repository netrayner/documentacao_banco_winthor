# 📊 Tabela: PCORDEMSERVICOI

### Estrutura de Colunas e Restrições

         Tabela                    Coluna   Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORDEMSERVICOI              NUMOSSERVICO    NUMBER(6,0)                           Indica o número da OS de serviço.    CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMSERVICOI                     NUMOS    NUMBER(6,0)                           Indica o número ordem de Serviço.            OPERACIONAL                        NaN
PCORDEMSERVICOI                   CODPROD    NUMBER(6,0)                                 Indica o código do produto.            OPERACIONAL                        NaN
PCORDEMSERVICOI                   CODFUNC    NUMBER(8,0)                             Indica o código do funcionário.            OPERACIONAL                        NaN
PCORDEMSERVICOI                     PRECO   NUMBER(24,6)                                  Indica o preço do serviço.            OPERACIONAL                        NaN
PCORDEMSERVICOI                  DTINICIO           DATE      Indica a data e hora de inicio da execução do serviço.            OPERACIONAL                        NaN
PCORDEMSERVICOI                   DTFINAL           DATE          Indica a data e hora final da execução do serviço.            OPERACIONAL                        NaN
PCORDEMSERVICOI         PERCALIQISSRETIDA    NUMBER(8,4)                        Percentual de alíquota retenção ISS.            OPERACIONAL                        NaN
PCORDEMSERVICOI                  RETERISS    VARCHAR2(1)            Se ISS retido sobre o valor do serviço prestado.            OPERACIONAL                        NaN
PCORDEMSERVICOI                     PUNIT   NUMBER(24,6)                                  Preço unitário do serviço.            OPERACIONAL                        NaN
PCORDEMSERVICOI        TITULOLEVANTAMENTO  VARCHAR2(100)                                         titulo levantamento            OPERACIONAL                        NaN
PCORDEMSERVICOI       DETALHELEVANTAMENTO VARCHAR2(4000)                                     detalhe do levantamento            OPERACIONAL                        NaN
PCORDEMSERVICOI             RETERINSSCPRB    VARCHAR2(1)                                                  Reter INSS            OPERACIONAL                        NaN
PCORDEMSERVICOI CODIGOINDICATIVOSUSPENSAO   VARCHAR2(14)                              Código Indicativo de Suspensão            OPERACIONAL                        NaN
PCORDEMSERVICOI               CODDEPOSITO   NUMBER(10,0) Código do depósito onde o estoque esta armazenado na filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*