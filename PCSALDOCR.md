# 📊 Tabela: PCSALDOCR

### Estrutura de Colunas e Restrições

   Tabela               Coluna Tipo/Tamanho                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDOCR             CODBANCO  NUMBER(4,0)                                                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOCR               CODCOB  VARCHAR2(4)                                                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOCR                 DATA         DATE                                                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOCR       VLSALDOINICIAL NUMBER(16,2)  Valor do saldo inicial, originalmente baseado na conciliação (futuramente descontinuará).            OPERACIONAL                        NaN
PCSALDOCR      VLSALDOCONCILID NUMBER(16,2)                                               Valor do saldo atual baseado em conciliação.            OPERACIONAL                        NaN
PCSALDOCR        DTULTCONCILIA         DATE                                                     Data da ultima conciliação dos saldos.            OPERACIONAL                        NaN
PCSALDOCR         VLSALDOFINAL NUMBER(18,6) Valor do saldo final, originalmente baseado na na conciliação (futuramente descontinuará).            OPERACIONAL                        NaN
PCSALDOCR              CODFUNC  NUMBER(6,0)                       Indica o código do funcionário responsável pelo fechamento do caixa.            OPERACIONAL                        NaN
PCSALDOCR           DTABERTURA         DATE                                                 Indica a data e hora de abertura do caixa.            OPERACIONAL                        NaN
PCSALDOCR     DTULTCOMPENSACAO         DATE                                                     Data da ultima compensação dos saldos.            OPERACIONAL                        NaN
PCSALDOCR    VLSALDOCOMPENSADO NUMBER(16,2)                                                                 Valor do saldo compensado.            OPERACIONAL                        NaN
PCSALDOCR         DTREFERENCIA         DATE                                                           Data de referência do resgistro.            OPERACIONAL                        NaN
PCSALDOCR            DTGERACAO         DATE                                                         Data em que o registro foi gerado.            OPERACIONAL                        NaN
PCSALDOCR VLSALDOINICIALCONCIL NUMBER(16,2)                                        Novo valor do saldo inicial baseado na conciliação.            OPERACIONAL                        NaN
PCSALDOCR   VLSALDOINICIALCOMP NUMBER(16,2)                                        Novo valor do saldo inicial baseado na compensação.            OPERACIONAL                        NaN
PCSALDOCR   VLSALDOFINALCONCIL NUMBER(16,2)                                          Novo valor do saldo final baseado na conciliação.            OPERACIONAL                        NaN
PCSALDOCR     VLSALDOFINALCOMP NUMBER(16,2)                                          Novo valor do saldo final baseado na compensação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*