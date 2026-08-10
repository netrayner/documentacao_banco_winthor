# 📊 Tabela: PCMANIFESTOELETRONICOCIOT

### Estrutura de Colunas e Restrições

                   Tabela       Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFESTOELETRONICOCIOT NUMTRANSACAO NUMBER(10,0)               Numero da Transacao do MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCIOT      NUMMDFE NUMBER(10,0)                            Numero do MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCIOT       NUMSEQ  NUMBER(3,0)                  Sequencia de Lançamentos            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCIOT      CPFCNPJ VARCHAR2(14) CNPJ CPF do responsavel pela geracao CIOT            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCIOT      NUMCIOT VARCHAR2(12)                            Codigo do CIOT            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*