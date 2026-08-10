# 📊 Tabela: PCLOGFATVAREJO

### Estrutura de Colunas e Restrições

        Tabela     Coluna Tipo/Tamanho  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGFATVAREJO       DATA         DATE                 Data            OPERACIONAL                        NaN
PCLOGFATVAREJO   NUMCAIXA  NUMBER(4,0)      Numero do caixa            OPERACIONAL                        NaN
PCLOGFATVAREJO       TIPO VARCHAR2(20)   Tipo de ocorrencia            OPERACIONAL                        NaN
PCLOGFATVAREJO    ARQUIVO         CLOB             Detalhes            OPERACIONAL                        NaN
PCLOGFATVAREJO   DETALHES         CLOB             Detalhes            OPERACIONAL                        NaN
PCLOGFATVAREJO DTEXCLUSAO         DATE     Data de exclusão            OPERACIONAL                        NaN
PCLOGFATVAREJO     NUMLOG NUMBER(10,0)    Numero sequencial    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGFATVAREJO  NUMPEDECF NUMBER(10,0) NUMERO DE PEDIDO ECF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*