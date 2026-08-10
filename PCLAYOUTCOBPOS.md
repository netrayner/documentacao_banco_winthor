# 📊 Tabela: PCLAYOUTCOBPOS

### Estrutura de Colunas e Restrições

        Tabela          Coluna   Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTCOBPOS CODLAYOUTMAGREG         NUMBER       Codigo layout    CHAVE PRIMÁRIA (PK)             PCLAYOUTCOBREG
PCLAYOUTCOBPOS          POSINI         NUMBER     Posição inicial    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTCOBPOS          POSFIM         NUMBER       Posição final            OPERACIONAL                        NaN
PCLAYOUTCOBPOS       DESCRICAO VARCHAR2(1000)           Descrição            OPERACIONAL                        NaN
PCLAYOUTCOBPOS            FIXO    VARCHAR2(1)               Fixo?            OPERACIONAL                        NaN
PCLAYOUTCOBPOS        CONTEUDO  VARCHAR2(200)            Conteudo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*