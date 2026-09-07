# 📊 Tabela: PCPRESTACAOCONTACENTROCUSTO

### Estrutura de Colunas e Restrições

                     Tabela                   Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRESTACAOCONTACENTROCUSTO CODPRESTCONTACENTROCUSTO NUMBER(10,0)      Código chave primária de Centro Custo    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTACAOCONTACENTROCUSTO      CODPRESTACAODETALHE NUMBER(10,0) Código chave extrangeira para Item Detalhe CHAVE ESTRANGEIRA (FK)    PCPRESTACAOCONTADETALHE
PCPRESTACAOCONTACENTROCUSTO           CODCENTROCUSTO VARCHAR2(40) Código chave extrangeira para Centro Custo CHAVE ESTRANGEIRA (FK)              PCCENTROCUSTO
PCPRESTACAOCONTACENTROCUSTO               PERCENTUAL NUMBER(10,6)        Valor do percentual do Centro Custo            OPERACIONAL                        NaN
PCPRESTACAOCONTACENTROCUSTO        STATUSCENTROCUSTO  VARCHAR2(2)                     Status do Centro Custo            OPERACIONAL                        NaN
PCPRESTACAOCONTACENTROCUSTO         MOTIVOAPROVACAO1 VARCHAR2(50)        Motivo aprovação primeiro aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTACENTROCUSTO         MOTIVOAPROVACAO2 VARCHAR2(50)         Motivo aprovação segundo aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTACENTROCUSTO          CODAPROVADORCC1  NUMBER(8,0)               Código do primeiro aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTACENTROCUSTO          CODAPROVADORCC2  NUMBER(8,0)                Código do segundo aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTACENTROCUSTO       STATUSAPROVADORCC1  VARCHAR2(1)               Status do primeiro aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTACENTROCUSTO       STATUSAPROVADORCC2  VARCHAR2(1)                Status do segundo aprovador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*