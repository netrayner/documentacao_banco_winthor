# 📊 Tabela: PCFECHACXCEGO

### Estrutura de Colunas e Restrições

       Tabela             Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFECHACXCEGO             CODCOB  VARCHAR2(4)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFECHACXCEGO           NUMCAIXA  NUMBER(4,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFECHACXCEGO          CODFUNCCX  NUMBER(8,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFECHACXCEGO               DATA         DATE                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFECHACXCEGO              VALOR NUMBER(16,3)                                  NaN            OPERACIONAL                        NaN
PCFECHACXCEGO          EXPORTADO  VARCHAR2(1)        Flag se a exportação ocorreu.            OPERACIONAL                        NaN
PCFECHACXCEGO       DTEXPORTACAO         DATE  Data de Exportação para o Servidor.            OPERACIONAL                        NaN
PCFECHACXCEGO NUMFECHAMENTOMOVCX NUMBER(10,0) Numero do fechamento da movimentacao            OPERACIONAL                        NaN
PCFECHACXCEGO      DTMOVIMENTOCX         DATE       Data da movimentacao do caixa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*