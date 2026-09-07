# 📊 Tabela: PCINTEGRACAOWMSSAASITEM

### Estrutura de Colunas e Restrições

                 Tabela        Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOWMSSAASITEM NUMDOCWMSSAAS NUMBER(14,0) Número do documento integrado no WMS Saas            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAASITEM       CODPROD  NUMBER(6,0)                         Código do produto            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAASITEM        QTORIG NUMBER(20,6)          Quantidade original do documento            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAASITEM            QT NUMBER(20,6)                   Quantidade do documento            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAASITEM    QTSEPARADA NUMBER(20,6)               Quantidade separada do item            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAASITEM     QTCORTADA NUMBER(20,6)                Quantidade cortada do item            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAASITEM       NUMLOTE VARCHAR2(15)                            Número do lote            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAASITEM        NUMSEQ NUMBER(20,0)               Número de sequencia do item            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAASITEM    DTVALIDADE         DATE                          Data de validade            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*