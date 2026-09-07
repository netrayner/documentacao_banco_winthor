# 📊 Tabela: PCPERFILEXPEDIENTES

### Estrutura de Colunas e Restrições

             Tabela      Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERFILEXPEDIENTES          ID NUMBER(10,0)          Identificador do expediente    CHAVE PRIMÁRIA (PK)                        NaN
PCPERFILEXPEDIENTES    PERFILID NUMBER(10,0) Identificador com os dados do Perfil CHAVE ESTRANGEIRA (FK)                   PCPERFIL
PCPERFILEXPEDIENTES HORAINICIAL         DATE           Hora inicial do expediente            OPERACIONAL                        NaN
PCPERFILEXPEDIENTES   HORAFINAL         DATE             Hora final do expediente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*