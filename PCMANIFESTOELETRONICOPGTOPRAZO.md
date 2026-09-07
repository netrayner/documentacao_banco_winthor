# 📊 Tabela: PCMANIFESTOELETRONICOPGTOPRAZO

### Estrutura de Colunas e Restrições

                        Tabela       Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFESTOELETRONICOPGTOPRAZO  NUMSEQPRAZO NUMBER(10,0)                       Número sequencial do prazo    CHAVE PRIMÁRIA (PK)                        NaN
PCMANIFESTOELETRONICOPGTOPRAZO    NUMEVENTO NUMBER(10,0) Número sequencial do evento (vinculo com evento)    CHAVE PRIMÁRIA (PK)                        NaN
PCMANIFESTOELETRONICOPGTOPRAZO   NUMPARCELA  VARCHAR2(3)                                Número da parcela            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTOPRAZO       DTVENC         DATE                    Data de vencimento da Parcela            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTOPRAZO VALORPARCELA NUMBER(18,6)                                 Valor da parcela            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTOPRAZO NUMTRANSACAO NUMBER(10,0)                               Transação do MDF-e            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*