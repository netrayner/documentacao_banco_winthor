# 📊 Tabela: PCEDITAISITENS

### Estrutura de Colunas e Restrições

        Tabela                  Coluna   Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEDITAISITENS               CODEDITAL    NUMBER(9,0)              Código edital.    CHAVE PRIMÁRIA (PK)                        NaN
PCEDITAISITENS                 CODPROD    NUMBER(9,0)             Código produto.            OPERACIONAL                        NaN
PCEDITAISITENS      DESCRICAO_AUXILIAR VARCHAR2(4000)         Descrição auxiliar.            OPERACIONAL                        NaN
PCEDITAISITENS                    LOTE   VARCHAR2(10)                       Lote.    CHAVE PRIMÁRIA (PK)                        NaN
PCEDITAISITENS             NUMERO_ITEM    NUMBER(9,0)             Numero do Item.    CHAVE PRIMÁRIA (PK)                        NaN
PCEDITAISITENS              QUANTIDADE   NUMBER(10,0)                 Quantidade.            OPERACIONAL                        NaN
PCEDITAISITENS TIPO_DESCRICAO_AUXILIAR        CHAR(1) Tipo da descrição auxiliar.            OPERACIONAL                        NaN
PCEDITAISITENS              CODUNIDADE    VARCHAR2(2)             Código unidade.            OPERACIONAL                        NaN
PCEDITAISITENS                UTILIZAR        CHAR(1)                   Utilizar.            OPERACIONAL                        NaN
PCEDITAISITENS                CODMARCA    NUMBER(8,0)               Código Marca.            OPERACIONAL                        NaN
PCEDITAISITENS         UNIDADEPROPOSTA    VARCHAR2(3)            Unidade Proposta            OPERACIONAL                        NaN
PCEDITAISITENS          FATORCONVERSAO  NUMBER(30,16)             Fator Conversão            OPERACIONAL                        NaN
PCEDITAISITENS    LICITUSARDESONERAICM    VARCHAR2(1)  Licit Usar Desoneração ICM            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*