# 📊 Tabela: PCTABELALGPD

### Estrutura de Colunas e Restrições

      Tabela        Coluna Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTABELALGPD     CODTABELA  NUMBER(8,0)                                        Identificador único    CHAVE PRIMÁRIA (PK)                        NaN
PCTABELALGPD    CODPERSONA  NUMBER(8,0)                                          Código do persona CHAVE ESTRANGEIRA (FK)              PCPERSONALGPD
PCTABELALGPD        TABELA VARCHAR2(40)                                    Tabela elegivél ao LGPD            OPERACIONAL                        NaN
PCTABELALGPD  CAMPOIDBUSCA VARCHAR2(40) Campo que será utilizado para filtrar o registro da tabela            OPERACIONAL                        NaN
PCTABELALGPD    CAMPOCHAVE VARCHAR2(40)                       Campo que é chave primaria da tabela            OPERACIONAL                        NaN
PCTABELALGPD          HASH VARCHAR2(32)                   Hash para garantir a fidelidade do dados            OPERACIONAL                        NaN
PCTABELALGPD     MATRICULA  NUMBER(8,0)       Código da matrícula do usuário que gravou o registro            OPERACIONAL                        NaN
PCTABELALGPD      DATAHORA         DATE                        Data e hora da gravação do registro            OPERACIONAL                        NaN
PCTABELALGPD  CODTABELAPAI  NUMBER(8,0)                Código da tabela que relaciona a tabela pai            OPERACIONAL                        NaN
PCTABELALGPD CAMPOCHAVEPAI VARCHAR2(40)                     Campo chave que relaciona a tabela pai            OPERACIONAL                        NaN
PCTABELALGPD        STATUS  VARCHAR2(1)         Indica se o registro está A - Ativo ou I - Inativo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*