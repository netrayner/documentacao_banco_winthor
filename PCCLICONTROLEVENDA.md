# 📊 Tabela: PCCLICONTROLEVENDA

### Estrutura de Colunas e Restrições

            Tabela               Coluna   Tipo/Tamanho      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLICONTROLEVENDA               CODCLI    NUMBER(6,0)             Cód. Cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCCLICONTROLEVENDA CODTIPOCONTROLEVENDA    NUMBER(3,0) Cód. Tipo Controle Venda    CHAVE PRIMÁRIA (PK)                        NaN
PCCLICONTROLEVENDA               NUMDOC   VARCHAR2(30)         Número Documento            OPERACIONAL                        NaN
PCCLICONTROLEVENDA           DTVALIDADE           DATE             Dt. Validade            OPERACIONAL                        NaN
PCCLICONTROLEVENDA           OBSERVACAO VARCHAR2(2000)              Observações            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*