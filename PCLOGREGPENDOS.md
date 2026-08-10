# 📊 Tabela: PCLOGREGPENDOS

### Estrutura de Colunas e Restrições

        Tabela         Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGREGPENDOS        CODPEND   NUMBER(8,0)                  Indica código da pendência.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGREGPENDOS CODFUNCREGPEND   NUMBER(8,0) Indica o código do registrador da pendência.            OPERACIONAL                        NaN
PCLOGREGPENDOS      CODFILIAL   VARCHAR2(2)                   Indica o código da filial.            OPERACIONAL                        NaN
PCLOGREGPENDOS         NUMCAR   NUMBER(8,0)             Indica o número do carregamento.            OPERACIONAL                        NaN
PCLOGREGPENDOS         NUMPED  NUMBER(10,0)                   Indica o número do pedido.            OPERACIONAL                        NaN
PCLOGREGPENDOS        CODPROD   NUMBER(6,0)                  Indica o código do produto.            OPERACIONAL                        NaN
PCLOGREGPENDOS             QT  NUMBER(20,6)                         Indica a quantidade.            OPERACIONAL                        NaN
PCLOGREGPENDOS     QTSEPARADA  NUMBER(20,6)                Indica a quantidade separada.            OPERACIONAL                        NaN
PCLOGREGPENDOS         QTPEND  NUMBER(20,6)                Indica o quantidade pendente.            OPERACIONAL                        NaN
PCLOGREGPENDOS    CODFUNCPEND   NUMBER(8,0)  Indica o código do conferente da pendência.            OPERACIONAL                        NaN
PCLOGREGPENDOS      DTREGPEND          DATE      Indica a data de registro da pendência.            OPERACIONAL                        NaN
PCLOGREGPENDOS     OBSERVACAO VARCHAR2(200)              Indica o observação do registro            OPERACIONAL                        NaN
PCLOGREGPENDOS          NUMOS  NUMBER(15,0)                       Indica o número da OS.            OPERACIONAL                        NaN
PCLOGREGPENDOS         STATUS   VARCHAR2(1)                       Indica o status da OS.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*