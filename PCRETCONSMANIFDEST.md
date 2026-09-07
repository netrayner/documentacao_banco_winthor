# 📊 Tabela: PCRETCONSMANIFDEST

### Estrutura de Colunas e Restrições

            Tabela         Coluna   Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRETCONSMANIFDEST         CODIGO   NUMBER(10,0)                                               Código    CHAVE PRIMÁRIA (PK)                        NaN
PCRETCONSMANIFDEST      CODFILIAL    VARCHAR2(2)                                     Código da Filial            OPERACIONAL                        NaN
PCRETCONSMANIFDEST        NUMNOTA   NUMBER(10,0)                                       Número da Nota            OPERACIONAL                        NaN
PCRETCONSMANIFDEST       CHAVENFE   VARCHAR2(44)                                            Chave Nfe            OPERACIONAL                        NaN
PCRETCONSMANIFDEST            NSU   NUMBER(15,0)                                                  NSU            OPERACIONAL                        NaN
PCRETCONSMANIFDEST DATAREQUISICAO           DATE                           Daata e Hora da requisição            OPERACIONAL                        NaN
PCRETCONSMANIFDEST       AMBIENTE    VARCHAR2(1)                                         Ambiente Nfe            OPERACIONAL                        NaN
PCRETCONSMANIFDEST    SITUACAONFE   NUMBER(10,0)                                         Situação NFe            OPERACIONAL                        NaN
PCRETCONSMANIFDEST         IDLOTE   NUMBER(10,0)                                              Id Lote            OPERACIONAL                        NaN
PCRETCONSMANIFDEST      DESCRICAO VARCHAR2(1000) Mensagem / descrição da situação da consulta da nota            OPERACIONAL                        NaN
PCRETCONSMANIFDEST     XMLRETORNO           CLOB                   Contém o XML retornado pela SEFAZ.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*