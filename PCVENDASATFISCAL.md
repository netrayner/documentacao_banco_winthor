# 📊 Tabela: PCVENDASATFISCAL

### Estrutura de Colunas e Restrições

          Tabela            Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVENDASATFISCAL             CHAVE  VARCHAR2(80)              CHAVE SAT DO CLIENTE    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDASATFISCAL          NUMCUPOM  NUMBER(10,0)                      NRO DO CUPOM    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDASATFISCAL          SITUACAO VARCHAR2(200)                 SITUAÇÃO NA SEFAZ            OPERACIONAL                        NaN
PCVENDASATFISCAL         DTEMISSAO          DATE          DATA DE EMISSAO DO CUPOM            OPERACIONAL                        NaN
PCVENDASATFISCAL             VALOR  NUMBER(22,6)                    VALOR DO CUPOM            OPERACIONAL                        NaN
PCVENDASATFISCAL          ERROSCFE VARCHAR2(500)         MENSAGEM DE ERRO DA SEFAZ            OPERACIONAL                        NaN
PCVENDASATFISCAL           NUMLOTE  VARCHAR2(30)              NRO DO LOTE DE ENVIO            OPERACIONAL                        NaN
PCVENDASATFISCAL    NUMCAIXAFISCAL  NUMBER(10,0)               NRO DO CAIXA FISCAL            OPERACIONAL                        NaN
PCVENDASATFISCAL     NUMSERIEEQUIP  VARCHAR2(30)       NRO DE SERIE DO EQUIPTO SAT    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDASATFISCAL         CODFILIAL   VARCHAR2(3)          FILIAL DE VENDA DO CUPOM            OPERACIONAL                        NaN
PCVENDASATFISCAL STATUSCONCILIACAO VARCHAR2(100) STATUS DO PROCESSO DE CONCILIAÇÃO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*