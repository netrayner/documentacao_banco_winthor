# 📊 Tabela: PCAUTDOWNLOADXML

### Estrutura de Colunas e Restrições

          Tabela              Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTDOWNLOADXML                TIPO  VARCHAR2(1)         Tipo (E) Entrada ou (S) Saida            OPERACIONAL                        NaN
PCAUTDOWNLOADXML PCAUTDOWNLOADXML_ID  NUMBER(6,0)                      Campo Sequencial    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTDOWNLOADXML        NUMTRANSACAO NUMBER(10,0)     Numero da transacao saida/entrada            OPERACIONAL                        NaN
PCAUTDOWNLOADXML          TIPOPESSOA  VARCHAR2(1)     Tipo de pessoa Física ou Jurídica            OPERACIONAL                        NaN
PCAUTDOWNLOADXML                 CGC VARCHAR2(18) CGC ou CPF de acordo com o TIPOPESSOA            OPERACIONAL                        NaN
PCAUTDOWNLOADXML                NOME VARCHAR2(60)                  Nome ou Razão social            OPERACIONAL                        NaN
PCAUTDOWNLOADXML           DESCRICAO VARCHAR2(60)                             Descrição            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*