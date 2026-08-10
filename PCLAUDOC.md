# 📊 Tabela: PCLAUDOC

### Estrutura de Colunas e Restrições

  Tabela          Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAUDOC         IDLAUDO  NUMBER(8,0)     Identificação do Laudo.    CHAVE PRIMÁRIA (PK)                        NaN
PCLAUDOC         CODPROD  NUMBER(8,0)         Código do Produto.             OPERACIONAL                        NaN
PCLAUDOC DESCRICAOPADRAO VARCHAR2(40)      Descrição da análise.             OPERACIONAL                        NaN
PCLAUDOC     VALORPADRAO VARCHAR2(40)   Valor padrão da análise.             OPERACIONAL                        NaN
PCLAUDOC          VERSAO  NUMBER(8,0) Versão das especificações.             OPERACIONAL                        NaN
PCLAUDOC          DTLANC         DATE Data de cadastro do laudo.             OPERACIONAL                        NaN
PCLAUDOC     CODFUNCLANC  NUMBER(8,0)   Funcionário responsável.             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*