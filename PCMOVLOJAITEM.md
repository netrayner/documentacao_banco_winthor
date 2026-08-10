# 📊 Tabela: PCMOVLOJAITEM

### Estrutura de Colunas e Restrições

       Tabela            Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVLOJAITEM        CODMOVLOJA   NUMBER(6,0)                              Código sequencial    CHAVE PRIMÁRIA (PK)                  PCMOVLOJA
PCMOVLOJAITEM           CODPROD   NUMBER(6,0)                              Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVLOJAITEM      QTLANCAMENTO  NUMBER(22,6)                       Quantidade do lançamento            OPERACIONAL                        NaN
PCMOVLOJAITEM      QTREGISTRADA  NUMBER(22,6)                           Quantidade efetivada            OPERACIONAL                        NaN
PCMOVLOJAITEM   QTFRENTELOJAANT  NUMBER(22,6) Quantidade anterior da loja antes da alteração            OPERACIONAL                        NaN
PCMOVLOJAITEM QTFRENTELOJAATUAL  NUMBER(22,6)                 Quantidade atualizada da loja             OPERACIONAL                        NaN
PCMOVLOJAITEM            MOTIVO VARCHAR2(200)     Motivo de alteração da quantidade aplicada            OPERACIONAL                        NaN
PCMOVLOJAITEM         CODFUNCAD   NUMBER(8,0)              Código do funcionário de cadastro            OPERACIONAL                        NaN
PCMOVLOJAITEM        DTCADASTRO          DATE                               Data de cadastro            OPERACIONAL                        NaN
PCMOVLOJAITEM     NUMTRANSVENDA  NUMBER(10,0)                               Número da venda.            OPERACIONAL                        NaN
PCMOVLOJAITEM            NUMSEQ  NUMBER(20,0)                  Número sequência de inclusão.            OPERACIONAL                        NaN
PCMOVLOJAITEM     QTREGISTRADA2  NUMBER(22,6)      Quantidade registrada da segunda contagem            OPERACIONAL                        NaN
PCMOVLOJAITEM     QTREGISTRADA3  NUMBER(22,6)     Quantidade registrada da terceira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEM      CODFUNCCONT1   NUMBER(8,0)     Código do funcionario da primeira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEM      CODFUNCCONT2   NUMBER(8,0)      Código do funcionario da segunda contagem            OPERACIONAL                        NaN
PCMOVLOJAITEM      CODFUNCCONT3   NUMBER(8,0)     Código do funcionario da terceira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEM         DATACONT1          DATE                      Data da primeira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEM         DATACONT2          DATE                       Data da segunda contagem            OPERACIONAL                        NaN
PCMOVLOJAITEM         DATACONT3          DATE                      Data da terceira contagem            OPERACIONAL                        NaN
PCMOVLOJAITEM         CANCELADO   VARCHAR2(1)                    Verificar se está cancelado            OPERACIONAL                        NaN
PCMOVLOJAITEM          QTCANCEL  NUMBER(22,6)                           Quantidade Cancelada            OPERACIONAL                        NaN
PCMOVLOJAITEM       CODAUXILIAR  NUMBER(20,0)                                  Cód. Auxiliar            OPERACIONAL                        NaN
PCMOVLOJAITEM       QTDEVOLVIDA  NUMBER(22,6)                Quantidade devolvida ao estoque            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*