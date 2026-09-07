# 📊 Tabela: PCBIONEXOPARAM

### Estrutura de Colunas e Restrições

        Tabela                Coluna  Tipo/Tamanho                                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBIONEXOPARAM             USUARIOWS VARCHAR2(100)               Esta coluna armazena o usuário que será utilizado na comunicação com o webservice da Bioinexo            OPERACIONAL                        NaN
PCBIONEXOPARAM               SENHAWS VARCHAR2(100)                 Esta coluna armazena a senha que será utilizado na comunicação com o webservice da Bioinexo            OPERACIONAL                        NaN
PCBIONEXOPARAM                 URLWS VARCHAR2(200)                   Esta coluna armazena a URL que será utilizado na comunicação com o webservice da Bioinexo            OPERACIONAL                        NaN
PCBIONEXOPARAM           ULTTOKEMPDC  NUMBER(10,0)                                                                                          Token de validação            OPERACIONAL                        NaN
PCBIONEXOPARAM           ULTTOKEMWJC  NUMBER(10,0)                                                                                          Token de validação            OPERACIONAL                        NaN
PCBIONEXOPARAM               CODUSUR   NUMBER(4,0)                   Esta coluna armazena o RCA que será utilizado na comunicação com o webservice da Bioinexo            OPERACIONAL                        NaN
PCBIONEXOPARAM       MOSTRARIMPOSTOS   VARCHAR2(1) Esta coluna determina se será apresentado ao usuário da rotina os impostos dos produtos contidos na cotação            OPERACIONAL                        NaN
PCBIONEXOPARAM           MEDICAMENTO   VARCHAR2(1)                                                  Esta coluna determina se o produto é ou não um medicamento            OPERACIONAL                        NaN
PCBIONEXOPARAM UTILIZAFATORCONVERSAO   VARCHAR2(1)                               Esta coluna informa se o produto utilizará o fator de convesão para a Bionexo            OPERACIONAL                        NaN
PCBIONEXOPARAM      PRAZOENTREGADIAS   NUMBER(5,0)                                                      Esta coluna armazena o prazo para entrega dos produtos            OPERACIONAL                        NaN
PCBIONEXOPARAM     VLRFATURAMENTOMIN   NUMBER(8,2)                Esta coluna armazena o valor mínimo aceito pela distribuição para faturamento de uma cotação            OPERACIONAL                        NaN
PCBIONEXOPARAM              CODPRACA   NUMBER(4,0)                             Esta coluna determina o código da praça que será utilizado no pedido da cotação            OPERACIONAL                        NaN
PCBIONEXOPARAM        INCLUIRCLIAUTO   VARCHAR2(1)                           Esta coluna determina se o cliente da cotação será incluso ou não automaticamente            OPERACIONAL                        NaN
PCBIONEXOPARAM      NUMDECIMAISVENDA   NUMBER(4,0)                                    Esta coluna determina o número de casas decimais aceitas pela integração            OPERACIONAL                        NaN
PCBIONEXOPARAM        FORMAPAGAMENTO  NUMBER(10,0)                                                            Forma de pagamento a ser utilizada na integração            OPERACIONAL                        NaN
PCBIONEXOPARAM             TIPOFRETE   VARCHAR2(3)                                                                      Tipo de frente utilizado na integração            OPERACIONAL                        NaN
PCBIONEXOPARAM QTDEDIASVALIDPROPOSTA   NUMBER(5,0)                            Esta coluna determina a quantidade de dias aceito na proposta/retorno da cotação            OPERACIONAL                        NaN
PCBIONEXOPARAM             CODFILIAL   VARCHAR2(2)                                                                  Código da filial do parâmetro, obrigatório    CHAVE PRIMÁRIA (PK)                        NaN
PCBIONEXOPARAM     DESCINTERMEDIADOR  VARCHAR2(60)                                                                                     Descrição Intermediador            OPERACIONAL                        NaN
PCBIONEXOPARAM     CNPJINTERMEDIADOR  VARCHAR2(20)                                                                                          CNPJ Intermediador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*