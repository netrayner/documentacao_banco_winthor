# 📊 Tabela: PCCODBARRASPALETES

### Estrutura de Colunas e Restrições

            Tabela       Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCODBARRASPALETES       CODIGO NUMBER(10,0) Código único para o código de barras    CHAVE PRIMÁRIA (PK)                        NaN
PCCODBARRASPALETES CODIGOBARRAS VARCHAR2(80)           Código de barras do palete    CHAVE PRIMÁRIA (PK)                        NaN
PCCODBARRASPALETES   DTCADASTRO         DATE                     Data do cadastro            OPERACIONAL                        NaN
PCCODBARRASPALETES   CODFUNCCAD  NUMBER(6,0)  Código do funcionário que cadastrou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*