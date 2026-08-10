# 📊 Tabela: PCLOGCONCAUTOMBAIXA

### Estrutura de Colunas e Restrições

             Tabela        Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCONCAUTOMBAIXA       CODOPER NUMBER(10,0)        Sequencial para identificar as baixas realizadas.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA     CODFILIAL  VARCHAR2(2)                                Filial do título baixado.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA NUMTRANSVENDA NUMBER(10,0)                   Número da transação do título baixado.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA         PREST  VARCHAR2(2)                             Prestação do título baixado.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA      NUMTRANS NUMBER(10,0)     Número da transação do lançamento de DNI conciliado.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA       VALORCR NUMBER(18,6)                                 Valor do título baixado.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA     VALORLANC NUMBER(18,6)                   Valor do lançamento de DNI conciliado.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA          DATA         DATE                      Dara e Hora da baixa e conciliação.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA       CODFUNC  NUMBER(8,0) Código do funcionário da baixa e conciliação automática.             OPERACIONAL                        NaN
PCLOGCONCAUTOMBAIXA      OPERACAO VARCHAR2(20)                     Indica a operação que gerou a baixa.             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*