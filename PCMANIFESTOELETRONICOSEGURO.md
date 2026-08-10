# 📊 Tabela: PCMANIFESTOELETRONICOSEGURO

### Estrutura de Colunas e Restrições

                     Tabela            Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFESTOELETRONICOSEGURO      NUMTRANSACAO NUMBER(10,0)                 Transação do MDFe que vinculado a este seguro            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOSEGURO    NOMESEGURADORA VARCHAR2(30)                          Nome da seguradora vinculada ao MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOSEGURO    CNPJSEGURADORA VARCHAR2(14)                            CNPJ da segurador vinculada o MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOSEGURO RESPONSAVELSEGURO  NUMBER(1,0) 1 - Emitente do MDFe 2 - Contratante do serviço de transporte            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOSEGURO    CNPJRESPSEGURO VARCHAR2(14)                       CNPJ do responsável pelo seguro do MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOSEGURO      NUMAVERBACAO VARCHAR2(40)                      Número de averbação do seguro contratado            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOSEGURO        NUMAPOLICE VARCHAR2(20)                          Número da apolice do seguro contrato            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*