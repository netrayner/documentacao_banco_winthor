# 📊 Tabela: PCLIMITECOMPRADIAENT

### Estrutura de Colunas e Restrições

              Tabela           Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLIMITECOMPRADIAENT        CODFILIAL  VARCHAR2(2)                Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCLIMITECOMPRADIAENT             DATA         DATE                  Data do Limite    CHAVE PRIMÁRIA (PK)                        NaN
PCLIMITECOMPRADIAENT       QTDELIMITE NUMBER(18,6)           Qtde do Limite diário            OPERACIONAL                        NaN
PCLIMITECOMPRADIAENT QTDELIMITEVOLUME NUMBER(18,6) Quantidade limite compra volume            OPERACIONAL                        NaN
PCLIMITECOMPRADIAENT   QTDELIMITEPESO NUMBER(18,6)   Quantidade limite compra Peso            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*