# 📊 Tabela: PCCONTRATOEMPRESTIMO

### Estrutura de Colunas e Restrições

              Tabela                   Coluna  Tipo/Tamanho                                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTRATOEMPRESTIMO NUMSEQCONTRATOEMPRESTIMO  NUMBER(10,0)                                                                                 Número sequencial do contrato            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO              NUMCONTRATO  VARCHAR2(20)                                                                       Número do contrato de empréstimo FINIMP            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO               DTCONTRATO          DATE                                                                         Data do contrato de empréstimo FINIMP            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO             TIPOCONTRATO   VARCHAR2(1)                                                                                              Tipo do contrato            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO         MOEDAESTRANGEIRA   NUMBER(6,0)                                                                     Código da moeda estrangeira de negociação            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO                DTCOTACAO          DATE                                                            Data da cotação da moeda estrangeira de negociação            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO                 PRAZOPER   NUMBER(4,0)                                                                        Prazo da operação do empréstimo FINIMP            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO                   TXJURO  NUMBER(12,2)                                                                                                 Taxa de juros            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO                CODFORNEC   NUMBER(6,0)                                                                                        Código parceiro(banco)            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO                 CODBANCO   NUMBER(4,0)                                                    Código do caixa/banco (não utilizado no empréstimo FINIMP)            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO               OBSERVACAO VARCHAR2(200)                                                                            Observações definidas pelo usuário            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO                 VLRTOTAL  NUMBER(12,2)                                                                            Valor total do empréstimo em reais            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO           TIPOEMPRESTIMO   VARCHAR2(1)                                                                                            Tipo do emprestimo            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO            MOEDANACIONAL   VARCHAR2(1) Gravar sempre 'S' se o empréstimo foi adquirido em moeda nacional e 'N' se foi adquirido em moeda estrangeira            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO           VALORPRINCIPAL  NUMBER(14,2)                                                                                  Valor principal do contrato.            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO    JUROSMOEDAESTRANGEIRA   VARCHAR2(1)                                                    Informar se utiliza juros de moeda estrangeira no contrato            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO                 VLRJUROS  NUMBER(12,2)                                                   Valor dos juros, relacionado ao campo JUROSMOEDAESTRANGEIRA            OPERACIONAL                        NaN
PCCONTRATOEMPRESTIMO      CONTROLASALDOFORNEC   VARCHAR2(1)                                                                                Controlar saldo por fornecedor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*