# 📊 Tabela: PCREGISTROCIRURGIA

### Estrutura de Colunas e Restrições

            Tabela              Coluna  Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREGISTROCIRURGIA         NUMCIRURGIA  NUMBER(10,0)              Num. Cirurgia    CHAVE PRIMÁRIA (PK)                        NaN
PCREGISTROCIRURGIA   CODMEDICOCIRURGIA   NUMBER(6,0)                Cód. Médico            OPERACIONAL                        NaN
PCREGISTROCIRURGIA CODPACIENTECIRURGIA   NUMBER(9,0)              Cód. Paciente            OPERACIONAL                        NaN
PCREGISTROCIRURGIA          DTCIRURGIA          DATE           Data da Cirurgia            OPERACIONAL                        NaN
PCREGISTROCIRURGIA         ORDEMCOMPRA  VARCHAR2(20)            Ordem de Compra            OPERACIONAL                        NaN
PCREGISTROCIRURGIA            CONVENIO  VARCHAR2(30)                   Convênio            OPERACIONAL                        NaN
PCREGISTROCIRURGIA          OBSERVACAO VARCHAR2(100)                Observações            OPERACIONAL                        NaN
PCREGISTROCIRURGIA      CODPROMOCAOMED   NUMBER(9,0)            Código Promoção            OPERACIONAL                        NaN
PCREGISTROCIRURGIA     CODTIPOCIRURGIA   NUMBER(6,0) Codigo Do Tipo De Cirurgia            OPERACIONAL                        NaN
PCREGISTROCIRURGIA         CODCONVENIO   NUMBER(6,0)         Codigo Do Convenio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*