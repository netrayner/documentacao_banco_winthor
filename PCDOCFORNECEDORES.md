# 📊 Tabela: PCDOCFORNECEDORES

### Estrutura de Colunas e Restrições

           Tabela           Coluna  Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCFORNECEDORES        CODFORNEC   NUMBER(7,0)     Código fornecedor.            OPERACIONAL                        NaN
PCDOCFORNECEDORES CODTIPODOCUMENTO   NUMBER(6,0) Código tipo documento.            OPERACIONAL                        NaN
PCDOCFORNECEDORES           COPIAS   NUMBER(6,0)                Copias.            OPERACIONAL                        NaN
PCDOCFORNECEDORES       DIAS_AVISO   NUMBER(4,0)         Dias de aviso.            OPERACIONAL                        NaN
PCDOCFORNECEDORES       OBSERVACAO VARCHAR2(100)            Observação.            OPERACIONAL                        NaN
PCDOCFORNECEDORES         VALIDADE          DATE              Validade.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*