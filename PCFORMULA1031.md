# 📊 Tabela: PCFORMULA1031

### Estrutura de Colunas e Restrições

       Tabela                 Coluna   Tipo/Tamanho                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMULA1031             CODFORMULA    NUMBER(4,0)                                                                                                   Código da fórmula    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULA1031                     UF    VARCHAR2(2)                                                                                           UF da fórmula (padrão RN)            OPERACIONAL                        NaN
PCFORMULA1031            TIPOFORMULA    VARCHAR2(1)                                                                       Tipo da fórmula (A - aquisições / S - saídas)            OPERACIONAL                        NaN
PCFORMULA1031                 STATUS    VARCHAR2(1)                                                                       Situação da fórmula (A - ativo / I - inativo)            OPERACIONAL                        NaN
PCFORMULA1031            DESCFORMULA  VARCHAR2(100)                                                                                                Descrição da fórmula            OPERACIONAL                        NaN
PCFORMULA1031           PERCAPURACAO   NUMBER(12,4)                                                                                              Percentual de apuração            OPERACIONAL                        NaN
PCFORMULA1031          FAIXAALIQUOTA    NUMBER(1,0) Faixa da aliquota do ICMS (0 - entre / 1 - menor que / 2 - menor ou igual a / 3 - maior que / 4 - maior ou igual a)            OPERACIONAL                        NaN
PCFORMULA1031            PERCMINICMS   NUMBER(12,4)                                                                                           Percentual mínimo de ICMS            OPERACIONAL                        NaN
PCFORMULA1031            PERCMAXICMS   NUMBER(12,4)                                                                                           Percentual máximo de ICMS            OPERACIONAL                        NaN
PCFORMULA1031         CESTABASICALEG    VARCHAR2(1)                                                                                      Valida cesta básica legislação            OPERACIONAL                        NaN
PCFORMULA1031      DECRETOESPECIFICO    VARCHAR2(1)                                                                                      Detentor de decreto especifico            OPERACIONAL                        NaN
PCFORMULA1031     TIPOAQUISICAOSAIDA    VARCHAR2(1)                                                               Tipo de aquisição / saída (I - interna / E - externa)            OPERACIONAL                        NaN
PCFORMULA1031             TIPOFORNEC   VARCHAR2(20)                                                                            Tipo do fornecedor (somente aquisições).            OPERACIONAL                        NaN
PCFORMULA1031            TIPOCLIENTE    VARCHAR2(1)                                                                                    Tipo do cliente (somente saídas)            OPERACIONAL                        NaN
PCFORMULA1031          TIPOVALIDANCM    VARCHAR2(1)                                                                  Tipo de validação do NCM (I - valida / N - exclui)            OPERACIONAL                        NaN
PCFORMULA1031               LISTANCM VARCHAR2(1000)                                                                                                Lista / faixa de NCM            OPERACIONAL                        NaN
PCFORMULA1031         TIPOVALIDACFOP    VARCHAR2(1)                                                                 Tipo de validação do CFOP (I - valida / N - exclui)            OPERACIONAL                        NaN
PCFORMULA1031              LISTACFOP VARCHAR2(1000)                                                                                               Lista / faixa de CFOP            OPERACIONAL                        NaN
PCFORMULA1031         TIPOVALIDACEST    VARCHAR2(1)                                                                 Tipo de validação do CEST (I - valida / N - exclui)            OPERACIONAL                        NaN
PCFORMULA1031              LISTACEST VARCHAR2(1000)                                                                                               Lista / faixa de CEST            OPERACIONAL                        NaN
PCFORMULA1031          FORMULAFORAUF    VARCHAR2(1)                                                      Fórmula aceita validação para aquisição / saída fora do estado            OPERACIONAL                        NaN
PCFORMULA1031        CODFUNCCADASTRO    NUMBER(8,0)                                                                               Matricula de quem cadastrou a fórmula            OPERACIONAL                        NaN
PCFORMULA1031             DTCADASTRO           DATE                                                                                         Data de cadastro da fórmula            OPERACIONAL                        NaN
PCFORMULA1031        CODFUNCULTALTER    NUMBER(8,0)                                                            Matricula de quem realizou a última alteração na fórmula            OPERACIONAL                        NaN
PCFORMULA1031             DTULTALTER           DATE                                                                                 Data da última alteração na fórmula            OPERACIONAL                        NaN
PCFORMULA1031         CODFUNCINATIVO    NUMBER(8,0)                                                                                Matricula de quem inativou a fórmula            OPERACIONAL                        NaN
PCFORMULA1031              DTINATIVO           DATE                                                                                       Data de inativação da fórmula            OPERACIONAL                        NaN
PCFORMULA1031           ORGAOPUBLICO    VARCHAR2(1)                                                                Valida órgão público (municipal, estadual e federal)            OPERACIONAL                        NaN
PCFORMULA1031              PERCFUNDO   NUMBER(12,4)                                                                                                Percentual de fundos            OPERACIONAL                        NaN
PCFORMULA1031             CLIENTECPF    VARCHAR2(1)                                                                                      Valida somente cliente com CPF            OPERACIONAL                        NaN
PCFORMULA1031    CLIENTECONTRIBUINTE    VARCHAR2(1)                                                                                 Valida somente cliente contribuinte            OPERACIONAL                        NaN
PCFORMULA1031            CUPOMFISCAL    VARCHAR2(1)                                                                                     Permitir vendas de cupom fiscal            OPERACIONAL                        NaN
PCFORMULA1031          ENTRADATRANSF    VARCHAR2(1)                                                                                  Permitir entradas de transferência            OPERACIONAL                        NaN
PCFORMULA1031        PERCICMSEFETIVO   NUMBER(12,4)                                                                                          Percentual do ICMS efetivo            OPERACIONAL                        NaN
PCFORMULA1031         TIPOAJUSTE1097   VARCHAR2(50)                             Tipo de ajuste dos registros C197/D197, na opção "Ajustes Doc. Fiscais", da rotina 1097            OPERACIONAL                        NaN
PCFORMULA1031              CODFILIAL    VARCHAR2(2)                                                                       Código da filial que a fórmula foi cadastrada            OPERACIONAL                        NaN
PCFORMULA1031            TIPOCALCULO    VARCHAR2(2)                                                Tipo de Cálculo (CP - Crédito Presumido / RE - Recolhimento Efetivo)            OPERACIONAL                        NaN
PCFORMULA1031  DEDUZDEVCLISAIDASTRIB    VARCHAR2(1)                                                                 Deduzir entrada de devoluções das saídas tributadas            OPERACIONAL                        NaN
PCFORMULA1031 USABASECREDPRESVLFUNDO    VARCHAR2(1)                                              Usa valor Crédito Presumido no calculo da base de calculo do Vlr.Fundo            OPERACIONAL                        NaN
PCFORMULA1031      CONSVALOROPERACAO    VARCHAR2(1)                                                                                        Considerar valor da operação            OPERACIONAL                        NaN
PCFORMULA1031            DESCONSCFOP    VARCHAR2(1)                                                                                                  Desconsiderar CFOP            OPERACIONAL                        NaN
PCFORMULA1031             DESCONSNCM    VARCHAR2(1)                                                                                                   Desconsiderar NCM            OPERACIONAL                        NaN
PCFORMULA1031            DESCONSCEST    VARCHAR2(1)                                                                                           Desconsiderar código CEST            OPERACIONAL                        NaN
PCFORMULA1031  MAIORVLICMSOUCREDPRES    VARCHAR2(1)                                                           Comparar o valor do ICMS com o valor do Crédito Presumido            OPERACIONAL                        NaN
PCFORMULA1031  DESCONSNFCOMPLEMENTAR    VARCHAR2(1)                                                                                       Desconsiderar NF Complementar            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*