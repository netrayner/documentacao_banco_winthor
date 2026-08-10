# 📊 Tabela: PCFECHACONVENIO

### Estrutura de Colunas e Restrições

         Tabela            Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFECHACONVENIO     NUMFECHAMENTO  NUMBER(8,0)                    NÚMERO DO FECHAMENTO.    CHAVE PRIMÁRIA (PK)                        NaN
PCFECHACONVENIO         CODFILIAL  VARCHAR2(2)                           CÓDIGO FILIAL.            OPERACIONAL                        NaN
PCFECHACONVENIO            CODCLI  NUMBER(6,0)                          CÓDIGO CLIENTE.            OPERACIONAL                        NaN
PCFECHACONVENIO        DTFECPREST         DATE                          DATA PRESTAÇÃO.            OPERACIONAL                        NaN
PCFECHACONVENIO          DTFECREL         DATE               DATA FECHAMENTO RELATÓRIO.            OPERACIONAL                        NaN
PCFECHACONVENIO           DTFECNF         DATE                DATA FECHAMENTO CONVÊNIO.            OPERACIONAL                        NaN
PCFECHACONVENIO   CODFUNCFECPREST  NUMBER(8,0)          CÓD. FUNCIONÁRIO DO FECHAMENTO.            OPERACIONAL                        NaN
PCFECHACONVENIO     CODFUNCFECREL  NUMBER(8,0) CÓD. FUNCIONÁRIO QUE GEROU O  RELATÓRIO.            OPERACIONAL                        NaN
PCFECHACONVENIO      CODFUNCFECNF  NUMBER(8,0)          CÓD. FUNCIONÁRIO DO FECHAMENTO.            OPERACIONAL                        NaN
PCFECHACONVENIO NUMTRANSVENDADEST NUMBER(10,0)                        NÚMERO DO TÍTULO.            OPERACIONAL                        NaN
PCFECHACONVENIO         PRESTDEST  VARCHAR2(2)                        NÚMERO PRESTAÇÃO.            OPERACIONAL                        NaN
PCFECHACONVENIO        NUMVIASREL NUMBER(10,0)                 NÚMERO DE VIA RELATÓRIO.            OPERACIONAL                        NaN
PCFECHACONVENIO          SITUACAO  VARCHAR2(2)                                SITUAÇÃO.            OPERACIONAL                        NaN
PCFECHACONVENIO   NUMTRANSVENDANF NUMBER(10,0)                         NÚMERO DA VENDA.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*