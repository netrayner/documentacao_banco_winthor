# 📊 Tabela: PCMANIFESTOELETRONICOI

### Estrutura de Colunas e Restrições

                Tabela                   Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFESTOELETRONICOI                  NUMMDFE NUMBER(10,0)                                   NUMERO DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI            NUMTRANSVENDA NUMBER(10,0)                           NUMERO TRANSACAO DA NOTA/CT            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI             NUMTRANSACAO NUMBER(10,0)                      NUMERO DE TRANSAÇÃO DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                  NUMNOTA NUMBER(10,0)                                       Número da Nota.            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                 CHAVENFE VARCHAR2(44) Chave da nota fiscal eletrônica transportada no MDFe.            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                  DTSAIDA         DATE                                            Data saida            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                  VLTOTAL NUMBER(12,2)                              Valor total do documento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                 SULFRAMA VARCHAR2(15)                                           PIN SUFRAMA            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                  CODIBGE NUMBER(10,0)                                           Código IBGE            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                  ESPECIE  VARCHAR2(2)                                  Especie do documento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                     TIPO  NUMBER(2,0)                      1 - NFe, 2 - NF, 3 - CTe, 4 - CT            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                  TOTPESO NUMBER(18,6)                               Peso total do documento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI           NOMESEGURADORA VARCHAR2(30)                                    Nome da Seguradora            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI           CNPJSEGURADORA VARCHAR2(14)                          Número do CNPJ da seguradora            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI               NUMAPOLICE VARCHAR2(20)                                     Número da Apólice            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI             NUMAVERBACAO VARCHAR2(40)                                   Número da Averbação            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI        RESPONSAVELSEGURO  NUMBER(1,0)                               Responsável pelo seguro            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI           CNPJRESPSEGURO VARCHAR2(14)                       CNPJ do responsável pelo seguro            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI CODCIDADEDESCARREGAMENTO NUMBER(10,0)                         Código cidade descarregamento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOI                   NUMSEQ  NUMBER(8,0)     Numero de sequencia do evento de inclusão do MDFe            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*