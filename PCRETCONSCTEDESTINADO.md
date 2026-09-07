# 📊 Tabela: PCRETCONSCTEDESTINADO

### Estrutura de Colunas e Restrições

               Tabela         Coluna   Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRETCONSCTEDESTINADO         CODIGO   NUMBER(10,0) Código sequencial da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCRETCONSCTEDESTINADO      CODFILIAL    VARCHAR2(2)            Código da filial            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO         NUMCTE   NUMBER(10,0)               Número do CTe            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO       CHAVECTE   VARCHAR2(44)                Chave do CTe            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO            NSU   NUMBER(15,0)  Número do sequencial único            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO DATAREQUISICAO           DATE          Data da requisição            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO       AMBIENTE    VARCHAR2(1)             Ambiente do CTe            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO    SITUACAOCTE   NUMBER(10,0)             Situação do CTe            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO         IDLOTE   NUMBER(10,0)       Identificador do lote            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO      DESCRICAO VARCHAR2(1000)       Descrição do registro            OPERACIONAL                        NaN
PCRETCONSCTEDESTINADO     XMLRETORNO           CLOB     Xml de retorno da Sefaz            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*