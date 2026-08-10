# 📊 Tabela: PCEQUIFAX

### Estrutura de Colunas e Restrições

   Tabela          Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEQUIFAX              ID  NUMBER(5,0)               Identificador do Registro    CHAVE PRIMÁRIA (PK)                        NaN
PCEQUIFAX   IDTIPOPRODUTO  NUMBER(2,0)            Código do produto da Equifax            OPERACIONAL                        NaN
PCEQUIFAX NOMETIPOPRODUTO VARCHAR2(30)         Descrição do Produto da Equifax            OPERACIONAL                        NaN
PCEQUIFAX        DATAHORA         DATE          Data/Hora Execução da Consulta            OPERACIONAL                        NaN
PCEQUIFAX         CODFUNC VARCHAR2(10)     Funcionário que executou a pesquisa            OPERACIONAL                        NaN
PCEQUIFAX          CODCLI  NUMBER(6,0) Código do Cliente Utilizado na Consulta            OPERACIONAL                        NaN
PCEQUIFAX            CNPJ VARCHAR2(20)                     CPF/CNPJ do cliente            OPERACIONAL                        NaN
PCEQUIFAX             XML         CLOB              XML de retorno da consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*