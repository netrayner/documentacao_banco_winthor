# 📊 Tabela: PCCSTTRIBUTACAOIBSCBS

### Estrutura de Colunas e Restrições

               Tabela                     Coluna   Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCSTTRIBUTACAOIBSCBS      CODSITUACAOTRIBUTARIA    VARCHAR2(3)                        Código do situação tributária    CHAVE PRIMÁRIA (PK)                        NaN
PCCSTTRIBUTACAOIBSCBS      DESSITUACAOTRIBUTARIA  VARCHAR2(100)                     Descrição da situação Tributária            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS          TRIBUTACAOREGULAR    VARCHAR2(3)                                   Tributação Regular            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS               REDUCAOBCCST    VARCHAR2(3)                                    Redução de BC CST            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS          REDUCAODEALIQUOTA    VARCHAR2(3)                                  Redução de Alíquota            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS     TRANSFERENCIADECREDITO    VARCHAR2(3)                             Transferência de Crédito            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                DIFERIMENTO    VARCHAR2(3)                                          Diferimento            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                 MONOFASICA    VARCHAR2(3)                                           Monofásica            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS     CREDITOPRESUMIDOIBSZFM    VARCHAR2(3)          Crédito Presumido IBS Zona Franca de Manaus            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS        AJUSTEDECOMPETENCIA    VARCHAR2(3)                                Ajuste de Competência            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS CODCLASSIFICACAOTRIBUTARIA    VARCHAR2(6)                   Código da Classificação Tributaria    CHAVE PRIMÁRIA (PK)                        NaN
PCCSTTRIBUTACAOIBSCBS DESCLASSIFICACAOTRIBUTARIA VARCHAR2(1500)      Descrição do Código da Classificação Tributaria            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS       PERCENTUALREDUCAOIBS    NUMBER(7,4)                               Percentual Redução IBS            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS       PERCENTUALREDUCAOCBS    NUMBER(7,4)                               Percentual Redução CBS            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                  REDUCAOBC    VARCHAR2(3)                                           Redução BC            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS           CREDITOPRESUMIDO    VARCHAR2(3)                                    Credito Presumido            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS           ESTORNODECREDITO    VARCHAR2(3)                                   Estorno de Credito            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS             TIPODEALIQUOTA   VARCHAR2(25)                                     Tipo de Alíquota            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                        NFE    VARCHAR2(3)                               Nota fiscal eletrônica            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                       NFCE    VARCHAR2(3)                                  NF Cupom eletrônico            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                        CTE    VARCHAR2(3)                                        CT eletrônico            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                      CTEOS    VARCHAR2(3)                                    CTe Ordem Serviço            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                        BPE    VARCHAR2(3)                                        Documento BPe            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                       NF3E    VARCHAR2(3)                                       Documento NF3e            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                      NFCOM    VARCHAR2(3)                                      Documento NFCom            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                       NFSE    VARCHAR2(3)                                       Documento NFSE            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                      BPETM    VARCHAR2(3)                                      Documento BPeTM            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                      BPETA    VARCHAR2(3)                                      Documento BPeTA            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                       NFAG    VARCHAR2(3)                                       Documento NFAg            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                     NFSVIA    VARCHAR2(3)                                     Documento NFSVIA            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                      NFABI    VARCHAR2(3)                                      Documento NFABI            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                      NFGAS    VARCHAR2(3)                                      Documento NFGas            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                       DERE    VARCHAR2(3)                                       Documento DERE            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS              NUMERODOANEXO    VARCHAR2(5)                                      Numero do Anexo            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS            URLDALEGISLACAO  VARCHAR2(100)                                    Url da Legislação            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                         UF    VARCHAR2(2)                                     Unidade Federada    CHAVE PRIMÁRIA (PK)                        NaN
PCCSTTRIBUTACAOIBSCBS          TRIBUTACAOGIBSCBS    VARCHAR2(3)                                   Gera grupo IBS CBS            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS             TRIBMONONORMAL    VARCHAR2(3)                         Tributação Monofásica Normal            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS              TRIBMONORETEN    VARCHAR2(3)             Tributação Monofásica sujeita a retenção            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS             TRIBMONORETANT    VARCHAR2(3)           Tributação Monofásica retida anteriormente            OPERACIONAL                        NaN
PCCSTTRIBUTACAOIBSCBS                TRIBMONODIF    VARCHAR2(3) Tributação Monofásica de Combustível com diferimento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*