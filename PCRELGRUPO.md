# 📊 Tabela: PCRELGRUPO

### Estrutura de Colunas e Restrições

    Tabela           Coluna Tipo/Tamanho  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRELGRUPO         CODGRUPO  NUMBER(8,0)     Código do Grupo.    CHAVE PRIMÁRIA (PK)                        NaN
PCRELGRUPO     CODRELATORIO  NUMBER(4,0) Código do Relatório.            OPERACIONAL                        NaN
PCRELGRUPO            ORDEM  NUMBER(3,0)      Ordem do Grupo.            OPERACIONAL                        NaN
PCRELGRUPO        DESCRICAO VARCHAR2(80)           Descrição.            OPERACIONAL                        NaN
PCRELGRUPO EXIBE_VLCONTABIL  VARCHAR2(1)  Exibir Vl.Contábil.            OPERACIONAL                        NaN
PCRELGRUPO     EXIBE_VLBASE  VARCHAR2(1)      Exibir Vl.Base.            OPERACIONAL                        NaN
PCRELGRUPO     EXIBE_VLICMS  VARCHAR2(1)      Exibir Vl.ICMS.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*