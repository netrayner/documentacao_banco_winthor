# 📊 Tabela: PCDOCEMPRESAS

### Estrutura de Colunas e Restrições

       Tabela           Coluna  Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCEMPRESAS        CODFILIAL   VARCHAR2(2)         Código filial.            OPERACIONAL                        NaN
PCDOCEMPRESAS CODTIPODOCUMENTO   NUMBER(6,0) Código tipo documento.            OPERACIONAL                        NaN
PCDOCEMPRESAS           COPIAS   NUMBER(6,0)                Copias.            OPERACIONAL                        NaN
PCDOCEMPRESAS       DIAS_AVISO   NUMBER(4,0)            Dias Aviso.            OPERACIONAL                        NaN
PCDOCEMPRESAS          EMISSAO          DATE               Emissão.            OPERACIONAL                        NaN
PCDOCEMPRESAS       OBSERVACAO VARCHAR2(100)           Obeservação.            OPERACIONAL                        NaN
PCDOCEMPRESAS         VALIDADE          DATE              Validade.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*