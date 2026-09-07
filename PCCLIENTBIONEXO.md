# 📊 Tabela: PCCLIENTBIONEXO

### Estrutura de Colunas e Restrições

         Tabela       Coluna  Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIENTBIONEXO       CODCLI   NUMBER(6,0)                                     Código do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO      CLIENTE  VARCHAR2(60)                                  Descrição do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     FANTASIA  VARCHAR2(40)              Descrição do nome de fantasia do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       CGCENT  VARCHAR2(18)                                   CPF/CNPJ do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO INSCESTADUAL  VARCHAR2(20)                         Inscrição estadual do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     EMAILNFE VARCHAR2(100)                 Email usado para envio do arquivo NFE            OPERACIONAL                        NaN
PCCLIENTBIONEXO       CEPCOM   VARCHAR2(9)                                        CEP do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     ENDERCOM  VARCHAR2(40)                         Endereço comercial do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     MUNICCOM  VARCHAR2(15)            Município do endereço comercial do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       ESTCOM   VARCHAR2(2)   Unidade federativa do endereço comercial do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       TELCOM  VARCHAR2(13)                         Telefone comercial do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       FAXCOM  VARCHAR2(15)                              Fax comercial do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       CEPENT   VARCHAR2(9)                  CEP do endereço comercial do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     ENDERENT  VARCHAR2(40)                        Endereço de entrega do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     MUNICENT  VARCHAR2(15)           Município do endereço de entrega do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       ESTENT   VARCHAR2(2)  Unidade federativa do endereço de entrega do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       TELENT  VARCHAR2(13)                        Telefone de entrega do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       CEPCOB   VARCHAR2(9)                            CEP de cobrança do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     ENDERCOB  VARCHAR2(40)                       Endereço de cobrança do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     MUNICCOB  VARCHAR2(15)                      Munícipio de cobrança do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       ESTCOB   VARCHAR2(2) Unidade federativa do endereço de cobrança do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO       TELCOB  VARCHAR2(13)                       Telefone de cobrança do cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO     CODPRACA   NUMBER(6,0)                  Código da praça vinculada ao cliente            OPERACIONAL                        NaN
PCCLIENTBIONEXO   DTCADASTRO          DATE                                      Data de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*