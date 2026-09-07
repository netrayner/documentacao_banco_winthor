# 📊 Tabela: PCDIAATAC

### Estrutura de Colunas e Restrições

   Tabela          Coluna Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDIAATAC          CODIGO  NUMBER(8,0)  Sequencial do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCDIAATAC       CODFILIAL  VARCHAR2(2)        Código da filial            OPERACIONAL                        NaN
PCDIAATAC         DIAATAC         DATE          Dia do atacado            OPERACIONAL                        NaN
PCDIAATAC     NOMEDIAATAC VARCHAR2(40)   Descrição da promoção            OPERACIONAL                        NaN
PCDIAATAC     CODFUNCLANC  NUMBER(8,0)   Usuário do lançamento            OPERACIONAL                        NaN
PCDIAATAC          DTLANC         DATE      Data de lançamento            OPERACIONAL                        NaN
PCDIAATAC        DTCANCEL         DATE    Data de cancelamento            OPERACIONAL                        NaN
PCDIAATAC   CODFUNCCANCEL  NUMBER(8,0) Usuário do cancelamento            OPERACIONAL                        NaN
PCDIAATAC    MOTIVOCANCEL VARCHAR2(80)  Motivo do cancelamento            OPERACIONAL                        NaN
PCDIAATAC        CODDEPTO  NUMBER(6,0)  Código do Departamento            OPERACIONAL                        NaN
PCDIAATAC          CODSEC  NUMBER(6,0)         Código da Seção            OPERACIONAL                        NaN
PCDIAATAC    CODCATEGORIA  NUMBER(6,0)     Código da categoria            OPERACIONAL                        NaN
PCDIAATAC CODSUBCATEGORIA  NUMBER(6,0)  Código da Subcategoria            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*