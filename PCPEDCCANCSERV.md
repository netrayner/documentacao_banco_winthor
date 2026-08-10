# 📊 Tabela: PCPEDCCANCSERV

### Estrutura de Colunas e Restrições

        Tabela        Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDCCANCSERV      NUMCUPOM NUMBER(10,0)              Número do cupom    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDCCANCSERV NUMSERIEEQUIP VARCHAR2(30)              Número de série    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDCCANCSERV     CODFILIAL  VARCHAR2(2)             Código da filial            OPERACIONAL                        NaN
PCPEDCCANCSERV          DATA         DATE                         Data            OPERACIONAL                        NaN
PCPEDCCANCSERV       CODFUNC NUMBER(10,0)        Código do funcionário            OPERACIONAL                        NaN
PCPEDCCANCSERV NUMTRANSVENDA NUMBER(10,0) Número da transação de venda            OPERACIONAL                        NaN
PCPEDCCANCSERV  VENDAFECHADA  VARCHAR2(1)                Venda fechada            OPERACIONAL                        NaN
PCPEDCCANCSERV        NUMPED NUMBER(10,0)             Número do Pedido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*