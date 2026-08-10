# 📊 Tabela: PCRAZAOPERIODOFORNEC

### Estrutura de Colunas e Restrições

              Tabela    Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRAZAOPERIODOFORNEC       MES  NUMBER(2,0) Indica o mês gerador do razão auxiliar.    CHAVE PRIMÁRIA (PK)                        NaN
PCRAZAOPERIODOFORNEC       ANO  NUMBER(4,0) Indica o ano gerador do razão auxiliar.    CHAVE PRIMÁRIA (PK)                        NaN
PCRAZAOPERIODOFORNEC ENCERRADO  VARCHAR2(1)              Indica encerredo com exito            OPERACIONAL                        NaN
PCRAZAOPERIODOFORNEC   PERIODO VARCHAR2(40)          Indica a descrição do período.            OPERACIONAL                        NaN
PCRAZAOPERIODOFORNEC CODFILIAL  VARCHAR2(2)              Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*