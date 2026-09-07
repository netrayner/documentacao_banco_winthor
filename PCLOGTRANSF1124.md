# 📊 Tabela: PCLOGTRANSF1124

### Estrutura de Colunas e Restrições

         Tabela              Coluna Tipo/Tamanho                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGTRANSF1124            DTTRANSF         DATE                                                                           Data da transação (DD/MM/AAAA).            OPERACIONAL                        NaN
PCLOGTRANSF1124            OPERACAO  VARCHAR2(2) Tipo da operação de transferência (EF - Entre filiais / OP - Operador logístico / DF - Deposito fechado).            OPERACIONAL                        NaN
PCLOGTRANSF1124         NUMTRANSENT NUMBER(10,0)                                              Número da transação de entrada usado para carregar os itens.            OPERACIONAL                        NaN
PCLOGTRANSF1124       CODFILIALORIG  VARCHAR2(2)                                                                               Código da filial de origem.            OPERACIONAL                        NaN
PCLOGTRANSF1124 NUMTRANSVENDATRANSF NUMBER(10,0)                                                                      Número da transação de saída gerado.            OPERACIONAL                        NaN
PCLOGTRANSF1124       CODFILIALDEST  VARCHAR2(2)                                                                                 Código da filial destino.            OPERACIONAL                        NaN
PCLOGTRANSF1124   NUMTRANSENTTRANSF NUMBER(10,0)                                                                    Número da transação de entrada gerado.            OPERACIONAL                        NaN
PCLOGTRANSF1124            DTCANCEL         DATE                                                                    Data de cancelamento da transferência.            OPERACIONAL                        NaN
PCLOGTRANSF1124       CODFUNCCANCEL  NUMBER(8,0)                                                               Matricula de quem cancelou a transferência.            OPERACIONAL                        NaN
PCLOGTRANSF1124      CHAVENFVINCULO VARCHAR2(45)                                 Chave NF-e vinculada a transação de entrada usada para carregar os itens.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*