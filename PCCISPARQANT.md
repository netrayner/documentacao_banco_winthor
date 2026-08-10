# 📊 Tabela: PCCISPARQANT

### Estrutura de Colunas e Restrições

      Tabela                       Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCISPARQANT                     CNPJCISP VARCHAR2(20)                  CNPJ ou CPF do cliente cadastrado.    CHAVE PRIMÁRIA (PK)                        NaN
PCCISPARQANT                         DATA         DATE                Data que foi gerado o ultimo arquivo            OPERACIONAL                        NaN
PCCISPARQANT               DTULTIMACOMPRA         DATE                    Data da Ultima Compra do Cliente            OPERACIONAL                        NaN
PCCISPARQANT            VALORULTIMACOMPRA NUMBER(12,2)                              Valor da Ultima Compra            OPERACIONAL                        NaN
PCCISPARQANT             VALORDEBITOATUAL NUMBER(12,2)         Valor do Débito atual do cliente na empresa            OPERACIONAL                        NaN
PCCISPARQANT              VLDEBITOAVENCER NUMBER(12,2)       Valor do Débito atual de titulos não vencidos            OPERACIONAL                        NaN
PCCISPARQANT        MEDIAPONDERADAAVENCER NUMBER(12,2)                Média Ponderada dos titulos a vencer            OPERACIONAL                        NaN
PCCISPARQANT             PRAZOMEDIOVENDAS NUMBER(12,2)                              Prazo médio das vendas            OPERACIONAL                        NaN
PCCISPARQANT        VLDEBITOVENCMAIS5DIAS NUMBER(12,2)                Valor dos Débitos Venc a + de 5 dias            OPERACIONAL                        NaN
PCCISPARQANT  MEDIAPONDERADAVENCMAIS5DIAS NUMBER(12,2)  Média Ponderada dos titulos vencidos a + de 5 dias            OPERACIONAL                        NaN
PCCISPARQANT       VLDEBITOVENCMAIS15DIAS NUMBER(12,2)               Valor dos Débitos Venc a + de 15 dias            OPERACIONAL                        NaN
PCCISPARQANT MEDIAPONDERADAVENCMAIS15DIAS NUMBER(12,2) Média Ponderada dos titulos vencidos a + de 15 dias            OPERACIONAL                        NaN
PCCISPARQANT       VLDEBITOVENCMAIS30DIAS NUMBER(12,2)               Valor dos Débitos Venc a + de 30 dias            OPERACIONAL                        NaN
PCCISPARQANT             VLPAGOMESPASSADO NUMBER(12,2)              Valor Pago pelo cliente no Mês Passado            OPERACIONAL                        NaN
PCCISPARQANT             DTMAIORACUMULADO         DATE         Data que o cliente teve maior saldo Devedor            OPERACIONAL                        NaN
PCCISPARQANT          VALORMAIORACUMULADO NUMBER(12,2)     Maior Valor que o Cliente teve de saldo Devedor            OPERACIONAL                        NaN
PCCISPARQANT     MEDIAPONDERADAATRASOPAGO NUMBER(12,2)             Média ponderada de pagamentos atrasados            OPERACIONAL                        NaN
PCCISPARQANT             MEDIAARITMETPAGO NUMBER(12,2)                      Média Aritmética de Pagamentos            OPERACIONAL                        NaN
PCCISPARQANT MEDIAPONDERADAVENCMAIS30DIAS NUMBER(12,2) Média Ponderada dos titulos vencidos a + de 30 dias            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*