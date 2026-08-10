# 📊 Tabela: PCCONFIGSISTGRUPLANO

### Estrutura de Colunas e Restrições

              Tabela                   Coluna   Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGSISTGRUPLANO               CODSISTEMA   VARCHAR2(20)                          Código do Sistema    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGSISTGRUPLANO                 CODGRUPO    NUMBER(6,0)                            Código do Grupo    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGSISTGRUPLANO                DESCRICAO   VARCHAR2(40)                         Descrição do Grupo            OPERACIONAL                        NaN
PCCONFIGSISTGRUPLANO    VALORAGRUPAMENTOETICO VARCHAR2(4000)    Valores do Agrupamento de Planos Éticos            OPERACIONAL                        NaN
PCCONFIGSISTGRUPLANO VALORAGRUPAMENTOGENERICO VARCHAR2(4000) Valores de Agrupamento de Planos Genéricos            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*