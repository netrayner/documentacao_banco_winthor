# 📊 Tabela: PCLAUDOI

### Estrutura de Colunas e Restrições

  Tabela           Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAUDOI          IDLAUDO  NUMBER(8,0)                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLAUDOI          CODPROD  NUMBER(8,0)          Código do Produto.            OPERACIONAL                        NaN
PCLAUDOI  DESCRICAOPADRAO VARCHAR2(40)      Descrição da análise.             OPERACIONAL                        NaN
PCLAUDOI      VALORPADRAO VARCHAR2(40)   Valor padrão da análise.             OPERACIONAL                        NaN
PCLAUDOI           VERSAO  NUMBER(8,0) Versão das especificações.             OPERACIONAL                        NaN
PCLAUDOI           DTLANC         DATE Data de cadastro do laudo.             OPERACIONAL                        NaN
PCLAUDOI      CODFUNCLANC  NUMBER(8,0)   Funcionário responsável.             OPERACIONAL                        NaN
PCLAUDOI        CODFILIAL  VARCHAR2(2)  Código da Filial do lote.             OPERACIONAL                        NaN
PCLAUDOI          NUMLOTE VARCHAR2(15) Número do lote do produto.             OPERACIONAL                        NaN
PCLAUDOI RESULTADOANALISE VARCHAR2(40)   Valor padrão da análise.             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*