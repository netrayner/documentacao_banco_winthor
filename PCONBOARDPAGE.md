# 📊 Tabela: PCONBOARDPAGE

### Estrutura de Colunas e Restrições

       Tabela       Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCONBOARDPAGE       IDPAGE   NUMBER(6,0)                    Código da Página    CHAVE PRIMÁRIA (PK)                        NaN
PCONBOARDPAGE    IDONBOARD   NUMBER(6,0)                Código do Onboard FK            OPERACIONAL                        NaN
PCONBOARDPAGE    SEQUENCIA   NUMBER(3,0)     Sequencia de Exibição da Página            OPERACIONAL                        NaN
PCONBOARDPAGE TIPOCONTEUDO  VARCHAR2(10)          Tipo de Conteúdo da Página            OPERACIONAL                        NaN
PCONBOARDPAGE       TITULO  VARCHAR2(50)                    Título da Página            OPERACIONAL                        NaN
PCONBOARDPAGE   EXPLICACAO VARCHAR2(200)                Explicação da Página            OPERACIONAL                        NaN
PCONBOARDPAGE    ICOBASE64          CLOB                     Ícone da Página            OPERACIONAL                        NaN
PCONBOARDPAGE SOMENTEADMIN   VARCHAR2(1) Permissão de Visualização da Página            OPERACIONAL                        NaN
PCONBOARDPAGE      BINARIO          BLOB          Arquivo de Mídia da Página            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*