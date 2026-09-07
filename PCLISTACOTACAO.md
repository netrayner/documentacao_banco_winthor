# 📊 Tabela: PCLISTACOTACAO

### Estrutura de Colunas e Restrições

        Tabela     Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLISTACOTACAO CODCOTACAO  NUMBER(6,0)                Código da cotação            OPERACIONAL                        NaN
PCLISTACOTACAO       DATA         DATE                  Data da cotação            OPERACIONAL                        NaN
PCLISTACOTACAO  CODFILIAL  VARCHAR2(2)      Código da filial da cotação            OPERACIONAL                        NaN
PCLISTACOTACAO NOMEOBJETO VARCHAR2(33) Nome do objeto do banco de dados            OPERACIONAL                        NaN
PCLISTACOTACAO     CODIGO  VARCHAR2(8)                   Valor do campo            OPERACIONAL                        NaN
PCLISTACOTACAO DTEXCLUSAO         DATE     Data de exclusao do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*