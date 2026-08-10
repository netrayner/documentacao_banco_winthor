# 📊 Tabela: PCCLIENTDELIVERY

### Estrutura de Colunas e Restrições

          Tabela                    Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIENTDELIVERY            CODCLIDELIVERY   NUMBER(6,0)                             Código do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTDELIVERY                   CLIENTE  VARCHAR2(60)                               Nome do cliente            OPERACIONAL                        NaN
PCCLIENTDELIVERY                    CGCENT  VARCHAR2(18)                                      CPF/CNPJ            OPERACIONAL                        NaN
PCCLIENTDELIVERY                  ENDERENT  VARCHAR2(40)                                      Endereço            OPERACIONAL                        NaN
PCCLIENTDELIVERY                 NUMEROENT   VARCHAR2(6)                            Número do endereço            OPERACIONAL                        NaN
PCCLIENTDELIVERY                 BAIRROENT  VARCHAR2(40)                                        Bairro            OPERACIONAL                        NaN
PCCLIENTDELIVERY                    TELENT  VARCHAR2(15)                                      Telefone            OPERACIONAL                        NaN
PCCLIENTDELIVERY                 CODCIDADE   NUMBER(6,0)                                 Código cidade            OPERACIONAL                        NaN
PCCLIENTDELIVERY                  MUNICENT  VARCHAR2(15)                                     Municipio            OPERACIONAL                        NaN
PCCLIENTDELIVERY                    ESTENT   VARCHAR2(2)                                        Estado            OPERACIONAL                        NaN
PCCLIENTDELIVERY                    CEPENT   VARCHAR2(9)                                           CEP            OPERACIONAL                        NaN
PCCLIENTDELIVERY                     EMAIL VARCHAR2(100)                                        E-mail            OPERACIONAL                        NaN
PCCLIENTDELIVERY                        RG  VARCHAR2(20)                          Número da identidade            OPERACIONAL                        NaN
PCCLIENTDELIVERY                     IEENT  VARCHAR2(15)                            Inscrição estadual            OPERACIONAL                        NaN
PCCLIENTDELIVERY                       OBS VARCHAR2(100)                        Observação de cadastro            OPERACIONAL                        NaN
PCCLIENTDELIVERY                    DTNASC          DATE                            Data de nascimento            OPERACIONAL                        NaN
PCCLIENTDELIVERY               NOMECONTATO  VARCHAR2(40)                    Nome do contato do cliente            OPERACIONAL                        NaN
PCCLIENTDELIVERY           TELEFONECONTATO  VARCHAR2(15)                           Telefone do contato            OPERACIONAL                        NaN
PCCLIENTDELIVERY                OBSCONTATO  VARCHAR2(75)                         Observação do contato            OPERACIONAL                        NaN
PCCLIENTDELIVERY       DTEXPORTACAOSERVINT          DATE Dta de exportação para servidor intermediário            OPERACIONAL                        NaN
PCCLIENTDELIVERY          EXPORTADOSERVINT   VARCHAR2(1)       Exportado para o servidor intermediário            OPERACIONAL                        NaN
PCCLIENTDELIVERY        IMPORTADOSERVPRINC   VARCHAR2(1)             Importado para servidor principal            OPERACIONAL                        NaN
PCCLIENTDELIVERY     DTIMPORTACAOSERVPRINC          DATE     Dta de exportação para servidor principal            OPERACIONAL                        NaN
PCCLIENTDELIVERY IDENTIFICACAO_ESTRANGEIRO  VARCHAR2(20)        Identificação para cliente estrangeiro            OPERACIONAL                        NaN
PCCLIENTDELIVERY                DTCADASTRO          DATE                              Data de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*