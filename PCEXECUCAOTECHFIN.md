# 📊 Tabela: PCEXECUCAOTECHFIN

### Estrutura de Colunas e Restrições

           Tabela        Coluna Tipo/Tamanho                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXECUCAOTECHFIN        PEDIDO NUMBER(10,0)                                                                          Numero do pedido            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN       REENVIO  VARCHAR2(1)                                                Informa se houve reenvio do pedido ou nota            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN    INTEGRACAO VARCHAR2(30)                                              Nome da integração que esta sendo processada            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN      OPERACAO  VARCHAR2(2)                                       Armazenar o código da operação de integração da API            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN        FILIAL  VARCHAR2(2)                                                               Armazena o código da filial            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN      EXECUCAO  VARCHAR2(1)                                                         Valor M - Manual e A - automático            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN    DTEXECUCAO TIMESTAMP(6)                                               Data e hora em que foi realizada a execução            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN        STATUS  VARCHAR2(1) Apresentar o status final do processamento da API. S - Sucesso F - Falha ou P-Processando            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN       DETALHE         CLOB           Apresentar as informações de processamento da API e retorno por ela apresentada            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN    NOTAFISCAL NUMBER(10,0)                                           Número da nota fiscal que esta sendo processado            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN NUMTRANSVENDA NUMBER(10,0)                          Número da transação de saída do título que esta sendo processado            OPERACIONAL                        NaN
PCEXECUCAOTECHFIN         PREST  VARCHAR2(2)                                   Número da prestação do título que esta sendo processado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*