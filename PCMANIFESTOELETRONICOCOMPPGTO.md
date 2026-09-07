# 📊 Tabela: PCMANIFESTOELETRONICOCOMPPGTO

### Estrutura de Colunas e Restrições

                       Tabela              Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFESTOELETRONICOCOMPPGTO           NUMEVENTO NUMBER(10,0)            Número sequencial do evento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCOMPPGTO        TPCOMPONENTE  VARCHAR2(2)                     Tipo do Componente            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCOMPPGTO        VLCOMPONENTE NUMBER(13,2)                    Valor do Componente            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCOMPPGTO DESCRICAOCOMPONENTE VARCHAR2(60) Descrição do componente do tipo Outros            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCOMPPGTO          VLCONTRATO NUMBER(13,2)                Valor total do contrato            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCOMPPGTO              INDPAG  NUMBER(1,0)        Indicador da Forma de Pagamento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCOMPPGTO          NUMSEQCOMP NUMBER(10,0)        Número sequencial do componente            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOCOMPPGTO        NUMTRANSACAO NUMBER(10,0)                     Transação do MDF-e            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*