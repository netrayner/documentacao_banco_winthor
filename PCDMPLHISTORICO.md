# 📊 Tabela: PCDMPLHISTORICO

### Estrutura de Colunas e Restrições

         Tabela    Coluna  Tipo/Tamanho                                                                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDMPLHISTORICO   CODDMPL  NUMBER(10,0) Código DMPL - Está coluna foi descontinuada, devido falha de modelagem, o Histórico de DMPL é disponível a todas as DMPL, e não a cada uma. CHAVE ESTRANGEIRA (FK)                     PCDMPL
PCDMPLHISTORICO   CODHIST  VARCHAR2(20)                                                                                                                            Código Histórico    CHAVE PRIMÁRIA (PK)                        NaN
PCDMPLHISTORICO HISTORICO VARCHAR2(100)                                                                                                                                   Descrição            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*