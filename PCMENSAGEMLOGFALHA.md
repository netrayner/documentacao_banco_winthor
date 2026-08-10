# 📊 Tabela: PCMENSAGEMLOGFALHA

### Estrutura de Colunas e Restrições

            Tabela         Coluna   Tipo/Tamanho                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENSAGEMLOGFALHA        CODMENS   NUMBER(10,0)                                                                                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGEMLOGFALHA     DTREGISTRO           DATE                                                                                                                 NaN            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA        ASSUNTO  VARCHAR2(100)                                                                                                                 NaN            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA       MENSAGEM VARCHAR2(4000)                                                                                                                 NaN            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA     DTEXCLUSAO           DATE                                                                                                                 NaN            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA       EXCLUIDO    VARCHAR2(1)                                                                                                                 NaN            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA CODIGO_ASSUNTO   VARCHAR2(40)                                 Armazena o código do assunto. Este código é uma forma de categoriazar as mensagens.            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA      LITERAL_1  VARCHAR2(200)         Este campo é destinado a armazenar informações literarias (filial, numlote, subcategoria do assunto, etc..)            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA      LITERAL_2  VARCHAR2(200)         Este campo é destinado a armazenar informações literarias (filial, numlote, subcategoria do assunto, etc..)            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA      LITERAL_3  VARCHAR2(200)         Este campo é destinado a armazenar informações literarias (filial, numlote, subcategoria do assunto, etc..)            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA     NUMERICO_1   NUMBER(30,0) Este campo é destinado a armazenar informações numerica (codprod, qtde movimentada, qtde de produtos ativos, etc..)            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA     NUMERICO_2   NUMBER(30,0) Este campo é destinado a armazenar informações numerica (codprod, qtde movimentada, qtde de produtos ativos, etc..)            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA     NUMERICO_3   NUMBER(30,0) Este campo é destinado a armazenar informações numerica (codprod, qtde movimentada, qtde de produtos ativos, etc..)            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA     NUMERICO_4   NUMBER(30,0) Este campo é destinado a armazenar informações numerica (codprod, qtde movimentada, qtde de produtos ativos, etc..)            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA     NUMERICO_5   NUMBER(30,0) Este campo é destinado a armazenar informações numerica (codprod, qtde movimentada, qtde de produtos ativos, etc..)            OPERACIONAL                        NaN
PCMENSAGEMLOGFALHA     NUMERICO_6   NUMBER(30,0) Este campo é destinado a armazenar informações numerica (codprod, qtde movimentada, qtde de produtos ativos, etc..)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*